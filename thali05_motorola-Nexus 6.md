#### Test 51986340a77003b_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 24899(1317KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.822ms total 36.691ms
I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2742): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2742): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2742): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3231): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3231): CheckJNI is OFF
D/AndroidRuntime( 3231): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  824): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  824): addAppToken: AppWindowToken{afab9f1 token=Token{273c3d98 ActivityRecord{169e7b7b u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3231): Shutting down VM
V/WindowManager(  824): Adding window Window{1b45ad62 u0 Starting com.test.thalitest} at 3 of 8 (after Window{35ccc6f6 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1510): Closing mic
I/MicrophoneInputStream( 1510): mic_close com.google.android.apps.gsa.speech.audio.u@41d1752
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
I/ActivityManager(  824): Start proc 3245:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1510): Hotword detection finished
I/HotwordRecognitionRnr( 1510): Stopping hotword detection.
I/ActivityManager(  824): Killing 2701:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659876627
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  824): Killing 2834:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3245): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3245): Time to load native libraries: 4 ms (timestamps 284-288)
,I/LibraryLoader( 3245): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3245): Binding Chromium to main looper Looper (main, tid 1) {12b9b33b}
,I/LibraryLoader( 3245): Expected native library version number "",actual native library version number "",
I/chromium( 3245): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3245): Initializing chromium process, singleProcess=true
,W/art     ( 3245): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3245): ApplicationContext is null in ApplicationStatus
,W/chromium( 3245): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3245): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3245): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3245): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3245): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22383312:true
,D/BluetoothAdapter( 3245): 631309346: getState() :  mService = null. Returning STATE_OFF,
,W/art     ( 3245): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3245): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3245): CordovaWebView is running on device made by: motorola
,W/art     ( 3245): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3245): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3245): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3245): Validating map...
,V/WindowManager(  824): Adding window Window{316f84c2 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{1b45ad62 u0 Starting com.test.thalitest})
,W/chromium( 3245): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3245): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3245): Enabling debug mode 0
,I/ActivityManager(  824): Displayed com.test.thalitest/.MainActivity: +974ms (total +1m47s225ms)
,I/Keyboard.Facilitator( 1213): onFinishInput()
,W/BindingManager( 3245): Cannot call determinedVisibility() - never saw a connection for the pid: 3245
,D/JsMessageQueue( 3245): Set native->JS mode to OnlineEventsBridgeMode
,I/kickstart(  871): STATUS: Received file 'm9kefs2'
I/kickstart(  871): STATUS: 950272 bytes transferred in 0.985682 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed
,D/jxcore_app_log( 3245): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576190592
D/JX-Cordova( 3245): jxcore cordova android initializing
,W/jxcore-log( 3245): Initializing JXcore engine
W/jxcore-log( 3245): JXcore engine is ready
,W/jxcore-log( 3245): Starting JXcore engine
,W/.test.thalitest( 3245): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9882]" dev="sockfs" ino=9882 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
W/.test.thalitest( 3245): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3245): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[12860]" dev="sockfs" ino=12860 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3245): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20118]" dev="sockfs" ino=20118 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3245): Platform android
W/jxcore-log( 3245): 
W/jxcore-log( 3245): Process ARCH arm
W/jxcore-log( 3245): 
,I/jxcore-log( 3245): JXcore Cordova bridge is ready!
I/jxcore-log( 3245): 
W/jxcore-log( 3245): JXcore engine is started
,I/Choreographer( 3245): Skipped 130 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3245): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3245): Toggling radios to true
I/jxcore-log( 3245): 
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  824): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  824): Message: 1
,D/BluetoothManagerService(  824): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  824): New client listening to asynchronous messages
D/WifiService(  824): setWifiEnabled: true pid=3245, uid=10265
,E/WifiService(  824): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  354): Softap fwReload - Ok
I/jxcore-log( 3245): Radios toggled
I/jxcore-log( 3245): 
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
,D/CommandListener(  354): Clearing all IP addresses on wlan0
I/ActivityManager(  824): Start proc 3300:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,E/WifiMonitor(  824): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/WifiMonitor(  824): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  824): Start proc 3319:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,W/ResourcesManager( 3300): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 211us total 10.961ms
,I/wpa_supplicant( 3307): Successfully initialized wpa_supplicant
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 10.514ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 9.426ms
,I/wpa_supplicant( 3307): rfkill: Cannot open RFKILL control device
,D/AdapterServiceConfig( 3300): Adding HeadsetService
D/AdapterServiceConfig( 3300): Adding A2dpService
D/AdapterServiceConfig( 3300): Adding HidService
D/AdapterServiceConfig( 3300): Adding HealthService
,D/AdapterServiceConfig( 3300): Adding PanService
D/AdapterServiceConfig( 3300): Adding GattService
D/AdapterServiceConfig( 3300): Adding BluetoothMapService
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f3faf27:true
,D/BluetoothAdapterState( 3300): make
,I/bluedroid( 3300): init
,I/BluetoothAdapterState( 3300): Entering OffState
,I/bte_conf( 3300): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3300): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3300): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3300): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3300): get_profile_interface socket
I/GKI_LINUX( 3300): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 3300): get_profile_interface map_client
,D/BluetoothAdapterProperties( 3300): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  824): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  824): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3300): Name is: Nexus 6
,D/BluetoothManagerService(  824): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  824): Message: 40
,D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 3300): config_hci_snoop_log
,D/BluetoothManagerService(  824): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  824): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3300): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3300): Setting state to 11
I/BluetoothAdapterState( 3300): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  824): Message: 60
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  824): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3300): make
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,D/BluetoothAdapterService( 3300): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284f7a58
,D/HeadsetService( 3300): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3300): classInitNative: succeeds
,D/HeadsetStateMachine( 3300): make
,I/BluetoothAdapterState( 3300): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3300): max_hf_connections = 1
I/bluedroid( 3300): get_profile_interface handsfree
,D/BluetoothAdapterService( 3300): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284f7a58
,I/art     (  824): Explicit concurrent mark sweep GC freed 18614(917KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.949ms total 58.789ms
D/BluetoothA2dp( 1065): Proxy object connected
D/BluetoothA2dp(  824): Proxy object connected
D/A2dpService( 3300): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3300): classInitNative: succeeds
,I/bluedroid( 3300): get_profile_interface avrcp
,D/HeadsetStateMachine( 3300): Enter Disconnected: -2, size: 0
E/RemoteController( 3300): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3300): classInitNative: succeeds
D/A2dpStateMachine( 3300): make
,I/bluedroid( 3300): get_profile_interface a2dp
I/GKI_LINUX( 3300): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3300): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3300): classInitNative: succeeds
D/BluetoothAdapterService( 3300): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284f7a58
,D/BluetoothInputDevice( 1065): Proxy object connected
,D/HidService( 3300): Received start request. Starting profile...
I/bluedroid( 3300): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3300): classInitNative: succeeds
,D/BluetoothAdapterService( 3300): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284f7a58
D/HealthService( 3300): Received start request. Starting profile...
,I/bluedroid( 3300): get_profile_interface health
,I/BluetoothPanServiceJni( 3300): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3300): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284f7a58
,D/PanService( 3300): Received start request. Starting profile...
D/BluetoothPan( 1065): BluetoothPAN Proxy object connected
D/BluetoothPanServiceJni( 3300): initializeNative(L110): pan
I/bluedroid( 3300): get_profile_interface pan
,I/BtGatt.JNI( 3300): classInitNative(L873): classInitNative: Success!
,D/BluetoothAdapterService( 3300): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284f7a58
,D/BtGatt.DebugUtils( 3300): handleDebugAction() action=null
,D/BtGatt.GattService( 3300): Received start request. Starting profile...
D/BtGatt.GattService( 3300): start()
I/bluedroid( 3300): get_profile_interface gatt
D/BluetoothAdapterService( 3300): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284f7a58
D/BtGatt.AdvertiseManager( 3300): advertise manager created
,D/BluetoothAdapterService( 3300): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@284f7a58
,D/BluetoothMap( 1065): Proxy object connected
D/BluetoothMapService( 3300): Received start request. Starting profile...
D/BluetoothMapService( 3300): start()
,D/BluetoothMapEmailSettingsLoader( 3300): Found 0 applications
D/BluetoothMapEmailAppObserver( 3300): createReceiver()
,D/BluetoothMapEmailAppObserver( 3300): initObservers()
D/BluetoothMapEmailAppObserver( 3300): getEnabledAccountItems()
,D/HeadsetStateMachine( 3300): Proxy object connected
D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3300): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3300): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3300): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3300): enable
,I/bt_hci_bdroid( 3300): init
I/GKI_LINUX( 3300): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3300): btu_task pending for preload complete event
,I/bt_vendor( 3300): init
,I/bt_vnd_conf( 3300): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3300): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3300): userial_init
,I/ActivityManager(  824): Start proc 3363:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  824): Killing 2871:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/bt_userial_vendor( 3300): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3300): device fd = 53 open,
D/bt_userial( 3300): Entering userial_read_thread()
,I/bt_hwcfg( 3300): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3300): Chipset BCM4354A2
,D/bt_hwcfg( 3300): Target name = [BCM4354A2]
I/bt_hwcfg( 3300): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/ActivityManager(  824): Start proc 3386:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/Tethering(  824): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  824): Killing 2801:com.google.android.gm/u0a78 (adj 15): empty #17
,I/bt_hwcfg( 3300): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3300): Settlement delay -- 100 ms
I/bt_hwcfg( 3300): Setting fw settlement delay to 100 
,I/wpa_supplicant( 3307): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3307): Could not read interface p2p-dev-wlan0 flags: No such device
,I/bt_hwcfg( 3300): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg( 3300): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3300): vendor lib fwcfg completed
I/bt-btu  ( 3300): btu_task received preload complete event
,I/        ( 3300): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3300): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3300): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3300): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3300): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3300): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3300): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3300): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3300): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3300): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3300): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3300): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3300): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3300): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3300): BTE_InitTraceLevels -- TRC_BTIF
D/WifiConfigStore(  824): Loading config and enabling all networks 
,D/WifiService(  824): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@262f55ff}
,E/WifiConfigStore(  824): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  824): Setting external_sim to 1
W/Settings( 2654): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  824): Setting OUI to 92-68-C3
I/WifiNative-HAL(  824): startHal
D/wifi    (  824): setting scan oui 0xb4bdbe50
,D/WifiHAL (  824): Sending mac address OUI
,E/WifiStateMachine(  824): cancelDelayedScan -> 1
,W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
,D/WifiScanningService(  824): SCAN_AVAILABLE : 3
D/RttService(  824): SCAN_AVAILABLE : 3
D/RttService(  824): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  824): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  824): startHal
D/wifi    (  824): getting scan capabilities on interface[0] = 0xb4bdbe50
D/WifiHAL (  824): Creating message to get scan capablities; iface = 5
D/WifiHAL (  824): In GetCapabilities::handleResponse
D/WifiHAL (  824): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  824): StartedState
D/CommandListener(  354): Setting iface cfg
E/WifiP2pService(  824): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  824): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  824): p2pGetDeviceAddress
,D/WifiNative-HAL(  824): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 3307): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/ActivityManager(  824): Killing 2358:com.google.android.calendar/u0a37 (adj 15): empty #17
,E/native  (  824): do suspend false
,E/bt-btm  ( 3300): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2de2085 
E/bt-btm  ( 3300): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2de2085 
,D/BluetoothAdapterProperties( 3300): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3300): Calling BTA_HhEnable
,E/bt-btif ( 3300): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 3300): Address is:F8:CF:C5:D9:E5:61
,W/bt-btm  ( 3300): Stopping oneshot timer,
,D/BluetoothAdapterProperties( 3300): Name is: Nexus 6
,D/BluetoothManagerService(  824): Bluetooth Adapter name changed to Nexus 6
,D/BluetoothManagerService(  824): Stored Bluetooth name: Nexus 6
,D/BluetoothAdapterProperties( 3300): Scan Mode:20
D/BluetoothAdapterProperties( 3300): Discoverable Timeout:120
,D/bte_conf( 3300): Device ID record 1 : primary
D/bte_conf( 3300):   vendorId            = 000f
,D/bte_conf( 3300):   vendorIdSource      = 0001
,D/bte_conf( 3300):   product             = 1200
D/bte_conf( 3300):   version             = 1436
,D/bte_conf( 3300):   clientExecutableURL = 
D/bte_conf( 3300):   serviceDescription  = 
D/bte_conf( 3300):   documentationURL    = 
,D/bte_conf( 3300): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3300): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3300): ScanMode =  20,
D/BluetoothAdapterProperties( 3300): State =  11
D/BluetoothAdapterProperties( 3300): Setting state to 12
,I/BluetoothAdapterState( 3300): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  824): Message: 60
D/BluetoothPanServiceJni( 3300): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan,
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  824): Broadcasting onBluetoothStateChange(true) to 13 receivers.
,I/BluetoothAdapterState( 3300): Entering On State
D/BluetoothHeadset( 1065): onBluetoothStateChange: up=true
D/BluetoothManagerService(  824): Creating new ProfileServiceConnections object for profile: 1,
,E/bt_h4   ( 3300): vendor lib postload completed
,I/ActivityManager(  824): Start proc 3410:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
D/BluetoothAdapterProperties( 3300): Scan Mode:21
D/BluetoothAdapterProperties( 3300): Discoverable Timeout:120
,D/BluetoothHeadset(  824): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  824): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  824): onBluetoothStateChange: up=true
,D/BluetoothMap( 1065): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 1065): onBluetoothStateChange: up=true
,D/BluetoothAvrcpController( 1065): onBluetoothStateChange: up=true,
,E/BluetoothAvrcpController( 1065): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController },
,D/BluetoothA2dpSink( 1065): onBluetoothStateChange: up=true,
,E/BluetoothA2dpSink( 1065): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
,D/BluetoothPan( 1065): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1276): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 1065): onBluetoothStateChange: up=true
D/BluetoothHeadset(  824): onBluetoothStateChange: up=true
D/BluetoothHeadsetClient( 1065): onBluetoothStateChange: up=true
,E/BluetoothHeadsetClient( 1065): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothManagerService(  824): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  824): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 3300): onReceive
D/BluetoothMapService( 3300): STATE_ON
,D/BluetoothManagerService(  824): Message: 40
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapMasInstance( 3300): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3300): MAS initSocket()
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3300): Accepting socket connection...
,D/BluetoothManagerService(  824): Message: 400
D/BluetoothHeadset( 1065): Proxy object connected
,D/BluetoothManagerService(  824): Message: 400
D/BluetoothHeadset(  824): Proxy object connected
,D/BluetoothManagerService(  824): Message: 400
D/BluetoothHeadset(  824): Proxy object connected
,D/BluetoothManagerService(  824): Message: 400
,D/BluetoothHeadset( 1276): Proxy object connected
,D/BluetoothManagerService(  824): Message: 400
D/BluetoothHeadset(  824): Proxy object connected
,D/StrictMode( 3410): StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
D/StrictMode( 3410): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3410): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3410): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3410): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3410): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3410): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3410): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3410): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3410): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3410): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3410): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3410): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3410): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3410): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3410): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3410): StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3410): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3410): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3410): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3410): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3410): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3410): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3410): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3410): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3410): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3410): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3410): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3410): StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3410): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3410): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3410): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3410): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3410,): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3410): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3410): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3410): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3410): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3410): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3410): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3410): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3410): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3410): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3410): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3410): StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3410): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3410): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3410): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3410): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3410): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3410): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3410): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3410): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3410): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3410): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3410): StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3410): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3410): 	,at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3410): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3410): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
,D/StrictMode( 3410): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3410): 	at java.lang.Runtime.loadLibrary(Runtime.java:360),
D/StrictMode( 3410): 	,at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3410): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3410): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3410): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3410): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3410): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3410): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3410): StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3410): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3410): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3410): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3410): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3410): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3410): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3410): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3410): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3410): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3410): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3410): # via Binder call with stack:
D/StrictMode( 3410): android.os.StrictMode$LogStackTrace
D/StrictMode( 3410): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3410): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3410): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3410): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3410): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3410): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3410): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3410): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3410): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3410): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3410): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
,D/StrictMode( 3410): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3410): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3410): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3410): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3410): StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3410): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3410): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3410): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3410): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3410): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3410): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3410): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3410): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3410): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3410): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3410): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3410): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3410): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3410): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3410): StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3410): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3410): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3410): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3410): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3410): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3410): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3410): ,	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3410): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3410): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3410): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3410): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3410): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3410): 	,at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3410): StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3410): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3410): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3410): ,	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3410): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3410): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3410): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3410): ,	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3410): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3410): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3410): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3410): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3410): 	,at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3410): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3410): StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3410): ,	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3410): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3410): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3410): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3410): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3410): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3410): 	at com.google.p.j.c(PG:1152)
,D/StrictMode( 3410): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3410): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3410): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3410): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3410): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.map.n.f.a(PG:323),
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3410): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3410): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3410): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3410): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3410): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3410): 	at android.os.Handler.dispatchMessage(Handler.java:102),
D/StrictMode( 3410): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3410): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3410): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3410): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,W/com.google.a.a.a.b.a( 3410): Application name is not set. Call Builder#setApplicationName.,
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bd740da:true
,I/ActivityManager(  824): Killing 2906:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1482): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/jxcore-log( 3245): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3245): ,
I/jxcore-log( 3245): my name is : motorola-Nexus 6_PT1326
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): attempting to connect to test coordinator
I/jxcore-log( 3245): 
I/jxcore-log( 3245): check test folder
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): found test : ./testFindPeers.js
I/jxcore-log( 3245): 
,W/ContextImpl( 3386): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log( 3245): found test : ./testReConnect.js
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): found test : ./testSendData.js
I/jxcore-log( 3245): 
,D/BluetoothManagerService(  824): Message: 20,
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@78d1132:true
,I/jxcore-log( 3245): Test app app.js loaded,
I/jxcore-log( 3245): 
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,D/AuthorizationBluetoothService( 1482): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/Choreographer( 3245): Skipped 135 frames!  The application may be doing too much work on its main thread.
,D/LocalBluetoothProfileManager( 3386): Adding local A2DP profile
,D/BluetoothManagerService(  824): Message: 30
,I/chromium( 3245): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3386): Adding local HEADSET profile
,I/BtOppRfcommListener( 3300): Accept thread started.
,D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): Message: 30
,D/LocalBluetoothProfileManager( 3386): Adding local MAP profile
,D/BluetoothMap( 3386): Create BluetoothMap proxy object
,D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): Message: 30
,D/LocalBluetoothProfileManager( 3386): LocalBluetoothProfileManager construction complete,
,D/DockEventReceiver( 3386): finishStartingService: stopping service
,D/BluetoothA2dp( 3386): Proxy object connected
,D/A2dpProfile( 3386): Bluetooth service connected
,D/BluetoothInputDevice( 3386): Proxy object connected
D/HidProfile( 3386): Bluetooth service connected
,D/BluetoothPan( 3386): BluetoothPAN Proxy object connected
D/PanProfile( 3386): Bluetooth service connected
D/BluetoothMap( 3386): Proxy object connected
D/MapProfile( 3386): Bluetooth service connected
D/BluetoothMap( 3386): getConnectedDevices()
,D/BluetoothPbap( 3386): Proxy object connected
D/PbapServerProfile( 3386): Bluetooth service connected
,D/BluetoothManagerService(  824): Message: 400
,D/BluetoothHeadset( 3386): Proxy object connected
D/HeadsetProfile( 3386): Bluetooth service connected
,I/wpa_supplicant( 3307): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  824): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  824):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  824):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  824): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  824): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  824): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  824): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  824): will read network variables netId=0
,E/WifiStateMachine(  824): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  824): will read network variables netId=0
,I/wpa_supplicant( 3307): wlan0: Trying to associate with SSID 'NG7005g'
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/wpa_supplicant( 3307): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3307): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3307): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  824): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  824): Start Dhcp Watchdog 1
,E/WifiStateMachine(  824):  WifiLinkLayerStats: 
E/WifiStateMachine(  824):  my bss beacon rx: 1
E/WifiStateMachine(  824):  RSSI mgmt: -44
E/WifiStateMachine(  824):  BE :  rx=0 tx=4 lost=0 retries=0
E/WifiStateMachine(  824):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  on_time : 0 tx_time=58 rx_time=61 scan_time=0
,D/ConnectivityService(  824): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  824): do suspend false
,E/WifiStateMachine(  824): scanCount==0 - aborting
,I/dhcpcd  ( 3449): version 5.5.6 starting
,I/dhcpcd  ( 3449): wlan0: broadcasting for a lease
,I/dhcpcd  ( 3449): wlan0: offered 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 3449): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 3449): wlan0: leased 192.168.1.110 for 86400 seconds
,D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  824): Adding iface wlan0 to network 100
,E/WifiStateMachine(  824): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  824): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  824): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  824): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  824): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  824): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  824): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  824): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  824): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  824):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  824): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  824): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  824): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  824): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  824): MasterInitialState.processMessage what=3
,V/BackupManagerService(  824): Scheduling immediate backup pass
,D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  824): getDataEnabled: retVal=false
,I/ActivityManager(  824): Start proc 3486:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,V/BackupManagerService(  824): Running a backup pass
D/AlarmManagerService(  824): Setting time of day to sec=1448876916
W/AlarmManagerService(  824): Unable to set rtc to 1448876916: Invalid argument
,V/BackupManagerService(  824): clearing pending backups
,D/NetworkChangeNotifierAutoDetect( 1510): Network connectivity changed, type is: 2
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 30 Nov 2015 09:48:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448876916622], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448876916602]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Validated
D/ConnectivityService(  824): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  824): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  824): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  824): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  824): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
V/PerformBackupTask(  824): Beginning backup of 14 targets
,D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,D/PerformBackupTask(  824): invokeAgentForBackup on @pm@
,E/GpsLocationProvider(  824): No APN found to select.
,V/BackupServiceBinder(  824): doBackup() invoked
,I/PMBA    (  824): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  824): Getting widget state for user: 0
,D/GpsLocationProvider(  824): NTP server returned: 1448876916602 (Mon Nov 30 10:48:36 GMT+01:00 2015) reference: 149435 certainty: 8 system time offset: -87
,I/MusicStore( 3486): Database version: 120
,I/GoogleURLConnFactory( 1482): Using platform SSLCertificateSocketFactory
,W/GmsBackupTransport( 1752): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1752): starting performBackup for @pm@
,V/GmsBackupTransport( 1752): performBackup done for @pm@
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1787): [CredentialSyncAdapter] Unknown sync event.
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 16075(895KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 2.614ms total 36.217ms
,W/GLSActivity( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1482): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1482): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1752): Error sending final backup to server: 
W/GmsBackupTransport( 1752): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1752): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1752): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1752): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1752): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1752): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1752): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1752): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1752): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1752): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1752): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1752): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1752): 	... 1 more
,D/BackupManagerService(  824): Now staging backup of com.google.android.talk
,D/BackupManagerService(  824): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  824): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  824): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  824): Now staging backup of com.google.android.gm
,D/BackupManagerService(  824): Now staging backup of com.android.providers.userdictionary
,W/DriveInitializer( 1787): Background init thread started
,I/ConfigFetchService( 1787): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigService( 1482): onCreate
,I/ConfigFetchService( 1787): running network task: configservice_periodic
D/BackupManagerService(  824): Now staging backup of com.android.nfc
E/WakeLock( 1787): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1787): launchTask
,D/BackupManagerService(  824): Now staging backup of com.google.android.apps.genie.geniewidget
,I/ConfigFetchService( 1787): service connected
,D/ConfigFetchService( 1787): ConfigApi connection successful.
,D/BackupManagerService(  824): Now staging backup of com.google.android.marvin.talkback
,W/ResourcesManager( 3486): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3486): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BackupManagerService(  824): Now staging backup of com.google.android.inputmethod.latin
,I/art     (  824): Explicit concurrent mark sweep GC freed 53688(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 7.998ms total 91.866ms
,V/ConfigFetchTask( 1787): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XiXE8fwTXk4gsfh8Fab5qkSfRyf-JFyx0XKoFyY_48DD03HI0ySoLjxwBR7e-xoul0G1iTR7DSxWkTA81yt-yY2ZUaIywPtstKo-8-qnrearThiXU3d9ICPbPJ8MVVSVJKdLe7JGdySWk3Y8P3B1PizFF1GNlfbV9pe5gyatf-M_EIEM3QhgiELC0z0we_9Sp8w6Ah
,W/DriveInitializer( 1787): Background init thread ended
,D/BackupManagerService(  824): Now staging backup of com.google.android.calendar
,V/JNIHelp ( 3486): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/BackupManagerService(  824): Now staging backup of com.android.vending
,D/BackupManagerService(  824): Now staging backup of android
,D/BackupManagerService(  824): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1752): Next backup will happen in 43199814 millis.
,I/GoogleURLConnFactory( 1787): Using platform SSLCertificateSocketFactory
,I/BackupManagerService(  824): Backup pass finished.
,I/ProviderInstaller( 3486): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3486): GMSCore installation verified
,I/ConfigStore( 3486): Config Database version: 1
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3010): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3010): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3010): 	at jdm.a(PG:82)
E/HttpOperation( 3010): 	at jcs.o(PG:406)
E/HttpOperation( 3010): 	at jcn.a(PG:1379)
E/HttpOperation( 3010): 	at jcs.i(PG:143)
E/HttpOperation( 3010): 	at blb.a(PG:3937)
E/HttpOperation( 3010): 	at czp.a(PG:18188)
E/HttpOperation( 3010): 	at czp.a(PG:9081)
E/HttpOperation( 3010): 	at czq.run(PG:1686)
E/HttpOperation( 3010): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3010): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3010): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3010): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3010): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3010): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3010): 	at jdj.a(PG:4091)
E/HttpOperation( 3010): 	at jdj.a(PG:1125)
E/HttpOperation( 3010): 	at jdm.a(PG:77)
E/HttpOperation( 3010): 	... 12 more
E/HttpOperation( 3010): Caused by: faj: BadAuthentication
E/HttpOperation( 3010): 	at fal.a(PG:38)
E/HttpOperation( 3010): 	at jdj.a(PG:4089)
E/HttpOperation( 3010): 	... 14 more
,I/MediaRouter( 3486): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3486): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/NetworkMonitor( 3486): type=WIFI subType= reason=null isConnected=true
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3010): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3010): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3010): 	at jdm.a(PG:82)
E/HttpOperation( 3010): 	at jcs.o(PG:406)
E/HttpOperation( 3010): 	at jcn.a(PG:1379)
E/HttpOperation( 3010): 	at jcs.i(PG:143)
E/HttpOperation( 3010): 	at hec.a(PG:42)
E/HttpOperation( 3010): 	at hee.a(PG:102)
E/HttpOperation( 3010): 	at czr.a(PG:65)
E/HttpOperation( 3010): 	at kka.a(PG:108)
E/HttpOperation( 3010): 	at czp.a(PG:19176)
E/HttpOperation( 3010): 	at czp.a(PG:9081)
E/HttpOperation( 3010): 	at czq.run(PG:1686)
E/HttpOperation( 3010): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3010): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3010): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3010): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3010): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3010): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3010): 	at jdj.a(PG:4091)
E/HttpOperation( 3010): 	at jdj.a(PG:1125)
E/HttpOperation( 3010): 	at jdm.a(PG:77)
E/HttpOperation( 3010): 	... 15 more
E/HttpOperation( 3010): Caused by: faj: BadAuthentication
E/HttpOperation( 3010): 	at fal.a(PG:38)
E/HttpOperation( 3010): 	at jdj.a(PG:4089)
E/HttpOperation( 3010): 	... 17 more
E/ExperimentLoader( 3010): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3010): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3010): 	at jdm.a(PG:82)
E/ExperimentLoader( 3010): 	at jcs.o(PG:406)
E/ExperimentLoader( 3010): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3010): 	at jcs.i(PG:143)
E/ExperimentLoader( 3010): 	at hec.a(PG:42)
E/ExperimentLoader( 3010): 	at hee.a(PG:102)
E/ExperimentLoader( 3010): 	at czr.a(PG:65)
E/ExperimentLoader( 3010): 	at kka.a(PG:108)
E/ExperimentLoader( 3010): 	at czp.a(PG:19176)
E/ExperimentLoader( 3010): 	at czp.a(PG:9081)
E/ExperimentLoader( 3010): 	at czq.run(PG:1686)
E/ExperimentLoader( 3010): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3010): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3010): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3010): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3010): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3010): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3010): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3010): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3010): 	at jdm.a(PG:77)
E/ExperimentLoader( 3010): 	... 15 more
E/ExperimentLoader( 3010): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3010): 	at fal.a(PG:38)
E/ExperimentLoader( 3010): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3010): 	... 17 more
,I/NetworkMonitor( 3486): type=WIFI subType= reason=null isConnected=true
,D/DownloadManager( 1087): [71] Starting
,I/ActivityManager(  824): Start proc 3557:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,W/ActivityThread( 1087): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/GHttpClientFactory( 3486): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3486): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 3557): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3557): simOperator:  IMSI: null
D/SprintDMReceiver( 3557): Not Sprint UICC, don't do anything.
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 37108, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/SystemUpdateService( 1787): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1787): onCreate
,D/SystemUpdateService( 1787): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1787): active receiver: enabled
,I/SystemUpdateService( 1787): showing system update notification
,V/KeepSync( 3363): Connecting to GoogleApiClient
,I/ActivityManager(  824): Start proc 3584:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
I/CheckinService( 1787): Checking schedule, now: 1448876917340 next: 1448644092874
I/CheckinService( 1787): active receiver: enabled
,I/CheckinService( 1787): Preparing to send checkin request
,I/EventLogService( 1787): Accumulating logs since 1448876078325
,I/ValidateNoPeople(  824): skipping global notification
,V/SystemUpdateService( 1787): retry (wakeup: false) in 3599937 ms
,V/GoogleAuthProtoRequest( 3319): [341] a.<init>: mAccountName set to: thalitester@gmail.com
I/art     ( 1482): Explicit concurrent mark sweep GC freed 17202(998KB) AllocSpace objects, 2(55KB) LOS objects, 37% free, 26MB/42MB, paused 973us total 25.675ms
,I/iu.SyncManager( 1787): SYNC; picasa accounts
,D/NetworkLogImpl( 1787): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1787): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/SystemUpdateService( 1787): onDestroy
,I/EventLogService( 1787): Opted in for usage reporting
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1787): num queued entries: 0
I/iu.UploadsManager( 1787): num updated entries: 0
I/iu.SyncManager( 1787): NEXT; no task
,D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,I/GcmGroups( 1787): Failed to subscribe to group.
I/GcmGroups( 1787): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 1787): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 1787): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 1787): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 1787): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 1787): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 1787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 1787): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 1787): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  824): Start proc 3612:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GcmGroups( 1787): Groups upload failed, retrying in 24000:00:00
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 2654): connection state changed from DISCONNECTED to CONNECTED
,E/ClientConnectionOperation( 1787): Handling authorization failure
E/ClientConnectionOperation( 1787): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1787): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1787): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1787): 	... 7 more
W/Kids    ( 1787): [AccountUtils] Account not ready
W/Kids    ( 1787): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1787): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1787): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1787): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1787): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1787): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1787): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1787): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1787): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1787): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1787): 	at java.lang.Thread.run(Thread.java:818)
,V/KeepSync( 3363): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3363): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3363): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3363): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/EventLogAggregator( 1787): Unknown tag: snet_gcore
W/EventLogAggregator( 1787): Unknown tag: snet_launch_service
,I/jxcore-log( 3245): BLE advertisement not supported: Not supported
I/jxcore-log( 3245): 
,I/GAv4    ( 3612): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3612):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3612):   adb logcat -s GAv4
,I/ConfigFetchTask( 1787): updating config table for com.google.android.gms
,W/GAv4    ( 3612): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/GCM     ( 1482): Connected
,W/ExperimentUpdateService( 3319): [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/GAv4    ( 3612): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/ExperimentUpdateService( 3319): [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3319): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3319): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3319): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3319): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3319): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3319): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3319): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3319): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3319): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3319): 	at com.a.a.k.run(SourceFile:110)
,I/CheckinRequestBuilder( 1787): Checkin reason type: 12 attempt count: 1
,W/GAv4    ( 3612): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/WifiService(  824): New client listening to asynchronous messages
,E/ActivityThread( 1787): Failed to find provider info for com.google.android.wearable.settings
,D/GCM     ( 1482): Message class com.google.f.a.a.p
,I/ActivityManager(  824): Start proc 3643:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,I/art     (  824): Explicit concurrent mark sweep GC freed 27217(1265KB) AllocSpace objects, 4(104KB) LOS objects, 32% free, 33MB/49MB, paused 1.627ms total 54.947ms
,D/DownloadManager( 1087): [71] Finished with status SUCCESS
,I/ConfigFetchService( 1787): fetch service done; releasing wakelock
I/ConfigFetchService( 1787): stopping self
,W/ResourcesManager( 3643): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3643): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAV2    ( 3584): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3584): Created application version: 3.6.8 (30608)
,V/JNIHelp ( 3643): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3643): Installed default security provider GmsCore_OpenSSL
,I/WebViewFactory( 3612): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3612): Time to load native libraries: 2 ms (timestamps 853-855)
,I/LibraryLoader( 3612): Expected native library version number "",actual native library version number ""
,I/art     ( 1787): Explicit concurrent mark sweep GC freed 25292(1754KB) AllocSpace objects, 15(263KB) LOS objects, 35% free, 29MB/45MB, paused 3.365ms total 151.064ms
,V/WebViewChromiumFactoryProvider( 3612): Binding Chromium to main looper Looper (main, tid 1) {18838c2c}
,I/LibraryLoader( 3612): Expected native library version number "",actual native library version number ""
,I/chromium( 3612): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BooksSync( 3584): Starting books sync for 61035162, extras: ade
I/BrowserStartupController( 3612): Initializing chromium process, singleProcess=true
,W/art     ( 3612): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3612): ApplicationContext is null in ApplicationStatus
,E/YouTube MDX( 3643): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/chromium( 3612): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/libEGL  ( 3612): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3612): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3612): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/dex2oat ( 3692): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads963494651.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads963494651.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3692): dex2oat took 51.963ms (threads: 4) arena alloc=121KB java alloc=12KB native alloc=964KB free=7MB
,I/NSApplication( 3612): Starting up...
,I/ActivityManager(  824): Killing 2952:com.android.providers.calendar/u0a3 (adj 15): empty #17
,W/AudioManagerAndroid( 3612): Requires BLUETOOTH permission
,I/BooksConfig( 3584): GmsCore Version = 7.8.99 (2134222-430)
,E/KeepSync( 3363): IOException
E/KeepSync( 3363): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3363): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3363): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3363): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3363): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3363): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3363): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3363): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3363): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3363): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3363): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3363): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3363): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3363): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3363): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3363): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3363): 	... 10 more
W/KeepSync( 3363): Sync result 2
,W/InstanceID/Rpc( 3643): Found 10011
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 37110, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  824): Start proc 3771:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  824): Killing 2438:android.process.acore/u0a5 (adj 15): empty #17
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/BooksAccountManager( 3584): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksSync( 3584): Soft error
E/BooksSync( 3584): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3584): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3584): Sync error
E/BooksSync( 3584): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3584): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3584): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37111, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  824): Killing 3125:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 30383(1681KB) AllocSpace objects, 5(362KB) LOS objects, 37% free, 27MB/43MB, paused 1.078ms total 33.009ms
,I/ActivityManager(  824): Start proc 3800:com.google.android.gm/u0a78 for service com.google.android.gm/.provider.MailSyncAdapterService
,W/CheckinRequestBuilder( 1787): awaiting user notification for token
,I/Gmail   ( 3800): getAccountsCursor
,D/ActivityThread( 3800): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  824): Start proc 3822:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 9.233ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 19.326ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 8.659ms
,I/ActivityManager(  824): Start proc 3839:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,I/art     (  824): Explicit concurrent mark sweep GC freed 22024(898KB) AllocSpace objects, 4(158KB) LOS objects, 32% free, 33MB/49MB, paused 1.537ms total 49.637ms
,W/ResourcesManager( 3839): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3839): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SyncAdapterService( 3612): Ignoring sync request for non-current account
,I/MultiDex( 3839): VM with version 2.1.0 has multidex support
I/MultiDex( 3839): install
I/MultiDex( 3839): VM has multidex support, MultiDex support library is disabled.
W/GAV2    ( 3800): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/JNIHelp ( 3839): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/Gmail   ( 3800): Sync started for account: account:61035162
,I/Gmail   ( 3800): getAccountsCursor
W/ActivityManager(  824): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Exchange( 3822): EasService.onCreate
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 3822): RestartPingTask
,I/ProviderInstaller( 3839): Installed default security provider GmsCore_OpenSSL
,I/Gmail   ( 3800): Observing account changes for notifications
,I/ActivityManager(  824): Start proc 3880:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,D/WVCdm   (  358): Instantiating CDM.
,I/WVCdm   (  358): CdmEngine::OpenSession
I/WVCdm   (  358): Level3 Library Dec 11 2014 16:13:16
,E/SQLiteLog( 3800): (283) recovered 9 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/WVCdm   (  358): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  358): Service_Initialize: starts!
D/QSEECOMAPI: (  358): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  358): App is not loaded in QSEE
,I/Exchange( 3822): RestartPingsTask did not start any pings.
I/Exchange( 3822): PSS stopIfIdle
I/Exchange( 3822): PSS has no active accounts; stopping service.
,I/Exchange( 3822): onDestroy
,I/ActivityManager(  824): Killing 3146:com.android.musicfx/u0a18 (adj 15): empty #17
,I/Gmail   ( 3800): notifyAccountChanged
,I/Gmail   ( 3800): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3800): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3800): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3800): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ContactLocale( 3880): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/GoogleURLConnFactory( 3839): Using platform SSLCertificateSocketFactory
,I/[@@    ] SyncAdapterProxy( 1482): Delagator disabled, using the (deprecated) GData sync adapter
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3800): notifyAccountChanged
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QSEECOMAPI: (  358): Loaded image: APP id = 3
,D/DrmWidevineDash(  358): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
E/DrmWidevineDash(  358): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
,D/DrmLibTime(  313): got the req here! ret=0
D/DrmLibTime(  313): command id, time_cmd_id = 770
,D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  313): QSEE Time Listener: seconds: 1448876919
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 411062707
D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1448876919; nsec = 411062707
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
,W/GLSActivity( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1482): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1482): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
D/ContactsSyncAdapter( 1482): innerSync failed
D/ContactsSyncAdapter( 1482): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1482): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1482): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1482): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1482): 	at com.google.android.syncadapters.contacts.delegation.SyncAdapterProxy.onPerformLoggedSync(SyncAdapterProxy.java:123)
D/ContactsSyncAdapter( 1482): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1482): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1482): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1482): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
D/ContactsSyncAdapter( 1482): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1482): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
D/ContactsSyncAdapter( 1482): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/DrmWidevineDash(  358): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4045800, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  358): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  358): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  358): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  358): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d78840, idLength=0xb2ff1710
,I/ActivityManager(  824): Start proc 3906:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,I/ActivityManager(  824): Killing 1821:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  358): PrepareKeyRequest: nonce=3253380178
D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4d28600
,D/DrmWidevineDash(  358): message_length=1599, signature=0xb4c54300, signature_length=3003062004
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  358): CdmEngine::CloseSession
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  358): L3 Terminate.
D/DrmWidevineDash(  358): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  358): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  358): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  358): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  358): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  824): Killing 3174:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 37120, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  824): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 185331, reason: Periodic
,E/SQLiteLog( 3906): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal,
,I/ActivityManager(  824): Start proc 3928:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3928): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Gmail   ( 3800): getAccountsCursor
,I/CalendarProvider2( 3928): Created com.android.providers.calendar.CalendarAlarmManager@36e585ca(com.android.providers.calendar.CalendarProvider2@12b9b33b)
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3800): getAccountsCursor
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  824): Start proc 3952:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/Gmail   ( 3800): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4353, normalSync: true
,I/AnalyticsLogBase( 3906): PlayLogger.onLoggerConnected
,I/AnalyticsLogBase( 3906): PlayLogger.onLoggerConnected
,D/TimeService( 3952): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448876920060
D/        ( 3952): TimeServiceNative: User Time to be set is 1448876920061
D/QC-time-services( 3952): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3952): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3952): Lib:time_genoff_operation: pargs->ts_val = 1448876920061
D/QC-time-services(  373): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3952): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  373): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448876920061
D/QC-time-services(  373): Daemon:genoff_opr: Base = 2, val = 1448876920061, operation = 0
,D/QC-time-services(  373): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/17/70 6:1:38
D/QC-time-services(  373): Daemon:Value read from RTC seconds = 9180098000
D/QC-time-services(  373): Daemon:new time 1448876920061 
D/QC-time-services(  373): Daemon: delta 1439696822061 genoff 1439696822061 
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696822061 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  373): Updating the TOD offset
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696822061 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  373): Daemon:Update to modem bit set
D/QC-time-services(  373): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  373): Daemon: Base = 2, Value being sent to MODEM = 1132912120061
E/QC-time-services( 3952): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  824): Killing 3080:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/dex2oat ( 3970): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3970): dex2oat took 20.971ms (threads: 4) arena alloc=87KB java alloc=18KB native alloc=1246KB free=6MB
,I/Adreno  ( 3839): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/ResourcesManager( 3906): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3906): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/QC-time-services(  373): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  373): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,V/JNIHelp ( 3906): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3906): Installed default security provider GmsCore_OpenSSL
W/AbstractGoogleClient( 3906): Application name is not set. Call Builder#setApplicationName.
,I/art     (  824): Explicit concurrent mark sweep GC freed 14900(661KB) AllocSpace objects, 3(330KB) LOS objects, 32% free, 33MB/49MB, paused 1.445ms total 46.768ms
,I/Adreno  ( 3839): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/ResourcesManager( 3800): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3800): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3800): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  824): Start proc 3979:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ProviderInstaller( 3800): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  358): CdmEngine::OpenSession
I/WVCdm   (  358): Level3 Library Dec 11 2014 16:13:16
,I/GAv4    ( 3979): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3979):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3979):   adb logcat -s GAv4
,W/WVCdm   (  358): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  358): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  358): Service_Initialize: starts!
D/QSEECOMAPI: (  358): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  358): App is not loaded in QSEE
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 3979): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3979): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3979): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/GLSActivity( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1482): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1482): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1482): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1482): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ActivityManager(  824): Killing 2742:com.android.vending/u0a19 (adj 15): empty #17
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Gmail   ( 3800): notifyAccountChanged
,I/Gmail   ( 3800): getAccountsCursor
,D/QSEECOMAPI: (  358): Loaded image: APP id = 3
,D/DrmWidevineDash(  358): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
E/DrmWidevineDash(  358): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmLibTime(  313): got the req here! ret=0
D/DrmLibTime(  313): command id, time_cmd_id = 770
D/DrmLibTime(  313): time_getutcsec starts!
,D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  313): QSEE Time Listener: seconds: 1448876920
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 496649008
,D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1448876920; nsec = 496649008
,D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DrmWidevineDash(  358): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  358): hlos api version =  9,
D/DrmWidevineDash(  358): tz api version =  9
,D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  358): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: starts! SID=0xbe864520
,D/DrmWidevineDash(  358): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: starts! randomData=0xb4c4e230, dataLength=8
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4047000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  358): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  358): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  358): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  358): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d78880, idLength=0xb2ff1710
V/Herrevad( 1787): NQAS connected
,D/GCM     ( 1482): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
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
,D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  358): PrepareKeyRequest: nonce=3546841243
D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4d28600
D/DrmWidevineDash(  358): message_length=1634, signature=0xb4c54300, signature_length=3003062004
I/ConfigFetchService( 1787): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,D/WifiService(  824): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@262f55ff}
I/ConfigFetchService( 1787): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1787): GmsCore config value changed; rescheduling
I/ConfigFetchService( 1787): service connected
,D/ConfigFetchService( 1787): ConfigApi connection successful.
,I/ConfigFetchService( 1787): self-hosted config:fetch_interval = 43200
,I/DictionaryProvider:UpdateHandler( 1213): downloadFinished() : DownloadId = 71
,I/ConfigFetchService( 1787): stopping self
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  358): CdmEngine::CloseSession
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  358): L3 Terminate.
D/DrmWidevineDash(  358): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  358): Service_Uninitialize: starts!
D/QSEECOMAPI: (  358): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  358): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  358): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_Terminate: ends! returns 0
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 16800(958KB) AllocSpace objects, 9(992KB) LOS objects, 36% free, 27MB/43MB, paused 1.039ms total 103.712ms
,D/GCM     ( 1482): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1482): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1787): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/Gmail   ( 3800): notifyAccountChanged
,W/Gmail   ( 3800): Sync complete for account: account:61035162
,I/Gmail   ( 3800): getAccountsCursor
,E/CalendarSyncAdapter( 3906): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 3906): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 3906): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 3906): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 3906): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 3906): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 3906): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 3906): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 3906): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2382)
E/CalendarSyncAdapter( 3906): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1850)
E/CalendarSyncAdapter( 3906): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:1733)
E/CalendarSyncAdapter( 3906): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:503)
E/CalendarSyncAdapter( 3906): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:392)
E/CalendarSyncAdapter( 3906): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 3906): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 3906): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 3906): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 3906): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 3906): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 3906): 	... 12 more
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  824): Start proc 4016:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 37120, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  824): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 184251, reason: Periodic
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 1787): Restart initialization of location
,W/ResourcesManager( 4016): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4016): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Babel   ( 2654): UserRecoverableAuthException.
E/Babel   ( 2654): eei: BadAuthentication
E/Babel   ( 2654): 	at eeg.a(Unknown Source)
E/Babel   ( 2654): 	at eeg.a(Unknown Source)
E/Babel   ( 2654): 	at eeg.a(Unknown Source)
E/Babel   ( 2654): 	at g.a(Unknown Source)
E/Babel   ( 2654): 	at cae.a(SourceFile:3089)
E/Babel   ( 2654): 	at cae.a(SourceFile:1131)
E/Babel   ( 2654): 	at cws.a(SourceFile:4333)
E/Babel   ( 2654): 	at cws.a(SourceFile:1419)
E/Babel   ( 2654): 	at crl.a(SourceFile:492)
E/Babel   ( 2654): 	at crl.a(SourceFile:1468)
E/Babel   ( 2654): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2654): 	at cas.b(SourceFile:106)
E/Babel   ( 2654): 	at cap.d(SourceFile:335)
E/Babel   ( 2654): 	at caq.run(SourceFile:81)
E/Babel   ( 2654): Error getting auth token
E/Babel   ( 2654): dvm
E/Babel   ( 2654): 	at g.a(Unknown Source)
E/Babel   ( 2654): 	at cae.a(SourceFile:3089)
E/Babel   ( 2654): 	at cae.a(SourceFile:1131)
E/Babel   ( 2654): 	at cws.a(SourceFile:4333)
E/Babel   ( 2654): 	at cws.a(SourceFile:1419)
E/Babel   ( 2654): 	at crl.a(SourceFile:492)
E/Babel   ( 2654): 	at crl.a(SourceFile:1468)
E/Babel   ( 2654): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2654): 	at cas.b(SourceFile:106)
E/Babel   ( 2654): 	at cap.d(SourceFile:335)
E/Babel   ( 2654): 	at caq.run(SourceFile:81)
,E/Babel   ( 2654): Account registration failed 1-Redacted-21
E/Babel   ( 2654): cyp: null -- null
E/Babel   ( 2654): 	at cae.a(SourceFile:3121)
E/Babel   ( 2654): 	at cae.a(SourceFile:1131)
E/Babel   ( 2654): 	at cws.a(SourceFile:4333)
E/Babel   ( 2654): 	at cws.a(SourceFile:1419)
E/Babel   ( 2654): 	at crl.a(SourceFile:492)
E/Babel   ( 2654): 	at crl.a(SourceFile:1468)
E/Babel   ( 2654): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2654): 	at cas.b(SourceFile:106)
E/Babel   ( 2654): 	at cap.d(SourceFile:335)
E/Babel   ( 2654): 	at caq.run(SourceFile:81)
,I/art     ( 2654): Note: end time exceeds epoch: 
,I/MultiDex( 4016): VM with version 2.1.0 has multidex support
I/MultiDex( 4016): install
I/MultiDex( 4016): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4016): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ProviderInstaller( 4016): Installed default security provider GmsCore_OpenSSL
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 37120, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  824): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 183736, reason: Periodic
D/GCM     ( 1482): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ResourcesManager( 1482): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,D/WearableService( 4016): callingUid 10011, callindPid: 4016
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,E/MDM     ( 1752): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,I/GHttpClientFactory( 3486): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3486): Using platform SSLCertificateSocketFactory
,E/Babel   ( 2654): Unexpected exception while authenticating.
,E/Babel   ( 2654): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2654): 	at eeg.b(Unknown Source)
E/Babel   ( 2654): 	at eeg.b(Unknown Source)
E/Babel   ( 2654): 	at g.a(Unknown Source)
E/Babel   ( 2654): 	at cae.b(SourceFile:1146)
E/Babel   ( 2654): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2654): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2654): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2654): 	at java.lang.Thread.run(Thread.java:818)
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,I/art     (  824): Explicit concurrent mark sweep GC freed 18540(783KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.310ms total 61.628ms
,I/ActivityManager(  824): Killing 3386:com.android.settings/1000 (adj 15): empty #17
,I/CalendarProvider2( 3928): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3928): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/DictionaryProvider:UpdateHandler( 1213): downloadFinished() : Success = true
I/DictionaryProvider:UpdateHandler( 1213): downloadFinished() : Metadata Success
,I/Keyboard.Facilitator( 1213): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1213): run()
,I/Decoder ( 1213): createOrResetDecoder
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): run()
,D/AuthorizationBluetoothService( 1482): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/MusicLifecycle( 3486): Sync started
,V/GmsCoreStatsServiceLauncher( 1787): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1752): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1787): Restart initialization of location
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1213): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1213): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1213): run()
I/StatsUtilsManager( 1213): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1213): shouldRecordStats() = Too Soon
,I/ActivityManager(  824): Killing 3410:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  824): Start proc 4062:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,I/DictionaryProvider:UpdateHandler( 1213): downloadFinished() : Success = true
I/DictionaryProvider:UpdateHandler( 1213): downloadFinished() : Metadata Success
,I/Keyboard.Facilitator( 1213): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1213): run()
,I/Decoder ( 1213): createOrResetDecoder
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): run()
,V/GoogleAuthProtoRequest( 3319): [342] a.<init>: mAccountName set to: thalitester@gmail.com
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 20105(1085KB) AllocSpace objects, 11(1212KB) LOS objects, 37% free, 26MB/42MB, paused 867us total 23.695ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1213): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1213): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1213): run()
I/StatsUtilsManager( 1213): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1213): shouldRecordStats() = Too Soon
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  824): Start proc 4086:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Ads     ( 1787): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1482): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1482): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ExperimentUpdateService( 3319): [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3319): [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3319): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3319): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3319): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3319): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3319): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3319): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3319): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3319): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3319): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3319): 	at com.a.a.k.run(SourceFile:110)
,I/art     ( 1787): Explicit concurrent mark sweep GC freed 18738(1058KB) AllocSpace objects, 9(144KB) LOS objects, 35% free, 29MB/45MB, paused 1.362ms total 57.636ms
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 4062): Sync request not initiated by GCP app. Dropping
,E/SQLiteLog( 3928): (284) automatic index on view_events(_id)
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=84.62 rxSuccessRate=84.81 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,I/ActivityManager(  824): Killing 1510:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  824): Client connection lost with reason: 4
,I/MusicLifecycle( 3486): Sync ended
W/MusicSyncAdapter( 3486): Sync failed due to an authentication issue.
,I/VacuumService( 1482): Vacuum at: now=1448876921846 tag=VacuumService
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 37120, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  824): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 185700, reason: Periodic
,D/DelayedSyncController( 1231): Delaying sync.
,I/EventLogService( 1787): Opted in for usage reporting
,I/MusicLeanback( 3486): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3486): Stop autocaching.
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=84.62 rxSuccessRate=84.81 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,I/GoogleURLConnFactory( 1787): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1787): [CredentialSyncAdapter] Unknown sync event.
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1482): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1482): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
,W/SubscribedFeeds( 1787): Hard error
,E/GmsUtils( 3486): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3486): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 37120, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,I/ActivityManager(  824): Killing 3557:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
D/SyncManager(  824): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 185352, reason: Periodic
,I/ReminderSync( 1787): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=240:priority=5:group=main]
,I/art     (  824): Explicit concurrent mark sweep GC freed 32767(1481KB) AllocSpace objects, 8(505KB) LOS objects, 32% free, 33MB/49MB, paused 1.540ms total 55.894ms
,I/MusicLeanback( 3486): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3486): Stop autocaching.
,E/GmsUtils( 3486): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3486): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/PeopleSync( 1787): onPerformSync() [5005f081]
,I/GoogleURLConnFactory( 1482): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleDatabaseHelper( 1787): cleanUpNonGplusAccounts done.
,E/Uploader( 1482): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1482): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1752): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1752): Using Auth Proxy for data requests.
,I/GLSUser ( 1752): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1752): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/PeopleSync( 1787): Setting subscription: result=true [5005f081]
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleSync( 1787): Starting sync, feed=null [5005f081]
,E/GCoreUlr( 1752): 
E/GCoreUlr( 1752): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1752): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1752): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1752): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1752): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1752): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1752): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1752): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1752): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1752): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1752): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1752): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1752): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1752): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1752): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1752): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 37120, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  824): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 187315, reason: Periodic
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 31308(1696KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 27MB/43MB, paused 1.147ms total 52.829ms
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  824): Start proc 4149:com.google.android.apps.docs.editors.docs/u0a47 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,I/CheckinTask( 1787): Sending checkin request (10485 bytes)
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,E/Uploader( 1482): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1482): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/PeopleSync( 1787): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleSync( 1787): Sync finished, successful=false, took 35ms
,I/PeopleSync( 1787): Cannot authenticate [5005f081]
I/PeopleSync( 1787): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 1787): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 1787): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 1787): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 1787): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 1787): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 1787): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 1787): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 1787): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 1787): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 1787): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 1787): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/PeopleSync( 1787): ***Sync finished***, duration: 463 [5005f081]
,W/Uploader( 1482): No account for auth token provided
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 41791, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  824): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 188222, reason: Periodic
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ReminderSync( 1787): AuthError [T SyncAdapterThread-2:id=243:priority=5:group=main]
,I/GAV2    ( 3584): Thread[GAThread,5,main]: No campaign data found.
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 41818, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  824): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 187748, reason: Periodic
,W/Uploader( 1482): No account for auth token provided
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 211us total 9.864ms
,I/ActivityManager(  824): Start proc 4170:com.google.android.apps.docs/u0a46 for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 228us total 12.101ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 9.351ms
,I/CheckinRequestBuilder( 1787): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1787): Failed to find provider info for com.google.android.wearable.settings
,W/Uploader( 1482): No account for auth token provided
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 1787): awaiting user notification for token
,I/EventLogService( 1787): Opted in for usage reporting
,I/GAv4    ( 4170): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4170):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4170):   adb logcat -s GAv4
,I/CheckinTask( 1787): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GAv4    ( 4170): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4170): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinService( 1787): Checking schedule, now: 1448876923217 next: 1448918066205
I/CheckinService( 1787): active receiver: disabled
,W/GAv4    ( 4170): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4170): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,W/Uploader( 1482): No account for auth token provided
,I/art     (  824): Explicit concurrent mark sweep GC freed 27862(1246KB) AllocSpace objects, 7(300KB) LOS objects, 32% free, 33MB/49MB, paused 1.311ms total 46.884ms
,D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1482): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     ( 1787): Explicit concurrent mark sweep GC freed 28771(3MB) AllocSpace objects, 14(223KB) LOS objects, 35% free, 29MB/45MB, paused 1.018ms total 34.573ms
D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ResourcesManager( 4170): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4170): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 4170): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4170): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 4170): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/Uploader( 1482): No account for auth token provided
,W/Kids    ( 1787): [AccountUtils] Account not ready
W/Kids    ( 1787): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1787): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1787): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1787): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1787): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1787): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1787): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1787): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1787): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1787): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1787): 	at java.lang.Thread.run(Thread.java:818)
,I/ProviderInstaller( 4170): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiService(  824): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@203fc564}
,I/GAv4    ( 4149): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4149):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4149):   adb logcat -s GAv4
,W/GAv4    ( 4149): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4149): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4149): Analytics setup for ID UA-21125203-4, app name Docs, version 1.4.292.15.30
,W/GAv4    ( 4149): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/Uploader( 1482): No account for auth token provided
,W/ResourcesManager( 4149): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4149): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4149): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4149): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  824): Killing 3010:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,W/Uploader( 1482): No account for auth token provided
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1482): No account for auth token provided
,W/GLSActivity( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1482): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1482): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DefaultHttpIssuer( 4170): Attempt to consume entity of HttpIssuer when no request is executing.
,E/DefaultHttpIssuer( 4170): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 4170): java.io.IOException
E/DefaultHttpIssuer( 4170): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 4170): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 4170): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 4170): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 4170): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 4170): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 4170): 	at dlr.run(PG:3031)
,E/BaseSyncManager( 4170): AuthenticatorException
E/BaseSyncManager( 4170): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 4170): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/BaseSyncManager( 4170): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 4170): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/BaseSyncManager( 4170): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 4170): 	at android.os.Binder.execTransact(Binder.java:446)
,D/WifiService(  824): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@203fc564}
,I/ActivityManager(  824): Start proc 4246:com.google.android.apps.docs.editors.sheets/u0a48 for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,I/ActivityManager(  824): Killing 3584:com.google.android.apps.books/u0a34 (adj 15): empty #17
,I/GAV2    ( 3800): Thread[GAThread,5,main]: No campaign data found.
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,I/GAV2    ( 3906): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4    ( 4246): Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4246):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4246):   adb logcat -s GAv4
,W/Uploader( 1482): No account for auth token provided
,W/GAv4    ( 4246): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4246): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4246): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4246): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.332.11.30
,W/Uploader( 1482): No account for auth token provided
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  824): Killing 3612:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,W/ResourcesManager( 4246): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4246): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4246): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4246): Installed default security provider GmsCore_OpenSSL
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,I/ActivityManager(  824): Start proc 4296:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,W/Uploader( 1482): No account for auth token provided
,D/Finsky  ( 4296): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager(  824): Killing 3822:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,D/Finsky  ( 4296): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Uploader( 1482): No account for auth token provided
,I/ActivityManager(  824): Start proc 4332:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 4296): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4296): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4332): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4332): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4296): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4296): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4296): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 4332): VM with version 2.1.0 has multidex support
I/MultiDex( 4332): install
I/MultiDex( 4332): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 4296): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  824): Killing 3363:com.google.android.keep/u0a79 (adj 15): empty #17
,V/JNIHelp ( 4332): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4332): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1482): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1482): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1787): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1752): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Uploader( 1482): No account for auth token provided
,D/LocationInitializer( 1787): Restart initialization of location
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 134429(8MB) AllocSpace objects, 28(2MB) LOS objects, 36% free, 28MB/44MB, paused 1.131ms total 36.548ms
,I/ConfigService( 1482): onDestroy
,V/Finsky  ( 4296): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
W/Uploader( 1482): No account for auth token provided
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4296): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4296): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4296): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ActivityManager(  824): Killing 3952:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  824): Killing 3979:com.google.android.deskclock/u0a44 (adj 15): empty #17
,W/Uploader( 1482): No account for auth token provided,
,D/Finsky  ( 4296): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1482): No account for auth token provided
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4296): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  824): Explicit concurrent mark sweep GC freed 26969(1317KB) AllocSpace objects, 11(458KB) LOS objects, 32% free, 33MB/49MB, paused 2.275ms total 98.735ms
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4296): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1482): No account for auth token provided
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4296): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4296): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4296): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4296): [1] DailyHygiene.reschedule: Scheduling new run in 772 minutes (failures=5)
,D/Finsky  ( 4296): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/DeviceConnectionService( 1752): client connected with version: 7571000
,D/Finsky  ( 4296): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,W/Uploader( 1482): No account for auth token provided
,I/ActivityManager(  824): Killing 2654:com.google.android.talk/u0a61 (adj 15): empty #17
,W/Uploader( 1482): No account for auth token provided
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1482): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1482): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482):  no longer exists, so no auth token.
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1482): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1482): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1482): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1482): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1482): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/PowerManagerService(  824): Going to sleep due to screen timeout (uid 1000)...
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Adreno  (  824): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/Uploader( 1482): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1482): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PermissionCache(  276): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (360 us)
,W/Uploader( 1482): No account for auth token provided,
,W/Uploader( 1482): No account for auth token provided
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1482): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1482): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DisplayManagerService(  824): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  276): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  276): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  824): Display changed displayId=0
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,E/Uploader( 1482): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1482): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1482): No account for auth token provided
,I/qdhwcomposer(  276): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  276): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  824): Excessive delay in setPowerMode(): 283ms
I/DreamManagerService(  824): Entering dreamland.
I/PowerManagerService(  824): Dozing...
,I/DreamController(  824): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on,
,E/WifiStateMachine(  824): cancelDelayedScan -> 5
,E/native  (  824): do suspend false
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1482): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1482): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/WifiService(  824): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@65060d1}
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=85.23 rxSuccessRate=61.05 targetRoamBSSID=any RSSI=-47
,I/Keyboard.Facilitator( 1213): onFinishInput()
,E/WifiStateMachine(  824): cancelDelayedScan -> 7
,E/native  (  824): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,W/Uploader( 1482): No account for auth token provided
,I/ActivityManager(  824): Killing 3771:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/ActivityManager(  824): Killing 3800:com.google.android.gm/u0a78 (adj 15): empty #17
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1482): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1482): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1482): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1482): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,I/GoogleURLConnFactory( 1752): Using platform SSLCertificateSocketFactory
,W/GoogleHttpClient( 1752): Ignoring unsupported parameter: http.conn-manager.max-per-route,
,I/InputReader(  824): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  824): Start proc 4382:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher
,I/art     ( 1752): Explicit concurrent mark sweep GC freed 22460(1303KB) AllocSpace objects, 7(135KB) LOS objects, 37% free, 26MB/42MB, paused 1.135ms total 40.320ms
,E/DataBuffer( 1752): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3490650c)
,D/WifiService(  824): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@65060d1}
,E/DataBuffer( 1752): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@138cde55)
,V/GmsNetworkLocationProvi( 1752): DISABLE
,D/BackupManagerService(  824): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  824): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  824): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/art     (  824): Explicit concurrent mark sweep GC freed 34389(1729KB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 1.424ms total 49.663ms
,V/BackupManagerService(  824): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  824): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@37c23ad
,E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/BackupManagerService(  824): Scheduling immediate backup pass
,V/BackupManagerService(  824): Running a backup pass
,V/BackupManagerService(  824): clearing pending backups
,V/PerformBackupTask(  824): Beginning backup of 14 targets
,V/GmsNetworkLocationProvi( 1752): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,D/PerformBackupTask(  824): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  824): doBackup() invoked
I/PMBA    (  824): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,V/GmsNetworkLocationProvi( 1752): ENABLE
,V/GmsNetworkLocationProvi( 1752): SET-REQUEST
V/GmsNetworkLocationProvi( 1752): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,I/BackupRestoreController(  824): Getting widget state for user: 0
,W/GmsBackupTransport( 1752): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1752): starting performBackup for @pm@
,V/GmsBackupTransport( 1752): performBackup done for @pm@
,I/ActivityManager(  824): Start proc 4406:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,I/Launcher( 1305): Deferring update until onResume
,I/ActivityManager(  824): Start proc 4423:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,I/ActivityManager(  824): Killing 3643:com.google.android.youtube/u0a86 (adj 15): empty #17
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 4423): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1482): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1482): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1752): Error sending final backup to server: 
W/GmsBackupTransport( 1752): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1752): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1752): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1752): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1752): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1752): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1752): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1752): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1752): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1752): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1752): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1752): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1752): 	... 1 more
D/BackupManagerService(  824): Now staging backup of com.google.android.talk
,D/BackupManagerService(  824): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  824): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  824): Now staging backup of com.android.sharedstoragebackup,
,D/BackupManagerService(  824): Now staging backup of com.google.android.gm
,D/BackupManagerService(  824): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  824): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  824): Now staging backup of com.android.nfc
,D/BackupManagerService(  824): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  824): Now staging backup of com.android.vending
,D/BackupManagerService(  824): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  824): Now staging backup of com.google.android.inputmethod.latin
D/BackupManagerService(  824): Now staging backup of android
D/BackupManagerService(  824): Now staging backup of com.google.android.googlequicksearchbox
I/GmsBackupTransport( 1752): Next backup will happen in 43199922 millis.
,I/BackupManagerService(  824): Backup pass finished.
,I/Babel_SMS( 4423): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4423): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4423): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 4423): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4423): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4423): MmsConfig.loadFromResources
,E/Babel_SMS( 4423): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4423): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,W/Settings( 4423): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4423): startup - clean
,I/Babel   ( 4423): deleted: false for 0
,I/Babel_telephony( 4423): TeleModule.launchCompleted
,W/Telecom (  824): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 4423): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 4423): BAM#gBA: invalid account id: -1
W/Babel   ( 4423): BAM#gBA: invalid account id: -1
,I/Babel_telephony( 4423): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,W/Telecom (  824): TelecomServiceImpl: null is not visible for the calling user
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 114909(6MB) AllocSpace objects, 31(2MB) LOS objects, 35% free, 28MB/44MB, paused 1.040ms total 31.723ms
,D/PackageBroadcastService( 1787): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1787): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 4382): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1305): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@25a10422 new=com.google.android.velvet.VelvetApplication@25a10422
,I/Icing   ( 1787): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  824): Start proc 4460:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,W/VideoCapabilities( 4423): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 4460): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/VideoCapabilities( 4423): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4423): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4423): Unrecognized profile 2130706433 for video/avc
I/UpdateIcingCorporaServi( 4382): UpdateCorporaTask done [took 103 ms] updated apps [took 103 ms] 
,W/VideoCapabilities( 4423): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4423): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4423): onServiceConnected
W/Babel   ( 4423): Attempted to change video mute state without an active call.
,W/ResourcesManager( 4423): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4423): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4423): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4423): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  824): Killing 3319:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=5.00 rxSuccessRate=2.50 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,I/ActivityManager(  824): Killing 4086:com.google.android.apps.cloudprint/u0a41 (adj 15): empty #17,
,I/ActivityManager(  824): Killing 3928:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4296): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4296): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4296): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): ,
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/ActivityManager(  824): Start proc 4496:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,I/ActivityManager(  824): Start proc 4513:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4296): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4296): [1] 5.onFinished: Installation state replication failed.
,W/ResourcesManager( 4513): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4513): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4296): [1] 5.onFinished: Giving up after 6 failures.
,V/JNIHelp ( 4513): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GoogleAuthProtoRequest( 4496): [490] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ProviderInstaller( 4513): Installed default security provider GmsCore_OpenSSL
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4496): [490] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4496): [490] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4496): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4496): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4496): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4496): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  824): Killing 3906:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/dex2oat ( 4552): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads963494651.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads963494651.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4552): dex2oat took 26.076ms (threads: 4) arena alloc=129KB java alloc=12KB native alloc=1218KB free=6MB
,E/YouTube MDX( 4513): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/art     (  824): Explicit concurrent mark sweep GC freed 25345(1277KB) AllocSpace objects, 8(882KB) LOS objects, 32% free, 33MB/49MB, paused 1.748ms total 91.575ms
,W/InstanceID/Rpc( 4513): Found 10011
,V/GoogleAuthProtoRequest( 4496): [491] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4496): [491] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4496): [491] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4496): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4496): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4496): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4496): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  824): Killing 4062:com.google.android.apps.cloudprint:sync/u0a41 (adj 15): empty #17
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/ActivityManager(  824): Start proc 4614:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/GAV2    ( 4614): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4614): Created application version: 3.6.8 (30608)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4460): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at blb.a(PG:3937)
E/HttpOperation( 4460): 	at czp.a(PG:18188)
E/HttpOperation( 4460): 	at czp.a(PG:9087)
E/HttpOperation( 4460): 	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 12 more
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 14 more
,I/BooksSync( 4614): Starting books sync for 61035162, extras: ade
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4460): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at blb.a(PG:3937)
E/HttpOperation( 4460): 	at czp.a(PG:18188)
E/HttpOperation( 4460): 	at czp.a(PG:9081)
E/HttpOperation( 4460): 	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 12 more
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 14 more
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 25548(1590KB) AllocSpace objects, 19(2MB) LOS objects, 37% free, 26MB/42MB, paused 1.223ms total 26.593ms
,I/BooksConfig( 4614): GmsCore Version = 7.8.99 (2134222-430),
,E/HttpOperation( 4460): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at hec.a(PG:42)
E/HttpOperation( 4460): 	at hee.a(PG:102)
E/HttpOperation( 4460): 	at czr.a(PG:65)
E/HttpOperation( 4460): 	at kka.a(PG:108)
E/HttpOperation( 4460): 	at czp.a(PG:19176)
E/HttpOperation( 4460): 	at czp.a(PG:9081)
E/HttpOperation( 4460): 	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 15 more
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 17 more
E/ExperimentLoader( 4460): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4460): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4460): 	at jdm.a(PG:82)
E/ExperimentLoader( 4460): 	at jcs.o(PG:406)
E/ExperimentLoader( 4460): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4460): 	at jcs.i(PG:143)
E/ExperimentLoader( 4460): 	at hec.a(PG:42)
E/ExperimentLoader( 4460): 	at hee.a(PG:102)
E/ExperimentLoader( 4460): 	at czr.a(PG:65)
E/ExperimentLoader( 4460): 	at kka.a(PG:108)
E/ExperimentLoader( 4460): 	at czp.a(PG:19176)
E/ExperimentLoader( 4460): 	at czp.a(PG:9081)
E/ExperimentLoader( 4460): 	at czq.run(PG:1686)
E/ExperimentLoader( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4460): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4460): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4460): 	at jdm.a(PG:77)
E/ExperimentLoader( 4460): 	... 15 more
E/ExperimentLoader( 4460): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4460): 	at fal.a(PG:38)
E/ExperimentLoader( 4460): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4460): 	... 17 more
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 150131, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  824): Start proc 4652:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 11.173ms
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 197us total 11.291ms
,E/BooksAccountManager( 4614): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 4614): Soft error
E/BooksSync( 4614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4614): Sync error
E/BooksSync( 4614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4614): Finished books sync
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 253us total 13.361ms
,I/ActivityManager(  824): Killing 3486:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 182480, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 4652): Connecting to GoogleApiClient
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1787): Handling authorization failure
E/ClientConnectionOperation( 1787): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1787): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1787): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1787): 	... 7 more
,V/KeepSync( 4652): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  824): Explicit concurrent mark sweep GC freed 27434(1185KB) AllocSpace objects, 4(158KB) LOS objects, 32% free, 33MB/49MB, paused 1.940ms total 76.706ms
,E/KeepSync( 4652): IOException
E/KeepSync( 4652): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4652): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4652): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4652): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4652): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4652): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4652): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4652): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4652): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4652): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4652): 	... 10 more
,W/KeepSync( 4652): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 183859, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  824): Killing 4149:com.google.android.apps.docs.editors.docs/u0a47 (adj 15): empty #17
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/GAV2    ( 4614): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,D/Finsky  ( 4296): [474] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 4296): [474] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/Keyboard.Facilitator.LanguageModelFlusher( 1213): run()
I/Keyboard.Facilitator( 1213): flushDynamicLanguageModels()
,I/ConfigService( 1482): onCreate
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/ConfigService( 1482): onDestroy
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4460): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at blb.a(PG:3937)
E/HttpOperation( 4460): 	at czp.a(PG:18188)
E/HttpOperation( 4460): 	at czp.a(PG:9081)
E/HttpOperation( 4460): ,	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 12 more,
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 14 more
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 22147(1282KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.960ms total 48.480ms
,E/HttpOperation( 4460): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at hec.a(PG:42)
E/HttpOperation( 4460): 	at hee.a(PG:102)
E/HttpOperation( 4460): 	at czr.a(PG:65)
E/HttpOperation( 4460): 	at kka.a(PG:108)
E/HttpOperation( 4460): 	at czp.a(PG:19176)
E/HttpOperation( 4460): 	at czp.a(PG:9081)
E/HttpOperation( 4460): 	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 15 more
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 17 more
,E/ExperimentLoader( 4460): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4460): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4460): 	at jdm.a(PG:82)
E/ExperimentLoader( 4460): 	at jcs.o(PG:406)
E/ExperimentLoader( 4460): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4460): 	at jcs.i(PG:143)
E/ExperimentLoader( 4460): 	at hec.a(PG:42)
E/ExperimentLoader( 4460): 	at hee.a(PG:102)
E/ExperimentLoader( 4460): 	at czr.a(PG:65)
E/ExperimentLoader( 4460): 	at kka.a(PG:108)
E/ExperimentLoader( 4460): 	at czp.a(PG:19176)
E/ExperimentLoader( 4460): 	at czp.a(PG:9081)
E/ExperimentLoader( 4460): 	at czq.run(PG:1686)
E/ExperimentLoader( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4460): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4460): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4460): 	at jdm.a(PG:77)
E/ExperimentLoader( 4460): 	... 15 more
E/ExperimentLoader( 4460): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4460): 	at fal.a(PG:38)
E/ExperimentLoader( 4460): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4460): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 241268, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,V/GoogleAuthProtoRequest( 4496): [493] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4496): [493] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4496): [493] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4496): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4496): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4496): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4496): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/BooksSync( 4614): Starting books sync for 61035162, extras: ade
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/BooksConfig( 4614): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 4652): Connecting to GoogleApiClient
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1787): Handling authorization failure
E/ClientConnectionOperation( 1787): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1787): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1787): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1787): 	... 7 more
,V/KeepSync( 4652): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4614): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4614): Soft error
E/BooksSync( 4614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4614): Sync error
E/BooksSync( 4614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4614): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 272505, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4652): IOException
E/KeepSync( 4652): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4652): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4652): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4652): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4652): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4652): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4652): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4652): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4652): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4652): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4652): 	... 10 more
W/KeepSync( 4652): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 276491, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3245): 
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector connect called
I/jxcore-log( 3245): 
I/jxcore-log( 3245): Coordinator is now connected to the server!
I/jxcore-log( 3245): 
,I/chromium( 3245): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63),
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 4460): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at blb.a(PG:3937)
E/HttpOperation( 4460): 	at czp.a(PG:18188)
E/HttpOperation( 4460): 	at czp.a(PG:9081)
E/HttpOperation( 4460): 	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 12 more
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 14 more
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4460): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at hec.a(PG:42)
E/HttpOperation( 4460): 	at hee.a(PG:102)
E/HttpOperation( 4460): 	at czr.a(PG:65)
E/HttpOperation( 4460): 	at kka.a(PG:108)
E/HttpOperation( 4460): 	at czp.a(PG:19176)
E/HttpOperation( 4460): 	at czp.a(PG:9081)
E/HttpOperation( 4460): 	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 15 more
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 17 more
,E/ExperimentLoader( 4460): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4460): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4460): 	at jdm.a(PG:82)
E/ExperimentLoader( 4460): 	at jcs.o(PG:406)
E/ExperimentLoader( 4460): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4460): 	at jcs.i(PG:143)
E/ExperimentLoader( 4460): 	at hec.a(PG:42)
E/ExperimentLoader( 4460): 	at hee.a(PG:102)
E/ExperimentLoader( 4460): ,	at czr.a(PG:65)
E/ExperimentLoader( 4460): 	at kka.a(PG:108)
E/ExperimentLoader( 4460): 	at czp.a(PG:19176)
E/ExperimentLoader( 4460): 	at czp.a(PG:9081)
E/ExperimentLoader( 4460): 	at czq.run(PG:1686)
E/ExperimentLoader( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/ExperimentLoader( 4460): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4460): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4460): 	at jdm.a(PG:77)
E/ExperimentLoader( 4460): 	... 15 more
E/ExperimentLoader( 4460): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4460): 	at fal.a(PG:38)
E/ExperimentLoader( 4460): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4460): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 332294, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 4496): [494] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  824): Explicit concurrent mark sweep GC freed 37082(1612KB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 2.140ms total 76.458ms
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4496): [494] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4496): [494] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4496): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4496): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4496): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4496): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 4614): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4614): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4614): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4614): Soft error
E/BooksSync( 4614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4614): Sync error
E/BooksSync( 4614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4614): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 424289, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/jxcore-log( 3245): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector command called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"B4:CE:F6:AB:A4
,I/jxcore-log( 3245): Start now : testSendData.js
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): check server
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): serverPort is 50286
I/jxcore-log( 3245): 
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): stop: Stopping Bluetooth and peer discovery...,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): initialize: F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1326
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3245): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): setState: INITIALIZED
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1326","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): start: OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): setState: RUNNING
I/jxcore-log( 3245): StartBroadcasting started ok
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): do fake peer & start,
I/jxcore-log( 3245): 
I/jxcore-log( 3245): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:53:32.200Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
I/jxcore-log( 3245): 2015-11-30T09:53:32.201Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:53:32.201Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: null 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/jxcore-log( 3245): 2015-11-30T09:53:32.210Z SendDataTCPServer.js: TCP/IP server is bound to port: 50286
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/chromium( 3245): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onWifiStateChanged: State changed to 2
,W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
,W/bt-btif ( 3300): info:x10
D/        ( 3300): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 3300): aclStateChangeCallback: Device is NULL
,D/btif_config( 3300): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1,
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1,
E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 3300): Failed to remove device: E0:DB:10:1F:C9:5E
,I/ActivityManager(  824): Start proc 4758:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
I/BluetoothBondStateMachine( 3300): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 344)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 344
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 344)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@256db61f:true
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, samsung-SM-N9005_PT4028
,I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket,
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
I/jxcore-log( 3245): 2015-11-30T09:53:33.787Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
I/ActivityManager(  824): Killing 4246:com.google.android.apps.docs.editors.sheets/u0a48 (adj 15): empty #17
,I/jxcore-log( 3245): 2015-11-30T09:53:34.739Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.745Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.749Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.782Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.788Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:53:34.818Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:53:34.829Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.863Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
,I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.871Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.875Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.908Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.911Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.918Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.922Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.926Z SendDataTCPServer.js: TCP/IP server has received 33932 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:34.998Z SendDataTCPServer.js: TCP/IP server has received 35912 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.029Z SendDataTCPServer.js: TCP/IP server has received 37892 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.032Z SendDataTCPServer.js: TCP/IP server has received 39872 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.037Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.067Z SendDataTCPServer.js: TCP/IP server has received 43832 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.099Z SendDataTCPServer.js: TCP/IP server has received 45812 bytes of data
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3245): 2015-11-30T09:53:35.301Z SendDataTCPServer.js: TCP/IP server has received 47792 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.332Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.341Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.349Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.378Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.382Z SendDataTCPServer.js: TCP/IP server has received 59672 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.386Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.418Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.458Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.469Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.474Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
,I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.535Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.540Z SendDataTCPServer.js: TCP/IP server has received 77492 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.546Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.550Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.556Z SendDataTCPServer.js: TCP/IP server has received 83432 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.588Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.592Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.596Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.602Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.609Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.638Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.655Z SendDataTCPServer.js: TCP/IP server has received 99272 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:35.659Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3245): 
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): info:x10,
,D/        ( 3300): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
E/BluetoothRemoteDevices( 3300): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,D/btif_config( 3300): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3300): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 348)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 348)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 348),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 348)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 348
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 348)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 348)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, LGE-LG-D802_PT3202
,I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/jxcore-log( 3245): 2015-11-30T09:53:40.820Z SendDataTCPServer.js: TCP/IP server connected,
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,V/KeepSync( 4652): Connecting to GoogleApiClient
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1787): Handling authorization failure,
E/ClientConnectionOperation( 1787): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1787): 	,at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1787): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1787): 	at java.lang.Thread.run(Thread.java:818),
E/ClientConnectionOperation( 1787): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1787): 	... 7 more
V/KeepSync( 4652): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4652): IOException
E/KeepSync( 4652): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4652): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4652): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4652): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4652): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4652): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4652): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4652): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4652): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4652): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4652): 	... 10 more
W/KeepSync( 4652): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 430952, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3245): 2015-11-30T09:53:42.045Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.105Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.137Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.196Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.230Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.258Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.266Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.298Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.303Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
,I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.339Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.355Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.364Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.398Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.404Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.438Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.442Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.478Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.485Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.518Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.523Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.558Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.562Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.599Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.604Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.608Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:42.648Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3245): 
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1482): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1482): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4296): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4296): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4296): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 4296): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4296): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 4296): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4296): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 4296): Ignoring header User-Agent because its value was null.
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a244 rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): info:x10
D/        ( 3300): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3300): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,D/btif_config( 3300): btif_get_device_type: Device [08:ec:a9:50:76:27] type 1
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
D/BluetoothAdapterProperties( 3300): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 352)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 352)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 352)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 83 bytes successfully (thread ID: 352)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7891 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7891 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 352)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7891 08:EC:A9:50:76:27]
,I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, samsung-SM-A300FU_PT7891
,I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket,
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 47202,
I/BtConnectorHelper( 3245): Request socket is using : 47202
I/BtToRequestSocket( 3245): Now accepting connections
E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a244 rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :47202
,I/jxcore-log( 3245): 2015-11-30T09:53:54.150Z SendDataConnector.js: CLIENT connected to 47202, error: null
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:54.151Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 47202
,I/BtToRequestSocket( 3245): Set local streams
I/BtToRequestSocket( 3245): rin ended ---------------------------;
,I/jxcore-log( 3245): 2015-11-30T09:53:54.173Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16792
,I/jxcore-log( 3245): 2015-11-30T09:53:54.801Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18048
,I/jxcore-log( 3245): 2015-11-30T09:53:54.846Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14088
,I/jxcore-log( 3245): 2015-11-30T09:53:54.900Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:54.993Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4188
,I/jxcore-log( 3245): 2015-11-30T09:53:55.094Z SendDataConnector.js: CLIENT is data received : 50000,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:55.173Z SendDataConnector.js: CLIENT is data received : 60000,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:55.295Z SendDataConnector.js: CLIENT is data received : 70000,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:55.382Z SendDataConnector.js: CLIENT is data received : 80000,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:55.431Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:55.439Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:55.440Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:55.443Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:53:55.444Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/BtConnectorHelper( 3245): Disconnect outgoing peer: 08:EC:A9:50:76:27,
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
,I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket,
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
,I/BtToRequestSocket( 3245): Close server socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3245): 2015-11-30T09:53:55.450Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3245): 
I/jxcore-log( 3245): ---- round done--------
I/jxcore-log( 3245): 
I/jxcore-log( 3245): do fake peer & start
I/jxcore-log( 3245): 
I/jxcore-log( 3245): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:53:55.452Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:53:55.452Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:53:55.452Z SendDataConnector.js: do connect now
,I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: null 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/chromium( 3245): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,W/bt-btif ( 3300): info:x10,
D/        ( 3300): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3300): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,D/btif_config( 3300): btif_get_device_type: Device [58:3f:54:73:64:c0] type 1
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1,
,E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State,
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
D/BluetoothAdapterProperties( 3300): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 357)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 357)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 357)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 357)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 357)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, LGE-LG-D855_PT8606
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 50719
,I/BtConnectorHelper( 3245): Request socket is using : 50719
I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :50719
,I/jxcore-log( 3245): 2015-11-30T09:53:57.836Z SendDataConnector.js: CLIENT connected to 50719, error: null
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:57.837Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 50719
,I/BtToRequestSocket( 3245): Set local streams
,I/jxcore-log( 3245): 2015-11-30T09:53:57.849Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3245): 
I/BtToRequestSocket( 3245): rin ended ---------------------------;
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 3245): 2015-11-30T09:53:58.333Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:58.418Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14088
,I/jxcore-log( 3245): 2015-11-30T09:53:58.513Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:58.563Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4188
,I/jxcore-log( 3245): 2015-11-30T09:53:58.608Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:58.714Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:58.833Z SendDataConnector.js: CLIENT is data received : 70000,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:58.891Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:53:58.988Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3300): onReceive
,D/BluetoothManagerService(  824): Message: 20
,D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e27a582:true
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): dm_pm_timer expires,
W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 51748(2MB) AllocSpace objects, 6(661KB) LOS objects, 36% free, 27MB/43MB, paused 2.301ms total 70.855ms
,E/HttpOperation( 4460): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at blb.a(PG:3937)
E/HttpOperation( 4460): 	at czp.a(PG:18188)
E/HttpOperation( 4460): 	at czp.a(PG:9081)
E/HttpOperation( 4460): 	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 12 more
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 14 more
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4460): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at hec.a(PG:42)
E/HttpOperation( 4460): 	at hee.a(PG:102)
E/HttpOperation( 4460): 	at czr.a(PG:65)
E/HttpOperation( 4460): 	at kka.a(PG:108)
,E/HttpOperation( 4460): 	at czp.a(PG:19176)
E/HttpOperation( 4460): 	at czp.a(PG:9081)
E/HttpOperation( 4460): 	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
,E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 15 more
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 17 more
E/ExperimentLoader( 4460): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4460): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4460): 	at jdm.a(PG:82)
E/ExperimentLoader( 4460): 	at jcs.o(PG:406)
E/ExperimentLoader( 4460): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4460): 	at jcs.i(PG:143)
E/ExperimentLoader( 4460): 	at hec.a(PG:42)
E/ExperimentLoader( 4460): 	at hee.a(PG:102)
E/ExperimentLoader( 4460): 	at czr.a(PG:65)
E/ExperimentLoader( 4460): ,	at kka.a(PG:108)
E/ExperimentLoader( 4460): 	at czp.a(PG:19176)
E/ExperimentLoader( 4460): 	at czp.a(PG:9081)
E/ExperimentLoader( 4460): 	at czq.run(PG:1686)
E/ExperimentLoader( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4460): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4460): ,	at jdj.a(PG:1125)
E/ExperimentLoader( 4460): 	at jdm.a(PG:77)
E/ExperimentLoader( 4460): 	... 15 more
E/ExperimentLoader( 4460): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4460): 	at fal.a(PG:38)
E/ExperimentLoader( 4460): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4460): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 484031, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
W/bt-btif ( 3300): invalid rfc slot id: 4
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4028
I/BtToSocketBase( 3245): Stop ReceivingThread
,I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close localHostSocket
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close bt in
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4028
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt socket
,I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/jxcore-log( 3245): 2015-11-30T09:54:26.118Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0,
W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive,
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3300): invalid rfc slot id: 6
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
,I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
,I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
,I/BtToSocketBase( 3245): Close bt socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3245): 2015-11-30T09:54:33.075Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x45
,W/bt-btif ( 3300): info:x10
D/        ( 3300): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,W/bt-btif ( 3300): dm_pm_timer expires
W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 361)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 361)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 361),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 361)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 361
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 361)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 361)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, samsung-SM-N9005_PT4028
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/jxcore-log( 3245): 2015-11-30T09:54:37.376Z SendDataTCPServer.js: TCP/IP server connected
,I/jxcore-log( 3245): 
I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T09:54:37.825Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:37.830Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:37.836Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:37.847Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:37.852Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:37.856Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): info:x10
,D/        ( 3300): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 4382): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,D/btif_config( 3300): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1,
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3300): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 365)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 365)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 365),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 365)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 365
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 365)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 365)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, LGE-LG-D802_PT3202,
,I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BTConnectedThread
,I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286,
I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T09:54:44.718Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3245): 2015-11-30T09:54:45.170Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:45.215Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:45.231Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:45.239Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:45.244Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 1
W/bt-btif ( 3300): proc dm_pm_timer expires
,I/jxcore-log( 3245): 2015-11-30T09:54:48.990Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:48.991Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:48.993Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:54:48.994Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:54:48.995Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
,I/BtToSocketBase( 3245): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3245): Disconnect outgoing peer: LGE-LG-D855_PT8606
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
,I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
,I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
,I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1
,I/jxcore-log( 3245): 2015-11-30T09:54:53.997Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:53.997Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:59.003Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:54:59.004Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:54:59.004Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:54:59.005Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: G3-1 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3300): info:x10
D/        ( 3300): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 370)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 370)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 370),
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=1,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 370)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 370)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, LGE-LG-D855_PT8606
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 33246
I/BtConnectorHelper( 3245): Request socket is using : 33246
I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :33246
,I/jxcore-log( 3245): 2015-11-30T09:55:03.106Z SendDataConnector.js: CLIENT connected to 33246, error: null
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:03.107Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 33246,
I/BtToRequestSocket( 3245): Set local streams
,I/BtToRequestSocket( 3245): rin ended ---------------------------;
I/jxcore-log( 3245): 2015-11-30T09:55:03.118Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3245): 
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
W/bt-btif ( 3300): invalid rfc slot id: 7
,I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4028
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
,I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
,I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3245): 2015-11-30T09:55:27.958Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x4b
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
W/bt-btif ( 3300): invalid rfc slot id: 9
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
,I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3245): 2015-11-30T09:55:35.430Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0,
W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x4e
,W/bt-btif ( 3300): info:x10,
D/        ( 3300): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive,
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 374)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 374)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 374),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 374)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 374
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 374)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 374)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, samsung-SM-N9005_PT4028
,I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T09:55:40.002Z SendDataTCPServer.js: TCP/IP server connected
,I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:40.461Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:40.468Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:40.474Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:40.517Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:40.523Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): ,
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): info:x10
D/        ( 3300): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Thali Test's G2
,D/btif_config( 3300): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 3300): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 378)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 378)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 378
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 378)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B],
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, LGE-LG-D802_PT3202
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T09:55:47.469Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:47.911Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:47.915Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:47.919Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:47.923Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:47.949Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3245): 2015-11-30T09:55:53.176Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:53.177Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:55:53.179Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:55:53.179Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:55:53.180Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
I/BtToSocketBase( 3245): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3245): Disconnect outgoing peer: LGE-LG-D855_PT8606
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
,I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
,I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3245): 2015-11-30T09:55:58.181Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:55:58.182Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1
,I/jxcore-log( 3245): 2015-11-30T09:56:03.185Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:03.186Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:56:03.186Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:03.187Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: G3-1 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3300): info:x10
D/        ( 3300): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=0,
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14),
W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 383)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 383)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 383)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=1,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 383)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 383)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
,I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, LGE-LG-D855_PT8606
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 39867
,I/BtConnectorHelper( 3245): Request socket is using : 39867
I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :39867
,I/jxcore-log( 3245): 2015-11-30T09:56:05.839Z SendDataConnector.js: CLIENT connected to 39867, error: null
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:05.841Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 39867
,I/BtToRequestSocket( 3245): Set local streams
I/BtToRequestSocket( 3245): rin ended ---------------------------;
,I/jxcore-log( 3245): 2015-11-30T09:56:05.857Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3245): 
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): dm_pm_timer expires
W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
W/bt-btif ( 3300): invalid rfc slot id: 10
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4028
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3245): 2015-11-30T09:56:30.801Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,I/art     (  824): Explicit concurrent mark sweep GC freed 34664(1577KB) AllocSpace objects, 6(378KB) LOS objects, 32% free, 33MB/49MB, paused 2.368ms total 87.078ms
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive,
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
,I/BtToSocketBase( 3245): Close local in
W/bt-btif ( 3300): invalid rfc slot id: 12
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
,I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3245): 2015-11-30T09:56:38.267Z SendDataTCPServer.js: TCP/IP server is ended
,I/jxcore-log( 3245): 
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x47
,W/bt-btif ( 3300): info:x10
D/        ( 3300): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 387)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 387)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 387)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 387)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 387
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 387)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 387)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, samsung-SM-N9005_PT4028
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T09:56:42.003Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:42.421Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
,I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:42.424Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:42.431Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:42.438Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:42.441Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): ,
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Thali Test's G2
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): info:x10,
D/        ( 3300): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Thali Test's G2,
,D/btif_config( 3300): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1,
E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 3300): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 391)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 391)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 391)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 391),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 391
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 391)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
,I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, LGE-LG-D802_PT3202
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 391)
,I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T09:56:49.454Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:49.899Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:49.931Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:49.962Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:49.991Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:50.002Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3245): 2015-11-30T09:56:55.907Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:56:55.908Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:56:55.910Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:56:55.910Z SendDataConnector.js: tryAgain afer: 5000 ms.
,I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:56:55.912Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
I/BtToSocketBase( 3245): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3245): Disconnect outgoing peer: LGE-LG-D855_PT8606
,I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
,I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,V/GoogleAuthProtoRequest( 4496): [495] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4496): [495] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
I/jxcore-log( 3245): 2015-11-30T09:57:00.911Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:57:00.911Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
,W/ExperimentUpdateService( 4496): [495] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4496): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4496): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4496): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4496): 	at com.a.a.k.run(SourceFile:110)
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1
,I/jxcore-log( 3245): 2015-11-30T09:57:05.916Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:05.917Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:57:05.918Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:05.918Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: G3-1 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
,W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3300): info:x10,
D/        ( 3300): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1,
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 396)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 396)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 396)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 396)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 396)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, LGE-LG-D855_PT8606
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 46460
,I/BtConnectorHelper( 3245): Request socket is using : 46460
I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :46460
,I/jxcore-log( 3245): 2015-11-30T09:57:08.014Z SendDataConnector.js: CLIENT connected to 46460, error: null
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:08.017Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 46460
,I/BtToRequestSocket( 3245): Set local streams
I/BtToRequestSocket( 3245): rin ended ---------------------------;
I/jxcore-log( 3245): 2015-11-30T09:57:08.031Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3245): 
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): dm_pm_timer expires
W/bt-btif ( 3300): dm_pm_timer expires 0
,W/bt-btif ( 3300): proc dm_pm_timer expires
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/BooksSync( 4614): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4614): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4614): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4614): Soft error
E/BooksSync( 4614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4614): Sync error
E/BooksSync( 4614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4614): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 673028, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a244 rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): info:x10
,D/        ( 3300): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3300): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a244 rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a5d4 rs_disc_pending=0,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,D/btif_config( 3300): btif_get_device_type: Device [34:fc:ef:11:b1:66] type 1,
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 3300): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 400)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 400)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a5d4 rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a5d4 rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 400
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 400)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 400)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, LGE-Nexus 5_PT9919
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T09:57:28.311Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.058Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.061Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.067Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.072Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.077Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.140Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.147Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.178Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.184Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.218Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.224Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data,
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:57:29.226Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.259Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.266Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.270Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.309Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.315Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.322Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.358Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.365Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.398Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.404Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:29.438Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3245): 
,W/bt-btif ( 3300): dm_pm_timer expires
W/bt-btif ( 3300): dm_pm_timer expires 1
W/bt-btif ( 3300): proc dm_pm_timer expires
,W/bt-btif ( 3300): invalid rfc slot id: 13
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4028
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
,I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close bt in
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4028
I/BtToSocketBase( 3245): Close bt in
,I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
,I/jxcore-log( 3245): 2015-11-30T09:57:32.628Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a5d4 rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x4d
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive,
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
,W/bt-btif ( 3300): invalid rfc slot id: 15
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close bt in
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close bt out
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
I/BtToSocketBase( 3245): Close bt socket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
,I/BtToSocketBase( 3245): Close bt socket
I/jxcore-log( 3245): 2015-11-30T09:57:40.105Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0,
W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x41
,W/bt-btif ( 3300): info:x10
D/        ( 3300): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Thali Test's G2,
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 404)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 404)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 404)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 404
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 404)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 404)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, samsung-SM-N9005_PT4028
,I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T09:57:44.706Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:45.178Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:45.181Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:57:45.185Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:45.190Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:45.197Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 408)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 408)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 408)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 408)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 408
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 408)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 408)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
,I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, LGE-LG-D855_PT8606
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286,
,W/bt-btif ( 3300): info:x10,
D/        ( 3300): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106,
I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T09:57:51.289Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Thali Test's G2
,D/btif_config( 3300): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 3300): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 412)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 412)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 412),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 412)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 412
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 412)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 412)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT3202 34:FC:EF:9D:93:0B]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, LGE-LG-D802_PT3202
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T09:57:52.238Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.247Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.251Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.263Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.270Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.276Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
,I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.284Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
,I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.287Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.328Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.332Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.369Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.405Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.409Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.449Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.454Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.461Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.498Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.506Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.510Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.548Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.569Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.577Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data,
,I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.586Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
,I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.619Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.625Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.632Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.638Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.643Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.651Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.655Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.662Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.665Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.669Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.672Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.706Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.717Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:52.723Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,I/jxcore-log( 3245): 2015-11-30T09:57:58.111Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:57:58.112Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:57:58.114Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:57:58.114Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:57:58.115Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
I/BtToSocketBase( 3245): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3245): Disconnect outgoing peer: LGE-LG-D855_PT8606
,I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
,I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3245): Close bt out
,I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/jxcore-log( 3245): 2015-11-30T09:58:03.116Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:58:03.117Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
,W/bt-btif ( 3300): dm_pm_timer expires
W/bt-btif ( 3300): dm_pm_timer expires 0
,W/bt-btif ( 3300): proc dm_pm_timer expires
,I/jxcore-log( 3245): 2015-11-30T09:58:08.121Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:58:08.122Z SendDataConnector.js: Connect (retry count 4) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:08.123Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:08.123Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: G3-1 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 417)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 417)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 417)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 417)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 417)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, LGE-LG-D855_PT8606
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 37551
I/BtConnectorHelper( 3245): Request socket is using : 37551
I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :37551
,I/jxcore-log( 3245): 2015-11-30T09:58:08.987Z SendDataConnector.js: CLIENT connected to 37551, error: null
I/jxcore-log( 3245): ,
I/jxcore-log( 3245): 2015-11-30T09:58:08.988Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 37551
I/BtToRequestSocket( 3245): Set local streams
I/BtToRequestSocket( 3245): rin ended ---------------------------;
,I/jxcore-log( 3245): 2015-11-30T09:58:08.998Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3245): 
,W/bt-btif ( 3300): invalid rfc slot id: 16
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT9919
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT9919
,I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
,I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/jxcore-log( 3245): 2015-11-30T09:58:19.589Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a5d4 rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,V/KeepSync( 4652): Connecting to GoogleApiClient
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4460): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at blb.a(PG:3937)
E/HttpOperation( 4460): 	at czp.a(PG:18188)
E/HttpOperation( 4460): 	at czp.a(PG:9081)
E/HttpOperation( 4460): 	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 12 more
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 14 more
,E/ClientConnectionOperation( 1787): Handling authorization failure
E/ClientConnectionOperation( 1787): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1787): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1787): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1787): 	... 7 more
,V/KeepSync( 4652): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4460): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at hec.a(PG:42)
E/HttpOperation( 4460): 	at hee.a(PG:102)
E/HttpOperation( 4460): 	at czr.a(PG:65)
E/HttpOperation( 4460): 	at kka.a(PG:108)
E/HttpOperation( 4460): 	at czp.a(PG:19176)
E/HttpOperation( 4460): 	at czp.a(PG:9081)
E/HttpOperation( 4460): 	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 15 more
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 17 more
E/ExperimentLoader( 4460): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4460): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4460): 	at jdm.a(PG:82)
E/ExperimentLoader( 4460): 	at jcs.o(PG:406)
E/ExperimentLoader( 4460): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4460): 	at jcs.i(PG:143)
E/ExperimentLoader( 4460): 	at hec.a(PG:42)
E/ExperimentLoader( 4460): 	at hee.a(PG:102)
E/ExperimentLoader( 4460): 	at czr.a(PG:65)
E/ExperimentLoader( 4460): 	at kka.a(PG:108)
E/ExperimentLoader( 4460): 	at czp.a(PG:19176)
E/ExperimentLoader( 4460): 	at czp.a(PG:9081)
E/ExperimentLoader( 4460): 	at czq.run(PG:1686)
E/ExperimentLoader( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4460): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4460): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4460): 	at jdm.a(PG:77)
E/ExperimentLoader( 4460): 	... 15 more
E/ExperimentLoader( 4460): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4460): 	at fal.a(PG:38)
E/ExperimentLoader( 4460): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4460): 	... 17 more
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 732393, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 4652): IOException
E/KeepSync( 4652): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4652): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4652): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4652): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4652): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4652): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4652): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4652): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4652): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4652): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4652): 	... 10 more
W/KeepSync( 4652): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 716300, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): invalid rfc slot id: 18
I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4028
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
,I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3245): 2015-11-30T09:58:35.184Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1,
,W/bt-btif ( 3300): invalid rfc slot id: 20
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
I/BtToSocketBase( 3245): Stop ReceivingThread
,I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT3202
I/BtToSocketBase( 3245): Close localHostSocket
,I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out,
I/BtToSocketBase( 3245): Close bt socket
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
,I/BtToSocketBase( 3245): Close bt socket
I/jxcore-log( 3245): 2015-11-30T09:58:42.958Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,W/bt-btif ( 3300): invalid rfc slot id: 19
I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT8606
,I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream,
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
,I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3245): 2015-11-30T09:58:42.988Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a244 rs_disc_pending=0,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x49,
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 421)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 421)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 421),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 421)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 421
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 421)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 421)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, LGE-LG-D855_PT8606
,I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T09:58:54.558Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:55.120Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:55.126Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:55.318Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:55.433Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:55.439Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:55.445Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:59.064Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:59.065Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:58:59.066Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:59.073Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:58:59.074Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:59.077Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/BtConnectorHelper( 3245): Disconnect outgoing peer: 58:3F:54:73:64:C0
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in,
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
I/jxcore-log( 3245): 2015-11-30T09:58:59.088Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): ---- round done--------
I/jxcore-log( 3245): 
I/jxcore-log( 3245): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 1
I/jxcore-log( 3245): 
I/jxcore-log( 3245): do fake peer & start
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:58:59.089Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:58:59.089Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:58:59.089Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: null B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to null in address B0:C5:59:3F:75:69
,I/jxcore-log( 3245): 2015-11-30T09:58:59.095Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
I/chromium( 3245): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,W/bt-btif ( 3300): info:x10
,D/        ( 3300): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 3300): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a79c rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,D/btif_config( 3300): btif_get_device_type: Device [b0:c5:59:3f:75:69] type 1
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 3300): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a79c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 426)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 426)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 426)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a79c rs_disc_pending=1,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 426),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT4698 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT4698 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 426)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT4698 B0:C5:59:3F:75:69]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, samsung-SM-G900F_PT4698
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 37599
I/BtConnectorHelper( 3245): Request socket is using : 37599
,I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :37599
,I/jxcore-log( 3245): 2015-11-30T09:59:02.363Z SendDataConnector.js: CLIENT connected to 37599, error: null
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:59:02.364Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 37599
,I/BtToRequestSocket( 3245): Set local streams
I/jxcore-log( 3245): 2015-11-30T09:59:02.375Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): rin ended ---------------------------;
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:266
,I/jxcore-log( 3245): 2015-11-30T09:59:02.840Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:02.888Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:02.912Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:02.960Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:03.033Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:03.083Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:03.135Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:03.156Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:03.199Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:03.208Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:03.209Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:03.215Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:03.216Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/BtConnectorHelper( 3245): Disconnect outgoing peer: B0:C5:59:3F:75:69
,I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
,I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
,I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3245): 2015-11-30T09:59:03.225Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): ---- round done--------
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): do fake peer & start
I/jxcore-log( 3245): 
I/jxcore-log( 3245): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:59:03.232Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68,
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:59:03.233Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:59:03.233Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: null 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
,W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3245): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a79c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-sdp  ( 3300): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3300): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3300): invalid rfc slot id: 25
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 80:01:84:8A:B3:68 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): shutdown
,I/jxcore-log( 3245): 2015-11-30T09:59:08.387Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:08.388Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:59:08.389Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:13.390Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:13.391Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/jxcore-log( 3245): 2015-11-30T09:59:18.394Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68,
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:59:18.395Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:59:18.395Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:18.396Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: null 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3300): info:x10
,D/        ( 3300): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3300): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,D/btif_config( 3300): btif_get_device_type: Device [80:01:84:8a:b3:68] type 1,
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1,
E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3300): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3300): Failed to remove device: 80:01:84:8A:B3:68,
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 432)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 432)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 432)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=1,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 84 bytes successfully (thread ID: 432)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 432)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 53646
I/BtConnectorHelper( 3245): Request socket is using : 53646
I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :53646
,I/jxcore-log( 3245): 2015-11-30T09:59:21.834Z SendDataConnector.js: CLIENT connected to 53646, error: null
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T09:59:21.835Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 53646
,I/BtToRequestSocket( 3245): Set local streams
,I/BtToRequestSocket( 3245): rin ended ---------------------------;
I/jxcore-log( 3245): 2015-11-30T09:59:21.845Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:266
,I/jxcore-log( 3245): 2015-11-30T09:59:22.576Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:22.618Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:22.708Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:22.716Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:22.763Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:22.768Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:22.839Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:22.861Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T09:59:22.899Z SendDataConnector.js: CLIENT is data received : 90000
,I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=0,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,W/bt-btif ( 3300): info:x10
,D/        ( 3300): remote version info [34:fc:ef:11:b1:66]: 6, f, 4106
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=1,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): dm_pm_timer expires
W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,W/bt-btif ( 3300): invalid rfc slot id: 21
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT8606
I/BtToSocketBase( 3245): Stop ReceivingThread
,I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
,I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3245): 2015-11-30T09:59:45.494Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1
,I/ActivityManager(  824): Start proc 4987:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4987): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4987):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4987):   adb logcat -s GAv4
,W/GAv4    ( 4987): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4987): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4987): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  824): Killing 3839:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
,I/jxcore-log( 3245): 2015-11-30T10:00:12.899Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:00:12.900Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:00:12.901Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:00:12.902Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:00:12.903Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
I/BtToSocketBase( 3245): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3245): Disconnect outgoing peer: HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3245): Stop ReceivingThread
,I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
,I/BtToRequestSocket( 3245): Close server socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3245): 2015-11-30T10:00:17.904Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:00:17.905Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
,W/bt-btm  ( 3300): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a5d4 rs_disc_pending=2
E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3300): info:x10
D/        ( 3300): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1,
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 436)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 436)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 436)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 436)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 436
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 436)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 436)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, LGE-LG-D855_PT8606
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T10:00:20.784Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:00:21.220Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:00:21.225Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:00:21.231Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:00:21.241Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:00:22.909Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:00:22.910Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:00:22.911Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:00:22.912Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
,W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,W/bt-btif ( 3300): info:x10
D/        ( 3300): remote version info [80:01:84:8a:b3:68]: 6, f, 6109
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 441)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 441)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 441)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 84 bytes successfully (thread ID: 441)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 441)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3245): mHTTPPort  set to : 41383
I/BtConnectorHelper( 3245): Request socket is using : 41383
,I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :41383,
I/jxcore-log( 3245): 2015-11-30T10:00:25.972Z SendDataConnector.js: CLIENT connected to 41383, error: null
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:00:25.973Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 41383
,I/BtToRequestSocket( 3245): Set local streams
,I/jxcore-log( 3245): 2015-11-30T10:00:25.983Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): rin ended ---------------------------;
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 1
W/bt-btif ( 3300): proc dm_pm_timer expires
,I/art     (  824): Explicit concurrent mark sweep GC freed 35247(1626KB) AllocSpace objects, 8(410KB) LOS objects, 32% free, 33MB/49MB, paused 1.407ms total 70.452ms
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT8606
,I/BtToSocketBase( 3245): Stop ReceivingThread
,W/bt-btif ( 3300): invalid rfc slot id: 23
I/BtToSocketBase( 3245): Stop SendingThread
,I/BtToSocketBase( 3245): Close local in
,I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3245): 2015-11-30T10:01:11.497Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x4b
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/jxcore-log( 3245): 2015-11-30T10:01:16.052Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:01:16.053Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:01:16.054Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:01:16.055Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:01:16.056Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
I/BtToSocketBase( 3245): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3245): Disconnect outgoing peer: HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
,I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
,I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3245): 2015-11-30T10:01:21.057Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:01:21.058Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
,W/bt-btif ( 3300): info:x10
,D/        ( 3300): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 445)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 445)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 445),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 445)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 445
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 445)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 445)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, LGE-LG-D855_PT8606
,I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T10:01:21.911Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:01:22.360Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:01:22.364Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:01:22.369Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:01:22.373Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:01:22.380Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3245): 2015-11-30T10:01:26.062Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:01:26.063Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:01:26.064Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:01:26.064Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): info:x10,
D/        ( 3300): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a40c rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 450)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 450)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 450)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 84 bytes successfully (thread ID: 450)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 450)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 60627
I/BtConnectorHelper( 3245): Request socket is using : 60627
,I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :60627
,I/jxcore-log( 3245): 2015-11-30T10:01:30.969Z SendDataConnector.js: CLIENT connected to 60627, error: null
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:01:30.970Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 60627
I/BtToRequestSocket( 3245): Set local streams
I/jxcore-log( 3245): 2015-11-30T10:01:30.980Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): rin ended ---------------------------;
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT8606
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
,I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
,I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
W/bt-btif ( 3300): invalid rfc slot id: 27
,I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3245): 2015-11-30T10:02:12.441Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x49
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=0,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): dm_pm_timer expires
W/bt-btif ( 3300): dm_pm_timer expires 0
,W/bt-btif ( 3300): proc dm_pm_timer expires
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/jxcore-log( 3245): 2015-11-30T10:02:21.036Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:02:21.037Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:02:21.038Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:02:21.039Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:02:21.040Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
,I/BtToSocketBase( 3245): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3245): Disconnect outgoing peer: HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3245): Stop ReceivingThread
,I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
,I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,W/bt-btif ( 3300): info:x10,
D/        ( 3300): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
,W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 454)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 454)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 454)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 454)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 454
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 454)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 454)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT8606 58:3F:54:73:64:C0]
,I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, LGE-LG-D855_PT8606
,I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
,I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T10:02:25.123Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:02:25.554Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:02:25.559Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:02:25.562Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:02:25.569Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:02:25.578Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:02:25.586Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:02:26.040Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:02:26.041Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: HTC Desire 820,
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3245): 2015-11-30T10:02:31.045Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:02:31.046Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:02:31.048Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:02:31.048Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
,W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3300): info:x10
,D/        ( 3300): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3300): process_service_search_attr_rsp,
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 459)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 459)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 459)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 84 bytes successfully (thread ID: 459),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 459)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3245): mHTTPPort  set to : 60600
I/BtConnectorHelper( 3245): Request socket is using : 60600
I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :60600
,I/jxcore-log( 3245): 2015-11-30T10:02:35.768Z SendDataConnector.js: CLIENT connected to 60600, error: null
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:02:35.769Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 60600
I/BtToRequestSocket( 3245): Set local streams
,I/BtToRequestSocket( 3245): rin ended ---------------------------;
,I/jxcore-log( 3245): 2015-11-30T10:02:35.783Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3245): 
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,W/bt-btif ( 3300): invalid rfc slot id: 29,
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT8606
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
,I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3245): 2015-11-30T10:03:16.002Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3300): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 3300): RFCOMM_DisconnectInd LCID:0x43
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,W/bt-btif ( 3300): dm_pm_timer expires,
W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: G3-1
,I/jxcore-log( 3245): 2015-11-30T10:03:25.845Z SendDataConnector.js: Receiving data timeout now,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:25.846Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:25.847Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:03:25.852Z SendDataConnector.js: CLIENT Stop now
,I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:03:25.853Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:25.854Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/BtConnectorHelper( 3245): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
,I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3245): 2015-11-30T10:03:25.867Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3245): 
I/jxcore-log( 3245): ---- round done--------
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): do fake peer & start
I/jxcore-log( 3245): 
I/jxcore-log( 3245): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:03:25.871Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:25.871Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:03:25.872Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: Nexus 5 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/jxcore-log( 3245): 2015-11-30T10:03:25.878Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3245): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a964 rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14),
,W/bt-btif ( 3300): info:x10
,D/        ( 3300): remote version info [34:fc:ef:11:b1:66]: 6, 1d, 7d3
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a5d4 rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,D/btif_config( 3300): btif_get_device_type: Device [34:fc:ef:11:b1:66] type 1
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
,E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
D/BluetoothAdapterProperties( 3300): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 464)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 464)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 464)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a5d4 rs_disc_pending=0,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 77 bytes successfully (thread ID: 464)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 464)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, LGE-Nexus 5_PT9919
,I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3245): mHTTPPort  set to : 35921
,I/BtConnectorHelper( 3245): Request socket is using : 35921
I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :35921
,I/jxcore-log( 3245): 2015-11-30T10:03:28.863Z SendDataConnector.js: CLIENT connected to 35921, error: null
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:28.865Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 35921
,I/BtToRequestSocket( 3245): Set local streams
,I/BtToRequestSocket( 3245): rin ended ---------------------------;
,I/jxcore-log( 3245): 2015-11-30T10:03:28.889Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16792
,I/jxcore-log( 3245): 2015-11-30T10:03:29.319Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18048,
,I/jxcore-log( 3245): 2015-11-30T10:03:29.372Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11118,
,I/jxcore-log( 3245): 2015-11-30T10:03:29.425Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:29.462Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5178
,I/jxcore-log( 3245): 2015-11-30T10:03:29.498Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:29.583Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:29.639Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:29.654Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:29.712Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:29.718Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:29.718Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:29.723Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:03:29.724Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/BtConnectorHelper( 3245): Disconnect outgoing peer: 34:FC:EF:11:B1:66
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
,I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
,I/BtToRequestSocket( 3245): Close server socket
I/jxcore-log( 3245): 2015-11-30T10:03:29.733Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3245): 
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3245): ---- round done--------
I/jxcore-log( 3245): 
I/jxcore-log( 3245): do fake peer & start
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3245): ,
I/jxcore-log( 3245): 2015-11-30T10:03:29.737Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:03:29.737Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
,I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:03:29.738Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: null 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to null in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3245): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63),
D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a5d4 rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a5d4 rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive,
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Nexus 5
,I/GCM     ( 1787): Message from null null
E/GCM     ( 1787): Dropping message from null
,D/GCM     ( 1482): Message class com.google.f.a.a.i
,W/bt-btif ( 3300): info:x10,
D/        ( 3300): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3300): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,D/btif_config( 3300): btif_get_device_type: Device [08:ec:a9:50:75:41] type 1
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 3300): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3300): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3300): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3300): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
D/BluetoothAdapterProperties( 3300): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3300): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3300): StableState(): Entering Off State
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 469)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 469)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 469)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 469)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 469)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3245): mHTTPPort  set to : 33736
,I/BtConnectorHelper( 3245): Request socket is using : 33736
I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :33736
,I/jxcore-log( 3245): 2015-11-30T10:03:50.717Z SendDataConnector.js: CLIENT connected to 33736, error: null
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:03:50.718Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 33736
,I/BtToRequestSocket( 3245): Set local streams
I/BtToRequestSocket( 3245): rin ended ---------------------------;
I/jxcore-log( 3245): 2015-11-30T10:03:50.729Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 3245): 2015-11-30T10:03:51.133Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14088,
I/jxcore-log( 3245): 2015-11-30T10:03:51.169Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:51.180Z SendDataConnector.js: CLIENT is data received : 30000,
I/jxcore-log( 3245): 
,D/        ( 3300): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5178
,I/jxcore-log( 3245): 2015-11-30T10:03:51.211Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:51.214Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:51.248Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:51.256Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:51.304Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:03:51.311Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3245): 
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 0
,W/bt-btif ( 3300): proc dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires
W/bt-btif ( 3300): dm_pm_timer expires 0
,W/bt-btif ( 3300): proc dm_pm_timer expires
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:255
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 473)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 473)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 473)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 473)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 473
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 473)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 473)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/jxcore-log( 3245): 2015-11-30T10:04:40.201Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T10:04:40.932Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:40.937Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:40.941Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:40.944Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:40.951Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:40.958Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:40.963Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:40.998Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.005Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.009Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.039Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.063Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.068Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.071Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.111Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.113Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.117Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.120Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.123Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.160Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.163Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.165Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.169Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.207Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:41.309Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:04:41.310Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:04:41.312Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:04:41.313Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:04:41.314Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
,I/BtToSocketBase( 3245): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3245): Disconnect outgoing peer: samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
,I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/jxcore-log( 3245): 2015-11-30T10:04:46.315Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:46.316Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:51.320Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:51.321Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:04:51.322Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:04:51.322Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 478)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 478)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 478)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 478)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 478)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41],
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 49082
I/BtConnectorHelper( 3245): Request socket is using : 49082
,I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :49082
,I/jxcore-log( 3245): 2015-11-30T10:04:51.884Z SendDataConnector.js: CLIENT connected to 49082, error: null
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:04:51.885Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 49082
,I/BtToRequestSocket( 3245): Set local streams
,I/jxcore-log( 3245): 2015-11-30T10:04:51.895Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): rin ended ---------------------------;
,W/bt-btif ( 3300): dm_pm_timer expires
W/bt-btif ( 3300): dm_pm_timer expires 0
,W/bt-btif ( 3300): proc dm_pm_timer expires
,I/EventLogService( 1787): Opted in for usage reporting
,I/EventLogService( 1787): Aggregate from 1448876917644 (log), 1448876078325 (data)
,I/ServiceDumpSys( 1787): dumping service [account]
,V/GoogleAuthProtoRequest( 4496): [496] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 68332(3MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 1.740ms total 53.686ms
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4496): [496] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4496): [496] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4496): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4496): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4496): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4496): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4496): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4496): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,W/bt-btif ( 3300): invalid rfc slot id: 31
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
,I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
,I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close bt out
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close bt socket
,I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/jxcore-log( 3245): 2015-11-30T10:05:31.440Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,I/BooksSync( 4614): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4614): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4614): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4614): Soft error
E/BooksSync( 4614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source),
E/BooksSync( 4614): Sync error
E/BooksSync( 4614): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4614): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4614): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1170190, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5ab2c rs_disc_pending=0
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 482)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 482)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 482)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 482)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 482
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 482)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 482)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T10:05:41.644Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:05:41.956Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:05:41.956Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:05:41.958Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:05:41.959Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:05:41.960Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
I/BtToSocketBase( 3245): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3245): Disconnect outgoing peer: samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
,I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3245): Close bt out
,I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 3245): 2015-11-30T10:05:42.040Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:05:42.050Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:05:42.055Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:05:42.060Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:05:42.066Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data,
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:05:42.069Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:05:46.959Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:05:46.960Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:05:51.965Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:05:51.965Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:05:51.966Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:05:51.967Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
,W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 487)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 487)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 487)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 487)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
,I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 487)
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 43490
I/BtConnectorHelper( 3245): Request socket is using : 43490
,I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :43490
,I/jxcore-log( 3245): 2015-11-30T10:05:52.635Z SendDataConnector.js: CLIENT connected to 43490, error: null
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:05:52.636Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 43490
,I/BtToRequestSocket( 3245): Set local streams
,I/jxcore-log( 3245): 2015-11-30T10:05:52.647Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): rin ended ---------------------------;
,W/bt-btif ( 3300): dm_pm_timer expires
W/bt-btif ( 3300): dm_pm_timer expires 0
,W/bt-btif ( 3300): proc dm_pm_timer expires
,E/bt-btif ( 3300): bta_dm_pm_btm_status  hci_status=35
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,W/bt-btif ( 3300): invalid rfc slot id: 35
I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
,I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket,
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3245): 2015-11-30T10:06:32.289Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 4460): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at blb.a(PG:3937)
E/HttpOperation( 4460): 	at czp.a(PG:18188)
E/HttpOperation( 4460): 	at czp.a(PG:9081)
E/HttpOperation( 4460): 	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 12 more
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 14 more
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4460): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4460): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4460): 	at jdm.a(PG:82)
E/HttpOperation( 4460): 	at jcs.o(PG:406)
E/HttpOperation( 4460): 	at jcn.a(PG:1379)
E/HttpOperation( 4460): 	at jcs.i(PG:143)
E/HttpOperation( 4460): 	at hec.a(PG:42)
E/HttpOperation( 4460): 	at hee.a(PG:102)
E/HttpOperation( 4460): 	at czr.a(PG:65)
E/HttpOperation( 4460): 	at kka.a(PG:108)
E/HttpOperation( 4460): 	at czp.a(PG:19176)
E/HttpOperation( 4460): 	at czp.a(PG:9081)
E/HttpOperation( 4460): 	at czq.run(PG:1686)
E/HttpOperation( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4460): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4460): 	at jdj.a(PG:4091)
E/HttpOperation( 4460): 	at jdj.a(PG:1125)
E/HttpOperation( 4460): 	at jdm.a(PG:77)
E/HttpOperation( 4460): 	... 15 more
E/HttpOperation( 4460): Caused by: faj: BadAuthentication
E/HttpOperation( 4460): 	at fal.a(PG:38)
E/HttpOperation( 4460): 	at jdj.a(PG:4089)
E/HttpOperation( 4460): 	... 17 more
,E/ExperimentLoader( 4460): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 4460): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4460): 	at jdm.a(PG:82)
E/ExperimentLoader( 4460): ,	at jcs.o(PG:406)
E/ExperimentLoader( 4460): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4460): 	at jcs.i(PG:143)
E/ExperimentLoader( 4460): 	at hec.a(PG:42)
,E/ExperimentLoader( 4460): 	at hee.a(PG:102)
E/ExperimentLoader( 4460): 	at czr.a(PG:65)
E/ExperimentLoader( 4460): 	at kka.a(PG:108)
E/ExperimentLoader( 4460): 	,at czp.a(PG:19176)
E/ExperimentLoader( 4460): 	at czp.a(PG:9081)
E/ExperimentLoader( 4460): 	at czq.run(PG:1686)
E/ExperimentLoader( 4460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/ExperimentLoader( 4460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4460): 	at java.lang.Thread.run(Thread.java:818)
,E/ExperimentLoader( 4460): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4460): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4460): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4460): 	at jdm.a(PG:77)
,E/ExperimentLoader( 4460): 	... 15 more
E/ExperimentLoader( 4460): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4460): 	at fal.a(PG:38)
E/ExperimentLoader( 4460): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4460): 	,... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1228595, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/UsageStatsService(  824): User[0] Flushing usage stats to disk
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 491)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 491)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 491)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 491)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 491
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 491)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 491)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3245): --DoOneRunRound started
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T10:06:42.374Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:42.706Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:42.707Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:06:42.708Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:42.709Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:42.713Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
I/BtToSocketBase( 3245): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3245): Disconnect outgoing peer: samsung-SM-A300FU_PT406
,I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
,I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
,I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtToSocketBase( 3245): Close bt out
,I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket,
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND,
,I/jxcore-log( 3245): 2015-11-30T10:06:42.765Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:42.770Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
,I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:42.773Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
,I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:42.777Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:42.782Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:47.714Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:47.716Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:52.722Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:52.723Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:06:52.724Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:06:52.724Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: A3-1 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 496)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 496)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 496)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 496)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 496)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 46454
I/BtConnectorHelper( 3245): Request socket is using : 46454
I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :46454
,I/jxcore-log( 3245): 2015-11-30T10:06:53.134Z SendDataConnector.js: CLIENT connected to 46454, error: null
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:06:53.135Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 46454
,I/BtToRequestSocket( 3245): Set local streams
I/BtToRequestSocket( 3245): rin ended ---------------------------;
,I/jxcore-log( 3245): 2015-11-30T10:06:53.149Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3245): 
,W/bt-btif ( 3300): dm_pm_timer expires,
,W/bt-btif ( 3300): dm_pm_timer expires 0,
,W/bt-btif ( 3300): proc dm_pm_timer expires,
,V/KeepSync( 4652): Connecting to GoogleApiClient
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1787): Handling authorization failure,
E/ClientConnectionOperation( 1787): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1787): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1787): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1787): 	,at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1787): 	,... 7 more
,V/KeepSync( 4652): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4652): (284) automatic index on blob_node(is_deleted)
,I/art     (  824): Explicit concurrent mark sweep GC freed 38646(1904KB) AllocSpace objects, 10(348KB) LOS objects, 32% free, 33MB/49MB, paused 2.533ms total 72.982ms
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4652): IOException
E/KeepSync( 4652): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4652): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4652): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4652): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4652): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4652): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4652): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4652): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4652): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4652): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4652): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4652): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4652): 	... 10 more
W/KeepSync( 4652): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1256488, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/BTLD    ( 3300): ######################################################################
,E/BTLD    ( 3300): #
E/BTLD    ( 3300): # WARNING : BTU HCI(id=0) command timeout. opcode=0x803
E/BTLD    ( 3300): #
E/BTLD    ( 3300): ######################################################################
,W/bt-hci  ( 3300): HCI Cmd timeout counter 1
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,W/bt-btif ( 3300): invalid rfc slot id: 37,
I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
,I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
W/bt-hci  ( 3300): No command in queue matching opcode 2051
I/jxcore-log( 3245): 2015-11-30T10:07:32.817Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Incoming connection initialized (thread ID: 500)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 500)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 500)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 500)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): removeThreadFromList: Removing thread with ID 500
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Handshake thread disposed (thread ID: 500)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 500)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
,I/BtConnectorHelper( 3245): Starting the connected thread incoming : true, samsung-SM-A300FU_PT406
,I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BTConnectedThread
I/BtConnectorHelper( 3245): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3245): --DoOneRunRound started,
,I/BtToRequestSocket( 3245): LocalHost address: localhost/127.0.0.1, port: 50286,
,I/BtToRequestSocket( 3245): --DoOneRunRound ended
,I/jxcore-log( 3245): 2015-11-30T10:07:42.888Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:07:43.206Z SendDataConnector.js: Receiving data timeout now,
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:07:43.207Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:07:43.208Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:07:43.209Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:07:43.210Z SendDataConnector.js: ----------------- closeClientSocket
,I/jxcore-log( 3245): 
I/BtToSocketBase( 3245): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3245): Disconnect outgoing peer: samsung-SM-A300FU_PT406
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
,I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/jxcore-log( 3245): 2015-11-30T10:07:43.293Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:07:43.298Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:07:43.301Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:07:43.305Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:07:43.309Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:07:48.209Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:07:48.210Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,I/jxcore-log( 3245): 2015-11-30T10:07:53.214Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41,
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:07:53.215Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:07:53.216Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:07:53.217Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 505)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 505)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 505)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 505)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 505),
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41],
,I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, samsung-SM-A300FU_PT406
,I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket,
I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3245): mHTTPPort  set to : 45351
I/BtConnectorHelper( 3245): Request socket is using : 45351
,I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :45351,
I/jxcore-log( 3245): 2015-11-30T10:07:54.165Z SendDataConnector.js: CLIENT connected to 45351, error: null
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:07:54.165Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 45351,
,I/BtToRequestSocket( 3245): Set local streams
I/BtToRequestSocket( 3245): rin ended ---------------------------;
I/jxcore-log( 3245): 2015-11-30T10:07:54.177Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3245): 
,W/bt-btif ( 3300): dm_pm_timer expires
W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,E/BTLD    ( 3300): ######################################################################
E/BTLD    ( 3300): #
E/BTLD    ( 3300): # WARNING : BTU HCI(id=0) command timeout. opcode=0x803
E/BTLD    ( 3300): #
E/BTLD    ( 3300): ######################################################################
W/bt-hci  ( 3300): HCI Cmd timeout counter 1
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,W/bt-btif ( 3300): invalid rfc slot id: 39
,I/BtToSocketBase( 3245): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3245): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT406
,I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
W/bt-hci  ( 3300): No command in queue matching opcode 2051
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
I/BtToSocketBase( 3245): Close bt socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3245): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3245): 2015-11-30T10:08:33.692Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:44.235Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:44.236Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:08:44.237Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:44.244Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:08:44.245Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:44.246Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
,I/BtConnectorHelper( 3245): Disconnect outgoing peer: 08:EC:A9:50:75:41
,I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
,I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3245): Close bt out
,I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
,I/jxcore-log( 3245): 2015-11-30T10:08:44.259Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3245): 
I/jxcore-log( 3245): ---- round done--------
I/jxcore-log( 3245): 
I/jxcore-log( 3245): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3245): 
I/jxcore-log( 3245): do fake peer & start
I/jxcore-log( 3245): 
I/jxcore-log( 3245): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:44.263Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:08:44.263Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:08:44.264Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: Note3-1 E0:DB:10:1F:C9:5E,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
I/jxcore-log( 3245): 2015-11-30T10:08:44.269Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3245): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63),
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5ab2c rs_disc_pending=1,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): info:x10,
D/        ( 3300): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 510)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 510)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 510)
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=1
,W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 510)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 510)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
,I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, samsung-SM-N9005_PT4028
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 34742
I/BtConnectorHelper( 3245): Request socket is using : 34742
I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :34742
,I/jxcore-log( 3245): 2015-11-30T10:08:47.422Z SendDataConnector.js: CLIENT connected to 34742, error: null
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:47.423Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 34742
,I/BtToRequestSocket( 3245): Set local streams
,I/jxcore-log( 3245): 2015-11-30T10:08:47.436Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3245): 
I/BtToRequestSocket( 3245): rin ended ---------------------------;
,I/jxcore-log( 3245): 2015-11-30T10:08:47.861Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:47.910Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:47.977Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:47.993Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:48.065Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:48.175Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:48.197Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:48.211Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:08:48.217Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3245): 
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: A3-1
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): dm_pm_timer expires
W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 1
W/bt-btif ( 3300): proc dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
,E/bt-btm  ( 3300): tBTM_SEC_DEV:0xa2f5a07c rs_disc_pending=0,
W/bt-btif ( 3300): bta_dm_check_av:0
W/bt-btif ( 3300): btif_dm_cback : unhandled event (14)
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,I/jxcore-log( 3245): 2015-11-30T10:09:38.218Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:09:38.219Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:09:38.220Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:09:38.221Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:09:38.222Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3245): 
,I/BtToSocketBase( 3245): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3245): Disconnect outgoing peer: samsung-SM-N9005_PT4028
I/BtToSocketBase( 3245): Stop ReceivingThread
I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Close bt out
,I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1,
,I/jxcore-log( 3245): 2015-11-30T10:09:43.221Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:09:43.222Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:09:48.226Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:09:48.227Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:09:48.228Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:09:48.228Z SendDataConnector.js: do connect now
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Trying to connect...
,W/BluetoothAdapter( 3245): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3300): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3300): info:x10
D/        ( 3300): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 3300): process_service_search_attr_rsp
,W/bt-btif ( 3300): new conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3300): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Outgoing connection initialized (thread ID: 515),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesWritten: 82 bytes successfully written (thread ID: 515),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Entering thread (ID: 515)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): onBytesRead: Read 82 bytes successfully (thread ID: 515),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3245): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3245): Exiting thread (ID: 515)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/BtConnectorHelper( 3245): Starting the connected thread incoming : false, samsung-SM-N9005_PT4028
I/BtToSocketBase( 3245): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3245): mHTTPPort  set to : 39483
I/BtConnectorHelper( 3245): Request socket is using : 39483
I/BtToRequestSocket( 3245): Now accepting connections
,I/BtConnectorHelper( 3245): Calling ConnectionStatusUpdate with port :39483
,I/jxcore-log( 3245): 2015-11-30T10:09:50.175Z SendDataConnector.js: CLIENT connected to 39483, error: null
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): 2015-11-30T10:09:50.176Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): incoming data from: /127.0.0.1, port: 39483
,I/BtToRequestSocket( 3245): Set local streams
,I/jxcore-log( 3245): 2015-11-30T10:09:50.184Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3245): 
,I/BtToRequestSocket( 3245): rin ended ---------------------------;
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3300): dm_pm_timer expires
,W/bt-btif ( 3300): dm_pm_timer expires 0
W/bt-btif ( 3300): proc dm_pm_timer expires
I/jxcore-log( 3245): timeout now
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): dun
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): weAreDoneNow , resultArray.length: 3
,I/jxcore-log( 3245): 
,I/jxcore-log( 3245): done, now sending data to server
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): -- RESULT DATA {"name:":"motorola-Nexus 6_PT1326","time":1000075,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":23240,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":4120,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:B1:66","time":3848,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"E0:DB:10:1F:C9:5E","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"58:2A:F7:ED:96:BE","time":0,"result":"Fail"},{"connections
,I/jxcore-log( 3245): sendList : 100% : 23240 ms, 99% : 23240 ms, 95 : 23240 ms, 90% : 23240 ms.
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): Result count 3, range 3848 ms to  23240 ms.
I/jxcore-log( 3245): 
I/jxcore-log( 3245): sendList failed peers count : 4 [57.142857142857146 %]
I/jxcore-log( 3245): 
I/jxcore-log( 3245): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
I/jxcore-log( 3245): 
I/jxcore-log( 3245): - Peer ID : 58:3F:54:73:64:C0, Tried : 1
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): - Peer ID : 80:01:84:8A:B3:68, Tried : 1
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): - Peer ID : 08:EC:A9:50:75:41, Tried : 1
I/jxcore-log( 3245): 
I/jxcore-log( 3245): sendList never tried peers count : 14 [66.66666666666667 %]
I/jxcore-log( 3245): 
I/jxcore-log( 3245): - Peer ID : 7C:F9:0E:51:18:22
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3245): 
I/jxcore-log( 3245): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 3245): 
I/jxcore-log( 3245): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 3245): 
I/jxcore-log( 3245): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): - Peer ID : 58:2A:F7:ED:96:BE
I/jxcore-log( 3245): 
I/jxcore-log( 3245): - Peer ID : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3245): 
I/jxcore-log( 3245): - Peer ID : 50:2E:6C:AC:21:50
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): - Peer ID : 34:FC:EF:11:AE:67
I/jxcore-log( 3245): 
I/jxcore-log( 3245): - Peer ID : E0:DB:10:14:E2:C0
I/jxcore-log( 3245): 
I/jxcore-log( 3245): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 3245): 
I/jxcore-log( 3245): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3245): 
I/jxcore-log( 3245): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:10:12.245Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:10:12.245Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3245): 
I/jxcore-log( 3245): 2015-11-30T10:10:12.246Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3245): 
I/BtConnectorHelper( 3245): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 3245): Stop ReceivingThread
,I/BtToSocketBase( 3245): Stop SendingThread
I/BtToSocketBase( 3245): Close local in
I/BtToSocketBase( 3245): Close LocalOutputStream
I/BtToSocketBase( 3245): Close localHostSocket
I/BtToSocketBase( 3245): Close bt in
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3245): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3245): Close bt out
,I/BtToSocketBase( 3245): Close bt socket
I/BtToRequestSocket( 3245): Close server socket
I/jxcore-log( 3245): 2015-11-30T10:10:12.249Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3245): 
I/chromium( 3245): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3245): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3300): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,D/HeadsetStateMachine( 3300): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3300): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3300): onReceive
,I/BTConnectionReceiver( 4382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4382): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3245): DBG, CoordinatorConnector command called
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): stop tests now !
I/jxcore-log( 3245): 
I/jxcore-log( 3245): stop current!
I/jxcore-log( 3245): 
I/jxcore-log( 3245): testSendData stopped
I/jxcore-log( 3245): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): setState: INITIALIZED
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:91)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3245): StopBroadcasting went ok
I/jxcore-log( 3245): 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3245): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3245): onServerStopped
I/jxcore-log( 3245): 2015-11-30T10:10:45.657Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3245): 
,I/chromium( 3245): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onConnectionFailed: Socket is null
W/jxcore-log( 3245): $$jxcore_callback_44 wasn't registered
W/jxcore-log( 3245): 
,W/jxcore-log( 3245): $$jxcore_callback_44 wasn't registered
W/jxcore-log( 3245): 
,I/jxcore-log( 3245): DBG, CoordinatorConnector command called
I/jxcore-log( 3245): 
I/jxcore-log( 3245): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"34:FC:EF:11:B1:66\",\"time\":3848,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"B0:C5:59:3F:75:69\",\"time\":4120,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"08:EC:A9:50:76:27\",\"time\":23240,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"58:3F:54:73:64:C0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"80:01:84:8A:B3:68\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:75:41\",\"time\":0,\"result\":\"Fail\"}],\"notTriedList\":[{\"connections\":0,\"name\":\"7C:F9:0E:51:18:22\",\"time\":0,\"r
,I/jxcore-log( 3245): ****TEST TOOK:  ms ****
I/jxcore-log( 3245): 
I/jxcore-log( 3245): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3245): 
I/jxcore-log( 3245): stop tests now !
I/jxcore-log( 3245): 
,I/jxcore-log( 3245): end, event received
I/jxcore-log( 3245): 
I/jxcore-log( 3245): CoordinatorConnector close called
I/jxcore-log( 3245): 
I/jxcore-log( 3245): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3245): 
I/jxcore-log( 3245): The Coordinator has disconnected!
I/jxcore-log( 3245): 
I/jxcore-log( 3245): The Coordinator has closed!
I/jxcore-log( 3245): 
I/jxcore-log( 3245): stop tests now !
I/jxcore-log( 3245): 
I/jxcore-log( 3245): turning Radios off
I/jxcore-log( 3245): 
I/jxcore-log( 3245): Toggling radios to false
I/jxcore-log( 3245): 
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  824): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3ee30939 mBinding = false
,D/BluetoothManagerService(  824): Message: 2
,D/WifiService(  824): setWifiEnabled: false pid=3245, uid=10265
E/WifiService(  824): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService(  824): Sending off request.
,D/BluetoothAdapterState( 3300): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3300): Setting state to 13
I/BluetoothAdapterState( 3300): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3300): onBluetoothDisable()
I/BluetoothAdapterState( 3300): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3300): Scan Mode:20
,D/BluetoothAdapterState( 3300): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
W/bt-btif ( 3300): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/btif_config_util( 3300): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 3300): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3300): L2CAP - PSM: 0x0017 not found for deregistration
E/BtOppRfcommListener( 3300): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,V/BluetoothMapMasInstance( 3300): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3300): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3300): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3300): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3300): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3300): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3300): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3300): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,I/jxcore-log( 3245): Radios toggled
I/jxcore-log( 3245): 
,E/WifiStateMachine(  824): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/chromium( 3245): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onBluetoothAdapterScanModeChanged: Mode changed to 20
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onBluetoothAdapterScanModeChanged: Bluetooth disabled, stopping...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
,E/native  (  824): do suspend true
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/BluetoothManagerService(  824): Message: 60
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  824): Bluetooth State Change Intent: 12 -> 13
,V/NativeCrypto( 1482): Read error: ssl=0x9cc3b800: I/O error during system call, Connection timed out
,E/WifiStateMachine(  824): scanCount==0 - aborting
,D/BluetoothMapService( 3300): onReceive
D/BluetoothMapService( 3300): STATE_TURNING_OFF
D/BluetoothMapService( 3300): MAP Service closeService in
D/BluetoothMapMasInstance( 3300): MAP Service shutdown
I/BtOppRfcommListener( 3300): stopping Accept Thread
V/NativeCrypto( 1482): SSL shutdown failed: ssl=0x9cc3b800: I/O error during system call, Broken pipe,
I/BtOppRfcommListener( 3300): BluetoothSocket listen thread finished
,D/WifiNetworkAgent(  824): NetworkAgent: NetworkAgent channel lost
,D/WifiScanningService(  824): SCAN_AVAILABLE : 1
,D/WifiScanningService(  824): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  824): DefaultState
D/RttService(  824): SCAN_AVAILABLE : 1
,D/RttService(  824): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  824): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
E/native  (  824): do suspend true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3245): onWifiStateChanged: State changed to 1
,W/ContextImpl( 4758): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/CommandListener(  354): Clearing all IP addresses on wlan0
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,I/ActivityManager(  824): Start proc 5231:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
D/ConnectivityService(  824): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  824): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
E/WifiStateMachine(  824): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524292
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  824): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): OfflineState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Disconnected - quitting
,D/Tethering(  824): MasterInitialState.processMessage what=3
,D/Tethering(  824): MasterInitialState.processMessage what=3
D/ConnectivityService(  824): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/BluetoothManagerService(  824): Message: 30
,D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  824): getDataEnabled: retVal=false
,I/wpa_supplicant( 3307): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3307): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/BluetoothManagerService(  824): Message: 30
,D/LocalBluetoothProfileManager( 4758): Adding local MAP profile
,D/BluetoothMap( 4758): Create BluetoothMap proxy object
E/GpsLocationProvider(  824): No APN found to select.
,D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): Message: 30
,D/LocalBluetoothProfileManager( 4758): LocalBluetoothProfileManager construction complete
,D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  824): getDataEnabled: retVal=false
,E/GpsLocationProvider(  824): No APN found to select.
D/DockEventReceiver( 4758): finishStartingService: stopping service
,D/BluetoothInputDevice( 4758): Proxy object connected
,D/HidProfile( 4758): Bluetooth service connected
D/BluetoothPan( 4758): BluetoothPAN Proxy object connected
D/PanProfile( 4758): Bluetooth service connected
D/BluetoothMap( 4758): Proxy object connected
D/MapProfile( 4758): Bluetooth service connected
D/BluetoothMap( 4758): getConnectedDevices()
D/BluetoothMap( 4758): Bluetooth is Not enabled
,D/AndroidRuntime( 5220): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 5220): CheckJNI is OFF
,W/bt-btif ( 3300): ag scb idx 1 not allocated
E/bt-btif ( 3300): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3300): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3300): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3300): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3300): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3300): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3300): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3300): RX termination
W/bt_userial( 3300): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3300): Leaving userial_read_thread()
,D/bt_userial( 3300): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3300): hw_epilog_process
I/bt_userial_vendor( 3300): device fd = 53 close
,D/AndroidRuntime( 5220): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  824): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  824): Killing 3245:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,I/GKI_LINUX( 3300): gki_task task_id=0 [BTU] terminating
,W/PackageSettings(  824): Skipping PackageSetting{374c92a7 com.example.hello/10272} due to missing metadata
,I/GKI_LINUX( 3300): GKI_exit_task 0 done
I/GKI_LINUX( 3300): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3300): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/StrictMode( 5231): StrictMode policy violation; ~duration=168 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5231): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5231): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5231): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5231): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5231): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 5231): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 5231): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 5231): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 5231): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5231): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5231): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5231): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5231): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5231): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5231): StrictMode policy violation; ~duration=167 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5231): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5231): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5231): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5231): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5231): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5231): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5231): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5231): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5231): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5231): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 5231): StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
D/StrictMode( 5231): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5231): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5231): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 5231): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 5231): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 5231): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 5231): 	at java.lang.System.loadLibrary(System.java:988),
D/StrictMode( 5231): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 5231): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5231): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5231): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5231): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5231): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5231): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5231): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5231): StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5231): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5231): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202),
D/StrictMode( 5231): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 5231): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5231): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5231): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5231): ,	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5231): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5231): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903),
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5231): StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5231): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5231): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5231): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 5231): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 5231): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 5231): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 5231): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 5231): 	,at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5231): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5231): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5231): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
,D/StrictMode( 5231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5231): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5231): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5231): StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 5231): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5231): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 5231): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 5231): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 5231): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 5231): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 5231): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 5231): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 5231): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 5231): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 5231): # via Binder call with stack:
D/StrictMode( 5231): android.os.StrictMode$LogStackTrace
D/StrictMode( 5231): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 5231): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 5231): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 5231): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
,D/StrictMode( 5231): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 5231): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 5231): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 5231): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 5231): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84),
D/StrictMode( 5231): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5231): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5231): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5231): 	at android.os.Handler.dispatchMessage(Handler.java:102),
D/StrictMode( 5231): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5231): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Method.java:372)
,D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5231): ,	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5231): StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5231): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5231): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5231): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5231): 	at java.io.File.exists(File.java:363)
,D/StrictMode( 5231): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 5231): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 5231): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 5231): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
,D/StrictMode( 5231): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5231): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012),
D/StrictMode( 5231): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5231): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5231): 	at android.os.Looper.loop(Looper.java:135)
,D/StrictMode( 5231): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5231): StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5231): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137),
D/StrictMode( 5231): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5231): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 5231): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
,D/StrictMode( 5231): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 5231): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5231): 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5231): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5231): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5231): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5231): 	,at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5231): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 5231): StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5231): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5231): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 5231): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 5231): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
,D/StrictMode( 5231): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 5231): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5231): 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5231): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5231): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5231): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5231): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5231): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
,D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5231): StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5231): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5231): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 5231): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 5231): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 5231): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 5231): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 5231): 	at com.google.p.j.c(PG:1152)
,D/StrictMode( 5231): 	at com.google.p.j.a(PG:121)
D/StrictMode( 5231): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 5231): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 5231): 	at com.google.p.e.a(PG:170)
D/StrictMode( 5231): 	at com.google.p.e.b(PG:21)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
,D/StrictMode( 5231): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5231): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5231): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5231): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5231): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364),
D/StrictMode( 5231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5231): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5231): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5231): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5231): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/InputDispatcher(  824): channel '316f84c2 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  824): channel '316f84c2 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
I/WindowState(  824): WIN DEATH: Window{316f84c2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputDispatcher(  824): Attempted to unregister already unregistered input channel '316f84c2 com.test.thalitest/com.test.thalitest.MainActivity (server)'
D/WifiService(  824): Client connection lost with reason: 4
I/wpa_supplicant( 3307): wlan0: CTRL-EVENT-TERMINATING 
E/WifiMonitor(  824): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
D/Tethering(  824): InitialState.processMessage what=4
W/com.google.a.a.a.b.a( 5231): Application name is not set. Call Builder#setApplicationName.
,W/ActivityManager(  824): Force removing ActivityRecord{169e7b7b u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
,V/ActivityManager(  824): Display changed displayId=0
,I/ActivityManager(  824): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/Tethering(  824): sendTetherStateChangedBroadcast 0, 0, 0
D/HeadsetService( 3300): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 3300): Exit Disconnected: -1
D/TaskPersister(  824): removeObsoleteFile: deleting file=24_task.xml
,D/A2dpService( 3300): Received stop request...Stopping profile...
W/ActivityManager(  824): Spurious death for ProcessRecord{1de4a706 3245:com.test.thalitest/u0a265}, curProc for 3245: null
D/A2dpStateMachine( 3300): Exit Disconnected: -1
,D/HeadsetStateMachine( 3300): Unbinding service...
,D/BluetoothManagerService(  824): Message: 20
,D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20ea33f4:true
,I/Keyboard.Facilitator( 1213): resetDictionaries() : en_US
W/BluetoothHeadsetServiceJni( 3300): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3300): Cleaning up Bluetooth Handsfree callback object
,I/Keyboard.Facilitator.DecoderInitializer( 1213): run(),
D/HidService( 3300): Received stop request...Stopping profile...
I/GKI_LINUX( 3300): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3300): GKI_exit_task 2 done
I/GKI_LINUX( 3300): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/Settings( 1752): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothAdapterState( 3300): Stopping profile services that were post enabled
D/HealthService( 3300): Received stop request...Stopping profile...
D/BluetoothInputDevice( 4758): Proxy object disconnected
D/HidProfile( 4758): Bluetooth service disconnected
I/InputReader(  824): Reconfiguring input devices.  changes=0x00000010
W/Settings( 4423): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  824): Killing 4332:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/PanService( 3300): Received stop request...Stopping profile...
,I/art     ( 1065): Explicit concurrent mark sweep GC freed 73771(2MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 75MB/91MB, paused 4.708ms total 58.407ms
,D/BluetoothA2dp( 1065): Proxy object disconnected
D/BluetoothInputDevice( 1065): Proxy object disconnected
,I/Decoder ( 1213): createOrResetDecoder
,I/art     (  824): Explicit concurrent mark sweep GC freed 29465(1814KB) AllocSpace objects, 4(158KB) LOS objects, 32% free, 33MB/49MB, paused 1.371ms total 89.183ms
D/BluetoothHeadset(  824): Proxy object disconnected
D/BluetoothHeadset( 1065): Proxy object disconnected
D/BluetoothHeadset( 1276): Proxy object disconnected
,D/BluetoothHeadset(  824): Proxy object disconnected
,D/BluetoothHeadset(  824): Proxy object disconnected
D/BluetoothA2dp(  824): Proxy object disconnected
I/art     (  824): WaitForGcToComplete blocked for 86.817ms for cause Explicit
,I/art     (  824): Explicit concurrent mark sweep GC freed 3363(176KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.548ms total 57.791ms
,I/art     ( 5220): System.exit called, status: 0
I/AndroidRuntime( 5220): VM exiting with result code 0.
,D/AuthorizationBluetoothService( 1482): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPan( 4758): BluetoothPAN Proxy object disconnected,
,D/PanProfile( 4758): Bluetooth service disconnected,
D/BtGatt.DebugUtils( 3300): handleDebugAction() action=null
,D/BtGatt.GattService( 3300): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3300): stop(),
,D/BtGatt.AdvertiseManager( 3300): advertise clients cleared
,D/BluetoothPan( 1065): BluetoothPAN Proxy object disconnected
,I/ConfigService( 1482): onCreate
,W/BluetoothHidServiceJni( 3300): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3300): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3300): Cleaning up Bluetooth GID callback object
D/BluetoothMapService( 3300): Received stop request...Stopping profile...
D/BluetoothMapService( 3300): stop()
D/BluetoothMapEmailAppObserver( 3300): deinitObservers()
D/BluetoothMapEmailAppObserver( 3300): removeReceiver()
W/BluetoothHealthServiceJni( 3300): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3300): Cleaning up Bluetooth Health object
D/BluetoothMap( 1065): Proxy object disconnected
W/BluetoothPanServiceJni( 3300): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3300): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 3300): MAP Service closeService in
D/BluetoothAdapterState( 3300): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3300): Setting state to 10
I/BluetoothAdapterState( 3300): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 3300): cleanup()
D/BluetoothMapService( 3300): MAP Service closeService in
D/BluetoothManagerService(  824): Message: 60
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  824): Broadcasting onBluetoothStateChange(false) to 17 receivers.
I/BluetoothAdapterState( 3300): Entering OffState
D/BluetoothHeadset( 1065): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  824): onBluetoothStateChange: up=false
D/BluetoothA2dp(  824): onBluetoothStateChange: up=false
D/BluetoothHeadset(  824): onBluetoothStateChange: up=false
D/BluetoothMap( 1065): onBluetoothStateChange: up=false
D/BluetoothMap( 4758): Proxy object disconnected
D/MapProfile( 4758): Bluetooth service disconnected
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = user
,I/ActivityManager(  824): Start proc 5277:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1213): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1213): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1213): run()
I/StatsUtilsManager( 1213): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1213): shouldRecordStats() = Too Soon
,W/InputMethodManagerService(  824): Got RemoteException sending setActive(false) notification to pid 3245 uid 10265
,D/BluetoothInputDevice( 1065): onBluetoothStateChange: up=false
D/BluetoothMap( 4758): onBluetoothStateChange: up=false
,D/JobSchedulerService(  824): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  824): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/BluetoothAvrcpController( 1065): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1065): 
E/BluetoothAvrcpController( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@f0e907d
E/BluetoothAvrcpController( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1065): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothA2dpSink( 1065): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1065): 
E/BluetoothA2dpSink( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@16e7cb72
E/BluetoothA2dpSink( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1065): 	,at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1065): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset( 1276): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1065): onBluetoothStateChange: up=false
D/BluetoothHeadset(  824): onBluetoothStateChange: up=false
D/BluetoothPbap( 4758): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 4758): onBluetoothStateChange: up=false
,D/BluetoothHeadsetClient( 1065): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1065): 
E/BluetoothHeadsetClient( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@2cda8bc3
E/BluetoothHeadsetClient( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1065): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothManagerService(  824): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  824): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService(  824): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3ee30939 mBinding = false
,D/BluetoothManagerService(  824): Sending unbind request.
D/BluetoothManagerService(  824): Bluetooth State Change Intent: 13 -> 10
,I/Keyboard.Facilitator( 1213): onFinishInput()
,D/BluetoothAdapter( 1065): 421584616: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1065): 421584616: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1065): 421584616: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3300): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3300): GKI_exit_task 1 done
I/GKI_LINUX( 3300): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3300): cleanupNative: return from cleanup
I/art     ( 3300): System.exit called, status: 0
I/AndroidRuntime( 3300): VM exiting with result code 0, cleanup skipped.
,D/Launcher.Workspace( 1305): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1305): 11683562 - stripEmptyScreens()
,D/AndroidRuntime( 4382): Shutting down VM
,I/MusicStore( 5277): Database version: 120
,I/ActivityManager(  824): Start proc 5305:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,I/ActivityManager(  824): Process com.android.bluetooth (pid 3300) has died
,E/SharedPreferencesImpl( 4382): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,--------- beginning of crash
,E/AndroidRuntime( 4382): FATAL EXCEPTION: main
E/AndroidRuntime( 4382): Process: com.google.android.googlequicksearchbox:search, PID: 4382
E/AndroidRuntime( 4382): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 4382): 	at com.google.android.search.core.bh$2.onFailure(SearchController.java:381)
E/AndroidRuntime( 4382): 	at com.google.android.apps.gsa.shared.util.c.a.r$1.run(TaskRunnerImpl.java:329)
E/AndroidRuntime( 4382): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 4382): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4382): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4382): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4382): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4382): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4382): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 4382): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime( 4382): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime( 4382): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime( 4382): 	at com.google.android.apps.gsa.shared.util.c.d$1.call(LazyListenableFuture.java:46)
E/AndroidRuntime( 4382): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4382): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4382): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4382): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4382): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 4382): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 4382): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime( 4382): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime( 4382): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 4382): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 4382): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 4382): 	... 5 more
E/AndroidRuntime( 4382): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 4382): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime( 4382): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime( 4382): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime( 4382): 	... 9 more
E/AndroidRuntime( 4382): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 4382): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime( 4382): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime( 4382): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime( 4382): 	... 11 more
,E/SQLiteDatabase( 1482): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1482): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1482): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1482): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1482): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1482): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1482): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1482): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1482): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1482): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1482): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1482): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1482): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1482): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1482): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1482): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1482): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1482): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1482): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1482): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1482): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1482): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1482): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1482): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1482): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1482): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1482): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1482): 	at android.databa,se.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1482): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1482): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1482): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1482): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1482): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1482): Opened phenotype.db in read-only mode
E/SQLiteLog( 1482): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1482): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1482): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1482): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1482): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1482): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1482): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1482): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1482): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  824): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  824): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  824): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  824): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  824): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  824): 	... 5 more
E/ClearcutLoggerIntentService( 1482): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1482): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1482): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1482): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1482): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1482): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1482): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1482): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1482): 	at java.lang.Thread.run(Thread.java:818)
I/art     ( 1305): Explicit concurrent mark sweep GC freed 17561(901KB) AllocSpace objects, 12(1408KB) LOS objects, 30% free, 35MB/51MB, paused 1.196ms total 29.167ms
D/OpenGLRenderer(  824): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  824): Validating map...
,I/OpenGLRenderer(  824): Initialized EGL, version 1.4
D/OpenGLRenderer(  824): Enabling debug mode 0
,W/ResourcesManager( 5277): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5277): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/GFEEDBACK_SendErrorReportOperation( 1787): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 1787): Error saving report: java.io.IOException: failed to create reports directory
,V/JNIHelp ( 5277): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 5277): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5277): GMSCore installation verified
,I/ConfigStore( 5277): Config Database version: 1,
,E/SQLiteDatabase( 5277): Failed to open database '/data/data/com.google.android.music/databases/config.db'.,
E/SQLiteDatabase( 5277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5277): ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5277): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5277): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5277): 	at com.google.android.music.store.ConfigStore.getDatabase(ConfigStore.java:64)
E/SQLiteDatabase( 5277): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 5277): 	at com.google.android.music.store.ConfigContentProvider.query(ConfigContentProvider.java:129)
E/SQLiteDatabase( 5277): 	at android.content.ContentProvider.query(ContentProvider.java:966,)
E/SQLiteDatabase( 5277): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 5277): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 5277): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 5277): 	at com.google.android.music.utils.ConfigCache.get(ConfigCache.java:136)
E/SQLiteDatabase( 5277): 	at com.google.android.music.utils.ConfigUtils.getString(ConfigUtils.java:673)
E/SQLiteDatabase( 5277): 	at com.google.android.music.utils.ConfigUtils.getBoolean(ConfigUtils.java:709)
E/SQLiteDatabase( 5277): 	at com.google.android.music.utils.ConfigUtils.isPlayLoggingEnabled(ConfigUtils.java:399)
E/SQLiteDatabase( 5277): 	at com.google.android.music.eventlog.MusicEventLogger.<init>(MusicEventLogger.java:152)
E/SQLiteDatabase( 5277): 	at com.google.android.music.eventlog.MusicEventLogger.getInstance(MusicEventLogger.java:270)
E/SQLiteDatabase( 5277): 	at com.google.android.music.MusicApplication.onCreate(MusicApplication.java:87)
E/SQLiteDatabase( 5277): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
E/SQLiteDatabase( 5277): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
E/SQLiteDatabase( 5277): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
E/SQLiteDatabase( 5277): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
E/SQLiteDatabase( 5277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5277): ,	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5277): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 5277): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5277): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5277): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 5277): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/AndroidRuntime( 5277): Shutting down VM
E/AndroidRuntime( 5277): FATAL EXCEPTION: main
E/AndroidRuntime( 5277): Process: com.google.android.music:main, PID: 5277
E/AndroidRuntime( 5277): java.lang.RuntimeException: Unable to create application com.google.android.music.MusicApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5277): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4556)
E/AndroidRuntime( 5277): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
E/AndroidRuntime( 5277): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
E/AndroidRuntime( 5277): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5277): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5277): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 5277): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5277): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5277): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 5277): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,E/AndroidRuntime( 5277): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 5277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 5277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 5277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5277): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5277): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5277): 	at com.google.android.music.store.ConfigStore.getDatabase(ConfigStore.java:64)
E/AndroidRuntime( 5277): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 5277): ,	at com.google.android.music.store.ConfigContentProvider.query(ConfigContentProvider.java:129)
E/AndroidRuntime( 5277): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AndroidRuntime( 5277): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AndroidRuntime( 5277): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/AndroidRuntime( 5277): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/AndroidRuntime( 5277): 	at com.google.android.music.utils.ConfigCache.get(ConfigCache.java:136)
E/AndroidRuntime( 5277): 	at com.google.android.music.utils.ConfigUtils.getString(ConfigUtils.java:673)
E/AndroidRuntime( 5277): 	at com.google.android.music.utils.ConfigUtils.getBoolean(ConfigUtils.java:709)
E/AndroidRuntime( 5277): 	at com.google.android.music.utils.ConfigUtils.isPlayLoggingEnabled(ConfigUtils.java:399)
E/AndroidRuntime( 5277): 	at com.google.android.music.eventlog.MusicEventLogger.<init>(MusicEventLogger.java:152)
E/AndroidRuntime( 5277): 	at com.google.android.music.eventlog.MusicEventLogger.getInstance(MusicEventLogger.java:270)
E/AndroidRuntime( 5277): 	at com.google.android.music.MusicApplication.onCreate(MusicApplication.java:87)
E/AndroidRuntime( 5277): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
E/AndroidRuntime( 5277): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
E/AndroidRuntime( 5277): 	... 9 more
,E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  824): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  824): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  824): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  824): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  824): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  824): 	... 5 more

```
