#### Test 5133502830f515a_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2731): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2731): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2731): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3211): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3211): CheckJNI is OFF
D/AndroidRuntime( 3211): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{3fad5e74 token=Token{1b666647 ActivityRecord{37102d86 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
I/HotwordDetector( 1524): Closing mic
V/WindowManager(  821): Adding window Window{1f7eb899 u0 Starting com.test.thalitest} at 3 of 8 (after Window{23a9ef71 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/MicrophoneInputStream( 1524): mic_close com.google.android.apps.gsa.speech.audio.u@3b13e775
D/AndroidRuntime( 3211): Shutting down VM
I/ActivityManager(  821): Start proc 3225:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1524): Stopping hotword detection.
I/HotwordRecognitionRnr( 1524): Hotword detection finished
I/ActivityManager(  821): Killing 2690:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
I/ActivityManager(  821): Killing 2822:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/WebViewFactory( 3225): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3225): Time to load native libraries: 1 ms (timestamps 456-457)
I/LibraryLoader( 3225): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3225): Binding Chromium to main looper Looper (main, tid 1) {e25f564}
,I/LibraryLoader( 3225): Expected native library version number "",actual native library version number ""
,I/chromium( 3225): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3225): Initializing chromium process, singleProcess=true
,W/art     ( 3225): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3225): ApplicationContext is null in ApplicationStatus
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660564755
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/chromium( 3225): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3225): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3225): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3225): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3225): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33152dc2:true
,D/BluetoothAdapter( 3225): 335479760: getState() :  mService = null. Returning STATE_OFF
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,W/art     ( 3225): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3225): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3225): CordovaWebView is running on device made by: motorola
,W/art     ( 3225): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3225): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3225): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3225): Validating map...
,V/WindowManager(  821): Adding window Window{27f07779 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{1f7eb899 u0 Starting com.test.thalitest})
,W/chromium( 3225): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3225): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3225): Enabling debug mode 0,
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +818ms (total +1m48s24ms)
,I/Keyboard.Facilitator( 1213): onFinishInput()
,W/BindingManager( 3225): Cannot call determinedVisibility() - never saw a connection for the pid: 3225
,D/JsMessageQueue( 3225): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3225): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576316032
,D/JX-Cordova( 3225): jxcore cordova android initializing
,I/kickstart(  871): STATUS: Received file 'm9kefs1'
,I/kickstart(  871): STATUS: 950272 bytes transferred in 0.989122 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed
,W/jxcore-log( 3225): Initializing JXcore engine
W/jxcore-log( 3225): JXcore engine is ready
,W/jxcore-log( 3225): Starting JXcore engine
,W/.test.thalitest( 3225): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9964]" dev="sockfs" ino=9964 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3225): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3225): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[12698]" dev="sockfs" ino=12698 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3225): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20951]" dev="sockfs" ino=20951 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3225): Platform android
W/jxcore-log( 3225): 
,W/jxcore-log( 3225): Process ARCH arm
W/jxcore-log( 3225): 
,I/jxcore-log( 3225): JXcore Cordova bridge is ready!
I/jxcore-log( 3225): 
W/jxcore-log( 3225): JXcore engine is started
,I/Choreographer( 3225): Skipped 132 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3225): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3225): Toggling radios to true
I/jxcore-log( 3225): 
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  821): Message: 1
,D/BluetoothManagerService(  821): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  821): setWifiEnabled: true pid=3225, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  821): New client listening to asynchronous messages
,I/jxcore-log( 3225): Radios toggled
I/jxcore-log( 3225): 
,D/SoftapController(  355): Softap fwReload - Ok,
,D/CommandListener(  355): Setting iface cfg
D/CommandListener(  355): Trying to bring down wlan0
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  821): Start proc 3282:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
D/WifiMonitor(  821): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3281): Successfully initialized wpa_supplicant
,I/ActivityManager(  821): Start proc 3299:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,W/ResourcesManager( 3282): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 560us total 18.129ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 243us total 12.628ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 212us total 9.187ms
,I/wpa_supplicant( 3281): rfkill: Cannot open RFKILL control device
,I/art     (  821): Explicit concurrent mark sweep GC freed 18954(946KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.445ms total 57.707ms
,D/AdapterServiceConfig( 3282): Adding HeadsetService
,D/AdapterServiceConfig( 3282): Adding A2dpService
D/AdapterServiceConfig( 3282): Adding HidService
D/AdapterServiceConfig( 3282): Adding HealthService
,D/AdapterServiceConfig( 3282): Adding PanService
D/AdapterServiceConfig( 3282): Adding GattService
D/AdapterServiceConfig( 3282): Adding BluetoothMapService
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1846b522:true
D/BluetoothAdapterState( 3282): make
,I/bluedroid( 3282): init
,I/BluetoothAdapterState( 3282): Entering OffState
,I/bte_conf( 3282): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3282): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3282): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3282): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3282): get_profile_interface socket
I/bluedroid( 3282): get_profile_interface map_client
I/GKI_LINUX( 3282): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3282): Address is:F8:CF:C5:D9:E5:61
,I/ActivityManager(  821): Start proc 3329:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  821): Killing 2860:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/BluetoothAdapterProperties( 3282): Name is: Nexus 6
,D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
,D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  821): Message: 40
,D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3282): config_hci_snoop_log
,D/BluetoothManagerService(  821): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  821): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3282): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3282): Setting state to 11
I/BluetoothAdapterState( 3282): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  821): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3282): make
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,I/BluetoothAdapterState( 3282): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3282): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64623cd
,D/HeadsetService( 3282): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3282): classInitNative: succeeds
D/HeadsetStateMachine( 3282): make
,D/HeadsetStateMachine( 3282): max_hf_connections = 1
I/bluedroid( 3282): get_profile_interface handsfree
,D/HeadsetStateMachine( 3282): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3282): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64623cd
,D/A2dpService( 3282): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3282): classInitNative: succeeds
I/bluedroid( 3282): get_profile_interface avrcp
,D/BluetoothA2dp(  821): Proxy object connected
,E/RemoteController( 3282): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3282): classInitNative: succeeds
D/A2dpStateMachine( 3282): make
,D/BluetoothA2dp( 1067): Proxy object connected
I/bluedroid( 3282): get_profile_interface a2dp
I/GKI_LINUX( 3282): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3282): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3282): classInitNative: succeeds
,D/BluetoothAdapterService( 3282): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64623cd
,D/HidService( 3282): Received start request. Starting profile...
I/bluedroid( 3282): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3282): classInitNative: succeeds
,D/BluetoothAdapterService( 3282): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64623cd
D/BluetoothInputDevice( 1067): Proxy object connected
D/HealthService( 3282): Received start request. Starting profile...
,I/bluedroid( 3282): get_profile_interface health
,I/BluetoothPanServiceJni( 3282): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3282): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64623cd
,D/PanService( 3282): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3282): initializeNative(L110): pan
I/bluedroid( 3282): get_profile_interface pan
I/BtGatt.JNI( 3282): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3282): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64623cd
D/BtGatt.DebugUtils( 3282): handleDebugAction() action=null
D/BtGatt.GattService( 3282): Received start request. Starting profile...
D/BtGatt.GattService( 3282): start()
I/bluedroid( 3282): get_profile_interface gatt
,D/BluetoothAdapterService( 3282): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64623cd
D/BtGatt.AdvertiseManager( 3282): advertise manager created
,D/BluetoothPan( 1067): BluetoothPAN Proxy object connected
,D/BluetoothAdapterService( 3282): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64623cd
,D/BluetoothMap( 1067): Proxy object connected
,D/BluetoothMapService( 3282): Received start request. Starting profile...
D/BluetoothMapService( 3282): start()
,D/BluetoothMapEmailSettingsLoader( 3282): Found 0 applications
D/BluetoothMapEmailAppObserver( 3282): createReceiver()
D/BluetoothMapEmailAppObserver( 3282): initObservers()
D/BluetoothMapEmailAppObserver( 3282): getEnabledAccountItems()
D/HeadsetStateMachine( 3282): Proxy object connected
D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3282): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3282): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3282): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3282): enable
I/GKI_LINUX( 3282): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3282): btu_task pending for preload complete event
I/bt_hci_bdroid( 3282): init
,I/bt_vendor( 3282): init
I/bt_vnd_conf( 3282): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3282): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3282): userial_init
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 21240(1097KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.097ms total 19.264ms
,I/bt_userial_vendor( 3282): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3282): device fd = 53 open
D/bt_userial( 3282): Entering userial_read_thread()
,I/ActivityManager(  821): Start proc 3368:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  821): Killing 2789:com.google.android.gm/u0a78 (adj 15): empty #17
,I/bt_hwcfg( 3282): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3282): Chipset BCM4354A2
D/bt_hwcfg( 3282): Target name = [BCM4354A2]
I/bt_hwcfg( 3282): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,D/Tethering(  821): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3281): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3281): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  821): Loading config and enabling all networks 
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@30da09da}
,E/WifiConfigStore(  821): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 2659): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  821): Setting external_sim to 1
D/WifiStateMachine(  821): Setting OUI to 92-68-C3
I/WifiNative-HAL(  821): startHal
,D/wifi    (  821): setting scan oui 0xaec85118
D/WifiHAL (  821): Sending mac address OUI
,E/WifiStateMachine(  821): cancelDelayedScan -> 1
,W/CommandListener(  355): Failed to retrieve HW addr for p2p0 (No such device)
,D/WifiScanningService(  821): SCAN_AVAILABLE : 3
D/CommandListener(  355): Setting iface cfg
D/RttService(  821): SCAN_AVAILABLE : 3
D/RttService(  821): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  821): startHal
D/wifi    (  821): getting scan capabilities on interface[0] = 0xaec85118
D/WifiHAL (  821): Creating message to get scan capablities; iface = 5
E/WifiP2pService(  821): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  821): startMonitoring(p2p0) with mConnected = true
D/WifiHAL (  821): In GetCapabilities::handleResponse
D/WifiHAL (  821): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  821): StartedState
,D/WifiNative-HAL(  821): p2pGetDeviceAddress
,D/WifiNative-HAL(  821): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/ActivityManager(  821): Killing 2356:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/wpa_supplicant( 3281): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/native  (  821): do suspend false
,I/ActivityManager(  821): Start proc 3386:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/bt_hwcfg( 3282): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3282): Settlement delay -- 100 ms
,I/bt_hwcfg( 3282): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3282): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3282): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3282): vendor lib fwcfg completed,
,I/bt-btu  ( 3282): btu_task received preload complete event
,I/        ( 3282): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3282): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3282): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3282): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3282): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3282): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3282): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3282): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3282): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3282): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3282): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3282): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3282): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3282): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3282): BTE_InitTraceLevels -- TRC_BTIF
,D/StrictMode( 3386): StrictMode policy violation; ~duration=224 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3386): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3386): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3386): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3386): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3386): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3386): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3386): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3386): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3386): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3386): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3386): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3386): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3386): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3386): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3386): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3386): StrictMode policy violation; ~duration=223 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3386): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3386): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3386): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3386): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3386): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3386): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3386): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3386): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3386): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3386): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3386): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3386): StrictMode policy violation; ~duration=221 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
D/StrictMode( 3386): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3386): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182),
D/StrictMode( 3386): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3386): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3386): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3386): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3386): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3386): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
,D/StrictMode( 3386): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3386): ,	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3386): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3386): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3386): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3386): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3386): ,	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
,D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3386): StrictMode policy violation; ~duration=216 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3386): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137),
D/StrictMode( 3386): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3386): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3386): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3386): ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3386): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3386): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3386): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3386): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3386): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3386): 	,at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3386): StrictMode policy violation; ~duration=203 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3386): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3386): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3386): ,	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3386): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3386): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3386): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3386): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3386): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
,D/StrictMode( 3386): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3386): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3386): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3386): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3386): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3386): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3386): StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3386): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3386): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3386): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3386): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3386): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62),
D/StrictMode( 3386): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3386): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3386): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3386): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3386): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3386): # via Binder call with stack:
D/StrictMode( 3386): android.os.StrictMode$LogStackTrace
D/StrictMode( 3386): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3386): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527),
D/StrictMode( 3386): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3386): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3386): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3386): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3386): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3386): 	,at com.google.android.c.c.a(PG:107)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3386): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3386): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3386): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3386): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3386): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3386): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3386): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3386): StrictMode policy violation; ~duration=48 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3386): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3386): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3386): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3386): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3386): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3386): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3386): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3386): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3386): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3386): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3386): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3386): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3386): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3386): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run,(ZygoteInit.java:903)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3386): StrictMode policy violation; ~duration=47 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3386): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3386): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3386): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3386): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3386): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3386): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3386): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3386): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3386): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3386): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3386): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3386): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3386): StrictMode policy violation; ~duration=47 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3386): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3386): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3386): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3386): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3386): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3386): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3386): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3386): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3386): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3386): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3386): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3386): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3386): StrictMode policy violation; ~duration=46 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3386): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3386): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3386): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3386): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3386): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3386): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3386): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3386): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3386): ,	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3386): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3386): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3386): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3386): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3386): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3386): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3386): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3386): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3386): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3386): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3386): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3386): 	at java.lang.reflect.Method.invoke(Native Method)
D/Stric,tMode( 3386): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3386): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/bt-btm  ( 3282): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e33085 
E/bt-btm  ( 3282): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e33085 
W/com.google.a.a.a.b.a( 3386): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  821): Message: 20,
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@efffa32:true
,I/ActivityManager(  821): Killing 2894:com.google.android.music:main/u0a66 (adj 15): empty #17,
,D/BluetoothAdapterProperties( 3282): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true,
,E/bt-btif ( 3282): Calling BTA_HhEnable,
E/bt-btif ( 3282): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3282): Address is:F8:CF:C5:D9:E5:61
,W/bt-btm  ( 3282): Stopping oneshot timer,
,D/AuthorizationBluetoothService( 1501): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,D/BluetoothAdapterProperties( 3282): Name is: Nexus 6
,D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6
,D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
,D/BluetoothAdapterProperties( 3282): Scan Mode:20
D/BluetoothAdapterProperties( 3282): Discoverable Timeout:120
,D/bte_conf( 3282): Device ID record 1 : primary
D/bte_conf( 3282):   vendorId            = 000f
D/bte_conf( 3282):   vendorIdSource      = 0001
D/bte_conf( 3282):   product             = 1200
D/bte_conf( 3282):   version             = 1436
D/bte_conf( 3282):   clientExecutableURL = 
D/bte_conf( 3282):   serviceDescription  = 
D/bte_conf( 3282):   documentationURL    = 
D/bte_conf( 3282): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3282): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3282): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3282): ScanMode =  20
D/BluetoothAdapterProperties( 3282): State =  11
,D/BluetoothAdapterProperties( 3282): Scan Mode:21
D/BluetoothAdapterProperties( 3282): Setting state to 12
D/BluetoothAdapterProperties( 3282): Discoverable Timeout:120
I/BluetoothAdapterState( 3282): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService(  821): Broadcasting onBluetoothStateChange(true) to 13 receivers.
D/BluetoothA2dp(  821): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 3282): Entering On State
,D/BluetoothInputDevice( 1067): onBluetoothStateChange: up=true
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothManagerService(  821): Creating new ProfileServiceConnections object for profile: 1
D/BluetoothHeadsetClient( 1067): onBluetoothStateChange: up=true
E/BluetoothHeadsetClient( 1067): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothAvrcpController( 1067): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1067): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothMap( 1067): onBluetoothStateChange: up=true
D/BluetoothPan( 1067): onBluetoothStateChange(on) call bindService
,D/BluetoothA2dpSink( 1067): onBluetoothStateChange: up=true,
E/BluetoothA2dpSink( 1067): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothHeadset( 1280): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1067): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  821): onBluetoothStateChange: up=true,
,D/BluetoothA2dp( 1067): onBluetoothStateChange: up=true
D/BluetoothManagerService(  821): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 3282): onReceive
D/BluetoothMapService( 3282): STATE_ON
,D/BluetoothMapMasInstance( 3282): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 3282): MAS initSocket()
D/BluetoothManagerService(  821): Message: 40
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
E/bt_h4   ( 3282): vendor lib postload completed
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3282): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3282): Accepting socket connection...
,W/ContextImpl( 3368): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2340f0d7:true
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3282): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1501): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LocalBluetoothProfileManager( 3368): Adding local A2DP profile
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3282): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  821): Message: 30
,I/BtOppRfcommListener( 3282): Accept thread started.
,D/LocalBluetoothProfileManager( 3368): Adding local HEADSET profile
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3368): Adding local MAP profile
,D/BluetoothMap( 3368): Create BluetoothMap proxy object
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3368): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3368): finishStartingService: stopping service
,D/BluetoothA2dp( 3368): Proxy object connected
D/A2dpProfile( 3368): Bluetooth service connected
,D/BluetoothInputDevice( 3368): Proxy object connected
,D/HidProfile( 3368): Bluetooth service connected
,D/BluetoothPan( 3368): BluetoothPAN Proxy object connected
,D/PanProfile( 3368): Bluetooth service connected
D/BluetoothMap( 3368): Proxy object connected
D/MapProfile( 3368): Bluetooth service connected
D/BluetoothMap( 3368): getConnectedDevices()
D/BluetoothPbap( 3368): Proxy object connected
,D/PbapServerProfile( 3368): Bluetooth service connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset(  821): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 1280): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 1067): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 3368): Proxy object connected
D/HeadsetProfile( 3368): Bluetooth service connected
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3225): Got Device Bluetooth address: F8:CF:C5:D9:E5:61,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): my name is : motorola-Nexus 6_PT2491
I/jxcore-log( 3225): ,
,I/jxcore-log( 3225): attempting to connect to test coordinator
,I/jxcore-log( 3225): 
I/jxcore-log( 3225): check test folder
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): found test : ./testFindPeers.js
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): found test : ./testReConnect.js,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): found test : ./testSendData.js,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): Test app app.js loaded
I/jxcore-log( 3225): 
,I/Choreographer( 3225): Skipped 136 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/chromium( 3225): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,I/wpa_supplicant( 3281): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  821):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  821):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  821): will read network variables netId=0
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,I/wpa_supplicant( 3281): wlan0: Trying to associate with SSID 'NG7005g'
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3281): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3281): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 1
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 1
E/WifiStateMachine(  821):  RSSI mgmt: -44
E/WifiStateMachine(  821):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 0 tx_time=59 rx_time=57 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 3427): version 5.5.6 starting
,I/dhcpcd  ( 3427): wlan0: rebinding lease of 192.168.1.110
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/dhcpcd  ( 3427): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 3427): wlan0: leased 192.168.1.110 for 86400 seconds
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 100
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100,
D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  821): Setting Dns servers for network 100 to [/192.168.1.1],
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
,D/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1,
D/Tethering(  821): MasterInitialState.processMessage what=3
E/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,V/BackupManagerService(  821): Scheduling immediate backup pass
,I/ActivityManager(  821): Start proc 3464:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,E/GpsLocationProvider(  821): No APN found to select.
,D/AlarmManagerService(  821): Setting time of day to sec=1448446252
W/AlarmManagerService(  821): Unable to set rtc to 1448446252: Invalid argument
,V/BackupManagerService(  821): Running a backup pass
,V/BackupManagerService(  821): clearing pending backups
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 25 Nov 2015 10:10:52 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448446253011], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448446253099]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
,D/GpsLocationProvider(  821): NTP server returned: 1448446252992 (Wed Nov 25 11:10:52 GMT+01:00 2015) reference: 149594 certainty: 10 system time offset: -27
V/PerformBackupTask(  821): Beginning backup of 14 targets
,D/PerformBackupTask(  821): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  821): doBackup() invoked
,I/PMBA    (  821): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  821): Getting widget state for user: 0
,I/MusicStore( 3464): Database version: 120
,E/Auth.Api.Credentials( 1783): [CredentialSyncAdapter] Unknown sync event.
,W/GmsBackupTransport( 1754): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1754): starting performBackup for @pm@
,V/GmsBackupTransport( 1754): performBackup done for @pm@
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 48323(2MB) AllocSpace objects, 5(120KB) LOS objects, 32% free, 33MB/49MB, paused 1.215ms total 50.198ms
,W/ResourcesManager( 3464): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3464): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GLSActivity( 1501): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1501): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1501): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1501): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1501): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1501): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1501): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1754): Error sending final backup to server: 
W/GmsBackupTransport( 1754): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1754): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1754): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1754): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1754): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1754): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1754): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1754): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1754): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1754): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1754): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1754): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1754): 	... 1 more
,D/BackupManagerService(  821): Now staging backup of com.google.android.talk
,D/BackupManagerService(  821): Now staging backup of com.google.android.dialer
D/BackupManagerService(  821): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  821): Now staging backup of com.android.sharedstoragebackup
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 8538(441KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.054ms total 25.193ms
,D/BackupManagerService(  821): Now staging backup of com.google.android.gm
,W/DriveInitializer( 1783): Background init thread started
,D/BackupManagerService(  821): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  821): Now staging backup of com.android.nfc
,V/JNIHelp ( 3464): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/BackupManagerService(  821): Now staging backup of com.google.android.apps.genie.geniewidget
,W/DriveInitializer( 1783): Awaiting to be initialized
,D/BackupManagerService(  821): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  821): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  821): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  821): Now staging backup of com.android.vending
,D/BackupManagerService(  821): Now staging backup of android
,D/BackupManagerService(  821): Now staging backup of com.google.android.googlequicksearchbox
,I/ProviderInstaller( 3464): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3464): GMSCore installation verified
,I/GmsBackupTransport( 1754): Next backup will happen in 43199916 millis.
,I/BackupManagerService(  821): Backup pass finished.
,I/ConfigStore( 3464): Config Database version: 1
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MediaRouter( 3464): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,W/DriveInitializer( 1783): Background init thread ended
,E/HttpOperation( 2998): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at blb.a(PG:3937)
E/HttpOperation( 2998): 	at czp.a(PG:18188)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 12 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 14 more
,V/MusicLeanback( 3464): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3464): type=WIFI subType= reason=null isConnected=true
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at hec.a(PG:42)
E/HttpOperation( 2998): 	at hee.a(PG:102)
E/HttpOperation( 2998): 	at czr.a(PG:65)
E/HttpOperation( 2998): 	at kka.a(PG:108)
E/HttpOperation( 2998): 	at czp.a(PG:19176)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 15 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 17 more
E/ExperimentLoader( 2998): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): 	at jdm.a(PG:82)
E/ExperimentLoader( 2998): 	at jcs.o(PG:406)
E/ExperimentLoader( 2998): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2998): 	at jcs.i(PG:143)
E/ExperimentLoader( 2998): 	at hec.a(PG:42)
E/ExperimentLoader( 2998): 	at hee.a(PG:102)
E/ExperimentLoader( 2998): 	at czr.a(PG:65)
E/ExperimentLoader( 2998): 	at kka.a(PG:108)
E/ExperimentLoader( 2998): 	at czp.a(PG:19176)
E/ExperimentLoader( 2998): 	at czp.a(PG:9081)
E/ExperimentLoader( 2998): 	at czq.run(PG:1686)
E/ExperimentLoader( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2998): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2998): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2998): 	at jdm.a(PG:77)
E/ExperimentLoader( 2998): 	... 15 more
E/ExperimentLoader( 2998): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2998): 	at fal.a(PG:38)
E/ExperimentLoader( 2998): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2998): 	... 17 more
,I/NetworkMonitor( 3464): type=WIFI subType= reason=null isConnected=true
,V/KeepSync( 3329): Connecting to GoogleApiClient
,I/ActivityManager(  821): Start proc 3522:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/GHttpClientFactory( 3464): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3464): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 3522): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3522): simOperator:  IMSI: null
D/SprintDMReceiver( 3522): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1783): onCreate
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,W/BaseAppContext( 1783): Using Auth Proxy for data requests.
,W/BaseAppContext( 1783): Using Auth Proxy for data requests.
,I/iu.SyncManager( 1783): SYNC; picasa accounts
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599955 ms
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 36556, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/NetworkLogImpl( 1783): Loaded NetworkSpeedPredictor
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/iu.Environment( 1783): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1783): num queued entries: 0
,I/iu.UploadsManager( 1783): num updated entries: 0
I/iu.SyncManager( 1783): NEXT; no task
,I/ActivityManager(  821): Start proc 3554:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,D/SystemUpdateService( 1783): onDestroy
,V/KeepSync( 3329): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  821): Start proc 3577:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 2659): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1783): [AccountUtils] Account not ready
W/Kids    ( 1783): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1783): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1783): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1783): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1783): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1783): 	at java.lang.Thread.run(Thread.java:818)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3329): IOException
E/KeepSync( 3329): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3329): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3329): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3329): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3329): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3329): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3329): 	... 10 more
W/KeepSync( 3329): Sync result 2
,I/GAv4    ( 3577): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3577):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3577):   adb logcat -s GAv4
,I/ActivityManager(  821): Killing 2940:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 36558, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/GCM     ( 1501): Connected
,W/GAv4    ( 3577): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/GCM     ( 1501): Message class com.google.f.a.a.p
,W/GAv4    ( 3577): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3577): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 3225): BLE supported!!
I/jxcore-log( 3225): 
,W/GAV2    ( 3554): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3554): Created application version: 3.6.8 (30608)
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 16986(1068KB) AllocSpace objects, 4(252KB) LOS objects, 37% free, 26MB/42MB, paused 1.564ms total 41.427ms
,I/WebViewFactory( 3577): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3577): Time to load native libraries: 4 ms (timestamps 884-888)
I/LibraryLoader( 3577): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3577): Binding Chromium to main looper Looper (main, tid 1) {33f84551}
,I/LibraryLoader( 3577): Expected native library version number "",actual native library version number ""
I/chromium( 3577): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3577): Initializing chromium process, singleProcess=true
,W/art     ( 3577): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3577): ApplicationContext is null in ApplicationStatus
,I/art     (  821): Explicit concurrent mark sweep GC freed 27905(1258KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.275ms total 53.702ms
,W/chromium( 3577): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3577): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3577): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3577): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3577): Requires BLUETOOTH permission
,I/NSApplication( 3577): Starting up...
,I/BooksSync( 3554): Starting books sync for 61035162, extras: ade
,I/ActivityManager(  821): Killing 2437:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3648:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/BooksConfig( 3554): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3554): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3554): Soft error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3554): Sync error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3554): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36558, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Killing 3131:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3111:com.google.android.partnersetup/u0a16 (adj 15): empty #18
,I/ActivityManager(  821): Start proc 3669:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,I/ActivityManager(  821): Killing 1816:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,E/SQLiteLog( 3669): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  821): Start proc 3689:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3689): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3689): Created com.android.providers.calendar.CalendarAlarmManager@36f842f7(com.android.providers.calendar.CalendarProvider2@e25f564)
,I/AnalyticsLogBase( 3669): PlayLogger.onLoggerConnected
,I/ActivityManager(  821): Start proc 3711:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/art     (  370): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 10.276ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 210us total 10.678ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 220us total 9.594ms
,I/ActivityManager(  821): Killing 3158:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/TimeService( 3711): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448446255971
D/        ( 3711): TimeServiceNative: User Time to be set is 1448446255971
D/QC-time-services( 3711): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3711): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3711): Lib:time_genoff_operation: pargs->ts_val = 1448446255971
D/QC-time-services(  374): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3711): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  374): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448446255971
D/QC-time-services(  374): Daemon:genoff_opr: Base = 2, val = 1448446255971, operation = 0
D/QC-time-services(  374): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/12/70 6:23:57
D/QC-time-services(  374): Daemon:Value read from RTC seconds = 8749437000
D/QC-time-services(  374): Daemon:new time 1448446255971 
D/QC-time-services(  374): Daemon: delta 1439696818971 genoff 1439696818971 
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696818971 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  374): Updating the TOD offset
,D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696818971 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  374): Daemon:Update to modem bit set,
D/QC-time-services(  374): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 3711): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  374): Daemon: Base = 2, Value being sent to MODEM = 1132481455971
,E/QC-time-services(  374): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  374): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  821): Start proc 3731:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  821): Killing 3067:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/GAv4    ( 3731): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3731):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3731):   adb logcat -s GAv4
,W/GAv4    ( 3731): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3731): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3731): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  821): Killing 2731:com.android.vending/u0a19 (adj 15): empty #17
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,V/Herrevad( 1783): NQAS connected
,I/CalendarProvider2( 3689): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3689): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@30da09da}
,I/art     ( 1783): Explicit concurrent mark sweep GC freed 14521(1132KB) AllocSpace objects, 16(256KB) LOS objects, 35% free, 28MB/44MB, paused 1.214ms total 48.186ms
,D/WifiService(  821): New client listening to asynchronous messages
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 12542(558KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 1.107ms total 47.809ms
,E/Babel   ( 2659): UserRecoverableAuthException.,
E/Babel   ( 2659): eei: BadAuthentication
E/Babel   ( 2659): 	at eeg.a(Unknown Source)
E/Babel   ( 2659): 	at eeg.a(Unknown Source)
E/Babel   ( 2659): 	at eeg.a(Unknown Source)
E/Babel   ( 2659): 	at g.a(Unknown Source)
E/Babel   ( 2659): 	at cae.a(SourceFile:3089)
E/Babel   ( 2659): 	at cae.a(SourceFile:1131)
E/Babel   ( 2659): 	at cws.a(SourceFile:4333)
E/Babel   ( 2659): 	at cws.a(SourceFile:1419)
E/Babel   ( 2659): 	at crl.a(SourceFile:492)
E/Babel   ( 2659): 	at crl.a(SourceFile:1468)
E/Babel   ( 2659): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2659): 	at cas.b(SourceFile:106)
E/Babel   ( 2659): 	at cap.d(SourceFile:335)
E/Babel   ( 2659): 	at caq.run(SourceFile:81)
,E/Babel   ( 2659): Error getting auth token
E/Babel   ( 2659): dvm
E/Babel   ( 2659): 	at g.a(Unknown Source)
E/Babel   ( 2659): 	at cae.a(SourceFile:3089)
E/Babel   ( 2659): 	at cae.a(SourceFile:1131)
E/Babel   ( 2659): 	at cws.a(SourceFile:4333)
E/Babel   ( 2659): 	at cws.a(SourceFile:1419)
E/Babel   ( 2659): 	at crl.a(SourceFile:492)
E/Babel   ( 2659): 	at crl.a(SourceFile:1468)
E/Babel   ( 2659): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2659): 	at cas.b(SourceFile:106)
E/Babel   ( 2659): 	at cap.d(SourceFile:335)
E/Babel   ( 2659): 	at caq.run(SourceFile:81)
,E/Babel   ( 2659): Account registration failed 1-Redacted-21
E/Babel   ( 2659): cyp: null -- null
E/Babel   ( 2659): 	at cae.a(SourceFile:3121)
E/Babel   ( 2659): 	at cae.a(SourceFile:1131)
E/Babel   ( 2659): 	at cws.a(SourceFile:4333)
E/Babel   ( 2659): 	at cws.a(SourceFile:1419)
E/Babel   ( 2659): 	at crl.a(SourceFile:492)
E/Babel   ( 2659): 	at crl.a(SourceFile:1468)
E/Babel   ( 2659): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2659): 	at cas.b(SourceFile:106)
E/Babel   ( 2659): 	at cap.d(SourceFile:335)
E/Babel   ( 2659): 	at caq.run(SourceFile:81)
,I/art     ( 2659): Note: end time exceeds epoch: 
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1501): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2659): Unexpected exception while authenticating.
,E/Babel   ( 2659): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2659): 	at eeg.b(Unknown Source)
E/Babel   ( 2659): 	at eeg.b(Unknown Source)
E/Babel   ( 2659): 	at g.a(Unknown Source)
E/Babel   ( 2659): 	at cae.b(SourceFile:1146)
E/Babel   ( 2659): 	at dcg.run(SourceFile:5617)
,E/Babel   ( 2659): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2659): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2659): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 3689): (284) automatic index on view_events(_id)
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=22.41 rxSuccessRate=21.81 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=22.41 rxSuccessRate=21.81 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,I/MusicLeanback( 3464): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3464): Stop autocaching.
,I/ActivityManager(  821): Start proc 3776:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,W/ResourcesManager( 3776): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3776): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3776): VM with version 2.1.0 has multidex support
I/MultiDex( 3776): install
I/MultiDex( 3776): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3776): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProviderInstaller( 3776): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1501): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1501): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1783): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3776): callingUid 10011, callindPid: 3776
,D/LocationInitializer( 1783): Restart initialization of location
,E/MDM     ( 1754): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3464): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3464): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAV2    ( 3554): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 3669): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/ActivityManager(  821): Start proc 3814:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/Finsky  ( 3814): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3814): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  821): Start proc 3850:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3814): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3814): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/ResourcesManager( 3850): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3850): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 3814): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3814): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 3814): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3814): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/MultiDex( 3850): VM with version 2.1.0 has multidex support
I/MultiDex( 3850): install
I/MultiDex( 3850): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3850): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  821): Killing 3368:com.android.settings/1000 (adj 15): empty #17
,I/ProviderInstaller( 3850): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  821): Killing 3386:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/GCM     ( 1501): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1501): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1783): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,D/WearableService( 3776): callingUid 10011, callindPid: 3776
E/MDM     ( 1754): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Finsky  ( 3814): [399] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/LocationInitializer( 1783): Restart initialization of location
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 17322(967KB) AllocSpace objects, 7(771KB) LOS objects, 37% free, 26MB/42MB, paused 1.019ms total 34.015ms
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3814): [399] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3814): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,V/Finsky  ( 3814): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/Finsky  ( 3814): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3814): [1] 5.onFinished: Scheduling replication attempt 4.
,D/Finsky  ( 3814): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3814): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 19948(944KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.850ms total 87.231ms
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3814): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3814): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3814): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,D/Finsky  ( 3814): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3814): [1] DailyHygiene.reschedule: Scheduling new run in 836 minutes (failures=5)
,D/DeviceConnectionService( 1754): client connected with version: 7571000,
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (222 us)
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  821): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  821): Excessive delay in setPowerMode(): 277ms
,I/DreamManagerService(  821): Entering dreamland.
,I/PowerManagerService(  821): Dozing...
,I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 5
,E/native  (  821): do suspend false
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2299d9cd}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=2.34 rxSuccessRate=2.30 targetRoamBSSID=any RSSI=-44
,I/Keyboard.Facilitator( 1213): onFinishInput()
,E/WifiStateMachine(  821): cancelDelayedScan -> 7
,E/native  (  821): do suspend true,
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off,
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2299d9cd}
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/ActivityManager(  821): Killing 3522:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  821): Killing 1524:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  821): Client connection lost with reason: 4
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44,
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3299): [341] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3299): [342] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3299): [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3299): [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3299): 	,at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3299): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3299): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3299): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3299): [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3299): [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3299): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3299): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): ,	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3299): 	at com.a.a.k.run(SourceFile:110)
,I/VacuumService( 1501): Vacuum at: now=1448446276974 tag=VacuumService
,I/GoogleURLConnFactory( 1501): Using platform SSLCertificateSocketFactory
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1501): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1501): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1501): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1501): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1501): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1501): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1501): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1501): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1501): No account for auth token provided
,W/Uploader( 1501): No account for auth token provided
,W/Uploader( 1501): No account for auth token provided
,W/Uploader( 1501): No account for auth token provided
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1501): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1501): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1501): ,	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1501): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1501): No account for auth token provided
,W/Uploader( 1501): No account for auth token provided
,W/Uploader( 1501): No account for auth token provided
,W/Uploader( 1501): No account for auth token provided,
,W/Uploader( 1501): No account for auth token provided
,W/Uploader( 1501):  no longer exists, so no auth token.
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1501): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1501): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1501): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1501): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1501): No account for auth token provided
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1501): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1501): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1501): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1501): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1501): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1501): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1501): No account for auth token provided
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 67360(3MB) AllocSpace objects, 9(751KB) LOS objects, 36% free, 27MB/43MB, paused 1.532ms total 63.737ms
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3814): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3814): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3814): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/art     (  821): Explicit concurrent mark sweep GC freed 31207(1500KB) AllocSpace objects, 5(174KB) LOS objects, 31% free, 34MB/50MB, paused 1.387ms total 85.888ms
,V/GoogleAuthProtoRequest( 3299): [344] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3299): [345] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3299): [345] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3299): [345] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3299): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3299): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3299): 	at com.a.a.k.run(SourceFile:110)
D/Finsky  ( 3814): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3814): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3814): [1] 5.onFinished: Giving up after 6 failures.
,W/ExperimentUpdateService( 3299): [344] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3299): [344] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3299): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3299): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3299): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,V/KeepSync( 3329): Connecting to GoogleApiClient
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at blb.a(PG:3937)
E/HttpOperation( 2998): 	at czp.a(PG:18188)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 12 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 14 more
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	,at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 3329): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
E/HttpOperation( 2998): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at hec.a(PG:42)
E/HttpOperation( 2998): 	at hee.a(PG:102)
E/HttpOperation( 2998): 	at czr.a(PG:65)
E/HttpOperation( 2998): 	at kka.a(PG:108)
E/HttpOperation( 2998): 	at czp.a(PG:19176)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 15 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 17 more
,E/ExperimentLoader( 2998): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): 	at jdm.a(PG:82)
E/ExperimentLoader( 2998): 	at jcs.o(PG:406)
E/ExperimentLoader( 2998): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2998): 	at jcs.i(PG:143)
E/ExperimentLoader( 2998): 	at hec.a(PG:42)
E/ExperimentLoader( 2998): ,	at hee.a(PG:102)
E/ExperimentLoader( 2998): 	at czr.a(PG:65)
E/ExperimentLoader( 2998): 	at kka.a(PG:108)
E/ExperimentLoader( 2998): 	at czp.a(PG:19176)
E/ExperimentLoader( 2998): 	at czp.a(PG:9081)
E/ExperimentLoader( 2998): 	at czq.run(PG:1686)
E/ExperimentLoader( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2998): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2998): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2998): 	at jdm.a(PG:77)
E/ExperimentLoader( 2998): 	... 15 more,
E/ExperimentLoader( 2998): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2998): 	at fal.a(PG:38)
E/ExperimentLoader( 2998): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2998): 	... 17 more
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted),
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 181307, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/BooksSync( 3554): Starting books sync for 61035162, extras: ade
,E/KeepSync( 3329): IOException
E/KeepSync( 3329): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3329): ,	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3329): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3329): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3329): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3329): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3329): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3329): 	... 10 more
,W/KeepSync( 3329): Sync result 2
,I/BooksConfig( 3554): GmsCore Version = 7.8.99 (2134222-430)
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 182505, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3554): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3554): Soft error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3554): Sync error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3554): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 183384, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1213): run()
I/Keyboard.Facilitator( 1213): flushDynamicLanguageModels()
,I/ConfigService( 1501): onCreate
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3225): 
,I/ConfigService( 1501): onDestroy
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at blb.a(PG:3937)
E/HttpOperation( 2998): 	at czp.a(PG:18188)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 12 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 14 more
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at hec.a(PG:42)
E/HttpOperation( 2998): 	at hee.a(PG:102)
E/HttpOperation( 2998): 	at czr.a(PG:65)
E/HttpOperation( 2998): 	at kka.a(PG:108)
E/HttpOperation( 2998): 	at czp.a(PG:19176)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 15 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 17 more
,E/ExperimentLoader( 2998): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 2998): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): 	at jdm.a(PG:82)
E/ExperimentLoader( 2998): 	at jcs.o(PG:406)
E/ExperimentLoader( 2998): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2998): 	at jcs.i(PG:143)
E/ExperimentLoader( 2998): 	at hec.a(PG:42)
E/ExperimentLoader( 2998): ,	at hee.a(PG:102)
E/ExperimentLoader( 2998): 	at czr.a(PG:65)
E/ExperimentLoader( 2998): 	at kka.a(PG:108)
E/ExperimentLoader( 2998): 	at czp.a(PG:19176)
E/ExperimentLoader( 2998): ,	at czp.a(PG:9081)
E/ExperimentLoader( 2998): 	at czq.run(PG:1686)
E/ExperimentLoader( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2998): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2998): 	at jdj.a(PG:1125)
,E/ExperimentLoader( 2998): 	at jdm.a(PG:77)
E/ExperimentLoader( 2998): 	... 15 more
E/ExperimentLoader( 2998): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2998): 	at fal.a(PG:38)
E/ExperimentLoader( 2998): 	at jdj.a(PG:4089),
E/ExperimentLoader( 2998): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 272144, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,V/GoogleAuthProtoRequest( 3299): [346] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3299): [347] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3299): [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3299): [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3299): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3299): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3299): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3299): [347] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3299): [347] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3299): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3299): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3299): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/BooksSync( 3554): Starting books sync for 61035162, extras: ade
,I/art     (  821): Explicit concurrent mark sweep GC freed 36005(1609KB) AllocSpace objects, 10(631KB) LOS objects, 32% free, 33MB/49MB, paused 2.143ms total 89.469ms
,I/BooksConfig( 3554): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3329): Connecting to GoogleApiClient
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 3329): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted),
V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,E/BooksAccountManager( 3554): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3554): Soft error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3554): Sync error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3554): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 273974, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 53339(2MB) AllocSpace objects, 11(1212KB) LOS objects, 37% free, 26MB/42MB, paused 1.636ms total 25.765ms,
,E/KeepSync( 3329): IOException
E/KeepSync( 3329): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3329): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3329): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3329): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3329): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3329): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3329): 	... 10 more
W/KeepSync( 3329): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 274149, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect called
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Coordinator is now connected to the server!
I/jxcore-log( 3225): 
,I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63),
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at blb.a(PG:3937)
E/HttpOperation( 2998): 	at czp.a(PG:18188)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
,E/HttpOperation( 2998): 	... 12 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 14 more
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at hec.a(PG:42)
E/HttpOperation( 2998): 	at hee.a(PG:102)
E/HttpOperation( 2998): 	at czr.a(PG:65)
E/HttpOperation( 2998): 	at kka.a(PG:108)
E/HttpOperation( 2998): 	at czp.a(PG:19176)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 15 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 17 more
,E/ExperimentLoader( 2998): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): 	at jdm.a(PG:82)
E/ExperimentLoader( 2998): 	at jcs.o(PG:406)
E/ExperimentLoader( 2998): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2998): 	at jcs.i(PG:143)
E/ExperimentLoader( 2998): 	at hec.a(PG:42)
E/ExperimentLoader( 2998): 	at hee.a(PG:102)
E/ExperimentLoader( 2998): 	at czr.a(PG:65)
E/ExperimentLoader( 2998): 	at kka.a(PG:108)
E/ExperimentLoader( 2998): 	at czp.a(PG:19176)
E/ExperimentLoader( 2998): 	at czp.a(PG:9081)
E/ExperimentLoader( 2998): 	at czq.run(PG:1686)
E/ExperimentLoader( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2998): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2998): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2998): 	at jdm.a(PG:77)
E/ExperimentLoader( 2998): 	... 15 more
E/ExperimentLoader( 2998): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2998): 	at fal.a(PG:38)
E/ExperimentLoader( 2998): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2998): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 396963, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3299): [348] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3299): [348] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3299): [348] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3299): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3299): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3299): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3299): [349] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3299): [349] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3299): [349] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3299): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3299): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3299): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/jxcore-log( 3225): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): DBG, CoordinatorConnector command called,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":19,"addressList":[{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"
,I/jxcore-log( 3225): Start now : testSendData.js
I/jxcore-log( 3225): 
I/jxcore-log( 3225): stop tests now !
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 19
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): check server
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): serverPort is 40230
I/jxcore-log( 3225): 
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3225): Stoping All
I/        ( 3225): Stopping services
I/        ( 3225): Stop Bluetooth
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3225): Start-My BT: F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3225):  mInstanceString : {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2491","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3225): All stuff available and enabled
,I/        ( 3225): Stoping All
I/        ( 3225): Stopping services
I/        ( 3225): Stop Bluetooth
I/        ( 3225): Starting All
I/        ( 3225): Stopping services
I/        ( 3225): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2491","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@db3aa88
,I/        ( 3225): Stopping services
I/        ( 3225): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2491","ra":"F8:CF:C5:D9:E5:61"}
I/        ( 3225): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2491","ra":"F8:CF:C5:D9:E5:61"}, length : 82
,I/        ( 3225): peerDiscoveryTimer timeout value:6951
,I/        ( 3225): Stop Bluetooth
I/        ( 3225): StartBluetooth listener
,I/        ( 3225): StartBluetooth listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3225): StartBroadcasting started ok
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:32.123Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:15:32.123Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:15:32.123Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
I/BTListenerThread( 3225): starting to listen
I/BTListenerThread( 3225): waiting to accept incoming Connection
,I/        ( 3225): Selected device address: 58:2A:F7:ED:96:BE, name: null
I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to null, at 58:2A:F7:ED:96:BE,
I/jxcore-log( 3225): 2015-11-25T10:15:32.134Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 3225): 
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/WB      ( 3225): We already were running, thus doing nothing
I/        ( 3225): Added local service
I/        ( 3225): Cleared service requests
,I/        ( 3225): Stopped peer discovery
I/        ( 3225): Started peer discovery
I/        ( 3225): Discovery state changed to Started.
,W/bt-sdp  ( 3282): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3282): invalid rfc slot id: 5
,I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:15:37.282Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:37.282Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:37.284Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3225): Found 1 peers.
,I/SS      ( 3225): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3225): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3225): Added service request
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3225): Started service discovery,
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3225): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3225): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT7376, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT7376, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3225): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6119, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6119, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3225): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1879, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1879, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3225): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6304"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6304"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6304, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6304, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3225): 2015-11-25T10:15:42.285Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:42.287Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3225): 
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/jxcore-log( 3225): 2015-11-25T10:15:47.292Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:47.292Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:47.294Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:47.295Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback,
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3225): Connecting to null, at 58:2A:F7:ED:96:BE
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab07c rs_disc_pending=0
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,D/btif_config( 3282): btif_get_device_type: Device [80:01:84:8a:b3:68] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
,E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,I/ActivityManager(  821): Start proc 3994:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@db62190:true
,I/ActivityManager(  821): Killing 3577:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3282): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,W/bt-sdp  ( 3282): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3282): invalid rfc slot id: 6
,I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:15:52.459Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:15:52.460Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:52.460Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:255,
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3225): we got incoming connection,
,I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTListenerThread( 3225): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTListenerThread( 3225): got MESSAGE_READ 84 bytes.
,I/BTListenerThread( 3225): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3225): MESSAGE_WRITE 82 bytes.
I/HS      ( 3225): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT9507
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3225): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT9507
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BTConnectedThread
,I/BtConnectorHelper( 3225): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3225): --DoOneRunRound started
,I/BtToRequestSocket( 3225): LocalHost address: localhost/127.0.0.1, port: 40230
,I/BtToRequestSocket( 3225): --DoOneRunRound ended
,I/jxcore-log( 3225): 2015-11-25T10:15:52.597Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.009Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.023Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.046Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.101Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.152Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.170Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.271Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.310Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.327Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.338Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.369Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.427Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.450Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.462Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.500Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.509Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.582Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.591Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.613Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.649Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.671Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.716Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.750Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.756Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.762Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.789Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.799Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.839Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.904Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.922Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:53.937Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data,
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3225): Found 6 peers.
,I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(3): A5-1 7e:f9:0e:37:96:ac,
I/SS      ( 3225): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3225): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3225): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3225): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3225): Added service request
,I/jxcore-log( 3225): 2015-11-25T10:15:54.023Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:54.080Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:54.136Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:54.144Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:54.150Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:54.214Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:54.268Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:54.276Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3225): ,
,I/jxcore-log( 3225): 2015-11-25T10:15:54.323Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:54.329Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:54.336Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:54.370Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:54.411Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:15:54.415Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3225): 
,W/bt-btif ( 3282): invalid rfc slot id: 4
,I/BtToSocketBase( 3225): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9507
I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9507
I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Close bt out
,I/BtToSocketBase( 3225): Close bt socket
I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
,I/jxcore-log( 3225): 2015-11-25T10:15:54.487Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3225): 
,W/bt-rfcomm( 3282): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 3282): RFCOMM_DisconnectInd LCID:0x44
,I/        ( 3225): Started service discovery
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/        ( 3225): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5232, peerAddress: 34:FC:EF:9D:93:0B,
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5232, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B,
,I/jxcore-log( 3225): 2015-11-25T10:15:57.462Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:15:57.463Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3225): 
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/ActivityManager(  821): Start proc 4020:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20e07a8e:true
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  821): Start proc 4046:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,I/BluetoothClassifier( 4020): Bluetooth Device Name: HTC Desire 820
,I/ActivityManager(  821): Killing 3711:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3648:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/        ( 3225): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1879, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1879, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3225): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6304"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6304"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6304, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6304, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/BooksSync( 3554): Starting books sync for 61035162, extras: ade
,I/        ( 3225): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5024","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5024","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT5024, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT5024, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/art     (  821): Explicit concurrent mark sweep GC freed 31254(1395KB) AllocSpace objects, 6(284KB) LOS objects, 32% free, 33MB/49MB, paused 1.516ms total 77.456ms
,V/KeepSync( 3329): Connecting to GoogleApiClient
,D/btif_config( 3282): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3282): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,I/BooksConfig( 3554): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 3329): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 3282): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,E/BooksAccountManager( 3554): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3554): Soft error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3554): Sync error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3554): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 429852, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:255
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3225): we got incoming connection
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTListenerThread( 3225): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,E/KeepSync( 3329): IOException
E/KeepSync( 3329): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3329): 	,at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3329): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3329): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3329): 	,at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3329): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3329): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3329): 	... 10 more
,W/KeepSync( 3329): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 430609, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BTListenerThread( 3225): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3225): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3225): MESSAGE_WRITE 82 bytes.
I/HS      ( 3225): Incoming connection Hand Shake finished for : LGE-LG-D802_PT5232
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3225): Starting the connected thread incoming : true, LGE-LG-D802_PT5232
,I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BTConnectedThread
I/BtConnectorHelper( 3225): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3225): --DoOneRunRound started
,I/BtToRequestSocket( 3225): LocalHost address: localhost/127.0.0.1, port: 40230
,I/BtToRequestSocket( 3225): --DoOneRunRound ended
I/jxcore-log( 3225): 2015-11-25T10:16:00.902Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.321Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.342Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.345Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.353Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.358Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.365Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.376Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.410Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.475Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.510Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.515Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.522Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.528Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.559Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.645Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.675Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.704Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.731Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.769Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.774Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.779Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.809Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.815Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.843Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.883Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.912Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.965Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:01.974Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.021Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.025Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.032Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.109Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.113Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.121Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.129Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.164Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.199Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.260Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.411Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.430Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.466Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.467Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:02.468Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:02.468Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3225): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab244 rs_disc_pending=1
W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3282): invalid rfc slot id: 7,
I/BtToSocketBase( 3225): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT5232
I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
,I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
,I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3225): Close bt in
I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT5232
I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt in
,I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToSocketBase( 3225): Close bt socket
I/jxcore-log( 3225): 2015-11-25T10:16:02.824Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3225): 
,W/bt-rfcomm( 3282): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 3282): RFCOMM_DisconnectInd LCID:0x47
,W/bt-btif ( 3282): info:x10,
D/        ( 3282): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2faaeb4 rs_disc_pending=1
W/bt-btif ( 3282): bta_dm_check_av:0
,W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1501): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1501): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1501): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1501): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1501): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1501): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1501): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3814): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3814): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3814): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3814): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3814): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3814): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3814): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3814): Ignoring header User-Agent because its value was null.
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab244 rs_disc_pending=0
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,D/btif_config( 3282): btif_get_device_type: Device [58:2a:f7:ed:96:be] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
D/BluetoothAdapterProperties( 3282): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3225): Starting to Handshake
,I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTConnectToThread( 3225): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 3225): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT8047","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3225): HandshakeOk : HUAWEI-ALE-L21_PT8047
I/HS      ( 3225): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT8047
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT8047
,I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): mHTTPPort  set to : 33319
,I/BtConnectorHelper( 3225): Request socket is using : 33319
,I/BtToRequestSocket( 3225): Now accepting connections
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab244 rs_disc_pending=1
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :33319
,I/jxcore-log( 3225): 2015-11-25T10:16:04.826Z SendDataConnector.js: CLIENT connected to 33319, error: null
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:04.828Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 33319
I/BtToRequestSocket( 3225): Set local streams
,I/BtToRequestSocket( 3225): rin ended ---------------------------;
,I/jxcore-log( 3225): 2015-11-25T10:16:04.839Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10308,tx.queue.count:11,available:24707
,I/jxcore-log( 3225): 2015-11-25T10:16:05.098Z SendDataConnector.js: CLIENT is data received : 10000,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:05.121Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3225): 2015-11-25T10:16:05.176Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:05.239Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3225): 2015-11-25T10:16:05.284Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:05.338Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:05.486Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): ,
,I/jxcore-log( 3225): 2015-11-25T10:16:05.519Z SendDataConnector.js: CLIENT is data received : 80000,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:05.638Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:05.728Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:05.735Z SendDataConnector.js: got all data for this round,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:05.741Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:05.742Z SendDataConnector.js: CLIENT closeClientSocket
,I/jxcore-log( 3225): 
I/BtConnectorHelper( 3225): Disconnect outgoing peer: 58:2A:F7:ED:96:BE
,I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
,I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Close LocalOutputStream
,I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToRequestSocket( 3225): Close server socket
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3225): 2015-11-25T10:16:05.745Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3225): 
I/jxcore-log( 3225): ---- round done--------
I/jxcore-log( 3225): 
I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:05.748Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:05.748Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3225): 
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3225): 2015-11-25T10:16:05.748Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
I/        ( 3225): Selected device address: 7C:F9:0E:37:96:AB, name: null
I/        ( 3225): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 33616 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Thali Test's G2
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp,
,D/btif_config( 3282): btif_get_device_type: Device [7c:f9:0e:37:96:ab] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
D/BluetoothAdapterProperties( 3282): Failed to remove device: 7C:F9:0E:37:96:AB
I/BluetoothBondStateMachine( 3282): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 3225): Starting to Handshake
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTConnectToThread( 3225): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 3225): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9163","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3225): HandshakeOk : samsung-SM-A500FU_PT9163
I/HS      ( 3225): Hand Shake finished outgoing for : samsung-SM-A500FU_PT9163
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, samsung-SM-A500FU_PT9163,
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket,
I/BtToRequestSocket( 3225): mHTTPPort  set to : 41152
I/BtConnectorHelper( 3225): Request socket is using : 41152
I/BtToRequestSocket( 3225): Now accepting connections
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: ALE-L21
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :41152
,I/jxcore-log( 3225): 2015-11-25T10:16:09.736Z SendDataConnector.js: CLIENT connected to 41152, error: null,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:09.737Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): ,
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 41152
,I/BtToRequestSocket( 3225): Set local streams
,I/jxcore-log( 3225): 2015-11-25T10:16:09.746Z SendDataConnector.js: CLIENT now sending 100000 bytes of data,
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): rin ended ---------------------------;
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3225): Found 7 peers.,
I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3225): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3225): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3225): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3225): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3225): Added service request
,I/        ( 3225): Started service discovery
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3225): 2015-11-25T10:16:11.115Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3225): 
,I/        ( 3225): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9507, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9507, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3225): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5232, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5232, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3225): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT7376, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT7376, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3225): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6119, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6119, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3225): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1879, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1879, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3225): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6304"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6304"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT6304, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT6304, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3282): dm_pm_timer expires
W/bt-btif ( 3282): dm_pm_timer expires 0
W/bt-btif ( 3282): proc dm_pm_timer expires
,I/jxcore-log( 3225): 2015-11-25T10:16:18.702Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3225): 
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3225): 2015-11-25T10:16:22.944Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:23.099Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3199
,I/jxcore-log( 3225): 2015-11-25T10:16:23.182Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:23.233Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:23.280Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:23.680Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:23.740Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:24.767Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:24.768Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:24.774Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:24.775Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3225): 
,I/BtConnectorHelper( 3225): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
,I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in,
I/BtToSocketBase( 3225): Close LocalOutputStream
,I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Close bt in
,I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3225): Close bt out
,I/BtToSocketBase( 3225): Close bt socket
I/BtToRequestSocket( 3225): Close server socket
I/jxcore-log( 3225): 2015-11-25T10:16:24.789Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): ---- round done--------,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:24.791Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:24.792Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:24.792Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: F8:95:C7:87:3C:51, name: null
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3225): Connecting to null, at F8:95:C7:87:3C:51
,I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 19021 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,W/bt-btif ( 3282): info:x10,
D/        ( 3282): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp,
,D/btif_config( 3282): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3282): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3225): Starting to Handshake
,I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTConnectToThread( 3225): got MESSAGE_READ 76 bytes.
,I/BTConnectToThread( 3225): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3225): HandshakeOk : LGE-LG-H815_PT153
I/HS      ( 3225): Hand Shake finished outgoing for : LGE-LG-H815_PT153
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, LGE-LG-H815_PT153
,I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): mHTTPPort  set to : 45049
,I/BtConnectorHelper( 3225): Request socket is using : 45049
I/BtToRequestSocket( 3225): Now accepting connections
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :45049
,I/jxcore-log( 3225): 2015-11-25T10:16:27.383Z SendDataConnector.js: CLIENT connected to 45049, error: null
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:27.383Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 45049
I/BtToRequestSocket( 3225): Set local streams
,I/jxcore-log( 3225): 2015-11-25T10:16:27.398Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3225): 
I/BtToRequestSocket( 3225): rin ended ---------------------------;
,I/jxcore-log( 3225): 2015-11-25T10:16:27.527Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:27.844Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:28.150Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:28.279Z SendDataConnector.js: CLIENT is data received : 40000,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:28.394Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:28.469Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:28.570Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:28.697Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3225): 
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive,
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab5d4 rs_disc_pending=0
W/bt-btif ( 3282): bta_dm_check_av:0
,W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3225): 2015-11-25T10:16:29.676Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:30.510Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:30.510Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:30.514Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): ,
,I/jxcore-log( 3225): 2015-11-25T10:16:30.514Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3225): 
,I/BtConnectorHelper( 3225): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3225): Close bt in
,I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToRequestSocket( 3225): Close server socket
I/jxcore-log( 3225): 2015-11-25T10:16:30.522Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3225): 
I/jxcore-log( 3225): ---- round done--------
I/jxcore-log( 3225): 
I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:30.527Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:30.528Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:30.528Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3225): Connecting to null, at E0:DB:10:14:E2:C0
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 5720 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab5d4 rs_disc_pending=1
W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab5d4 rs_disc_pending=0
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: G4-1
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,D/btif_config( 3282): btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3282): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3282): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3225): Starting to Handshake
,I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTConnectToThread( 3225): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3225): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7850","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3225): HandshakeOk : samsung-SM-N910C_PT7850
I/HS      ( 3225): Hand Shake finished outgoing for : samsung-SM-N910C_PT7850
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, samsung-SM-N910C_PT7850
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): mHTTPPort  set to : 60038
,I/BtConnectorHelper( 3225): Request socket is using : 60038
I/BtToRequestSocket( 3225): Now accepting connections
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :60038
I/jxcore-log( 3225): 2015-11-25T10:16:36.635Z SendDataConnector.js: CLIENT connected to 60038, error: null
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:36.636Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 60038
I/BtToRequestSocket( 3225): Set local streams
,I/jxcore-log( 3225): 2015-11-25T10:16:36.647Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): rin ended ---------------------------;
,I/jxcore-log( 3225): 2015-11-25T10:16:36.815Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:36.882Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:36.972Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:37.040Z SendDataConnector.js: CLIENT is data received : 50000,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:37.083Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:37.089Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:37.172Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:37.241Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:37.242Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:37.247Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:37.249Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3225): 
I/BtConnectorHelper( 3225): Disconnect outgoing peer: E0:DB:10:14:E2:C0
I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3225): Close LocalOutputStream
,I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
,I/BtToRequestSocket( 3225): Close server socket
,I/jxcore-log( 3225): 2015-11-25T10:16:37.263Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): ---- round done--------,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:37.265Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:37.266Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:37.266Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/        ( 3225): Connecting to null, at F4:F1:E1:5C:3B:E2
,I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 6715 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab79c rs_disc_pending=0
W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3225): Found 7 peers.
I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3225): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3225): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3225): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(7): A3-1 0a:ec:a9:50:75:42
D/WifiP2pManager( 3225): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3225): Added service request
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab964 rs_disc_pending=1
W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab79c rs_disc_pending=1
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,I/        ( 3225): Started service discovery
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note4-1
,D/btif_config( 3282): btif_get_device_type: Device [f4:f1:e1:5c:3b:e2] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
,E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3282): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,I/        ( 3225): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9507, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9507, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3282): Failed to remove device: F4:F1:E1:5C:3B:E2
I/BluetoothBondStateMachine( 3282): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200,
I/BTConnectToThread( 3225): Starting to Handshake
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTConnectToThread( 3225): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3225): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3225): HandshakeOk : motorola-XT1039_PT6119,
,I/HS      ( 3225): Hand Shake finished outgoing for : motorola-XT1039_PT6119
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped,
I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, motorola-XT1039_PT6119
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3225): mHTTPPort  set to : 56124
I/BtConnectorHelper( 3225): Request socket is using : 56124
I/BtToRequestSocket( 3225): Now accepting connections
,I/        ( 3225): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5232, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5232, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3225): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
I/        ( 3225): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :56124
,I/jxcore-log( 3225): 2015-11-25T10:16:43.457Z SendDataConnector.js: CLIENT connected to 56124, error: null
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:43.458Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 56124,
I/BtToRequestSocket( 3225): Set local streams
,I/jxcore-log( 3225): 2015-11-25T10:16:43.468Z SendDataConnector.js: CLIENT now sending 100000 bytes of data,
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): rin ended ---------------------------;
,I/        ( 3225): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT7376, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT7376, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3225): 2015-11-25T10:16:43.763Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:43.863Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3225): 
,I/        ( 3225): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6119, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6119, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3225): 2015-11-25T10:16:44.033Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:44.132Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7159
,I/jxcore-log( 3225): 2015-11-25T10:16:44.185Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3225): ,
,I/jxcore-log( 3225): 2015-11-25T10:16:44.221Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:44.274Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:44.404Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:44.473Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:44.479Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3225): ,
,I/jxcore-log( 3225): 2015-11-25T10:16:44.479Z SendDataConnector.js: got all data for this round,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:44.486Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:44.489Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3225): 
,I/BtConnectorHelper( 3225): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
,I/BtToSocketBase( 3225): Stop ReceivingThread
,I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Close bt in
,I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToRequestSocket( 3225): Close server socket
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3225): 2015-11-25T10:16:44.497Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): ---- round done--------
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:44.501Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3225): 
W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
I/jxcore-log( 3225): 2015-11-25T10:16:44.503Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:44.503Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 7C:F9:0E:34:8A:A0, name: null
I/BTConnectToThread( 3225): Starting to connect,
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3225): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 7214 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3225): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1879, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1879, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3225): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5024","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5024","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT5024, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT5024, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,W/bt-btif ( 3282): info:x10,
,D/        ( 3282): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL,
,I/        ( 3225): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7850","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:,
,I/        ( 3225): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7850","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT7850, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT7850, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive,
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: XT1039
,W/bt-rfcomm( 3282): PORT_StartCnf failed result:5
,W/bt-btif ( 3282): invalid rfc slot id: 14
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btm  ( 3282): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fabb2c rs_disc_pending=2
E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3282): bta_dm_check_av:0
E/bt-btm  ( 3282): Device not in IRK list
E/bt-btif ( 3282): Do not find the bg connection mask for the remote device
I/jxcore-log( 3225): 2015-11-25T10:16:49.797Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:49.798Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:49.799Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c,
,I/BluetoothBondStateMachine( 3282): No record of the device:null
I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 9 Address: 7C:F9:0E:34:8A:A0 newState: 0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
E/BluetoothBondStateMachine( 3282): In stable state, received invalid newState: 10
E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3225): Found 6 peers.
I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3225): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3225): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3225): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3225): Added service request
,I/jxcore-log( 3225): 2015-11-25T10:16:54.800Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:54.801Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3225): Started service discovery
,I/        ( 3225): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9507, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9507, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3225): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5232, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5232, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3225): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3225): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT7376, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT7376, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3225): 2015-11-25T10:16:59.807Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:59.808Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:16:59.808Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:16:59.809Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3225): Connecting to null, at 7C:F9:0E:34:8A:A0
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [7c:f9:0e:37:96:ab]: 7, f, 610c
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 4020): Bluetooth Device Name: A5-1
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:255
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3225): we got incoming connection
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTListenerThread( 3225): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTListenerThread( 3225): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3225): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9163","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3225): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3225): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT9163
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3225): Starting the connected thread incoming : true, samsung-SM-A500FU_PT9163
,I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BTConnectedThread
I/BtConnectorHelper( 3225): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3225): --DoOneRunRound started
,I/BtToRequestSocket( 3225): LocalHost address: localhost/127.0.0.1, port: 40230
,I/BtToRequestSocket( 3225): --DoOneRunRound ended
,I/jxcore-log( 3225): 2015-11-25T10:17:01.164Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:01.741Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:01.821Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:01.955Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.064Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.089Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.108Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.123Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.160Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3225): 
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3225): 2015-11-25T10:17:02.220Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.231Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.251Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.290Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3225): 
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,I/jxcore-log( 3225): 2015-11-25T10:17:02.308Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.314Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.341Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.354Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.391Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.400Z SendDataTCPServer.js: TCP/IP server has received 40960 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.413Z SendDataTCPServer.js: TCP/IP server has received 42940 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.450Z SendDataTCPServer.js: TCP/IP server has received 50860 bytes of data
I/jxcore-log( 3225): ,
,I/jxcore-log( 3225): 2015-11-25T10:17:02.476Z SendDataTCPServer.js: TCP/IP server has received 52840 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.510Z SendDataTCPServer.js: TCP/IP server has received 58780 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.513Z SendDataTCPServer.js: TCP/IP server has received 60760 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.534Z SendDataTCPServer.js: TCP/IP server has received 62740 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.569Z SendDataTCPServer.js: TCP/IP server has received 66700 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.573Z SendDataTCPServer.js: TCP/IP server has received 68680 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.588Z SendDataTCPServer.js: TCP/IP server has received 70660 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.598Z SendDataTCPServer.js: TCP/IP server has received 72640 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.629Z SendDataTCPServer.js: TCP/IP server has received 74620 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.643Z SendDataTCPServer.js: TCP/IP server has received 76600 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.654Z SendDataTCPServer.js: TCP/IP server has received 78580 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.721Z SendDataTCPServer.js: TCP/IP server has received 80560 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.730Z SendDataTCPServer.js: TCP/IP server has received 82540 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.769Z SendDataTCPServer.js: TCP/IP server has received 86500 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.777Z SendDataTCPServer.js: TCP/IP server has received 88480 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.785Z SendDataTCPServer.js: TCP/IP server has received 90460 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.791Z SendDataTCPServer.js: TCP/IP server has received 92440 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.892Z SendDataTCPServer.js: TCP/IP server has received 94420 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.937Z SendDataTCPServer.js: TCP/IP server has received 96400 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:02.969Z SendDataTCPServer.js: TCP/IP server has received 98380 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:03.009Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3225): 
,D/btif_config( 3282): btif_get_device_type: Device [7c:f9:0e:34:8a:a0] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
D/BluetoothAdapterProperties( 3282): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3225): Starting to Handshake
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTConnectToThread( 3225): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3225): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3225): HandshakeOk : samsung-SM-G900F_PT4115
I/HS      ( 3225): Hand Shake finished outgoing for : samsung-SM-G900F_PT4115
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, samsung-SM-G900F_PT4115
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): mHTTPPort  set to : 49014
,I/BtConnectorHelper( 3225): Request socket is using : 49014
I/BtToRequestSocket( 3225): Now accepting connections
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :49014
,I/jxcore-log( 3225): 2015-11-25T10:17:03.685Z SendDataConnector.js: CLIENT connected to 49014, error: null,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:03.686Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 49014,
I/BtToRequestSocket( 3225): Set local streams
I/jxcore-log( 3225): 2015-11-25T10:17:03.696Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): rin ended ---------------------------;
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:675
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,I/jxcore-log( 3225): 2015-11-25T10:17:04.620Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:04.678Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3225): 
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3225): 2015-11-25T10:17:04.904Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:05.473Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:05.574Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:05.670Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:05.765Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:05.944Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3225): 
,D/btif_config( 3282): btif_get_device_type: Device [08:ec:a9:50:76:27] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,I/jxcore-log( 3225): 2015-11-25T10:17:06.622Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:06.699Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:06.699Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:06.702Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:06.705Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3225): 
,I/BtConnectorHelper( 3225): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
,I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
,I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3225): Close bt out
,I/BtToSocketBase( 3225): Close bt socket
I/BtToRequestSocket( 3225): Close server socket
I/jxcore-log( 3225): 2015-11-25T10:17:06.716Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): ---- round done--------
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:06.721Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:06.723Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:06.725Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820,
,I/        ( 3225): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68,
,I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 22198 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
D/BluetoothAdapterProperties( 3282): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fabb2c rs_disc_pending=0,
W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3225): we got incoming connection
,I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTListenerThread( 3225): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTListenerThread( 3225): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3225): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3108","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3225): MESSAGE_WRITE 82 bytes.
I/HS      ( 3225): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT3108
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3225): Starting the connected thread incoming : true, samsung-SM-A300FU_PT3108
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BTConnectedThread
,I/BtConnectorHelper( 3225): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3225): --DoOneRunRound started
,I/BtToRequestSocket( 3225): LocalHost address: localhost/127.0.0.1, port: 40230
,I/BtToRequestSocket( 3225): --DoOneRunRound ended
,I/jxcore-log( 3225): 2015-11-25T10:17:08.809Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3225): 
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fabb2c rs_disc_pending=1
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3225): 2015-11-25T10:17:09.577Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:09.717Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:09.868Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3225): 
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [80:01:84:8a:b3:68]: 0, 0, 0
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3282): dm_pm_timer expires
W/bt-btif ( 3282): dm_pm_timer expires 0
W/bt-btif ( 3282): proc dm_pm_timer expires
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3225): Found 6 peers.
I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3225): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3225): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3225): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3225): Added service request
,I/jxcore-log( 3225): 2015-11-25T10:17:10.253Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:10.256Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data,
I/jxcore-log( 3225): 
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,I/jxcore-log( 3225): 2015-11-25T10:17:10.542Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
,I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:10.636Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:10.857Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:10.900Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:10.904Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3225): 
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,I/jxcore-log( 3225): 2015-11-25T10:17:10.945Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data,
I/jxcore-log( 3225): 
D/BluetoothMapService( 3282): onReceive
,I/jxcore-log( 3225): 2015-11-25T10:17:10.953Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3225): 
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: S5-1
,I/jxcore-log( 3225): 2015-11-25T10:17:10.986Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3225): 
,I/        ( 3225): Started service discovery
,I/jxcore-log( 3225): 2015-11-25T10:17:11.155Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:11.161Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:11.216Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3225): 
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3225): Starting to Handshake
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3225): 2015-11-25T10:17:11.673Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:11.682Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3225): 
,I/BTConnectToThread( 3225): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3225): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3225): HandshakeOk : HTC-HTC Desire 820_PT9507
I/HS      ( 3225): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9507
I/jxcore-log( 3225): 2015-11-25T10:17:11.729Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3225): 
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9507
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): mHTTPPort  set to : 53411
I/BtConnectorHelper( 3225): Request socket is using : 53411
I/BtToRequestSocket( 3225): Now accepting connections
,I/jxcore-log( 3225): 2015-11-25T10:17:11.822Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:11.855Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:11.862Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:11.869Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:11.907Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:11.913Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:11.920Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:11.966Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:11.977Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.015Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.024Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.033Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data,
I/jxcore-log( 3225): 
I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :53411
I/jxcore-log( 3225): 2015-11-25T10:17:12.035Z SendDataConnector.js: CLIENT connected to 53411, error: null
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:12.036Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 53411,
I/BtToRequestSocket( 3225): Set local streams
,I/jxcore-log( 3225): 2015-11-25T10:17:12.044Z SendDataConnector.js: CLIENT now sending 100000 bytes of data,
I/jxcore-log( 3225): 
I/BtToRequestSocket( 3225): rin ended ---------------------------;
,I/jxcore-log( 3225): 2015-11-25T10:17:12.088Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.127Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.134Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.182Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.189Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.195Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.308Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.314Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.349Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.373Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.433Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.496Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.504Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.631Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.666Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.730Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.742Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.797Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.905Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:12.917Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3225): 
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3225): 2015-11-25T10:17:12.964Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:13.075Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:13.137Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:13.139Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:13.268Z SendDataConnector.js: CLIENT is data received : 30000,
I/jxcore-log( 3225): 
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fabcf4 rs_disc_pending=0
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3225): 2015-11-25T10:17:13.588Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:14.132Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3225): 
,W/bt-btif ( 3282): invalid rfc slot id: 16
,I/BtToSocketBase( 3225): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT3108
,I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
,I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3225): Close bt out
I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3225): Close bt socket
I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT3108
I/BtToSocketBase( 3225): Close bt in
,I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/jxcore-log( 3225): 2015-11-25T10:17:14.339Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:14.478Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3225): 
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fabcf4 rs_disc_pending=1
W/bt-btif ( 3282): bta_dm_check_av:0
,W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3282): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
,W/bt-rfcomm( 3282): RFCOMM_DisconnectInd LCID:0x4e
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fabcf4 rs_disc_pending=0
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 3282): dm_pm_timer expires
,W/bt-btif ( 3282): dm_pm_timer expires 0
W/bt-btif ( 3282): proc dm_pm_timer expires
,I/        ( 3225): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5868, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5868, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05,
,W/bt-btif ( 3282): invalid rfc slot id: 8,
I/BtToSocketBase( 3225): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT9163
I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT9163
I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToSocketBase( 3225): Close bt in
,I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
I/jxcore-log( 3225): 2015-11-25T10:17:23.406Z SendDataTCPServer.js: TCP/IP server is ended,
I/jxcore-log( 3225): 
,D/BluetoothMapService( 3282): onReceive,
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524],
I/BluetoothClassifier( 4020): Bluetooth Device Name: A5-1
,I/jxcore-log( 3225): 2015-11-25T10:17:24.479Z SendDataConnector.js: Receiving data timeout now,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:24.480Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:24.482Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:24.482Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:24.483Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3225): 
,I/BtToSocketBase( 3225): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3225): Disconnect outgoing peer: HTC-HTC Desire 820_PT9507
I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
,I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
,I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToRequestSocket( 3225): Close server socket
,I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/        ( 3225): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9507, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9507, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/jxcore-log( 3225): 2015-11-25T10:17:29.484Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:29.485Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3225): 
,I/        ( 3225): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3225): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT7376, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT7376, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 3281): wlan0: WPA: Group rekeying completed with c0:ff:d4:d3:aa:4a [GTK=CCMP],
,I/jxcore-log( 3225): 2015-11-25T10:17:34.488Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
,I/jxcore-log( 3225): ,
I/jxcore-log( 3225): 2015-11-25T10:17:34.489Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3225): ,
I/jxcore-log( 3225): 2015-11-25T10:17:34.490Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:34.490Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): btm_sec_disconnected - 
E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothMapService( 3282): onReceive
I/jxcore-log( 3225): 2015-11-25T10:17:35.026Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:35.027Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:35.028Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: HTC Desire 820
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,I/jxcore-log( 3225): 2015-11-25T10:17:40.029Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:40.030Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3225): Found 7 peers.
I/SS      ( 3225): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3225): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3225): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3225): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3225): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3225): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3225): Added service request,
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3281): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3225): Started service discovery
,I/jxcore-log( 3225): 2015-11-25T10:17:45.033Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:45.034Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:45.035Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:45.035Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820,
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3225): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3225): Starting to Handshake
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTConnectToThread( 3225): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3225): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3225): HandshakeOk : HTC-HTC Desire 820_PT9507
I/HS      ( 3225): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9507
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9507
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): mHTTPPort  set to : 56793
,I/BtConnectorHelper( 3225): Request socket is using : 56793
I/BtToRequestSocket( 3225): Now accepting connections
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :56793
,I/jxcore-log( 3225): 2015-11-25T10:17:47.372Z SendDataConnector.js: CLIENT connected to 56793, error: null
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:47.372Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 56793
,I/BtToRequestSocket( 3225): Set local streams
I/BtToRequestSocket( 3225): rin ended ---------------------------;
,I/jxcore-log( 3225): 2015-11-25T10:17:47.382Z SendDataConnector.js: CLIENT now sending 40000 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:47.562Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:47.616Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:47.674Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:47.736Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:47.737Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:47.741Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:47.742Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3225): 
,I/BtConnectorHelper( 3225): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 3225): Stop ReceivingThread
,I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Close LocalOutputStream
,I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Close bt in
,I/BtToSocketBase( 3225): Close bt out
,I/BtToSocketBase( 3225): Close bt socket,
,I/BtToRequestSocket( 3225): Close server socket,
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3225): 2015-11-25T10:17:47.752Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
,I/jxcore-log( 3225): 
I/jxcore-log( 3225): ---- round done--------
,I/jxcore-log( 3225): 
I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3225): ,
I/jxcore-log( 3225): 2015-11-25T10:17:47.755Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:47.755Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
,I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:47.756Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
I/        ( 3225): Selected device address: E0:DB:10:1F:C9:5E, name: null
,W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to null, at E0:DB:10:1F:C9:5E
D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 41015 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63),
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab07c rs_disc_pending=1
W/bt-btif ( 3282): bta_dm_check_av:0
,W/bt-btif ( 3282): btif_dm_cback : unhandled event (14),
,I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fabebc rs_disc_pending=1
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,D/btif_config( 3282): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
,E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3282): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab07c rs_disc_pending=0
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
D/BluetoothAdapterProperties( 3282): Failed to remove device: E0:DB:10:1F:C9:5E,
I/BluetoothBondStateMachine( 3282): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fabebc rs_disc_pending=0
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3225): Starting to Handshake
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTConnectToThread( 3225): got MESSAGE_READ 82 bytes.,
I/BTConnectToThread( 3225): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3225): HandshakeOk : samsung-SM-N9005_PT1879
,I/HS      ( 3225): Hand Shake finished outgoing for : samsung-SM-N9005_PT1879
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, samsung-SM-N9005_PT1879
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): mHTTPPort  set to : 35581
,I/BtConnectorHelper( 3225): Request socket is using : 35581
I/BtToRequestSocket( 3225): Now accepting connections
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :35581
,I/jxcore-log( 3225): 2015-11-25T10:17:52.387Z SendDataConnector.js: CLIENT connected to 35581, error: null
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:52.390Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 35581,
I/BtToRequestSocket( 3225): Set local streams,
,I/BtToRequestSocket( 3225): rin ended ---------------------------;
I/jxcore-log( 3225): 2015-11-25T10:17:52.402Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:93
,I/jxcore-log( 3225): 2015-11-25T10:17:52.565Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:52.890Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:52.961Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:53.079Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:53.083Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:53.119Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:53.198Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:53.285Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:53.342Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:53.533Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:53.534Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:53.540Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:53.541Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3225): 
,I/BtConnectorHelper( 3225): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
,I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToRequestSocket( 3225): Close server socket
,I/jxcore-log( 3225): 2015-11-25T10:17:53.556Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): ---- round done--------,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:17:53.559Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:53.559Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:17:53.559Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 3225): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 5780 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3225): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5868, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5868, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fabebc rs_disc_pending=1
W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1,
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3225): Found 6 peers.
I/SS      ( 3225): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3225): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(3): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3225): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3225): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3225): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3225): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3225): Added service request
,I/        ( 3225): Started service discovery
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3225): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9488","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9488","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT9488, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT9488, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3225): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5024","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5024","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT5024, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT5024, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3225): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5868, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5868, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-rfcomm( 3282): PORT_StartCnf failed result:5
,E/bt-btm  ( 3282): invalid rfc slot id: 22
W/bt-btif ( 3282): invalid rfc slot id: 22
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothMapService( 3282): onReceive
I/jxcore-log( 3225): 2015-11-25T10:18:15.139Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:15.139Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:15.140Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/SS      ( 3225): Found 5 peers.
,I/SS      ( 3225): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3225): Peer(2): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3225): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3225): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3225): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3225): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3225): Added service request
,I/        ( 3225): Started service discovery
,I/jxcore-log( 3225): 2015-11-25T10:18:20.142Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:20.142Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:25.146Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:25.147Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:25.148Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:25.148Z SendDataConnector.js: do connect now
,I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/        ( 3225): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5024","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5024","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT5024, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT5024, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,W/bt-sdp  ( 3282): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3282): invalid rfc slot id: 23
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:18:30.312Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:30.313Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:30.313Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:35.315Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:35.316Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3225): 
,I/        ( 3225): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5868, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5868, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 3225): 2015-11-25T10:18:40.320Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:40.321Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:40.322Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:40.322Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback,
I/        ( 3225): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3225): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}, typeCordovap2p._tcp.local.:,
I/        ( 3225): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9507, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9507, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3225): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}, typeCordovap2p._tcp.local.:,
I/        ( 3225): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5232, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5232, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3225): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"}, typeCordovap2p._tcp.local.:,
I/        ( 3225): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT7376, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT7376, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3,
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Thali Test (Galaxy A3),
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,I/        ( 3225): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT153, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT153, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3225): Starting to Handshake
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTConnectToThread( 3225): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 3225): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3108","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3225): HandshakeOk : samsung-SM-A300FU_PT3108
I/HS      ( 3225): Hand Shake finished outgoing for : samsung-SM-A300FU_PT3108
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, samsung-SM-A300FU_PT3108
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): mHTTPPort  set to : 50334
,I/BtConnectorHelper( 3225): Request socket is using : 50334
,I/BtToRequestSocket( 3225): Now accepting connections
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :50334
,I/jxcore-log( 3225): 2015-11-25T10:18:43.294Z SendDataConnector.js: CLIENT connected to 50334, error: null
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:43.296Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 50334
I/BtToRequestSocket( 3225): Set local streams
,I/BtToRequestSocket( 3225): rin ended ---------------------------;
I/jxcore-log( 3225): 2015-11-25T10:18:43.319Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4504
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3225): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3108","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3108","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3108, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3108, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3225): 2015-11-25T10:18:43.874Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19039
,I/jxcore-log( 3225): 2015-11-25T10:18:43.991Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3225): 
,I/        ( 3225): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6119, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6119, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3225): 2015-11-25T10:18:44.542Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9139
,I/jxcore-log( 3225): 2015-11-25T10:18:44.555Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:44.881Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3225): 2015-11-25T10:18:45.218Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3225): 
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3225): 2015-11-25T10:18:45.613Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:45.738Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:45.951Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3225): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:,
I/        ( 3225): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3225): 2015-11-25T10:18:46.231Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:46.232Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:46.235Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:46.235Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3225): 
I/BtConnectorHelper( 3225): Disconnect outgoing peer: 08:EC:A9:50:76:27
I/BtToSocketBase( 3225): Stop ReceivingThread,
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket,
,I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToRequestSocket( 3225): Close server socket
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
,I/jxcore-log( 3225): 2015-11-25T10:18:46.245Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): ---- round done--------
I/jxcore-log( 3225): 
I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:46.248Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:46.248Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:46.248Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
I/        ( 3225): Selected device address: 34:FC:EF:11:AE:67, name: null
I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to null, at 34:FC:EF:11:AE:67
D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 52673 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/        ( 3225): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fac084 rs_disc_pending=1
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,D/btif_config( 3282): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,I/        ( 3225): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9163","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9163","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9163, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9163, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 3282): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3225): Starting to Handshake
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
,I/BTConnectToThread( 3225): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3225): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3699","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3225): HandshakeOk : LGE-Nexus 5_PT3699
I/HS      ( 3225): Hand Shake finished outgoing for : LGE-Nexus 5_PT3699
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, LGE-Nexus 5_PT3699,
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): mHTTPPort  set to : 47777,
I/BtConnectorHelper( 3225): Request socket is using : 47777
I/BtToRequestSocket( 3225): Now accepting connections
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :47777
,I/jxcore-log( 3225): 2015-11-25T10:18:49.005Z SendDataConnector.js: CLIENT connected to 47777, error: null
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:49.006Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 47777
,I/BtToRequestSocket( 3225): Set local streams
,I/jxcore-log( 3225): 2015-11-25T10:18:49.013Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): rin ended ---------------------------;
,I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16792
,I/jxcore-log( 3225): 2015-11-25T10:18:49.554Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18049
,I/jxcore-log( 3225): 2015-11-25T10:18:49.651Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13099
,I/jxcore-log( 3225): 2015-11-25T10:18:49.764Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:49.941Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3225): 
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
I/jxcore-log( 3225): 2015-11-25T10:18:50.145Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:50.409Z SendDataConnector.js: CLIENT is data received : 60000,
I/jxcore-log( 3225): 
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fac084 rs_disc_pending=0
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3225): 2015-11-25T10:18:50.819Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:50.921Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:51.150Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:51.366Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:51.367Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:51.372Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:51.373Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3225): 
,I/BtConnectorHelper( 3225): Disconnect outgoing peer: 34:FC:EF:11:AE:67,
,I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
,I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToRequestSocket( 3225): Close server socket
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3225): 2015-11-25T10:18:51.385Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3225): 
I/jxcore-log( 3225): ---- round done--------
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:51.389Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:51.389Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:51.390Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 34:FC:EF:9D:93:0B, name: Thali Test's G2
,I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to Thali Test's G2, at 34:FC:EF:9D:93:0B
W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 5120 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fac084 rs_disc_pending=1
W/bt-btif ( 3282): bta_dm_check_av:0
,W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Thali Test's G2,
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3225): Starting to Handshake
,I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTConnectToThread( 3225): got MESSAGE_READ 77 bytes.,
I/BTConnectToThread( 3225): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3225): HandshakeOk : LGE-LG-D802_PT5232
I/HS      ( 3225): Hand Shake finished outgoing for : LGE-LG-D802_PT5232
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, LGE-LG-D802_PT5232
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): mHTTPPort  set to : 51676
,I/BtConnectorHelper( 3225): Request socket is using : 51676
I/BtToRequestSocket( 3225): Now accepting connections
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :51676
,I/jxcore-log( 3225): 2015-11-25T10:18:53.221Z SendDataConnector.js: CLIENT connected to 51676, error: null
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:53.221Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 51676
I/BtToRequestSocket( 3225): Set local streams
,I/jxcore-log( 3225): 2015-11-25T10:18:53.237Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): rin ended ---------------------------;
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1393
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3225): 2015-11-25T10:18:53.969Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:54.348Z SendDataConnector.js: CLIENT is data received : 20000
,I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:54.848Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:54.914Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3225): 
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,I/jxcore-log( 3225): 2015-11-25T10:18:55.069Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3225): 
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3225): 2015-11-25T10:18:55.173Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:55.276Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,I/jxcore-log( 3225): 2015-11-25T10:18:55.323Z SendDataConnector.js: CLIENT is data received : 80000,
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3225): Found 10 peers.
I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3225): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3225): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3225): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3225): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3225): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3225): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3225): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3225): Added service request
,I/jxcore-log( 3225): 2015-11-25T10:18:55.428Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:55.695Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:55.696Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:55.709Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:55.710Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3225): 
I/BtConnectorHelper( 3225): Disconnect outgoing peer: 34:FC:EF:9D:93:0B
I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToRequestSocket( 3225): Close server socket
,I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3225): 2015-11-25T10:18:55.719Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3225): 
I/jxcore-log( 3225): ---- round done--------
I/jxcore-log( 3225): 
I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:18:55.721Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:55.721Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:18:55.721Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
I/        ( 3225): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback,
I/        ( 3225): Connecting to null, at 50:2E:6C:AC:21:50
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 4310 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3281): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3225): Started service discovery
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3225): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1879, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1879, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab244 rs_disc_pending=0
W/bt-btif ( 3282): bta_dm_check_av:0
,W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,D/btif_config( 3282): btif_get_device_type: Device [50:2e:6c:ac:21:50] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
,E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
D/BluetoothAdapterProperties( 3282): Failed to remove device: 50:2E:6C:AC:21:50
I/BluetoothBondStateMachine( 3282): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,I/BTConnectToThread( 3225): Starting to Handshake
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTConnectToThread( 3225): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 3225): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3225): HandshakeOk : HTC-HTC One_M8_PT4589
I/HS      ( 3225): Hand Shake finished outgoing for : HTC-HTC One_M8_PT4589
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, HTC-HTC One_M8_PT4589
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): mHTTPPort  set to : 53239
I/BtConnectorHelper( 3225): Request socket is using : 53239
I/BtToRequestSocket( 3225): Now accepting connections
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :53239
,I/jxcore-log( 3225): 2015-11-25T10:19:03.808Z SendDataConnector.js: CLIENT connected to 53239, error: null
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:03.809Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 53239
,I/BtToRequestSocket( 3225): Set local streams
I/jxcore-log( 3225): 2015-11-25T10:19:03.816Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3225): 
I/BtToRequestSocket( 3225): rin ended ---------------------------;
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23853,
,I/jxcore-log( 3225): 2015-11-25T10:19:03.960Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14943
,I/jxcore-log( 3225): 2015-11-25T10:19:03.998Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:04.003Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7023
,I/jxcore-log( 3225): 2015-11-25T10:19:04.048Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3225): 
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,I/jxcore-log( 3225): 2015-11-25T10:19:04.095Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:04.154Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:04.193Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:04.202Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:04.271Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:04.309Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:04.310Z SendDataConnector.js: got all data for this round,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:04.313Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:04.314Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3225): 
I/BtConnectorHelper( 3225): Disconnect outgoing peer: 50:2E:6C:AC:21:50
I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToRequestSocket( 3225): Close server socket
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3225): 2015-11-25T10:19:04.319Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3225): 
I/jxcore-log( 3225): ---- round done--------
I/jxcore-log( 3225): 
I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:04.322Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:04.322Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3225): ,
I/jxcore-log( 3225): 2015-11-25T10:19:04.323Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): ,
I/        ( 3225): Selected device address: 44:80:EB:7B:5A:05, name: null
I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to null, at 44:80:EB:7B:5A:05
,W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 8590 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fac24c rs_disc_pending=1
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,V/GoogleAuthProtoRequest( 3299): [350] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3299): [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3299): [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3299): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3299): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3299): 	at com.a.a.k.run(SourceFile:110)
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL,
,V/GoogleAuthProtoRequest( 3299): [351] a.<init>: mAccountName set to: thalitester@gmail.com
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3299): [351] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3299): [351] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
,W/ExperimentUpdateService( 3299): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3299): 	,at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3299): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3299): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3299): 	,at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3299): 	at com.a.a.k.run(SourceFile:110)
,D/btif_config( 3282): btif_get_device_type: Device [44:80:eb:7b:5a:05] type 1
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3282): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3282): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3282): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3282): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0,
D/BluetoothAdapterProperties( 3282): Failed to remove device: 44:80:EB:7B:5A:05
I/BluetoothBondStateMachine( 3282): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3282): StableState(): Entering Off State
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3225): Starting to Handshake
,I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3225): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,I/BTConnectToThread( 3225): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3225): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3225): HandshakeOk : motorola-XT1072_PT5868
I/HS      ( 3225): Hand Shake finished outgoing for : motorola-XT1072_PT5868
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3225): Starting the connected thread incoming : false, motorola-XT1072_PT5868
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3225): mHTTPPort  set to : 40366
,I/BtConnectorHelper( 3225): Request socket is using : 40366
I/BtToRequestSocket( 3225): Now accepting connections
,I/BtConnectorHelper( 3225): Calling ConnectionStatusUpdate with port :40366
,I/jxcore-log( 3225): 2015-11-25T10:19:06.268Z SendDataConnector.js: CLIENT connected to 40366, error: null
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:06.269Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): incoming data from: /127.0.0.1, port: 40366
,I/BtToRequestSocket( 3225): Set local streams
I/jxcore-log( 3225): 2015-11-25T10:19:06.276Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3225): 
I/BtToRequestSocket( 3225): rin ended ---------------------------;
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3225): 2015-11-25T10:19:06.428Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18049
,I/jxcore-log( 3225): 2015-11-25T10:19:06.468Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15079
,I/jxcore-log( 3225): 2015-11-25T10:19:06.479Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3225): 
,D/        ( 3282): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7159
,I/jxcore-log( 3225): 2015-11-25T10:19:06.565Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:06.611Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:06.615Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:06.647Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:06.830Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:06.972Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3225): Found 10 peers.
,I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3225): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3225): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3225): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3225): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3225): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3225): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3225): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3225): Added service request
,I/jxcore-log( 3225): 2015-11-25T10:19:07.223Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:07.223Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:07.226Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:07.227Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3225): 
,I/BtConnectorHelper( 3225): Disconnect outgoing peer: 44:80:EB:7B:5A:05
,I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
,I/BtToSocketBase( 3225): Close local in
,I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
,I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Close bt out
,I/BtToSocketBase( 3225): Close bt socket
,I/BtToRequestSocket( 3225): Close server socket
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3225): 2015-11-25T10:19:07.235Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3225): 
I/jxcore-log( 3225): ---- round done--------
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:07.238Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:07.238Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:07.239Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
I/        ( 3225): Selected device address: B4:CE:F6:AB:A4:6A, name: null
W/bt-btif ( 3282): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
I/        ( 3225): Connecting to null, at B4:CE:F6:AB:A4:6A,
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 2902 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback,
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fac414 rs_disc_pending=0
W/bt-btif ( 3282): bta_dm_check_av:0
,W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3281): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3225): Started service discovery
,I/        ( 3225): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1879, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1879, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: HTC One_M8
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 57856(2MB) AllocSpace objects, 8(882KB) LOS objects, 36% free, 27MB/43MB, paused 1.563ms total 85.999ms
,I/art     (  821): Explicit concurrent mark sweep GC freed 46479(2MB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 2.398ms total 82.076ms
,E/HttpOperation( 2998): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at blb.a(PG:3937)
E/HttpOperation( 2998): 	at czp.a(PG:18188)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 12 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 14 more
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at hec.a(PG:42)
E/HttpOperation( 2998): 	at hee.a(PG:102)
E/HttpOperation( 2998): 	at czr.a(PG:65)
E/HttpOperation( 2998): 	at kka.a(PG:108)
E/HttpOperation( 2998): 	at czp.a(PG:19176)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 15 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 17 more
E/ExperimentLoader( 2998): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 2998): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): 	at jdm.a(PG:82)
E/ExperimentLoader( 2998): 	at jcs.o(PG:406)
E/ExperimentLoader( 2998): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2998): 	at jcs.i(PG:143)
E/ExperimentLoader( 2998): 	at hec.a(PG:42)
,E/ExperimentLoader( 2998): 	at hee.a(PG:102)
E/ExperimentLoader( 2998): 	at czr.a(PG:65)
E/ExperimentLoader( 2998): 	at kka.a(PG:108)
E/ExperimentLoader( 2998): 	at czp.a(PG:19176)
E/ExperimentLoader( 2998): 	at czp.a(PG:9081)
E/ExperimentLoader( 2998): 	at czq.run(PG:1686)
E/ExperimentLoader( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2998): 	at jdj.a(PG:4091)
,E/ExperimentLoader( 2998): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2998): 	at jdm.a(PG:77)
E/ExperimentLoader( 2998): 	... 15 more
E/ExperimentLoader( 2998): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2998): 	at fal.a(PG:38)
E/ExperimentLoader( 2998): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2998): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 645781, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 4020): Bluetooth Device Name: XT1072
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): invalid rfc slot id: 29
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3225): 2015-11-25T10:19:11.112Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:11.112Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:11.113Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,I/jxcore-log( 3225): 2015-11-25T10:19:16.114Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:16.115Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/SS      ( 3225): Found 9 peers.,
I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3225): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3225): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3225): Peer(5): Android_63cc 82:01:84:6b:e8:5d,
I/SS      ( 3225): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3225): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3225): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3225): Added service request
,I/        ( 3225): Started service discovery
,I/jxcore-log( 3225): 2015-11-25T10:19:21.119Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:21.119Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:21.120Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:21.121Z SendDataConnector.js: do connect now,
I/jxcore-log( 3225): ,
I/        ( 3225): Selected device address: B4:CE:F6:AB:A4:6A, name: null,
I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3225): Connecting to null, at B4:CE:F6:AB:A4:6A
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): info:x10,
D/        ( 3282): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp,
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3282): invalid rfc slot id: 30
,I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:19:21.515Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:21.516Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:21.517Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3225): 2015-11-25T10:19:26.518Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:26.519Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/        ( 3225): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1879, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1879, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3225): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0,
,I/jxcore-log( 3225): 2015-11-25T10:19:31.524Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:31.525Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:31.525Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:31.526Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to null, at B4:CE:F6:AB:A4:6A
D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): invalid rfc slot id: 31
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:19:32.825Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:32.826Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:32.826Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3225): 2015-11-25T10:19:37.828Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:37.828Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3225): Found 9 peers.
,I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3225): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3225): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3225): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3225): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3225): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3225): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3225): Added service request
,I/        ( 3225): Started service discovery
,I/jxcore-log( 3225): 2015-11-25T10:19:42.832Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:42.833Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:42.834Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:42.834Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3225): Connecting to null, at B4:CE:F6:AB:A4:6A
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): info:x10,
,D/        ( 3282): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): invalid rfc slot id: 32
,I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3225): 2015-11-25T10:19:43.146Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:43.147Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:43.147Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/jxcore-log( 3225): 2015-11-25T10:19:48.149Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:48.149Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/        ( 3225): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3225): 2015-11-25T10:19:53.153Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): ,
I/jxcore-log( 3225): 2015-11-25T10:19:53.154Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:53.155Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): ,
I/jxcore-log( 3225): 2015-11-25T10:19:53.155Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3225): Connecting to null, at B4:CE:F6:AB:A4:6A
D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): invalid rfc slot id: 33
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:19:54.061Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:54.062Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:54.065Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:54.068Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): ---- round done--------
I/jxcore-log( 3225): 
I/jxcore-log( 3225): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1
I/jxcore-log( 3225): 
I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:54.071Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:54.072Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:54.073Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3225): Starting to connect,
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to null, at 34:FC:EF:11:B1:66
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 46824 ms, rnd: 5, ex: Connection to B4:CE:F6:AB:A4:6A failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fac5dc rs_disc_pending=1
W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109,
E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): invalid rfc slot id: 34
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:19:54.708Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:54.709Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:19:54.712Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL,
,I/jxcore-log( 3225): 2015-11-25T10:19:59.713Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:19:59.714Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3225): Found 8 peers.
I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3225): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3225): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3225): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3225): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3225): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3225): Added service request
,I/wpa_supplicant( 3281): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3225): Started service discovery
,I/        ( 3225): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3225): 2015-11-25T10:20:04.718Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:04.719Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:04.720Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:04.720Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 34:FC:EF:11:B1:66, name: null,
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to null, at 34:FC:EF:11:B1:66
D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [34:fc:ef:11:b1:66]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): invalid rfc slot id: 35,
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3225): 2015-11-25T10:20:06.197Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:06.197Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:06.199Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3225): 2015-11-25T10:20:11.202Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:11.204Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,I/        ( 3225): Cleared service requests,
,I/        ( 3225): Started peer discovery,
,I/BooksSync( 3554): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3554): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3554): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3554): Soft error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3554): Sync error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3554): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 712255, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3225): 2015-11-25T10:20:16.209Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:16.210Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:16.211Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:16.211Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 34:FC:EF:11:B1:66, name: null,
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to null, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): invalid rfc slot id: 36
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:20:17.684Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:17.685Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:17.686Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3225): Found 8 peers.
I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3225): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3225): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3225): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3225): Peer(8): Android_8ae2 52:55:27:f0:fd:0b,
D/WifiP2pManager( 3225): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3225): Added service request
,I/wpa_supplicant( 3281): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3225): Started service discovery
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3225): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3225): 2015-11-25T10:20:22.687Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:22.688Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,I/jxcore-log( 3225): 2015-11-25T10:20:27.691Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:27.692Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:27.693Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:27.693Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 34:FC:EF:11:B1:66, name: null,
,I/        ( 3225): Connecting to null, at 34:FC:EF:11:B1:66,
I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): invalid rfc slot id: 37
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:20:30.924Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:30.925Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:30.926Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3225): Found 8 peers.
I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86,
I/SS      ( 3225): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3225): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3225): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3225): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3225): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3225): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3225): Added service request
,I/wpa_supplicant( 3281): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/        ( 3225): Started service discovery
,I/        ( 3225): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:,
I/        ( 3225): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3225): 2015-11-25T10:20:35.928Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:35.928Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,I/jxcore-log( 3225): 2015-11-25T10:20:40.932Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:40.933Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:40.934Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:40.934Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to null, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 3282): invalid rfc slot id: 38
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3225): 2015-11-25T10:20:43.579Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:43.580Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:43.583Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:43.591Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): ---- round done--------
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 3225): 
I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
I/jxcore-log( 3225): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:43.593Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:43.594Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:43.594Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 58:3F:54:73:64:C0, name: null
,I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3225): Connecting to null, at 58:3F:54:73:64:C0
,I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 49508 ms, rnd: 5, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): invalid rfc slot id: 39
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:20:45.654Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:45.654Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:45.655Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,V/KeepSync( 3329): Connecting to GoogleApiClient
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 3329): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3329): IOException
E/KeepSync( 3329): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3329): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3329): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3329): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3329): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3329): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3329): 	... 10 more
W/KeepSync( 3329): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 713572, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3225): Found 8 peers.
,I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3225): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3225): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3225): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3225): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3225): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3225): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3225): Added service request
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3281): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3225): Started service discovery
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3225): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/jxcore-log( 3225): 2015-11-25T10:20:50.657Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:50.658Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:55.662Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:55.663Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:55.663Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:55.664Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 58:3F:54:73:64:C0, name: null,
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3225): Connecting to null, at 58:3F:54:73:64:C0
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [58:3f:54:73:64:c0]: 6, f, 6109,
E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): invalid rfc slot id: 40
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/jxcore-log( 3225): 2015-11-25T10:20:56.491Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:20:56.491Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:20:56.492Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3225): 2015-11-25T10:21:01.492Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:01.493Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3225): Found 7 peers.
I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3225): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3225): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3225): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3225): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3225): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3225): Added service request
,I/        ( 3225): Started service discovery
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0,
I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3225): 2015-11-25T10:21:06.498Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:06.499Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true,
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:06.499Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:06.500Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 58:3F:54:73:64:C0, name: null
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3225): Connecting to null, at 58:3F:54:73:64:C0
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): info:x10,
D/        ( 3282): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab964 rs_disc_pending=0
W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3225): we got incoming connection
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3225): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started,
,I/BTListenerThread( 3225): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3225): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������,
,I/BTListenerThread( 3225): MESSAGE_WRITE 82 bytes.
I/HS      ( 3225): Incoming connection Hand Shake finished for : motorola-XT1039_PT6119
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3225): Starting the connected thread incoming : true, motorola-XT1039_PT6119
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket,
I/BtToRequestSocket( 3225): Creating BTConnectedThread
,I/BtConnectorHelper( 3225): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3225): --DoOneRunRound started
,I/BtToRequestSocket( 3225): LocalHost address: localhost/127.0.0.1, port: 40230
,I/jxcore-log( 3225): 2015-11-25T10:21:08.791Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3225): 
,I/BtToRequestSocket( 3225): --DoOneRunRound ended
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab964 rs_disc_pending=1
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3225): 2015-11-25T10:21:09.200Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.233Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.304Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.309Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.312Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.377Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.385Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3225): ,
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fac96c rs_disc_pending=1,
W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): invalid rfc slot id: 41
,I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:21:09.463Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3225): 
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:21:09.465Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.466Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:09.466Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:09.472Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.474Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3225): 
,I/        ( 3225): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3225): 2015-11-25T10:21:09.569Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.578Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.584Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.619Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.624Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data,
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.634Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3225): ,
,I/jxcore-log( 3225): 2015-11-25T10:21:09.639Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3225): 
,I/        ( 3225): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:,
I/        ( 3225): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
,I/jxcore-log( 3225): 2015-11-25T10:21:09.656Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3225): 
,I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3225): 2015-11-25T10:21:09.689Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.741Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.746Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.752Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data,
,I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.790Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.829Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.834Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.871Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.910Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.917Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.921Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.950Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.956Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.958Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:09.989Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3225): 
,W/bt-btif ( 3282): invalid rfc slot id: 18
,I/BtToSocketBase( 3225): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6119
,I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
,I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6119
,I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Close bt in
,I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
,I/jxcore-log( 3225): 2015-11-25T10:21:10.026Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3225): 
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fab964 rs_disc_pending=0,
,W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3282): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0,
W/bt-rfcomm( 3282): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fac96c rs_disc_pending=0,
W/bt-btif ( 3282): bta_dm_check_av:0
,W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3225): 2015-11-25T10:21:14.467Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:14.468Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: XT1039
,I/        ( 3225): Cleared service requests
,I/        ( 3225): Started peer discovery
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: HTC One_M8
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:255
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3225): we got incoming connection
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3225): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started,
,I/BTListenerThread( 3225): got MESSAGE_READ 80 bytes.
,I/BTListenerThread( 3225): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3225): MESSAGE_WRITE 82 bytes.
I/HS      ( 3225): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT4589
I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3225): Starting the connected thread incoming : true, HTC-HTC One_M8_PT4589
,I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3225): Creating BTConnectedThread
I/BtConnectorHelper( 3225): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3225): --DoOneRunRound started
,I/BtToRequestSocket( 3225): LocalHost address: localhost/127.0.0.1, port: 40230
,I/BtToRequestSocket( 3225): --DoOneRunRound ended
,I/jxcore-log( 3225): 2015-11-25T10:21:18.072Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.494Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.502Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.509Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.566Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.569Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:18.575Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.608Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.614Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.619Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.659Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.668Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.672Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.708Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.739Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.749Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.779Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.786Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.820Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.856Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.890Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.898Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:18.901Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3225): 
,W/bt-btif ( 3282): invalid rfc slot id: 42
,I/BtToSocketBase( 3225): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT4589
,I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
I/BtToSocketBase( 3225): Close local in
,I/jxcore-log( 3225): 2015-11-25T10:21:18.940Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3225): 
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT4589
I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Close bt in
,I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Close bt out
,I/BtToSocketBase( 3225): Close bt socket
,I/jxcore-log( 3225): 2015-11-25T10:21:18.948Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3225): ,
,W/bt-rfcomm( 3282): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 3282): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 3225): 2015-11-25T10:21:19.471Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:19.472Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:19.472Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:19.473Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 58:3F:54:73:64:C0, name: null,
,I/        ( 3225): Connecting to null, at 58:3F:54:73:64:C0
I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3281): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/SS      ( 3225): Found 6 peers.
,I/SS      ( 3225): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3225): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3225): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3225): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3225): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3225): Peer(6): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3225): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3225): Added service request
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/        ( 3225): Started service discovery,
,W/bt-btm  ( 3282): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!,
E/bt-btm  ( 3282): tBTM_SEC_DEV:0xa2fac24c rs_disc_pending=2
E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3282): bta_dm_check_av:0
W/bt-btif ( 3282): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: HTC One_M8
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3225): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3699","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3699","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT3699, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT3699, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3225): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 3282): info:x10
I/        ( 3225): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT153, peerAddress: F8:95:C7:87:3C:51
D/        ( 3282): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT153, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/        ( 3225): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9507, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9507, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3282): invalid rfc slot id: 44
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:21:24.636Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:24.637Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:24.638Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,I/        ( 3225): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5232, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5232, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 3281): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3225): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3225): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1879, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1879, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3225): 2015-11-25T10:21:29.638Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:29.639Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/        ( 3225): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3225): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5868, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3225): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5868, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/wpa_supplicant( 3281): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3225): 2015-11-25T10:21:34.644Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:34.644Z SendDataConnector.js: Connect (retry count 4) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:34.645Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:34.645Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
,I/        ( 3225): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 3225): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3225): Starting to connect
W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,--------- beginning of crash
F/libc    ( 3281): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 3281 (wpa_supplicant)
,I/libc    ( 3281): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
I/        ( 3225): Cleared service requests
,W/bt-sdp  ( 3282): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3282): invalid rfc slot id: 45
I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:21:39.809Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:39.809Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:39.813Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:39.815Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): ---- round done--------
I/jxcore-log( 3225): 
I/jxcore-log( 3225): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 1
I/jxcore-log( 3225): 
I/jxcore-log( 3225): do fake peer & start
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:39.818Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:39.819Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:39.819Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
I/        ( 3225): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3225): Starting to connect
,W/BluetoothAdapter( 3225): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3225): Connecting to null, at 08:EC:A9:50:75:41
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback round[0] time: 56216 ms, rnd: 5, ex: Connection to 58:3F:54:73:64:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3282): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3282): process_service_search_attr_rsp
,E/bt-btif ( 3282): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3282): invalid rfc slot id: 46
,I/BTConnectToThread( 3225): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3225): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3225): 2015-11-25T10:21:40.781Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:40.784Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:40.785Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3225): 
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3282): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3225): 2015-11-25T10:21:45.787Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:45.788Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3225): 
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: XT1072
,W/bt-btif ( 3282): new conn_srvc id:26, app_id:255
W/bt-btif ( 3282): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3282): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3225): we got incoming connection
I/BTHandshakeSocketThread( 3225): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3225): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread started
,D/WifiHW  (  821): 'P2P_FIND 120' command timed out.,
,I/        ( 3225): Starting peer discovery failed, error code 0
I/BTListenerThread( 3225): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3225): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������,
I/BTListenerThread( 3225): MESSAGE_WRITE 82 bytes.
I/HS      ( 3225): Incoming connection Hand Shake finished for : motorola-XT1072_PT5868
,I/BTHandshakeSocketThread( 3225): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3225): Starting the connected thread incoming : true, motorola-XT1072_PT5868
I/BtToSocketBase( 3225): BtToSocketBase BtConnectedRequestSocket,
I/BtToRequestSocket( 3225): Creating BTConnectedThread
I/BtConnectorHelper( 3225): Server socket is using : 0, and is now connected.
E/WifiStateMachine(  821): Connection lost, restart supplicant
E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown,
I/BtToRequestSocket( 3225): --DoOneRunRound started
,W/Settings( 2659): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
I/BtToRequestSocket( 3225): LocalHost address: localhost/127.0.0.1, port: 40230
I/jxcore-log( 3225): 2015-11-25T10:21:49.226Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3225): 
I/BtToRequestSocket( 3225): --DoOneRunRound ended
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  821): failed to set BSSID: any,
E/native  (  821): do suspend true
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,W/Settings( 1754): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/NativeCrypto( 1501): Read error: ssl=0xaec39000: I/O error during system call, Connection timed out,
,V/NativeCrypto( 1501): SSL shutdown failed: ssl=0xaec39000: I/O error during system call, Broken pipe
,I/jxcore-log( 3225): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3225): 
I/jxcore-log( 3225): The Coordinator has disconnected!
I/jxcore-log( 3225): 
D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  821): Unexpected BatchedScanResults :null
,D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
,D/WifiScanningService(  821): SCAN_AVAILABLE : 1
,D/RttService(  821): SCAN_AVAILABLE : 1
D/WifiScanningService(  821): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState
D/RttService(  821): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3225): Discovery state changed to Stopped.
,I/SS      ( 3225): We got empty peers list
I/        ( 3225): Starting peer discovery failed, error code 2
I/WB      ( 3225): Wifi is DISABLED !!
I/        ( 3225): Stoping All
I/        ( 3225): Stopping services
I/        ( 3225): Stopping services
,I/        ( 3225): Stop Bluetooth
I/        ( 3225): Stop Bluetooth
I/BTListenerThread( 3225): Stopped
I/        ( 3225): Clearing local services failed, error code 2
I/        ( 3225): Clearing service requests failed, error code 2
I/        ( 3225): Stopping peer discovery failed, error code 2
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3,
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 3464): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  821): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering(  821): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3464): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,I/ActivityManager(  821): Start proc 4279:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/GpsLocationProvider(  821): No APN found to select.
,D/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 4279): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4279): simOperator:  IMSI: null
,D/SprintDMReceiver( 4279): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1783): onCreate
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,I/iu.Environment( 1783): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1783): num queued entries: 0
I/iu.UploadsManager( 1783): num updated entries: 0
I/iu.SyncManager( 1783): NEXT; no task
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599951 ms
,I/Babel   ( 2659): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  821): Start proc 4299:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1783): onDestroy
,I/ActivityManager(  821): Killing 3669:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/jxcore-log( 3225): 2015-11-25T10:21:49.654Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.657Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.659Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.665Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.675Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.710Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
,I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.715Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.720Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.727Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.760Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.776Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.785Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.800Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.839Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.845Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.852Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.858Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.898Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
,I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.903Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
,I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.939Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.945Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3225): 
,I/GAv4    ( 4299): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4299):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4299):   adb logcat -s GAv4
,I/jxcore-log( 3225): 2015-11-25T10:21:49.979Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:49.983Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3225): 
,W/GAv4    ( 4299): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4299): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4299): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 3225): 2015-11-25T10:21:50.018Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
,I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:50.051Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:50.089Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:50.092Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:50.129Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3225): 
,W/bt-btif ( 3282): invalid rfc slot id: 43,
I/BtToSocketBase( 3225): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5868
I/BtToSocketBase( 3225): Stop ReceivingThread
I/BtToSocketBase( 3225): Stop SendingThread
,I/BtToSocketBase( 3225): Close local in
I/BtToSocketBase( 3225): Close LocalOutputStream
I/BtToSocketBase( 3225): Close localHostSocket
I/BtToSocketBase( 3225): Close bt in
I/BtToSocketBase( 3225): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3225): Close bt out
I/BtConnectorHelper( 3225): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3225): Close bt socket
I/BtConnectorHelper( 3225): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5868
I/BtToSocketBase( 3225): Close bt in
,I/BtToSocketBase( 3225): Close bt out
I/BtToSocketBase( 3225): Close bt socket
I/jxcore-log( 3225): 2015-11-25T10:21:50.171Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3225): 
,W/bt-rfcomm( 3282): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3282): RFCOMM_DisconnectInd LCID:0x47
,I/WebViewFactory( 4299): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4299): Time to load native libraries: 4 ms (timestamps 6842-6846)
,I/LibraryLoader( 4299): Expected native library version number "",actual native library version number "",
,I/jxcore-log( 3225): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3225): 
,D/WifiService(  821): setWifiEnabled: false pid=3225, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,V/WebViewChromiumFactoryProvider( 4299): Binding Chromium to main looper Looper (main, tid 1) {34287fdb}
,I/LibraryLoader( 4299): Expected native library version number "",actual native library version number "",
I/chromium( 4299): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,D/WifiService(  821): setWifiEnabled: true pid=3225, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,I/BrowserStartupController( 4299): Initializing chromium process, singleProcess=true
D/WifiController(  821): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 490ms
,W/art     ( 4299): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4299): ApplicationContext is null in ApplicationStatus
I/jxcore-log( 3225): Wifi toggled for connection repairment
I/jxcore-log( 3225): 
I/chromium( 3225): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/chromium( 4299): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4299): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4299): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 4299): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 4299): Requires BLUETOOTH permission
,I/art     (  821): Explicit concurrent mark sweep GC freed 45327(2MB) AllocSpace objects, 7(394KB) LOS objects, 32% free, 33MB/49MB, paused 7.123ms total 101.431ms
,I/NSApplication( 4299): Starting up...
,I/ActivityManager(  821): Killing 3689:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/WifiController(  821): DEFERRED_TOGGLE handled
,D/SoftapController(  355): Softap fwReload - Ok
,D/CommandListener(  355): Setting iface cfg
,D/CommandListener(  355): Trying to bring down wlan0
,I/jxcore-log( 3225): 2015-11-25T10:21:50.791Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3225): 
,I/jxcore-log( 3225): 2015-11-25T10:21:50.792Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:50.793Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3225): 
I/jxcore-log( 3225): 2015-11-25T10:21:50.794Z SendDataConnector.js: do connect now
I/jxcore-log( 3225): 
D/AndroidRuntime( 3225): Shutting down VM
,D/Tethering(  821): InitialState.processMessage what=4
D/CommandListener(  355): Clearing all IP addresses on wlan0
E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  821): Start proc 4359:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,D/Tethering(  821): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor(  821): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 4358): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4358): rfkill: Cannot open RFKILL control device
,V/MusicLeanback( 3464): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  821): Killing 3850:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/SprintDMReceiver( 4279): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4279): simOperator:  IMSI: null
D/SprintDMReceiver( 4279): Not Sprint UICC, don't do anything.
I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1783): onCreate
D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,I/ValidateNoPeople(  821): skipping global notification
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599955 ms
,D/SystemUpdateService( 1783): onDestroy
,D/Tethering(  821): sendTetherStateChangedBroadcast 1, 0, 0
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 4358): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 4358): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  821): Loading config and enabling all networks 
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@a7ac951}
,E/WifiConfigStore(  821): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  821): Setting external_sim to 1
W/Settings( 2659): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  821): Setting OUI to 92-68-C3
I/WifiNative-HAL(  821): startHal
D/wifi    (  821): setting scan oui 0xaec85118
D/WifiHAL (  821): Sending mac address OUI
,E/native  (  821): do suspend true
,W/CommandListener(  355): Failed to retrieve HW addr for p2p0 (No such device)
,D/WifiScanningService(  821): SCAN_AVAILABLE : 3
D/RttService(  821): SCAN_AVAILABLE : 3
D/CommandListener(  355): Setting iface cfg
D/WifiScanningService(  821): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  821): startHal
D/wifi    (  821): getting scan capabilities on interface[0] = 0xaec85118
D/WifiHAL (  821): Creating message to get scan capablities; iface = 5
E/WifiP2pService(  821): Unable to change interface settings: java.lang.IllegalStateException: command '58 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 58 Failed to set address (No such device)'
D/WifiHAL (  821): In GetCapabilities::handleResponse
D/WifiMonitor(  821): startMonitoring(p2p0) with mConnected = true
D/WifiHAL (  821): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  821): StartedState
D/RttService(  821): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-HAL(  821): p2pGetDeviceAddress
D/WifiNative-HAL(  821): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 4358): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/wpa_supplicant( 4358): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  821):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  821):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,I/wpa_supplicant( 4358): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 4358): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4358): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4358): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 2
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 1
E/WifiStateMachine(  821):  RSSI mgmt: -44
E/WifiStateMachine(  821):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 0 tx_time=51 rx_time=345 scan_time=0
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive,
,I/dhcpcd  ( 4389): version 5.5.6 starting
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: XT1072
,I/dhcpcd  ( 4389): wlan0: rebinding lease of 192.168.1.110
,I/dhcpcd  ( 4389): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 4389): wlan0: leased 192.168.1.110 for 86400 seconds
,E/native  (  821): do suspend true
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
D/ConnectivityService(  821): Adding iface wlan0 to network 101
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  821): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} },
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
,D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3464): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 3464): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,D/SprintDMReceiver( 4279): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4279): simOperator:  IMSI: null
D/SprintDMReceiver( 4279): Not Sprint UICC, don't do anything.
E/GpsLocationProvider(  821): No APN found to select.
I/SystemUpdateService( 1783): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1783): onCreate
,D/SystemUpdateService( 1783): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1783): active receiver: enabled
,I/SystemUpdateService( 1783): showing system update notification
,I/ValidateNoPeople(  821): skipping global notification
,I/iu.Environment( 1783): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1783): num queued entries: 0
,I/iu.UploadsManager( 1783): num updated entries: 0
,I/iu.SyncManager( 1783): NEXT; no task
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 25 Nov 2015 10:21:55 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448446915150], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448446915129]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Validated
,D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.,
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
,V/SystemUpdateService( 1783): retry (wakeup: false) in 3599976 ms
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1783): onDestroy
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1783): NQAS connected
,I/Babel   ( 2659): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1783): [AccountUtils] Account not ready
W/Kids    ( 1783): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1783): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1783): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1783): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1783): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1783): 	at java.lang.Thread.run(Thread.java:818)
,D/GCM     ( 1501): Connected
,D/GCM     ( 1501): Message class com.google.f.a.a.p
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@a7ac951}
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [e0:db:10:1f:c9:5e]: 6, 1d, 7d3
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1,
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive,
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0,
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: G4-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: G4-1
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at blb.a(PG:3937)
E/HttpOperation( 2998): 	at czp.a(PG:18188)
E/HttpOperation( 2998): 	at czp.a(PG:9087)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 12 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 14 more
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 63299(2MB) AllocSpace objects, 5(268KB) LOS objects, 32% free, 33MB/49MB, paused 1.071ms total 57.623ms
,E/HttpOperation( 2998): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at blb.a(PG:3937)
E/HttpOperation( 2998): 	at czp.a(PG:18188)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 12 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 14 more
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at hec.a(PG:42)
E/HttpOperation( 2998): 	at hee.a(PG:102)
E/HttpOperation( 2998): 	at czr.a(PG:65)
E/HttpOperation( 2998): 	at kka.a(PG:108)
E/HttpOperation( 2998): 	at czp.a(PG:19176)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 15 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 17 more
E/ExperimentLoader( 2998): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): 	at jdm.a(PG:82)
E/ExperimentLoader( 2998): 	at jcs.o(PG:406)
E/ExperimentLoader( 2998): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2998): 	at jcs.i(PG:143)
E/ExperimentLoader( 2998): 	at hec.a(PG:42)
E/ExperimentLoader( 2998): 	at hee.a(PG:102)
E/ExperimentLoader( 2998): 	at czr.a(PG:65)
E/ExperimentLoader( 2998): 	at kka.a(PG:108)
E/ExperimentLoader( 2998): 	at czp.a(PG:19176)
E/ExperimentLoader( 2998): 	at czp.a(PG:9081)
E/ExperimentLoader( 2998): 	at czq.run(PG:1686)
E/ExperimentLoader( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2998): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2998): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2998): 	at jdm.a(PG:77)
E/ExperimentLoader( 2998): 	... 15 more
E/ExperimentLoader( 2998): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2998): 	at fal.a(PG:38)
E/ExperimentLoader( 2998): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2998): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 646241, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: G4-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: G4-1
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: G4-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: G4-1
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: G4-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: G4-1
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: G4-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive,
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: G4-1,
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 57651(2MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 1.605ms total 67.912ms
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at blb.a(PG:3937)
E/HttpOperation( 2998): 	at czp.a(PG:18188)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 12 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 14 more
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at hec.a(PG:42)
E/HttpOperation( 2998): 	at hee.a(PG:102)
E/HttpOperation( 2998): 	at czr.a(PG:65)
E/HttpOperation( 2998): 	at kka.a(PG:108)
E/HttpOperation( 2998): 	at czp.a(PG:19176)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 15 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 17 more
,E/ExperimentLoader( 2998): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): 	at jdm.a(PG:82)
E/ExperimentLoader( 2998): 	at jcs.o(PG:406)
E/ExperimentLoader( 2998): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2998): 	at jcs.i(PG:143)
E/ExperimentLoader( 2998): 	at hec.a(PG:42)
E/ExperimentLoader( 2998): 	at hee.a(PG:102)
E/ExperimentLoader( 2998): 	at czr.a(PG:65)
E/ExperimentLoader( 2998): 	at kka.a(PG:108)
E/ExperimentLoader( 2998): 	at czp.a(PG:19176)
E/ExperimentLoader( 2998): 	at czp.a(PG:9081)
E/ExperimentLoader( 2998): 	at czq.run(PG:1686)
E/ExperimentLoader( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2998): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2998): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2998): 	at jdm.a(PG:77)
E/ExperimentLoader( 2998): 	... 15 more
E/ExperimentLoader( 2998): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2998): 	at fal.a(PG:38)
E/ExperimentLoader( 2998): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2998): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1025043, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btif ( 3282): info:x10,
D/        ( 3282): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: S5-1,
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: S5-1
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: S5-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: S5-1,
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: S5-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: S5-1
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at blb.a(PG:3937)
E/HttpOperation( 2998): 	at czp.a(PG:18188)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 12 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 14 more
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at hec.a(PG:42)
E/HttpOperation( 2998): 	at hee.a(PG:102)
E/HttpOperation( 2998): 	at czr.a(PG:65)
E/HttpOperation( 2998): 	at kka.a(PG:108)
E/HttpOperation( 2998): 	at czp.a(PG:19176)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 15 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 17 more
E/ExperimentLoader( 2998): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): 	at jdm.a(PG:82)
E/ExperimentLoader( 2998): 	at jcs.o(PG:406)
E/ExperimentLoader( 2998): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2998): 	at jcs.i(PG:143)
E/ExperimentLoader( 2998): 	at hec.a(PG:42)
E/ExperimentLoader( 2998): 	at hee.a(PG:102)
E/ExperimentLoader( 2998): 	at czr.a(PG:65)
E/ExperimentLoader( 2998): 	at kka.a(PG:108)
E/ExperimentLoader( 2998): 	at czp.a(PG:19176)
E/ExperimentLoader( 2998): 	at czp.a(PG:9081)
E/ExperimentLoader( 2998): 	at czq.run(PG:1686)
E/ExperimentLoader( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2998): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2998): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2998): 	at jdm.a(PG:77)
E/ExperimentLoader( 2998): 	... 15 more
E/ExperimentLoader( 2998): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2998): 	at fal.a(PG:38)
E/ExperimentLoader( 2998): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2998): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1117605, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: S5-1
,V/GoogleAuthProtoRequest( 3299): [352] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3299): [352] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3299): [352] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3299): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3299): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3299): 	at com.a.a.k.run(SourceFile:110)
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: S5-1,
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c,
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: S5-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: S5-1
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3299): [353] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3299): [353] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3299): [353] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3299): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3299): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3299): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3299): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3299): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [e0:db:10:1f:c9:5e]: 7, f, 610c
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btif ( 3282): info:x10,
D/        ( 3282): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1,
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,I/BooksSync( 3554): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3554): GmsCore Version = 7.8.99 (2134222-430),
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 35316(1645KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.969ms total 83.765ms
,E/BooksAccountManager( 3554): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): Soft error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3554): Sync error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3554): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1222253, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Note3-1
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2998): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at blb.a(PG:3937)
E/HttpOperation( 2998): 	at czp.a(PG:18188)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 12 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 14 more
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at hec.a(PG:42)
E/HttpOperation( 2998): 	at hee.a(PG:102)
E/HttpOperation( 2998): 	at czr.a(PG:65)
E/HttpOperation( 2998): 	at kka.a(PG:108)
E/HttpOperation( 2998): 	at czp.a(PG:19176)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 15 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 17 more
E/ExperimentLoader( 2998): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): 	at jdm.a(PG:82)
E/ExperimentLoader( 2998): 	at jcs.o(PG:406)
E/ExperimentLoader( 2998): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2998): 	at jcs.i(PG:143)
E/ExperimentLoader( 2998): 	at hec.a(PG:42)
E/ExperimentLoader( 2998): 	at hee.a(PG:102)
E/ExperimentLoader( 2998): 	at czr.a(PG:65)
E/ExperimentLoader( 2998): 	at kka.a(PG:108)
E/ExperimentLoader( 2998): 	at czp.a(PG:19176)
E/ExperimentLoader( 2998): 	at czp.a(PG:9081)
E/ExperimentLoader( 2998): 	at czq.run(PG:1686)
E/ExperimentLoader( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2998): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2998): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2998): 	at jdm.a(PG:77)
E/ExperimentLoader( 2998): 	... 15 more
E/ExperimentLoader( 2998): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2998): 	at fal.a(PG:38)
E/ExperimentLoader( 2998): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2998): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1247913, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [58:2a:f7:ed:96:be]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: ALE-L21
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: ALE-L21
,I/BooksSync( 3554): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3329): Connecting to GoogleApiClient
,I/BooksConfig( 3554): GmsCore Version = 7.8.99 (2134222-430)
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/BluetoothClassifier( 4020): Bluetooth Device Name: ALE-L21
V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 3329): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3554): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3554): Soft error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3554): Sync error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3554): Finished books sync,
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1255348, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3329): IOException
E/KeepSync( 3329): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3329): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3329): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3329): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3329): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3329): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3329): 	... 10 more
W/KeepSync( 3329): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1255029, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: ALE-L21
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 59928(3MB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 27MB/43MB, paused 1.492ms total 95.554ms
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608,
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: ALE-L21
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: ALE-L21
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: ALE-L21
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: ALE-L21
,V/KeepSync( 3329): Connecting to GoogleApiClient
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 3329): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted),
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3329): IOException
E/KeepSync( 3329): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3329): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3329): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3329): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3329): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3329): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3329): 	... 10 more
,W/KeepSync( 3329): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1314963, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/BooksSync( 3554): Starting books sync for 61035162, extras: ade
,I/art     (  821): Explicit concurrent mark sweep GC freed 38317(1725KB) AllocSpace objects, 11(270KB) LOS objects, 31% free, 34MB/50MB, paused 2.845ms total 88.315ms
,I/BooksConfig( 3554): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3554): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3554): Soft error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3554): Sync error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3554): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1347862, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [34:fc:ef:11:ae:67]: 6, 10f, 608
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3282): onReceive,
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btif ( 3282): info:x10
,D/        ( 3282): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3282): info:x10
D/        ( 3282): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5,
,D/btif_config_util( 3282): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3282): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3282): onReceive
,I/BTConnectionReceiver( 4020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4020): Bluetooth Device Name: Nexus 5
,V/KeepSync( 3329): Connecting to GoogleApiClient
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 3329): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3329): IOException
E/KeepSync( 3329): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3329): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3329): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3329): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3329): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3329): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3329): 	... 10 more
W/KeepSync( 3329): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1407287, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/BooksSync( 3554): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3554): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3554): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3554): Soft error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3554): Sync error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3554): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1503142, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at blb.a(PG:3937)
E/HttpOperation( 2998): 	at czp.a(PG:18188)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 12 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 14 more
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2998): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2998): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2998): 	at jdm.a(PG:82)
E/HttpOperation( 2998): 	at jcs.o(PG:406)
E/HttpOperation( 2998): 	at jcn.a(PG:1379)
E/HttpOperation( 2998): 	at jcs.i(PG:143)
E/HttpOperation( 2998): 	at hec.a(PG:42)
E/HttpOperation( 2998): 	at hee.a(PG:102)
E/HttpOperation( 2998): 	at czr.a(PG:65)
E/HttpOperation( 2998): 	at kka.a(PG:108)
E/HttpOperation( 2998): 	at czp.a(PG:19176)
E/HttpOperation( 2998): 	at czp.a(PG:9081)
E/HttpOperation( 2998): 	at czq.run(PG:1686)
E/HttpOperation( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2998): 	at jdj.a(PG:4091)
E/HttpOperation( 2998): 	at jdj.a(PG:1125)
E/HttpOperation( 2998): 	at jdm.a(PG:77)
E/HttpOperation( 2998): 	... 15 more
E/HttpOperation( 2998): Caused by: faj: BadAuthentication
E/HttpOperation( 2998): 	at fal.a(PG:38)
E/HttpOperation( 2998): 	at jdj.a(PG:4089)
E/HttpOperation( 2998): 	... 17 more
,E/ExperimentLoader( 2998): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2998): 	at jdm.a(PG:82)
E/ExperimentLoader( 2998): 	at jcs.o(PG:406)
E/ExperimentLoader( 2998): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2998): 	at jcs.i(PG:143)
E/ExperimentLoader( 2998): 	at hec.a(PG:42)
E/ExperimentLoader( 2998): 	at hee.a(PG:102)
E/ExperimentLoader( 2998): 	at czr.a(PG:65)
E/ExperimentLoader( 2998): 	at kka.a(PG:108)
E/ExperimentLoader( 2998): 	at czp.a(PG:19176)
E/ExperimentLoader( 2998): 	at czp.a(PG:9081)
E/ExperimentLoader( 2998): 	at czq.run(PG:1686)
E/ExperimentLoader( 2998): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2998): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2998): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2998): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2998): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2998): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2998): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2998): 	at jdm.a(PG:77)
E/ExperimentLoader( 2998): 	... 15 more
E/ExperimentLoader( 2998): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2998): 	at fal.a(PG:38)
E/ExperimentLoader( 2998): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2998): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1512213, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3329): Connecting to GoogleApiClient
,I/art     ( 3329): Explicit concurrent mark sweep GC freed 25109(3MB) AllocSpace objects, 0(0B) LOS objects, 25% free, 23MB/31MB, paused 465us total 57.220ms
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 3329): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 36306(1578KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 1.357ms total 84.605ms
,E/KeepSync( 3329): IOException
E/KeepSync( 3329): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3329): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3329): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3329): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3329): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3329): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3329): 	... 10 more
W/KeepSync( 3329): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1561755, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/art     ( 1501): Explicit concurrent mark sweep GC freed 61906(3MB) AllocSpace objects, 8(882KB) LOS objects, 36% free, 27MB/43MB, paused 1.697ms total 66.392ms
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/BooksSync( 3554): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3554): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3554): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3554): Soft error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3554): Sync error
E/BooksSync( 3554): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3554): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3554): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1764175, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  821): Prepared write state in 21ms
,I/ProcessStatsService(  821): Prepared write state in 10ms
,I/ProcessStatsService(  821): Pruning old procstats: /data/system/procstats/state-2015-11-24-12-07-21.bin
,V/KeepSync( 3329): Connecting to GoogleApiClient
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1783): Handling authorization failure
E/ClientConnectionOperation( 1783): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1783): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1783): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1783): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1783): 	... 7 more
,V/KeepSync( 3329): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3329): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3329): IOException
E/KeepSync( 3329): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3329): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3329): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3329): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3329): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3329): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3329): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3329): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3329): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3329): 	... 10 more
W/KeepSync( 3329): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1821407, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,I/EventLogService( 1783): Opted in for usage reporting
,I/EventLogService( 1783): Aggregate from 1448445946634 (log), 1448445946634 (data)
,D/GCM     ( 1501): Message class com.google.f.a.a.i
,I/GLSUser ( 1501): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1501): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1501): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1501): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1501): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/EventLogAggregator( 1783): Unknown tag: snet_gcore
W/EventLogAggregator( 1783): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1783): dumping service [account]
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3282): Stopping oneshot timer
,D/HeadsetStateMachine( 3282): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms)
```
