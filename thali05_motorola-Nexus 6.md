#### Test 52539314a265f91_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2705): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2705): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2705): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3168): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3168): CheckJNI is OFF
D/AndroidRuntime( 3168): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{3aaf08f token=Token{2312d3ee ActivityRecord{66ebd69 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
V/WindowManager(  821): Adding window Window{ffd2108 u0 Starting com.test.thalitest} at 3 of 8 (after Window{33f8d077 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1523): Closing mic
I/MicrophoneInputStream( 1523): mic_close com.google.android.apps.gsa.speech.audio.u@1bcdecc1
D/AndroidRuntime( 3168): Shutting down VM
I/ActivityManager(  821): Start proc 3182:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1523): Hotword detection finished
I/HotwordRecognitionRnr( 1523): Stopping hotword detection.
W/GCoreFlp( 1751): No location to return for getLastLocation()
I/ActivityManager(  821): Killing 2664:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1702135059
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/ActivityManager(  821): Killing 2796:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/WebViewFactory( 3182): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3182): Time to load native libraries: 1 ms (timestamps 4712-4713)
I/LibraryLoader( 3182): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3182): Binding Chromium to main looper Looper (main, tid 1) {1f24e555},
I/LibraryLoader( 3182): Expected native library version number "",actual native library version number "",
I/chromium( 3182): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3182): Initializing chromium process, singleProcess=true
,W/art     ( 3182): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3182): ApplicationContext is null in ApplicationStatus
,W/chromium( 3182): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3182): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3182): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 3182): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3182): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ebedc38:true
,D/BluetoothAdapter( 3182): 989728567: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3182): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3182): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3182): CordovaWebView is running on device made by: motorola
,W/art     ( 3182): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3182): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3182): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3182): Validating map...
,V/WindowManager(  821): Adding window Window{bdc368 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{ffd2108 u0 Starting com.test.thalitest})
,W/chromium( 3182): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  821): Explicit concurrent mark sweep GC freed 19093(920KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.653ms total 93.785ms
,I/OpenGLRenderer( 3182): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3182): Enabling debug mode 0,
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +1s185ms (total +2m2s580ms)
,I/Keyboard.Facilitator( 1198): onFinishInput()
,W/BindingManager( 3182): Cannot call determinedVisibility() - never saw a connection for the pid: 3182
,I/kickstart(  871): STATUS: Received file 'm9kefs2'
I/kickstart(  871): STATUS: 950272 bytes transferred in 0.981803 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed
,D/JsMessageQueue( 3182): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3182): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576265984
,D/JX-Cordova( 3182): jxcore cordova android initializing
,W/jxcore-log( 3182): Initializing JXcore engine
W/jxcore-log( 3182): JXcore engine is ready
,W/jxcore-log( 3182): Starting JXcore engine
,W/.test.thalitest( 3182): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12908]" dev="sockfs" ino=12908 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3182): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3182): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10935]" dev="sockfs" ino=10935 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3182): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19073]" dev="sockfs" ino=19073 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3182): Platform android
W/jxcore-log( 3182): 
W/jxcore-log( 3182): Process ARCH arm
W/jxcore-log( 3182): 
,I/jxcore-log( 3182): JXcore Cordova bridge is ready!
I/jxcore-log( 3182): 
W/jxcore-log( 3182): JXcore engine is started
I/Choreographer( 3182): Skipped 137 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3182): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3182): Toggling radios to true
I/jxcore-log( 3182): 
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  821): Message: 1
D/BluetoothManagerService(  821): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  821): setWifiEnabled: true pid=3182, uid=10265
D/WifiService(  821): New client listening to asynchronous messages
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  355): Softap fwReload - Ok
,I/jxcore-log( 3182): Radios toggled
I/jxcore-log( 3182): 
,D/CommandListener(  355): Setting iface cfg
D/CommandListener(  355): Trying to bring down wlan0
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  821): Start proc 3240:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,W/ResourcesManager( 3240): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/WifiMonitor(  821): startMonitoring(wlan0) with mConnected = false
E/WifiHW  (  821): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/ActivityManager(  821): Start proc 3258:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/wpa_supplicant( 3257): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3257): rfkill: Cannot open RFKILL control device
,D/AdapterServiceConfig( 3240): Adding HeadsetService
,D/AdapterServiceConfig( 3240): Adding A2dpService
D/AdapterServiceConfig( 3240): Adding HidService
,D/AdapterServiceConfig( 3240): Adding HealthService
D/AdapterServiceConfig( 3240): Adding PanService
D/AdapterServiceConfig( 3240): Adding GattService
D/AdapterServiceConfig( 3240): Adding BluetoothMapService
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9f1b075:true
D/BluetoothAdapterState( 3240): make
,I/bluedroid( 3240): init
I/BluetoothAdapterState( 3240): Entering OffState
,I/bte_conf( 3240): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3240): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3240): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3240): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3240): get_profile_interface socket
I/bluedroid( 3240): get_profile_interface map_client
I/GKI_LINUX( 3240): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3240): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6
,D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3240): Name is: Nexus 6
D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  821): Message: 40
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3240): config_hci_snoop_log
,D/BluetoothManagerService(  821): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  821): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3240): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON,
D/BluetoothAdapterProperties( 3240): Setting state to 11
I/BluetoothAdapterState( 3240): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  821): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3240): make
,I/BluetoothBondStateMachine( 3240): StableState(): Entering Off State
,D/BluetoothAdapterService( 3240): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3553bb6a
,D/HeadsetService( 3240): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3240): classInitNative: succeeds
D/HeadsetStateMachine( 3240): make
,I/ActivityManager(  821): Start proc 3291:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  821): Killing 2828:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/HeadsetStateMachine( 3240): max_hf_connections = 1
I/bluedroid( 3240): get_profile_interface handsfree
,D/HeadsetStateMachine( 3240): Enter Disconnected: -2, size: 0
,I/BluetoothAdapterState( 3240): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3240): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3553bb6a
,D/BluetoothA2dp( 1063): Proxy object connected
D/A2dpService( 3240): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3240): classInitNative: succeeds
D/BluetoothA2dp(  821): Proxy object connected
,I/bluedroid( 3240): get_profile_interface avrcp
,E/RemoteController( 3240): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3240): classInitNative: succeeds
D/A2dpStateMachine( 3240): make
I/bluedroid( 3240): get_profile_interface a2dp
I/GKI_LINUX( 3240): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/A2dpStateMachine( 3240): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3240): classInitNative: succeeds
,D/BluetoothAdapterService( 3240): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3553bb6a
,D/BluetoothInputDevice( 1063): Proxy object connected
D/HidService( 3240): Received start request. Starting profile...
I/bluedroid( 3240): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3240): classInitNative: succeeds
D/BluetoothAdapterService( 3240): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3553bb6a
,D/HealthService( 3240): Received start request. Starting profile...
I/bluedroid( 3240): get_profile_interface health
I/BluetoothPanServiceJni( 3240): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3240): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3553bb6a
,D/BluetoothPan( 1063): BluetoothPAN Proxy object connected
D/PanService( 3240): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3240): initializeNative(L110): pan
I/bluedroid( 3240): get_profile_interface pan
,D/HeadsetStateMachine( 3240): Proxy object connected
I/BtGatt.JNI( 3240): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3240): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3553bb6a
D/BtGatt.DebugUtils( 3240): handleDebugAction() action=null
D/BtGatt.GattService( 3240): Received start request. Starting profile...
D/BtGatt.GattService( 3240): start()
I/bluedroid( 3240): get_profile_interface gatt
D/BluetoothAdapterService( 3240): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3553bb6a
D/BtGatt.AdvertiseManager( 3240): advertise manager created
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3240): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3240): Disconnected process message: 11, size: 0
D/BluetoothAdapterService( 3240): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3553bb6a
,D/BluetoothMap( 1063): Proxy object connected
,D/BluetoothMapService( 3240): Received start request. Starting profile...
,D/BluetoothMapService( 3240): start(),
,D/BluetoothMapEmailSettingsLoader( 3240): Found 0 applications
D/BluetoothMapEmailAppObserver( 3240): createReceiver()
D/BluetoothMapEmailAppObserver( 3240): initObservers()
D/BluetoothMapEmailAppObserver( 3240): getEnabledAccountItems()
D/BluetoothAdapterState( 3240): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3240): enable
I/GKI_LINUX( 3240): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3240): btu_task pending for preload complete event
I/bt_hci_bdroid( 3240): init
,I/bt_vendor( 3240): init
I/bt_vnd_conf( 3240): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,I/bt_vnd_conf( 3240): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3240): userial_init
,I/bt_userial_vendor( 3240): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3240): device fd = 53 open
D/bt_userial( 3240): Entering userial_read_thread()
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 22263(1150KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.486ms total 34.720ms
,I/bt_hwcfg( 3240): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3240): Chipset BCM4354A2
D/bt_hwcfg( 3240): Target name = [BCM4354A2]
I/bt_hwcfg( 3240): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/ActivityManager(  821): Start proc 3326:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/art     (  370): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 11.468ms
,I/ActivityManager(  821): Killing 2765:com.google.android.gm/u0a78 (adj 15): empty #17
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 10.538ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 220us total 9.447ms
,D/Tethering(  821): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3257): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant( 3257): Could not read interface p2p-dev-wlan0 flags: No such device
,I/ActivityManager(  821): Killing 2355:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/bt_hwcfg( 3240): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3240): Settlement delay -- 100 ms
I/bt_hwcfg( 3240): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3240): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3240): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3240): vendor lib fwcfg completed
I/bt-btu  ( 3240): btu_task received preload complete event
I/        ( 3240): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3240): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3240): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3240): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3240): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3240): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3240): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3240): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3240): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3240): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3240): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3240): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3240): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3240): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3240): BTE_InitTraceLevels -- TRC_BTIF
,D/WifiConfigStore(  821): Loading config and enabling all networks 
,E/WifiConfigStore(  821): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  821): Start proc 3344:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/WifiNative-HAL(  821): Setting external_sim to 1
W/Settings( 2626): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  821): Setting OUI to 92-68-C3
I/WifiNative-HAL(  821): startHal
D/wifi    (  821): setting scan oui 0xaec78d30
D/WifiHAL (  821): Sending mac address OUI
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1ef2120d}
,E/WifiStateMachine(  821): cancelDelayedScan -> 1
,W/CommandListener(  355): Failed to retrieve HW addr for p2p0 (No such device)
D/CommandListener(  355): Setting iface cfg
E/WifiP2pService(  821): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  821): startMonitoring(p2p0) with mConnected = true
,D/WifiScanningService(  821): SCAN_AVAILABLE : 3
D/RttService(  821): SCAN_AVAILABLE : 3
D/WifiScanningService(  821): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  821): startHal
D/wifi    (  821): getting scan capabilities on interface[0] = 0xaec78d30
D/WifiHAL (  821): Creating message to get scan capablities; iface = 5
D/WifiHAL (  821): In GetCapabilities::handleResponse
D/WifiHAL (  821): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  821): StartedState
D/RttService(  821): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-HAL(  821): p2pGetDeviceAddress
,D/WifiNative-HAL(  821): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 3257): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/native  (  821): do suspend false
,E/bt-btm  ( 3240): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e0c085 
E/bt-btm  ( 3240): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e0c085 
,D/BluetoothAdapterProperties( 3240): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3240): Calling BTA_HhEnable
E/bt-btif ( 3240): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3240): Address is:F8:CF:C5:D9:E5:61
D/BluetoothAdapterProperties( 3240): Name is: Nexus 6
D/BluetoothAdapterProperties( 3240): Scan Mode:20
D/BluetoothAdapterProperties( 3240): Discoverable Timeout:120
,D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
D/bte_conf( 3240): Device ID record 1 : primary
D/bte_conf( 3240):   vendorId            = 000f
D/bte_conf( 3240):   vendorIdSource      = 0001
D/bte_conf( 3240):   product             = 1200
D/bte_conf( 3240):   version             = 1436
D/bte_conf( 3240):   clientExecutableURL = 
D/bte_conf( 3240):   serviceDescription  = 
D/bte_conf( 3240):   documentationURL    = 
D/bte_conf( 3240): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3240): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3240): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 3240): ScanMode =  20
D/BluetoothAdapterProperties( 3240): State =  11
D/BluetoothAdapterProperties( 3240): Setting state to 12
I/BluetoothAdapterState( 3240): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  821): Broadcasting onBluetoothStateChange(true) to 13 receivers.
I/BluetoothAdapterState( 3240): Entering On State
D/BluetoothAdapterProperties( 3240): Scan Mode:21
D/BluetoothAdapterProperties( 3240): Discoverable Timeout:120
D/BluetoothHeadset( 1063): onBluetoothStateChange: up=true
E/bt_h4   ( 3240): vendor lib postload completed
,D/BluetoothManagerService(  821): Creating new ProfileServiceConnections object for profile: 1
W/bt-btm  ( 3240): Stopping oneshot timer
,D/BluetoothPan( 1063): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadsetClient( 1063): onBluetoothStateChange: up=true
E/BluetoothHeadsetClient( 1063): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1272): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 1063): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1063): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothA2dp(  821): onBluetoothStateChange: up=true
D/BluetoothA2dpSink( 1063): onBluetoothStateChange: up=true
,E/BluetoothA2dpSink( 1063): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothMap( 1063): onBluetoothStateChange: up=true
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
,D/BluetoothAvrcpController( 1063): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1063): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
,D/BluetoothManagerService(  821): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothMapService( 3240): onReceive
D/BluetoothMapService( 3240): STATE_ON
,D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapMasInstance( 3240): Map Service startRfcommSocketListener
,W/bt-btm  ( 3240): Stopping oneshot timer
D/BluetoothManagerService(  821): Message: 40
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapMasInstance( 3240): MAS initSocket()
W/bt-btm  ( 3240): Stopping oneshot timer
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3240): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-btm  ( 3240): Stopping oneshot timer
,D/BluetoothMapMasInstance( 3240): Accepting socket connection...
,W/bt-btm  ( 3240): Stopping oneshot timer
,W/bt-btm  ( 3240): Stopping oneshot timer
,W/bt-btm  ( 3240): Stopping oneshot timer
,D/StrictMode( 3344): StrictMode policy violation; ~duration=201 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3344): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3344): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3344): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3344): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3344): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3344): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3344): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3344): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3344): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3344): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3344): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3344): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3344): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3344): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3344): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3344): StrictMode policy violation; ~duration=201 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3344): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3344): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3344): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3344): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3344): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3344): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3344): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3344): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3344): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3344): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3344): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3344): StrictMode policy violation; ~duration=199 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3344): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3344): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3344): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3344): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3344): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3344): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3344): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3344): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3344): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3344): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3344): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3344): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3344): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3344): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3344): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3344): StrictMode policy violation; ~duration=195 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3344): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3344): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3344): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3344): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3344): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3344): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3344): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3344): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3344): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3344): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3344): StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3344): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3344): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3344): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3344): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3344): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoade,r.java:77)
D/StrictMode( 3344): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3344): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3344): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3344): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3344): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3344): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3344): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3344): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3344): StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3344): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3344): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3344): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3344): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3344): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3344): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3344): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3344): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3344): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3344): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3344): # via Binder call with stack:
D/StrictMode( 3344): android.os.StrictMode$LogStackTrace
D/StrictMode( 3344): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3344): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3344): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3344): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3344): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3344): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3344): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3344): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3344): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3344): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java,:1012)
D/StrictMode( 3344): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3344): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3344): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3344): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3344): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3344): StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3344): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3344): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3344): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3344): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3344): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3344): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3344): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3344): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3344): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3344): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3344): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3344): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3344): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3344): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3344): StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3344): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3344): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3344): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3344): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3344): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3344): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication,.onCreate(PG:84)
D/StrictMode( 3344): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3344): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3344): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3344): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3344): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3344): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3344): StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3344): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3344): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3344): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3344): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3344): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3344): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3344): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3344): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3344): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3344): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3344): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3344): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3344): StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3344): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3344): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3344): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3344): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3344): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3344): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3344): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3344): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3344): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3344): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3344): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3344): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3344): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3344): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3344): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3344): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3344): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3344): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3344): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3344): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3344): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 3344): Application name is not set. Call Builder#setApplicationName.
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6ff0ee6:true
I/ActivityManager(  821): Killing 2864:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset( 1063): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset( 1272): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
,D/AuthorizationBluetoothService( 1401): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12d6db58:true
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3240): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1401): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LocalBluetoothProfileManager( 3326): Adding local A2DP profile
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3240): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  821): Message: 30
,I/BtOppRfcommListener( 3240): Accept thread started.
,D/LocalBluetoothProfileManager( 3326): Adding local HEADSET profile
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3326): Adding local MAP profile
,D/BluetoothMap( 3326): Create BluetoothMap proxy object
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3326): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3326): finishStartingService: stopping service
,D/BluetoothA2dp( 3326): Proxy object connected
,D/A2dpProfile( 3326): Bluetooth service connected
,D/BluetoothInputDevice( 3326): Proxy object connected
D/HidProfile( 3326): Bluetooth service connected
,D/BluetoothPan( 3326): BluetoothPAN Proxy object connected
,D/PanProfile( 3326): Bluetooth service connected
D/BluetoothMap( 3326): Proxy object connected
D/MapProfile( 3326): Bluetooth service connected
D/BluetoothMap( 3326): getConnectedDevices()
,D/BluetoothPbap( 3326): Proxy object connected
,D/PbapServerProfile( 3326): Bluetooth service connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 3326): Proxy object connected,
,D/HeadsetProfile( 3326): Bluetooth service connected,
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/jxcore-log( 3182): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): my name is : motorola-Nexus 6_PT8001
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): attempting to connect to test coordinator
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): check test folder
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): found test : ./testFindPeers.js
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): found test : ./testReConnect.js
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): found test : ./testSendData.js
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): Test app app.js loaded
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
I/Choreographer( 3182): Skipped 131 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3182): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3257): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  821):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  821):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  821): will read network variables netId=0
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,I/wpa_supplicant( 3257): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3257): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/wpa_supplicant( 3257): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3257): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 1
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 1
E/WifiStateMachine(  821):  RSSI mgmt: -47
E/WifiStateMachine(  821):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 0 tx_time=57 rx_time=41 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 3386): version 5.5.6 starting
,I/dhcpcd  ( 3386): wlan0: rebinding lease of 192.168.1.110
,I/dhcpcd  ( 3386): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 3386): wlan0: leased 192.168.1.110 for 86400 seconds
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 100
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  821): Setting Dns servers for network 100 to [/192.168.1.1]
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Connected
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} },
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524290
,D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
D/Tethering(  821): MasterInitialState.processMessage what=3
,V/BackupManagerService(  821): Scheduling immediate backup pass
,I/ActivityManager(  821): Start proc 3426:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,E/GpsLocationProvider(  821): No APN found to select.
,V/BackupManagerService(  821): Running a backup pass
V/BackupManagerService(  821): clearing pending backups
,V/PerformBackupTask(  821): Beginning backup of 14 targets
,D/PerformBackupTask(  821): invokeAgentForBackup on @pm@
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Dec 2015 08:05:15 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449216315127], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449216315106]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/AlarmManagerService(  821): Setting time of day to sec=1449216315
,W/AlarmManagerService(  821): Unable to set rtc to 1449216315: Invalid argument
D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524290
,V/BackupServiceBinder(  821): doBackup() invoked
,I/PMBA    (  821): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/GpsLocationProvider(  821): NTP server returned: 1449216315943 (Fri Dec 04 09:05:15 GMT+01:00 2015) reference: 162806 certainty: 19 system time offset: -1
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/MusicStore( 3426): Database version: 120
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/GoogleURLConnFactory( 1401): Using platform SSLCertificateSocketFactory
,I/BackupRestoreController(  821): Getting widget state for user: 0
,E/Auth.Api.Credentials( 1779): [CredentialSyncAdapter] Unknown sync event.
,D/PermissionCache(  261): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1215 us)
,I/art     (  821): Explicit concurrent mark sweep GC freed 50297(2MB) AllocSpace objects, 6(137KB) LOS objects, 32% free, 33MB/49MB, paused 1.759ms total 79.001ms
,W/GmsBackupTransport( 1751): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1751): starting performBackup for @pm@
,V/GmsBackupTransport( 1751): performBackup done for @pm@
,W/DriveInitializer( 1779): Background init thread started
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DriveInitializer( 1779): Awaiting to be initialized
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 10632(570KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 1.190ms total 34.138ms
,W/DriveInitializer( 1779): Background init thread ended
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1401): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1401): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1401): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1401): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1401): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1401): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1401): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1751): Error sending final backup to server: 
W/GmsBackupTransport( 1751): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1751): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1751): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1751): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1751): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1751): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1751): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1751): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1751): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1751): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1751): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1751): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1751): 	... 1 more
,D/BackupManagerService(  821): Now staging backup of com.google.android.talk
,W/ResourcesManager( 3426): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3426): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BackupManagerService(  821): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  821): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  821): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  821): Now staging backup of com.google.android.gm
,D/BackupManagerService(  821): Now staging backup of com.android.providers.userdictionary
,V/JNIHelp ( 3426): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/BackupManagerService(  821): Now staging backup of com.android.nfc
,D/BackupManagerService(  821): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  821): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  821): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  821): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  821): Now staging backup of com.android.vending
,D/BackupManagerService(  821): Now staging backup of android
,D/BackupManagerService(  821): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1751): Next backup will happen in 43199911 millis.
,I/BackupManagerService(  821): Backup pass finished.
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProviderInstaller( 3426): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3426): GMSCore installation verified
E/HttpOperation( 2951): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at blb.a(PG:3937)
E/HttpOperation( 2951): 	at czp.a(PG:18188)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 12 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 14 more
,I/ConfigStore( 3426): Config Database version: 1
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/KeepSync( 3291): Connecting to GoogleApiClient
,I/ActivityManager(  821): Start proc 3488:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,W/BaseAppContext( 1779): Using Auth Proxy for data requests.
,E/HttpOperation( 2951): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at hec.a(PG:42)
E/HttpOperation( 2951): 	at hee.a(PG:102)
E/HttpOperation( 2951): 	at czr.a(PG:65)
E/HttpOperation( 2951): 	at kka.a(PG:108)
E/HttpOperation( 2951): 	at czp.a(PG:19176)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 15 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 17 more
,E/ExperimentLoader( 2951): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): 	at jdm.a(PG:82)
E/ExperimentLoader( 2951): 	at jcs.o(PG:406)
E/ExperimentLoader( 2951): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2951): 	at jcs.i(PG:143)
E/ExperimentLoader( 2951): 	at hec.a(PG:42)
E/ExperimentLoader( 2951): 	at hee.a(PG:102)
E/ExperimentLoader( 2951): 	at czr.a(PG:65)
E/ExperimentLoader( 2951): 	at kka.a(PG:108)
E/ExperimentLoader( 2951): 	at czp.a(PG:19176)
E/ExperimentLoader( 2951): 	at czp.a(PG:9081)
E/ExperimentLoader( 2951): 	at czq.run(PG:1686)
E/ExperimentLoader( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2951): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2951): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2951): 	at jdm.a(PG:77)
E/ExperimentLoader( 2951): 	... 15 more
E/ExperimentLoader( 2951): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2951): 	at fal.a(PG:38)
E/ExperimentLoader( 2951): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2951): 	... 17 more
,W/BaseAppContext( 1779): Using Auth Proxy for data requests.,
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  821): Display changed displayId=0
D/SurfaceFlinger(  261): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  261): hwc_setPowerMode: Setting mode 0 on display: 0
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ResourcesManager( 3488): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3488): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MediaRouter( 3426): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3426): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 3291): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
,V/JNIHelp ( 3488): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
,I/NetworkMonitor( 3426): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 3426): type=WIFI subType= reason=null isConnected=true
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 36908, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ProviderInstaller( 3488): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  821): Start proc 3520:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/ActivityManager(  821): Start proc 3542:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/dex2oat ( 3540): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads2020949800.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads2020949800.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/SprintDMReceiver( 3520): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/YouTube MDX( 3488): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/GHttpClientFactory( 3426): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3426): Using platform SSLCertificateSocketFactory
,D/SprintDMHelper( 3520): simOperator:  IMSI: null
D/SprintDMReceiver( 3520): Not Sprint UICC, don't do anything.
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/dex2oat ( 3540): dex2oat took 44.922ms (threads: 4) arena alloc=176KB java alloc=12KB native alloc=1091KB free=6MB
,I/qdhwcomposer(  261): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  261): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  821): Excessive delay in setPowerMode(): 248ms
,I/DreamManagerService(  821): Entering dreamland.
I/PowerManagerService(  821): Dozing...
I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
,I/SystemUpdateService( 1779): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1779): onCreate
,D/SystemUpdateService( 1779): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/WifiStateMachine(  821): cancelDelayedScan -> 5
,I/SystemUpdateService( 1779): active receiver: enabled
,E/native  (  821): do suspend false
,I/CheckinService( 1779): Checking schedule, now: 1449216316810 next: 1449214176801
I/CheckinService( 1779): active receiver: enabled
,I/CheckinService( 1779): Preparing to send checkin request
I/EventLogService( 1779): Accumulating logs since 1449215327119
,I/SystemUpdateService( 1779): showing system update notification
,I/iu.SyncManager( 1779): SYNC; picasa accounts
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1779): retry (wakeup: false) in 3599946 ms
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 25977(1258KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.245ms total 49.773ms
,D/NetworkLogImpl( 1779): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1779): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=35.31 rxSuccessRate=33.62 targetRoamBSSID=any RSSI=-48
,D/SystemUpdateService( 1779): onDestroy
,I/EventLogService( 1779): Opted in for usage reporting
,I/iu.UploadsManager( 1779): num queued entries: 0
,I/iu.UploadsManager( 1779): num updated entries: 0
I/Keyboard.Facilitator( 1198): onFinishInput()
I/iu.SyncManager( 1779): NEXT; no task
,E/WifiStateMachine(  821): cancelDelayedScan -> 7
E/native  (  821): do suspend true
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,I/ActivityManager(  821): Start proc 3600:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,W/InstanceID/Rpc( 3488): Found 10011
,E/KeepSync( 3291): IOException
E/KeepSync( 3291): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3291): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3291): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3291): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3291): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3291): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3291): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3291): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3291): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3291): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3291): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3291): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3291): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3291): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3291): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3291): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3291): 	... 10 more
W/KeepSync( 3291): Sync result 2
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1779): [AccountUtils] Account not ready
W/Kids    ( 1779): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1779): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1779): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1779): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1779): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1779): 	at java.lang.Thread.run(Thread.java:818)
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 36910, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/EventLogAggregator( 1779): Unknown tag: snet_gcore
W/EventLogAggregator( 1779): Unknown tag: snet_launch_service
,I/CheckinRequestBuilder( 1779): Checkin reason type: 12 attempt count: 1
,I/GAv4    ( 3600): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3600):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3600):   adb logcat -s GAv4
D/WifiService(  821): New client listening to asynchronous messages
,E/ActivityThread( 1779): Failed to find provider info for com.google.android.wearable.settings
,W/GAv4    ( 3600): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3600): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3600): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 2626): connection state changed from DISCONNECTED to CONNECTED
,I/ActivityManager(  821): Killing 2204:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 31306(1748KB) AllocSpace objects, 2(55KB) LOS objects, 37% free, 26MB/42MB, paused 3.460ms total 54.874ms
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,W/GAV2    ( 3542): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3542): Created application version: 3.6.8 (30608)
,V/GoogleAuthProtoRequest( 3258): [331] a.<init>: mAccountName set to: thalitester@gmail.com
,I/BooksSync( 3542): Starting books sync for 61035162, extras: ade
,I/art     ( 1779): Explicit concurrent mark sweep GC freed 13181(1079KB) AllocSpace objects, 15(240KB) LOS objects, 35% free, 29MB/45MB, paused 4.587ms total 52.415ms
,I/WebViewFactory( 3600): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/GCM     ( 1401): Connected
,I/LibraryLoader( 3600): Time to load native libraries: 1 ms (timestamps 4327-4328)
,I/LibraryLoader( 3600): Expected native library version number "",actual native library version number ""
,D/GCM     ( 1401): Message class com.google.f.a.a.p
V/WebViewChromiumFactoryProvider( 3600): Binding Chromium to main looper Looper (main, tid 1) {25a5c21e}
,I/LibraryLoader( 3600): Expected native library version number "",actual native library version number ""
,I/chromium( 3600): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3600): Initializing chromium process, singleProcess=true
,W/art     ( 3600): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3600): ApplicationContext is null in ApplicationStatus
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 3600): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3600): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3600): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3600): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/ExperimentUpdateService( 3258): [331] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3258): [331] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3258): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3258): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3258): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3258): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3258): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3258): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3258): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3258): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3258): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3258): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AudioManagerAndroid( 3600): Requires BLUETOOTH permission
,I/NSApplication( 3600): Starting up...
,I/ActivityManager(  821): Killing 1362:android.process.acore/u0a5 (adj 15): empty #17
,W/CheckinRequestBuilder( 1779): awaiting user notification for token
,I/BooksConfig( 3542): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  821): Start proc 3717:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,W/ResourcesManager( 3717): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3717): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  821): Explicit concurrent mark sweep GC freed 21208(905KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.658ms total 75.699ms
,I/MultiDex( 3717): VM with version 2.1.0 has multidex support
I/MultiDex( 3717): install
I/MultiDex( 3717): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  821): Start proc 3737:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  821): Killing 3063:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,V/JNIHelp ( 3717): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/jxcore-log( 3182): BLE supported!!
I/jxcore-log( 3182): 
,I/ProviderInstaller( 3717): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1401): Vacuum at: now=1449216318276 tag=VacuumService
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Ads     ( 1779): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,E/BooksAccountManager( 3542): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3542): Soft error
E/BooksSync( 3542): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3542): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3542): Sync error
E/BooksSync( 3542): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3542): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3542): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36911, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Killing 3084:com.android.musicfx/u0a18 (adj 15): empty #17
,D/WVCdm   (  359): Instantiating CDM.
,I/WVCdm   (  359): CdmEngine::OpenSession
I/WVCdm   (  359): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  359): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  359): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  359): Service_Initialize: starts!
D/QSEECOMAPI: (  359): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  359): App is not loaded in QSEE
,I/GoogleURLConnFactory( 3717): Using platform SSLCertificateSocketFactory
,D/QSEECOMAPI: (  359): Loaded image: APP id = 3
,D/DrmWidevineDash(  359): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b90000
E/DrmWidevineDash(  359): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b90000
,D/DrmLibTime(  317): got the req here! ret=0
D/DrmLibTime(  317): command id, time_cmd_id = 770
D/DrmLibTime(  317): time_getutcsec starts!
D/DrmLibTime(  317): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  317): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  317): QSEE Time Listener: seconds: 1449216318
D/DrmLibTime(  317): QSEE Time Listener: nano seconds: 713522915
D/DrmLibTime(  317): time_getutcsec returns 0, sec = 1449216318; nsec = 713522915
D/DrmLibTime(  317): time_getutcsec finished! 
D/DrmLibTime(  317): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  317): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  359): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  359): hlos api version =  9
D/DrmWidevineDash(  359): tz api version =  9
,D/DrmWidevineDash(  359): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  359): OEMCrypto_IsKeyboxValid: starts!
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1ef2120d}
,D/DrmWidevineDash(  359): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  359): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  359): OEMCrypto_OpenSession: starts! SID=0xb3e03940
D/DrmWidevineDash(  359): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  359): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_GetRandom: starts! randomData=0xb58765b0, dataLength=8
,D/DrmWidevineDash(  359): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  359): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4082000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  359): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  359): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  359): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  359): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  359): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  359): OEMCrypto_GetDeviceID: starts! deviceID=0xb583d340, idLength=0xb2f5d710
,D/DrmWidevineDash(  359): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  359): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  359): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  359): hlos api version =  9
D/DrmWidevineDash(  359): tz api version =  9
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  359): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  359): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  359): PrepareKeyRequest: nonce=3550430719
D/DrmWidevineDash(  359): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4d0e600
D/DrmWidevineDash(  359): message_length=1599, signature=0xb4c53cc0, signature_length=3002455796
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/GoogleURLConnFactory( 1401): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  359): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  359): CdmEngine::CloseSession
D/DrmWidevineDash(  359): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  359): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  359): L3 Terminate.
D/DrmWidevineDash(  359): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  359): Service_Uninitialize: starts!
D/QSEECOMAPI: (  359): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  359): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  359): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  359): OEMCrypto_Terminate: ends! returns 0
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1401): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1401): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1401): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1401): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  821): Killing 1806:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3764:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,V/Herrevad( 1779): NQAS connected
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 3764): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 32274(1795KB) AllocSpace objects, 10(914KB) LOS objects, 37% free, 26MB/42MB, paused 1.110ms total 35.798ms
,E/Uploader( 1401): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1401): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1401): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1401): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  821): Start proc 3787:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3787): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/dex2oat ( 3806): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/CalendarProvider2( 3787): Created com.android.providers.calendar.CalendarAlarmManager@24f8280c(com.android.providers.calendar.CalendarProvider2@1f24e555)
,W/Uploader( 1401): No account for auth token provided
,I/dex2oat ( 3806): dex2oat took 34.417ms (threads: 4) arena alloc=121KB java alloc=18KB native alloc=1119KB free=6MB
,I/Adreno  ( 3717): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/ActivityManager(  821): Start proc 3816:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3764): PlayLogger.onLoggerConnected
,I/art     (  370): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 1.334ms total 10.285ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 10.170ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 462us total 12.198ms
,I/ActivityManager(  821): Killing 3114:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/TimeService( 3816): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449216319464
D/        ( 3816): TimeServiceNative: User Time to be set is 1449216319464
D/QC-time-services( 3816): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3816): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3816): Lib:time_genoff_operation: pargs->ts_val = 1449216319464
D/QC-time-services(  374): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3816): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  374): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449216319464
D/QC-time-services(  374): Daemon:genoff_opr: Base = 2, val = 1449216319464, operation = 0
D/QC-time-services(  374): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/21/70 4:18:15
D/QC-time-services(  374): Daemon:Value read from RTC seconds = 9519495000
D/QC-time-services(  374): Daemon:new time 1449216319464 
D/QC-time-services(  374): Daemon: delta 1439696824464 genoff 1439696824464 
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696824464 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  374): Updating the TOD offset
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696824464 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  374): Daemon:Update to modem bit set
D/QC-time-services(  374): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  374): Daemon: Base = 2, Value being sent to MODEM = 1133251519464
,E/QC-time-services( 3816): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/Adreno  ( 3717): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/QC-time-services(  374): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  374): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/WVCdm   (  359): CdmEngine::OpenSession
I/WVCdm   (  359): Level3 Library Dec 11 2014 16:13:16
,I/ActivityManager(  821): Killing 3016:com.android.defcontainer/u0a7 (adj 15): empty #17
,W/WVCdm   (  359): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  359): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  359): Service_Initialize: starts!
D/QSEECOMAPI: (  359): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  359): App is not loaded in QSEE
,D/QSEECOMAPI: (  359): Loaded image: APP id = 3,
,D/DrmWidevineDash(  359): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b90000
E/DrmWidevineDash(  359): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b90000
,D/DrmLibTime(  317): got the req here! ret=0
D/DrmLibTime(  317): command id, time_cmd_id = 770
D/DrmLibTime(  317): time_getutcsec starts!
D/DrmLibTime(  317): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  317): QSEE Time Listener: get_utc_seconds
,D/DrmLibTime(  317): QSEE Time Listener: seconds: 1449216319
,D/DrmLibTime(  317): QSEE Time Listener: nano seconds: 803327238
D/DrmLibTime(  317): time_getutcsec returns 0, sec = 1449216319; nsec = 803327238
D/DrmLibTime(  317): time_getutcsec finished! 
D/DrmLibTime(  317): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  317): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  359): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  359): hlos api version =  9
D/DrmWidevineDash(  359): tz api version =  9
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  359): OEMCrypto_IsKeyboxValid: starts!
,W/Uploader( 1401): No account for auth token provided
,D/DrmWidevineDash(  359): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  359): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  359): OEMCrypto_OpenSession: starts! SID=0xbea12520
D/DrmWidevineDash(  359): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  359): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_GetRandom: starts! randomData=0xb58762d8, dataLength=8,
D/DrmWidevineDash(  359): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  359): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4080e00, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  359): OEMCrypto_LoadDeviceRSAKey: ends! returns 0,
I/WVCdm   (  359): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  359): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  359): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  359): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  359): OEMCrypto_GetDeviceID: starts! deviceID=0xb583d380, idLength=0xb2f5d710
,D/DrmWidevineDash(  359): OEMCrypto_GetDeviceID: ends! returns 0,
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: wv_app_version = 21
,D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  359): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  359): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  359): hlos api version =  9
,D/DrmWidevineDash(  359): tz api version =  9
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  359): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  359): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  359): PrepareKeyRequest: nonce=3801412117
D/DrmWidevineDash(  359): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4d0e600
D/DrmWidevineDash(  359): message_length=1634, signature=0xb4c53cc0, signature_length=3002455796
,I/ActivityManager(  821): Start proc 3838:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/GAv4    ( 3838): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3838):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3838):   adb logcat -s GAv4
,W/GAv4    ( 3838): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3838): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3838): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  359): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  359): CdmEngine::CloseSession
,D/DrmWidevineDash(  359): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  359): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  359): L3 Terminate.
D/DrmWidevineDash(  359): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  359): Service_Uninitialize: starts!
D/QSEECOMAPI: (  359): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  359): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  359): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  359): OEMCrypto_Terminate: ends! returns 0
,W/Uploader( 1401): No account for auth token provided
,I/EventLogService( 1779): Opted in for usage reporting
,I/art     (  821): Explicit concurrent mark sweep GC freed 18257(879KB) AllocSpace objects, 8(410KB) LOS objects, 32% free, 33MB/49MB, paused 1.142ms total 54.765ms
,I/ActivityManager(  821): Killing 2705:com.android.vending/u0a19 (adj 15): empty #17
,W/Uploader( 1401): No account for auth token provided
,I/CheckinTask( 1779): Sending checkin request (9685 bytes)
,W/Uploader( 1401): No account for auth token provided
,D/GCM     ( 1401): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1401): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1779): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/Uploader( 1401): No account for auth token provided
,I/ActivityManager(  821): Start proc 3869:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,W/Uploader( 1401): No account for auth token provided
,D/LocationInitializer( 1779): Restart initialization of location
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/CalendarProvider2( 3787): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3787): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3869): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3869): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Babel   ( 2626): UserRecoverableAuthException.
W/Uploader( 1401): No account for auth token provided
,E/Babel   ( 2626): eei: BadAuthentication
E/Babel   ( 2626): 	at eeg.a(Unknown Source)
E/Babel   ( 2626): 	at eeg.a(Unknown Source)
E/Babel   ( 2626): 	at eeg.a(Unknown Source)
E/Babel   ( 2626): 	at g.a(Unknown Source)
E/Babel   ( 2626): 	at cae.a(SourceFile:3089)
E/Babel   ( 2626): 	at cae.a(SourceFile:1131)
E/Babel   ( 2626): 	at cws.a(SourceFile:4333)
E/Babel   ( 2626): 	at cws.a(SourceFile:1419)
E/Babel   ( 2626): 	at crl.a(SourceFile:492)
E/Babel   ( 2626): 	at crl.a(SourceFile:1468)
E/Babel   ( 2626): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2626): 	at cas.b(SourceFile:106)
E/Babel   ( 2626): 	at cap.d(SourceFile:335)
E/Babel   ( 2626): 	at caq.run(SourceFile:81)
E/Babel   ( 2626): Error getting auth token
E/Babel   ( 2626): dvm
E/Babel   ( 2626): 	at g.a(Unknown Source)
E/Babel   ( 2626): 	at cae.a(SourceFile:3089)
E/Babel   ( 2626): 	at cae.a(SourceFile:1131)
E/Babel   ( 2626): 	at cws.a(SourceFile:4333)
E/Babel   ( 2626): 	at cws.a(SourceFile:1419)
E/Babel   ( 2626): 	at crl.a(SourceFile:492)
E/Babel   ( 2626): 	at crl.a(SourceFile:1468)
E/Babel   ( 2626): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2626): 	at cas.b(SourceFile:106)
E/Babel   ( 2626): 	at cap.d(SourceFile:335)
E/Babel   ( 2626): 	at caq.run(SourceFile:81)
,E/Babel   ( 2626): Account registration failed 1-Redacted-21
,E/Babel   ( 2626): cyp: null -- null
E/Babel   ( 2626): 	at cae.a(SourceFile:3121)
E/Babel   ( 2626): 	at cae.a(SourceFile:1131)
E/Babel   ( 2626): 	at cws.a(SourceFile:4333)
E/Babel   ( 2626): 	at cws.a(SourceFile:1419)
E/Babel   ( 2626): 	at crl.a(SourceFile:492)
E/Babel   ( 2626): 	at crl.a(SourceFile:1468)
E/Babel   ( 2626): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2626): 	at cas.b(SourceFile:106)
E/Babel   ( 2626): 	at cap.d(SourceFile:335)
E/Babel   ( 2626): 	at caq.run(SourceFile:81)
,I/MultiDex( 3869): VM with version 2.1.0 has multidex support
I/MultiDex( 3869): install
I/MultiDex( 3869): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3869): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     ( 2626): Note: end time exceeds epoch: 
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1401): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ProviderInstaller( 3869): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1401): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1401): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1779): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/Babel   ( 2626): Unexpected exception while authenticating.
,E/Babel   ( 2626): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2626): 	at eeg.b(Unknown Source)
E/Babel   ( 2626): 	at eeg.b(Unknown Source)
E/Babel   ( 2626): 	at g.a(Unknown Source)
E/Babel   ( 2626): 	at cae.b(SourceFile:1146)
E/Babel   ( 2626): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2626): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2626): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2626): 	at java.lang.Thread.run(Thread.java:818)
,D/WearableService( 3869): callingUid 10011, callindPid: 3869
,E/Uploader( 1401): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1401): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1401): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1401): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/LocationInitializer( 1779): Restart initialization of location
,E/MDM     ( 1751): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1751): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/CheckinRequestBuilder( 1779): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1779): Failed to find provider info for com.google.android.wearable.settings
,W/Uploader( 1401): No account for auth token provided
,W/Uploader( 1401): No account for auth token provided
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1401): No account for auth token provided
,W/CheckinRequestBuilder( 1779): awaiting user notification for token
,I/EventLogService( 1779): Opted in for usage reporting
,W/Uploader( 1401): No account for auth token provided
,I/CheckinTask( 1779): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1779): Checking schedule, now: 1449216320804 next: 1449257463796
I/CheckinService( 1779): active receiver: disabled
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/Uploader( 1401): No account for auth token provided
,D/GCM     ( 1401): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1779): [AccountUtils] Account not ready
W/Kids    ( 1779): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1779): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1779): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1779): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1779): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1779): 	at java.lang.Thread.run(Thread.java:818)
,W/Uploader( 1401):  no longer exists, so no auth token.
,E/SQLiteLog( 3787): (284) automatic index on view_events(_id)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1401): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1401): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1401): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1401): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1401): No account for auth token provided
,W/Uploader( 1401): No account for auth token provided
,W/Uploader( 1401): No account for auth token provided
,W/Uploader( 1401): No account for auth token provided
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 66953(3MB) AllocSpace objects, 12(1137KB) LOS objects, 36% free, 27MB/43MB, paused 2.073ms total 53.445ms
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1401): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1401): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1401): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1401): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/MusicLeanback( 3426): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3426): Stop autocaching.
,E/GmsUtils( 3426): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3426): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1401): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1401): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1401): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1401): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1401): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1401): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GAV2    ( 3542): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=21.00 rxSuccessRate=16.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 7 -> obsolete
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=21.00 rxSuccessRate=16.00 targetRoamBSSID=any RSSI=-48
,E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 7 -> obsolete
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 3764): Thread[GAThread,5,main]: No campaign data found.,
,I/ActivityManager(  821): Killing 3326:com.android.settings/1000 (adj 15): empty #17
,I/art     (  821): Explicit concurrent mark sweep GC freed 22322(1092KB) AllocSpace objects, 4(346KB) LOS objects, 31% free, 34MB/50MB, paused 2.716ms total 87.283ms
,I/ActivityManager(  821): Killing 3344:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3488:com.google.android.youtube/u0a86 (adj 15): empty #17
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/ActivityManager(  821): Killing 3520:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #18
,I/ActivityManager(  821): Start proc 3930:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/Finsky  ( 3930): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3930): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  821): Start proc 3966:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3930): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3930): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 3966): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3966): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 3930): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3930): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 3930): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3930): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 3966): VM with version 2.1.0 has multidex support
I/MultiDex( 3966): install
I/MultiDex( 3966): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3966): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3966): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1401): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1401): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1779): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3869): callingUid 10011, callindPid: 3869
,E/MDM     ( 1751): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1779): Restart initialization of location
,V/Finsky  ( 3930): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3930): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3930): [1] 5.onFinished: Scheduling replication attempt 4.
,D/Finsky  ( 3930): [399] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3930): [399] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/Finsky  ( 3930): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3930): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3930): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3930): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3930): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3930): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3930): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1751): client connected with version: 7571000
,I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/ActivityManager(  821): Start proc 4007:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,V/GmsNetworkLocationProvi( 1751): DISABLE
,D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  821): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  821): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/GmsNetworkLocationProvi( 1751): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,D/PackageBroadcastService( 1779): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1779): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 1523): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,V/BackupManagerService(  821): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  821): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@299d88ba
W/Launcher( 1293): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2596ca4 new=com.google.android.velvet.VelvetApplication@2596ca4
,V/GmsNetworkLocationProvi( 1751): ENABLE
,I/Launcher( 1293): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1523): UpdateCorporaTask done [took 37 ms] updated apps [took 37 ms] 
,I/ContactLocale( 4007): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  821): Explicit concurrent mark sweep GC freed 24645(1164KB) AllocSpace objects, 7(771KB) LOS objects, 32% free, 33MB/49MB, paused 1.218ms total 52.796ms
,I/Icing   ( 1779): updateResources: need to parse f{com.google.android.gms}
,V/GmsNetworkLocationProvi( 1751): SET-REQUEST
,V/GmsNetworkLocationProvi( 1751): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/BackupManagerService(  821): Scheduling immediate backup pass
,V/BackupManagerService(  821): Running a backup pass
V/BackupManagerService(  821): clearing pending backups
,V/PerformBackupTask(  821): Beginning backup of 14 targets
,D/PerformBackupTask(  821): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  821): doBackup() invoked
I/PMBA    (  821): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  821): Getting widget state for user: 0
,W/GmsBackupTransport( 1751): Unknown package in backup request: @pm@
V/GmsBackupTransport( 1751): starting performBackup for @pm@
,V/GmsBackupTransport( 1751): performBackup done for @pm@
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1401): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1401): 	at com.google.android.gms.auth.p.e(SourceFile:1268),
W/GLSActivity( 1401): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1401): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1401): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1401): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1401): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1751): Error sending final backup to server: 
W/GmsBackupTransport( 1751): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1751): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1751): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1751): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1751): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1751): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1751): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1751): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1751): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1751): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1751): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1751): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1751): 	... 1 more
,D/BackupManagerService(  821): Now staging backup of com.google.android.talk
,D/BackupManagerService(  821): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  821): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  821): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  821): Now staging backup of com.google.android.gm
,D/BackupManagerService(  821): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  821): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  821): Now staging backup of com.android.nfc
,D/BackupManagerService(  821): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  821): Now staging backup of com.android.vending
,D/BackupManagerService(  821): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  821): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  821): Now staging backup of android
,D/BackupManagerService(  821): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1751): Next backup will happen in 43199962 millis.
,I/BackupManagerService(  821): Backup pass finished.
,I/ActivityManager(  821): Killing 3600:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=21.00 rxSuccessRate=16.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3182): 
,I/ActivityManager(  821): Killing 3542:com.google.android.apps.books/u0a34 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3258:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3182): 
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/ActivityManager(  821): Start proc 4038:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 33661(1866KB) AllocSpace objects, 14(1543KB) LOS objects, 37% free, 26MB/42MB, paused 1.093ms total 36.918ms
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3930): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3930): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GoogleAuthProtoRequest( 4038): [425] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4038): [425] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.,
,W/ExperimentUpdateService( 4038): [425] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4038): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4038): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4038): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  821): Killing 3291:com.google.android.keep/u0a79 (adj 15): empty #17
,E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3291
,V/GoogleAuthProtoRequest( 4038): [426] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4038): [426] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4038): [426] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4038): ,	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4038): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4038): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3930): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3930): [1] 5.onFinished: Giving up after 6 failures.
,I/ActivityManager(  821): Start proc 4070:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at blb.a(PG:3937)
E/HttpOperation( 2951): 	at czp.a(PG:18188)
E/HttpOperation( 2951): 	at czp.a(PG:9087)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 12 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 14 more
,W/GAV2    ( 4070): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4070): Created application version: 3.6.8 (30608)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at blb.a(PG:3937)
E/HttpOperation( 2951): 	at czp.a(PG:18188)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 12 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 14 more
,I/BooksSync( 4070): Starting books sync for 61035162, extras: ade
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at hec.a(PG:42)
E/HttpOperation( 2951): 	at hee.a(PG:102)
E/HttpOperation( 2951): 	at czr.a(PG:65)
E/HttpOperation( 2951): 	at kka.a(PG:108)
E/HttpOperation( 2951): 	at czp.a(PG:19176)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 15 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 17 more
,E/ExperimentLoader( 2951): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): 	at jdm.a(PG:82)
E/ExperimentLoader( 2951): 	at jcs.o(PG:406)
E/ExperimentLoader( 2951): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2951): 	at jcs.i(PG:143)
E/ExperimentLoader( 2951): 	at hec.a(PG:42)
E/ExperimentLoader( 2951): 	at hee.a(PG:102)
E/ExperimentLoader( 2951): 	at czr.a(PG:65)
E/ExperimentLoader( 2951): 	at kka.a(PG:108)
E/ExperimentLoader( 2951): 	at czp.a(PG:19176)
E/ExperimentLoader( 2951): 	at czp.a(PG:9081)
E/ExperimentLoader( 2951): 	at czq.run(PG:1686)
E/ExperimentLoader( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2951): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2951): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2951): 	at jdm.a(PG:77)
E/ExperimentLoader( 2951): 	... 15 more
E/ExperimentLoader( 2951): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2951): 	at fal.a(PG:38)
E/ExperimentLoader( 2951): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2951): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 163488, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/BooksConfig( 4070): GmsCore Version = 7.8.99 (2134222-430)
,I/ActivityManager(  821): Start proc 4103:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 27865(1335KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.497ms total 86.261ms
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 22750(1365KB) AllocSpace objects, 7(771KB) LOS objects, 38% free, 26MB/42MB, paused 1.641ms total 53.798ms
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4070): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4070): Soft error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4070): Sync error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4070): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 195746, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/ActivityManager(  821): Killing 3816:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/Keyboard.Facilitator.LanguageModelFlusher( 1198): run()
I/Keyboard.Facilitator( 1198): flushDynamicLanguageModels()
,I/ConfigService( 1401): onCreate
,V/KeepSync( 4103): Connecting to GoogleApiClient
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1779): Handling authorization failure,
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	,at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
,E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	,at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
,E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 4103): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted),
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4103): IOException
E/KeepSync( 4103): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4103): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4103): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4103): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4103): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4103): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4103): 	... 10 more
W/KeepSync( 4103): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 196288, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Killing 3838:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/GAV2    ( 4070): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3182): 
,I/ConfigService( 1401): onDestroy
,D/Finsky  ( 3930): [400] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3930): [400] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,V/GoogleAuthProtoRequest( 4038): [427] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 4038): [427] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4038): [427] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4038): 	at com.google.android.gms.gcm.c.run(Unknown Source)
,W/ExperimentUpdateService( 4038): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4038): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): ,
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at blb.a(PG:3937)
E/HttpOperation( 2951): 	at czp.a(PG:18188)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 12 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 14 more
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at hec.a(PG:42)
E/HttpOperation( 2951): 	at hee.a(PG:102)
E/HttpOperation( 2951): 	at czr.a(PG:65)
E/HttpOperation( 2951): 	at kka.a(PG:108)
E/HttpOperation( 2951): 	at czp.a(PG:19176)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 15 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 17 more
E/ExperimentLoader( 2951): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): 	at jdm.a(PG:82)
E/ExperimentLoader( 2951): 	at jcs.o(PG:406)
E/ExperimentLoader( 2951): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2951): 	at jcs.i(PG:143)
E/ExperimentLoader( 2951): 	at hec.a(PG:42)
E/ExperimentLoader( 2951): 	at hee.a(PG:102)
E/ExperimentLoader( 2951): 	at czr.a(PG:65)
E/ExperimentLoader( 2951): 	at kka.a(PG:108)
E/ExperimentLoader( 2951): 	at czp.a(PG:19176)
E/ExperimentLoader( 2951): 	at czp.a(PG:9081)
E/ExperimentLoader( 2951): 	at czq.run(PG:1686)
E/ExperimentLoader( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2951): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2951): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2951): 	at jdm.a(PG:77)
E/ExperimentLoader( 2951): 	... 15 more
E/ExperimentLoader( 2951): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2951): 	at fal.a(PG:38)
E/ExperimentLoader( 2951): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2951): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 254354, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3182): 
,V/GoogleAuthProtoRequest( 4038): [428] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4038): [428] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4038): [428] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4038): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4038): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4038): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3182): DBG, CoordinatorConnector connect called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): Coordinator is now connected to the server!
I/jxcore-log( 3182): 
,I/chromium( 3182): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63),
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,I/BooksSync( 4070): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4103): Connecting to GoogleApiClient
,I/BooksConfig( 4070): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 4103): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,I/art     (  821): Explicit concurrent mark sweep GC freed 31076(1381KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.707ms total 86.184ms
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4070): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): Soft error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4070): Sync error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4070): Finished books sync
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284891, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 4103): IOException
E/KeepSync( 4103): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4103): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4103): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4103): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4103): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4103): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4103): 	... 10 more
,W/KeepSync( 4103): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 289128, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 39949(2MB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 1.391ms total 45.453ms
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at blb.a(PG:3937)
E/HttpOperation( 2951): 	at czp.a(PG:18188)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 12 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 14 more
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at hec.a(PG:42)
E/HttpOperation( 2951): 	at hee.a(PG:102)
E/HttpOperation( 2951): 	at czr.a(PG:65)
E/HttpOperation( 2951): 	at kka.a(PG:108)
E/HttpOperation( 2951): 	at czp.a(PG:19176)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 15 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 17 more
E/ExperimentLoader( 2951): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): 	at jdm.a(PG:82)
E/ExperimentLoader( 2951): 	at jcs.o(PG:406)
E/ExperimentLoader( 2951): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2951): 	at jcs.i(PG:143)
E/ExperimentLoader( 2951): 	at hec.a(PG:42)
E/ExperimentLoader( 2951): 	at hee.a(PG:102)
E/ExperimentLoader( 2951): 	at czr.a(PG:65)
E/ExperimentLoader( 2951): 	at kka.a(PG:108)
E/ExperimentLoader( 2951): 	at czp.a(PG:19176)
E/ExperimentLoader( 2951): 	,at czp.a(PG:9081)
E/ExperimentLoader( 2951): 	at czq.run(PG:1686)
E/ExperimentLoader( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2951): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2951): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2951): 	,at jdm.a(PG:77)
E/ExperimentLoader( 2951): 	... 15 more
E/ExperimentLoader( 2951): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2951): 	at fal.a(PG:38)
E/ExperimentLoader( 2951): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2951): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 345373, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3182): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): DBG, CoordinatorConnector command called
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":20,"addressList":[{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"58:3F:54:73:64
,I/jxcore-log( 3182): Start now : testSendData.js
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 20
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): check server
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): serverPort is 35196
I/jxcore-log( 3182): 
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3182): Stoping All
,I/        ( 3182): Stopping services
I/        ( 3182): Stop Bluetooth
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/        ( 3182): Start-My BT: F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/        ( 3182):  mInstanceString : {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8001","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3182): All stuff available and enabled
,I/        ( 3182): Stoping All
I/        ( 3182): Stopping services
,I/        ( 3182): Stop Bluetooth
I/        ( 3182): Starting All
I/        ( 3182): Stopping services
,I/        ( 3182): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8001","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@10bdafe7
I/        ( 3182): Stopping services
,I/        ( 3182): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8001","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3182): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8001","ra":"F8:CF:C5:D9:E5:61"}, length : 82
,I/        ( 3182): peerDiscoveryTimer timeout value:7995
,I/        ( 3182): Stop Bluetooth
,I/        ( 3182): StartBluetooth listener
,I/        ( 3182): StartBluetooth listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3182): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3182): StartBroadcasting started ok
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): do fake peer & start
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:09:28.280Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:09:28.280Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3182): 
I/BTListenerThread( 3182): starting to listen
I/jxcore-log( 3182): 2015-12-04T08:09:28.281Z SendDataConnector.js: do connect now
I/jxcore-log( 3182): 
I/BTListenerThread( 3182): waiting to accept incoming Connection
,I/        ( 3182): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3182): Starting to connect
,W/BluetoothAdapter( 3182): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3182): Connecting to null, at E0:DB:10:14:E2:C0
D/BTIF_SOCK( 3240): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
I/jxcore-log( 3182): 2015-12-04T08:09:28.292Z SendDataTCPServer.js: TCP/IP server is bound to port: 35196
I/jxcore-log( 3182): 
I/chromium( 3182): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3182): We already were running, thus doing nothing
I/        ( 3182): Added local service
,I/        ( 3182): Cleared service requests
I/        ( 3182): Stopped peer discovery
,I/        ( 3182): Started peer discovery
I/        ( 3182): Discovery state changed to Started.
,I/wpa_supplicant( 3257): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3182): Found 1 peers.
I/SS      ( 3182): Peer(1): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3182): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3182): Added service request
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config( 3240): btif_get_device_type: Device [f4:f1:e1:5c:3b:e2] type 1,
,I/BluetoothBondStateMachine( 3240): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3240): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3240): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3240): Entering PendingCommandState State
,I/        ( 3182): Started service discovery
,I/ActivityManager(  821): Start proc 4192:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,I/BluetoothBondStateMachine( 3240): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3240): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3240): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23583821:true
,I/ActivityManager(  821): Killing 3737:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/BluetoothBondStateMachine( 3240): StableState(): Entering Off State
,I/        ( 3182): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}, typeCordovap2p._tcp.local.:
,I/        ( 3182): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT5954, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 3182): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT5954, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,W/bt-btif ( 3240): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3240): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3240): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3182): we got incoming connection
,I/BTHandshakeSocketThread( 3182): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3182): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3182): BTHandshakeSocketThread started
,I/BTListenerThread( 3182): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3182): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3182): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3182): Incoming connection Hand Shake finished for : motorola-XT1039_PT8025
I/BTHandshakeSocketThread( 3182): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3182): Starting the connected thread incoming : true, motorola-XT1039_PT8025
,I/BtToSocketBase( 3182): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3182): Creating BTConnectedThread
I/BtConnectorHelper( 3182): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3182): --DoOneRunRound started
,I/BtToRequestSocket( 3182): LocalHost address: localhost/127.0.0.1, port: 35196,
,I/BtToRequestSocket( 3182): --DoOneRunRound ended
,I/jxcore-log( 3182): 2015-12-04T08:09:31.506Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3182): 
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f83eb4 rs_disc_pending=1
,W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3182): 2015-12-04T08:09:32.510Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.522Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.593Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.601Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.607Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.706Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.729Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.760Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.780Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.785Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data,
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.881Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.920Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.923Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:32.932Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.016Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.050Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.057Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.063Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.072Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.107Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.156Z SendDataTCPServer.js: TCP/IP server has received 44376 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.169Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.207Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.213Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.251Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.291Z SendDataTCPServer.js: TCP/IP server has received 54276 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.314Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.354Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 3182): ,
,I/jxcore-log( 3182): 2015-12-04T08:09:33.395Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.411Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.491Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.551Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data,
I/jxcore-log( 3182): 
,W/bt-sdp  ( 3240): process_service_search_attr_rsp
,I/jxcore-log( 3182): 2015-12-04T08:09:33.639Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.680Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data,
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.693Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.730Z SendDataTCPServer.js: TCP/IP server has received 76056 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.779Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data,
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.786Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.791Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.830Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.836Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
,I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.841Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 3182): ,
,I/jxcore-log( 3182): 2015-12-04T08:09:33.858Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.886Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.946Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.983Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:33.997Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:34.031Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3182): 
,D/btif_config( 3240): btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,I/BluetoothBondStateMachine( 3240): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,E/bt-btif ( 3240): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3240): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3240): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3240): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3240): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3240): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3240): StableState(): Entering Off State
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f83eb4 rs_disc_pending=0
W/bt-btif ( 3240): bta_dm_check_av:0
,W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,I/        ( 3182): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3182): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9142, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3182): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9142, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,W/bt-btif ( 3240): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3240): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3240): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3182): Starting to Handshake,
I/BTHandshakeSocketThread( 3182): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3182): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3182): BTHandshakeSocketThread started,
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f83eb4 rs_disc_pending=1
,W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3182): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3182): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2368","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������,
I/BTConnectToThread( 3182): HandshakeOk : samsung-SM-N910C_PT2368
I/HS      ( 3182): Hand Shake finished outgoing for : samsung-SM-N910C_PT2368
I/BTHandshakeSocketThread( 3182): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3182): Starting the connected thread incoming : false, samsung-SM-N910C_PT2368
,I/BtToSocketBase( 3182): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3182): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3182): mHTTPPort  set to : 45058
,I/BtConnectorHelper( 3182): Request socket is using : 45058
I/BtToRequestSocket( 3182): Now accepting connections
,I/BtConnectorHelper( 3182): Calling ConnectionStatusUpdate with port :45058
,I/jxcore-log( 3182): 2015-12-04T08:09:37.792Z SendDataConnector.js: CLIENT connected to 45058, error: null
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:37.793Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3182): 
,I/BtToRequestSocket( 3182): incoming data from: /127.0.0.1, port: 45058
,I/BtToRequestSocket( 3182): Set local streams
,I/BtToRequestSocket( 3182): rin ended ---------------------------;
,I/jxcore-log( 3182): 2015-12-04T08:09:37.814Z SendDataConnector.js: CLIENT now sending 100000 bytes of data,
I/jxcore-log( 3182): 
,D/        ( 3240): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:266,
,I/jxcore-log( 3182): 2015-12-04T08:09:38.428Z SendDataConnector.js: CLIENT is data received : 10000,
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:38.486Z SendDataConnector.js: CLIENT is data received : 20000,
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:38.536Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:38.651Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:38.667Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:38.718Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:38.811Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3182): 
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3182): 2015-12-04T08:09:38.867Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3182): 
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f83eb4 rs_disc_pending=0
W/bt-btif ( 3240): bta_dm_check_av:0
,W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,W/bt-btif ( 3240): dm_pm_timer expires
,W/bt-btif ( 3240): dm_pm_timer expires 1
W/bt-btif ( 3240): proc dm_pm_timer expires
,V/GoogleAuthProtoRequest( 4038): [429] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4038): [429] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4038): [429] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
,W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
,W/ExperimentUpdateService( 4038): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4038): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4038): 	at com.a.a.k.run(SourceFile:110)
,W/bt-btif ( 3240): invalid rfc slot id: 4
I/BtToSocketBase( 3182): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3182): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3182): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT8025
,I/BtToSocketBase( 3182): Stop ReceivingThread
I/BtToSocketBase( 3182): Stop SendingThread
I/BtToSocketBase( 3182): Close local in
I/BtToSocketBase( 3182): Close LocalOutputStream
,I/BtToSocketBase( 3182): Close localHostSocket
I/BtToSocketBase( 3182): Close bt in
I/BtToSocketBase( 3182): Close bt out
,I/BtToSocketBase( 3182): Close bt socket
I/BtToSocketBase( 3182): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3182): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3182): 2015-12-04T08:09:44.310Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3182): 
,I/        ( 3182): Cleared service requests
,I/        ( 3182): Started peer discovery,
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f83eb4 rs_disc_pending=1,
W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3240): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0,
W/bt-rfcomm( 3240): RFCOMM_DisconnectInd LCID:0x43
,I/jxcore-log( 3182): 2015-12-04T08:09:48.868Z SendDataConnector.js: Receiving data timeout now,
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:09:48.870Z SendDataConnector.js: CLIENT closeClientSocket
,I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:09:48.874Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:09:48.875Z SendDataConnector.js: tryAgain afer: 5000 ms.,
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:48.877Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3182): 
,I/BtToSocketBase( 3182): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3182): Disconnect outgoing peer: samsung-SM-N910C_PT2368,
I/BtToSocketBase( 3182): Stop ReceivingThread
,I/BtToSocketBase( 3182): Stop SendingThread
I/BtToSocketBase( 3182): Close local in
,I/BtToSocketBase( 3182): Close LocalOutputStream
I/BtToSocketBase( 3182): Close localHostSocket
,I/BtToSocketBase( 3182): Close bt in
,I/BtToSocketBase( 3182): Close bt out
I/BtToSocketBase( 3182): Close bt socket
I/BtToSocketBase( 3182): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToRequestSocket( 3182): Close server socket
,W/bt-btif ( 3240): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/BooksSync( 4070): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4070): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f83eb4 rs_disc_pending=0
W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4070): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4070): Soft error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4070): Sync error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4070): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 435761, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3240): onReceive
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f298e32:true
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 3257): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
I/wpa_supplicant( 3257): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3257): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3257): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3182): Found 5 peers.
,I/SS      ( 3182): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3182): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3182): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3182): Peer(4): Android_2dc2 52:55:27:f0:ff:f0,
I/SS      ( 3182): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3182): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3182): Added service request
,I/        ( 3182): Started service discovery
,I/        ( 3182): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
,I/        ( 3182): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3182): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3182): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
,I/        ( 3182): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3182): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3182): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}, typeCordovap2p._tcp.local.:
,I/        ( 3182): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT5363, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3182): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT5363, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3240): onReceive,
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Note4-1,
,I/        ( 3182): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}, typeCordovap2p._tcp.local.:
,I/        ( 3182): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT8025, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3182): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT8025, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3182): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}, typeCordovap2p._tcp.local.:
,I/        ( 3182): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT5954, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3182): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT5954, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3182): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3182): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9142, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3182): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9142, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3182): 2015-12-04T08:09:53.878Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:53.880Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3182): 
,W/bt-btif ( 3240): info:x10,
D/        ( 3240): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,I/        ( 3182): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2491","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3182): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2491","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT2491, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3182): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT2491, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-btif ( 3240): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3240): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3240): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3182): we got incoming connection
I/BTHandshakeSocketThread( 3182): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3182): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3182): BTHandshakeSocketThread started
,I/BTListenerThread( 3182): got MESSAGE_READ 81 bytes.,
I/BTListenerThread( 3182): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3182): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3182): Incoming connection Hand Shake finished for : motorola-XT1039_PT8025
I/BTHandshakeSocketThread( 3182): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3182): Starting the connected thread incoming : true, motorola-XT1039_PT8025
I/BtToSocketBase( 3182): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3182): Creating BTConnectedThread
,I/BtConnectorHelper( 3182): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3182): --DoOneRunRound started
,I/BtToRequestSocket( 3182): LocalHost address: localhost/127.0.0.1, port: 35196
,I/BtToRequestSocket( 3182): --DoOneRunRound ended
,I/jxcore-log( 3182): 2015-12-04T08:09:55.777Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:56.211Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:56.215Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:56.228Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:09:56.232Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3182): 
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3182): 2015-12-04T08:09:58.891Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:09:58.891Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:09:58.892Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:09:58.892Z SendDataConnector.js: do connect now
I/jxcore-log( 3182): 
,I/        ( 3182): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1,
,I/BTConnectToThread( 3182): Starting to connect
W/BluetoothAdapter( 3182): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3182): Connecting to Note4-1, at E0:DB:10:14:E2:C0,
D/BTIF_SOCK( 3240): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f8407c rs_disc_pending=1
,W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,I/        ( 3182): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3182): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT5544, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3182): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT5544, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f83eb4 rs_disc_pending=1
W/bt-btif ( 3240): bta_dm_check_av:0
,W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3240): process_service_search_attr_rsp
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f83eb4 rs_disc_pending=0
,W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3240): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3240): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,I/BTConnectToThread( 3182): Starting to Handshake
W/bt-btif ( 3240): bta_dm_pm_ssr:2, lat:1200
I/BTHandshakeSocketThread( 3182): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3182): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3182): BTHandshakeSocketThread started
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f83eb4 rs_disc_pending=1
,W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3182): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3182): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2368","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3182): HandshakeOk : samsung-SM-N910C_PT2368
,I/HS      ( 3182): Hand Shake finished outgoing for : samsung-SM-N910C_PT2368
I/BTHandshakeSocketThread( 3182): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3182): Starting the connected thread incoming : false, samsung-SM-N910C_PT2368
I/BtToSocketBase( 3182): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3182): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3182): mHTTPPort  set to : 53864
,I/BtConnectorHelper( 3182): Request socket is using : 53864
I/BtToRequestSocket( 3182): Now accepting connections
,I/BtConnectorHelper( 3182): Calling ConnectionStatusUpdate with port :53864
,I/jxcore-log( 3182): 2015-12-04T08:10:03.135Z SendDataConnector.js: CLIENT connected to 53864, error: null
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:10:03.136Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3182): 
,I/BtToRequestSocket( 3182): incoming data from: /127.0.0.1, port: 53864
,I/BtToRequestSocket( 3182): Set local streams
I/BtToRequestSocket( 3182): rin ended ---------------------------;
,I/jxcore-log( 3182): 2015-12-04T08:10:03.154Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3182): 
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f83eb4 rs_disc_pending=0
W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3182): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:,
I/        ( 3182): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT5146, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3182): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT5146, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/wpa_supplicant( 3257): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,W/bt-btif ( 3240): invalid rfc slot id: 6
I/BtToSocketBase( 3182): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3182): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3182): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT8025
I/BtToSocketBase( 3182): Stop ReceivingThread
,I/BtToSocketBase( 3182): Stop SendingThread
I/BtToSocketBase( 3182): Close local in
I/BtToSocketBase( 3182): Close LocalOutputStream
,I/BtToSocketBase( 3182): Close localHostSocket
I/BtToSocketBase( 3182): Close bt in
,I/BtToSocketBase( 3182): Close bt out
I/BtToSocketBase( 3182): Close bt socket
I/BtToSocketBase( 3182): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3182): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3182): 2015-12-04T08:10:06.303Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3182): 
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f83eb4 rs_disc_pending=1
W/bt-btif ( 3240): bta_dm_check_av:0
,W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3257): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-rfcomm( 3240): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3240): RFCOMM_DisconnectInd LCID:0x47
,W/bt-btif ( 3240): dm_pm_timer expires,
W/bt-btif ( 3240): dm_pm_timer expires 0
W/bt-btif ( 3240): proc dm_pm_timer expires
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag,
D/BluetoothMapService( 3240): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039,
,--------- beginning of crash
F/libc    ( 3257): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 3257 (wpa_supplicant)
I/libc    ( 3257): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
I/        ( 3182): Cleared service requests
,I/jxcore-log( 3182): 2015-12-04T08:10:13.231Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:10:13.231Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:10:13.233Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:10:13.234Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:10:13.235Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3182): 
I/BtToSocketBase( 3182): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3182): Disconnect outgoing peer: samsung-SM-N910C_PT2368
,I/BtToSocketBase( 3182): Stop ReceivingThread,
I/BtToSocketBase( 3182): Stop SendingThread
I/BtToSocketBase( 3182): Close local in
,I/BtToSocketBase( 3182): Close LocalOutputStream
I/BtToSocketBase( 3182): Close localHostSocket
I/BtToSocketBase( 3182): Close bt in
,I/BtToSocketBase( 3182): Close bt out
I/BtToSocketBase( 3182): Close bt socket
I/BtToRequestSocket( 3182): Close server socket
I/BtToSocketBase( 3182): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f83eb4 rs_disc_pending=0
,W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3240): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3240): onReceive,
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,W/bt-btif ( 3240): new conn_srvc id:26, app_id:255
W/bt-btif ( 3240): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3240): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3182): we got incoming connection
I/BTHandshakeSocketThread( 3182): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3182): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3182): BTHandshakeSocketThread started
,I/BTListenerThread( 3182): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3182): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3182): MESSAGE_WRITE 82 bytes.
I/HS      ( 3182): Incoming connection Hand Shake finished for : motorola-XT1039_PT8025
I/BTHandshakeSocketThread( 3182): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3182): Starting the connected thread incoming : true, motorola-XT1039_PT8025
I/BtToSocketBase( 3182): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3182): Creating BTConnectedThread
I/BtConnectorHelper( 3182): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3182): --DoOneRunRound started
,I/BtToRequestSocket( 3182): LocalHost address: localhost/127.0.0.1, port: 35196
,I/BtToRequestSocket( 3182): --DoOneRunRound ended
,I/jxcore-log( 3182): 2015-12-04T08:10:18.020Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:10:18.236Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:10:18.236Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:10:18.421Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data,
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:10:18.425Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:10:18.433Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:10:18.440Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): 2015-12-04T08:10:18.446Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3182): 
,V/KeepSync( 4103): Connecting to GoogleApiClient
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): ,	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): ,	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more,
,V/KeepSync( 4103): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4103): IOException
E/KeepSync( 4103): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4103): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4103): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4103): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4103): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4103): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4103): 	... 10 more
W/KeepSync( 4103): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 443100, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,D/WifiHW  (  821): 'P2P_FIND 120' command timed out.
I/        ( 3182): Starting peer discovery failed, error code 0
,E/WifiStateMachine(  821): Connection lost, restart supplicant
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/Settings( 2626): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): failed to set BSSID: any
,E/native  (  821): do suspend true
W/Settings( 1751): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,D/CommandListener(  355): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1401): Read error: ssl=0x9d21e000: I/O error during system call, Connection timed out
,V/NativeCrypto( 1401): SSL shutdown failed: ssl=0x9d21e000: I/O error during system call, Broken pipe
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
I/jxcore-log( 3182): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3182): 
I/jxcore-log( 3182): The Coordinator has disconnected!
I/jxcore-log( 3182): 
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
,D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  821): Unexpected BatchedScanResults :null
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiScanningService(  821): SCAN_AVAILABLE : 1
D/RttService(  821): SCAN_AVAILABLE : 1
D/RttService(  821): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  821): StartedState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState
D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
,I/        ( 3182): Discovery state changed to Stopped.
I/WB      ( 3182): Wifi is DISABLED !!
I/        ( 3182): Stoping All
I/        ( 3182): Stopping services
I/        ( 3182): Stopping services
,I/        ( 3182): Stop Bluetooth
,I/        ( 3182): Stop Bluetooth
I/BTListenerThread( 3182): Stopped
I/SS      ( 3182): We got empty peers list
I/        ( 3182): Starting peer discovery failed, error code 2
I/        ( 3182): Clearing local services failed, error code 2,
I/        ( 3182): Clearing service requests failed, error code 2
I/        ( 3182): Stopping peer discovery failed, error code 2
,D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3,
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
D/Tethering(  821): MasterInitialState.processMessage what=3
D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/NetworkMonitor( 3426): type=WIFI subType= reason=null isConnected=false
,V/MusicLeanback( 3426): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,I/art     (  821): Explicit concurrent mark sweep GC freed 41930(1878KB) AllocSpace objects, 8(410KB) LOS objects, 31% free, 34MB/50MB, paused 1.509ms total 73.255ms
,I/ActivityManager(  821): Start proc 4262:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 4262): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4262): simOperator:  IMSI: null
D/SprintDMReceiver( 4262): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1779): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1779): onCreate
,D/SystemUpdateService( 1779): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1779): active receiver: enabled
,I/SystemUpdateService( 1779): showing system update notification,
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1779): retry (wakeup: false) in 3599979 ms
,I/iu.Environment( 1779): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/SystemUpdateService( 1779): onDestroy
I/iu.UploadsManager( 1779): num queued entries: 0
,I/iu.UploadsManager( 1779): num updated entries: 0
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.SyncManager( 1779): NEXT; no task
,I/Babel   ( 2626): connection state changed from CONNECTED to DISCONNECTED
,I/jxcore-log( 3182): 2015-12-04T08:10:23.239Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:10:23.239Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:10:23.239Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3182): 
I/jxcore-log( 3182): 2015-12-04T08:10:23.239Z SendDataConnector.js: do connect now
I/jxcore-log( 3182): 
D/AndroidRuntime( 3182): Shutting down VM
,I/ActivityManager(  821): Start proc 4283:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/ActivityManager(  821): Killing 3764:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 327us total 16.665ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 313us total 13.148ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 308us total 12.925ms
,I/GAv4    ( 4283): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4283):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4283):   adb logcat -s GAv4
,W/GAv4    ( 4283): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4283): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4283): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 4283): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4283): Time to load native libraries: 2 ms (timestamps 774-776)
,I/LibraryLoader( 4283): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4283): Binding Chromium to main looper Looper (main, tid 1) {1c569aa0}
,I/LibraryLoader( 4283): Expected native library version number "",actual native library version number ""
,I/chromium( 4283): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4283): Initializing chromium process, singleProcess=true
,W/art     ( 4283): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4283): ApplicationContext is null in ApplicationStatus
,W/chromium( 4283): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4283): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 4283): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 4283): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 4283): Requires BLUETOOTH permission
,I/NSApplication( 4283): Starting up...
,I/ActivityManager(  821): Killing 3787:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 4339:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,V/MusicLeanback( 3426): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  821): Killing 3717:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
,D/SprintDMReceiver( 4262): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4262): simOperator:  IMSI: null
D/SprintDMReceiver( 4262): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1779): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1779): onCreate,
,D/SystemUpdateService( 1779): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1779): active receiver: enabled
,I/SystemUpdateService( 1779): showing system update notification
,I/ValidateNoPeople(  821): skipping global notification
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1779): retry (wakeup: false) in 3599939 ms
,D/SystemUpdateService( 1779): onDestroy
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1401): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1401): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1401): ,	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1401): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
,W/GLSActivity( 1401): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
,W/GLSActivity( 1401): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1401): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3930): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 3930): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3930): 	,at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3930): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3930): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3930): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3930): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3930): Ignoring header User-Agent because its value was null.
,D/SoftapController(  355): Softap fwReload - Ok
,D/CommandListener(  355): Setting iface cfg
,D/CommandListener(  355): Trying to bring down wlan0
,D/Tethering(  821): InitialState.processMessage what=4
D/CommandListener(  355): Clearing all IP addresses on wlan0
,D/Tethering(  821): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/WifiMonitor(  821): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 4369): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4369): rfkill: Cannot open RFKILL control device
,D/Tethering(  821): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4369): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 4369): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  821): Loading config and enabling all networks 
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@8822b9e}
,E/WifiConfigStore(  821): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  821): Setting external_sim to 1
,D/WifiStateMachine(  821): Setting OUI to 92-68-C3
W/Settings( 2626): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiNative-HAL(  821): startHal
D/wifi    (  821): setting scan oui 0xaec78d30
D/WifiHAL (  821): Sending mac address OUI
,E/native  (  821): do suspend true
,D/WifiScanningService(  821): SCAN_AVAILABLE : 3
W/CommandListener(  355): Failed to retrieve HW addr for p2p0 (No such device)
D/RttService(  821): SCAN_AVAILABLE : 3
D/RttService(  821): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  821): startHal
,D/wifi    (  821): getting scan capabilities on interface[0] = 0xaec78d30
,D/WifiHAL (  821): Creating message to get scan capablities; iface = 5
D/WifiHAL (  821): In GetCapabilities::handleResponse
D/WifiHAL (  821): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  821): StartedState
D/CommandListener(  355): Setting iface cfg
,E/WifiP2pService(  821): Unable to change interface settings: java.lang.IllegalStateException: command '56 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 56 Failed to set address (No such device)'
D/WifiMonitor(  821): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 4369): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  821): p2pGetDeviceAddress
,D/WifiNative-HAL(  821): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,W/bt-btif ( 3240): invalid rfc slot id: 7
,I/BtToSocketBase( 3182): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3182): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3182): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT8025
I/BtToSocketBase( 3182): Stop ReceivingThread
I/BtToSocketBase( 3182): Stop SendingThread
I/BtToSocketBase( 3182): Close local in
I/BtToSocketBase( 3182): Close LocalOutputStream
I/BtToSocketBase( 3182): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3182): Close localHostSocket
I/BtConnectorHelper( 3182): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3182): Close bt in
I/BtConnectorHelper( 3182): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT8025
I/BtToSocketBase( 3182): Close bt out
I/BtToSocketBase( 3182): Close bt in
I/BtToSocketBase( 3182): Close bt socket
,I/BtToSocketBase( 3182): Close bt out
I/BtToSocketBase( 3182): Close bt socket
,I/wpa_supplicant( 4369): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  821):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  821):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,I/wpa_supplicant( 4369): wlan0: Trying to associate with SSID 'NG7005g'
,W/bt-rfcomm( 3240): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 3240): RFCOMM_DisconnectInd LCID:0x4b
,I/wpa_supplicant( 4369): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4369): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4369): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} },
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 2
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 1
E/WifiStateMachine(  821):  RSSI mgmt: -46
E/WifiStateMachine(  821):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 0 tx_time=59 rx_time=186 scan_time=0
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 4377): version 5.5.6 starting
,I/dhcpcd  ( 4377): wlan0: rebinding lease of 192.168.1.110
,I/dhcpcd  ( 4377): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 4377): wlan0: leased 192.168.1.110 for 86400 seconds
,W/ProcessCpuTracker(  821): Skipping unknown process pid 4389
,E/native  (  821): do suspend true
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
D/ConnectivityService(  821): Adding iface wlan0 to network 101
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  821): Setting Dns servers for network 101 to [/192.168.1.1]
,V/NativeCrypto( 1779): SSL shutdown failed: ssl=0x95cc5400: I/O error during system call, Connection timed out
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821):    accepting network in place of null
D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524290
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  821): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3426): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,V/MusicLeanback( 3426): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 4262): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4262): simOperator:  IMSI: null
,D/SprintDMReceiver( 4262): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1779): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1779): onCreate
,D/SystemUpdateService( 1779): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1779): active receiver: enabled
,I/SystemUpdateService( 1779): showing system update notification
,I/iu.Environment( 1779): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1779): num queued entries: 0
I/iu.UploadsManager( 1779): num updated entries: 0
I/iu.SyncManager( 1779): NEXT; no task
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1779): retry (wakeup: false) in 3599975 ms
,D/SystemUpdateService( 1779): onDestroy
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Dec 2015 08:10:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449216633683], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449216633667]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Validated
,D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524290
,I/Babel   ( 2626): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1779): [AccountUtils] Account not ready
W/Kids    ( 1779): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1779): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1779): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1779): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1779): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1779): 	at java.lang.Thread.run(Thread.java:818)
,I/art     ( 1751): Explicit concurrent mark sweep GC freed 17221(1042KB) AllocSpace objects, 13(208KB) LOS objects, 37% free, 26MB/42MB, paused 2.198ms total 41.244ms
,V/Herrevad( 1779): NQAS connected
,E/DataBuffer( 1751): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1021ea49)
,E/DataBuffer( 1751): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ce7186f)
,D/GCM     ( 1401): Connected
,D/GCM     ( 1401): Message class com.google.f.a.a.p
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@8822b9e}
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3240): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3240): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3,
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3240): onReceive
,I/BTConnectionReceiver( 1523): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1523): Bluetooth Device Name: XT1039
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,I/art     (  821): Explicit concurrent mark sweep GC freed 51662(2MB) AllocSpace objects, 4(346KB) LOS objects, 32% free, 33MB/49MB, paused 1.898ms total 61.761ms
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at blb.a(PG:3937)
E/HttpOperation( 2951): 	at czp.a(PG:18188)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 12 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 14 more
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at hec.a(PG:42)
E/HttpOperation( 2951): 	at hee.a(PG:102)
E/HttpOperation( 2951): 	at czr.a(PG:65)
E/HttpOperation( 2951): 	at kka.a(PG:108)
E/HttpOperation( 2951): 	at czp.a(PG:19176)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 15 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 17 more
E/ExperimentLoader( 2951): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): 	at jdm.a(PG:82)
E/ExperimentLoader( 2951): 	at jcs.o(PG:406)
E/ExperimentLoader( 2951): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2951): 	at jcs.i(PG:143)
E/ExperimentLoader( 2951): 	at hec.a(PG:42)
E/ExperimentLoader( 2951): 	at hee.a(PG:102)
E/ExperimentLoader( 2951): 	at czr.a(PG:65)
E/ExperimentLoader( 2951): 	at kka.a(PG:108)
E/ExperimentLoader( 2951): 	at czp.a(PG:19176)
E/ExperimentLoader( 2951): 	at czp.a(PG:9081)
E/ExperimentLoader( 2951): 	at czq.run(PG:1686)
E/ExperimentLoader( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2951): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2951): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2951): 	at jdm.a(PG:77)
E/ExperimentLoader( 2951): 	... 15 more
E/ExperimentLoader( 2951): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2951): 	at fal.a(PG:38)
E/ExperimentLoader( 2951): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2951): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 497568, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [00:f4:6f:30:e0:6c]: 7, f, 610c
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [b0:c5:59:3f:75:69]: 6, f, 410d
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [00:f4:6f:30:e0:6c]: 7, f, 610c
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL,
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [b0:c5:59:3f:75:69]: 6, f, 410d
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2951): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at blb.a(PG:3937)
E/HttpOperation( 2951): 	at czp.a(PG:18188)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
,E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error,
E/HttpOperation( 2951): 	,at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 12 more
,E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 14 more,
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 50234(2MB) AllocSpace objects, 12(1134KB) LOS objects, 36% free, 27MB/43MB, paused 1.253ms total 69.095ms
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at hec.a(PG:42)
E/HttpOperation( 2951): 	at hee.a(PG:102)
E/HttpOperation( 2951): 	at czr.a(PG:65)
E/HttpOperation( 2951): 	at kka.a(PG:108)
E/HttpOperation( 2951): 	at czp.a(PG:19176)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 15 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 17 more
E/ExperimentLoader( 2951): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): 	at jdm.a(PG:82)
E/ExperimentLoader( 2951): 	at jcs.o(PG:406)
E/ExperimentLoader( 2951): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2951): 	at jcs.i(PG:143)
E/ExperimentLoader( 2951): 	at hec.a(PG:42)
E/ExperimentLoader( 2951): 	at hee.a(PG:102)
E/ExperimentLoader( 2951): 	at czr.a(PG:65)
E/ExperimentLoader( 2951): 	at kka.a(PG:108)
E/ExperimentLoader( 2951): 	at czp.a(PG:19176)
E/ExperimentLoader( 2951): 	at czp.a(PG:9081)
E/ExperimentLoader( 2951): 	at czq.run(PG:1686)
E/ExperimentLoader( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2951): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2951): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2951): 	at jdm.a(PG:77)
E/ExperimentLoader( 2951): 	... 15 more
E/ExperimentLoader( 2951): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2951): 	at fal.a(PG:38)
E/ExperimentLoader( 2951): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2951): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 558552, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at blb.a(PG:3937)
E/HttpOperation( 2951): 	at czp.a(PG:18188)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 12 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 14 more
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at hec.a(PG:42)
E/HttpOperation( 2951): 	at hee.a(PG:102)
E/HttpOperation( 2951): 	at czr.a(PG:65)
E/HttpOperation( 2951): 	at kka.a(PG:108)
E/HttpOperation( 2951): 	at czp.a(PG:19176)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 15 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 17 more
,E/ExperimentLoader( 2951): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 2951): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): 	at jdm.a(PG:82)
E/ExperimentLoader( 2951): 	at jcs.o(PG:406)
E/ExperimentLoader( 2951): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2951): 	at jcs.i(PG:143),
E/ExperimentLoader( 2951): 	at hec.a(PG:42)
E/ExperimentLoader( 2951): 	at hee.a(PG:102)
E/ExperimentLoader( 2951): 	at czr.a(PG:65)
E/ExperimentLoader( 2951): 	at kka.a(PG:108)
E/ExperimentLoader( 2951): 	at czp.a(PG:19176)
E/ExperimentLoader( 2951): 	at czp.a(PG:9081)
E/ExperimentLoader( 2951): 	at czq.run(PG:1686)
E/ExperimentLoader( 2951): ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error,
E/ExperimentLoader( 2951): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2951): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2951): 	at jdm.a(PG:77)
E/ExperimentLoader( 2951): 	... 15 more
E/ExperimentLoader( 2951): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2951): 	at fal.a(PG:38)
E/ExperimentLoader( 2951): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2951): 	,... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 650824, reason: Periodic, SyncResult: stats [ numIoExceptions: 1],
,W/bt-btif ( 3240): info:x10,
D/        ( 3240): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 4038): [431] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4038): [431] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4038): [431] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4038): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4038): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4038): 	at com.a.a.k.run(SourceFile:110)
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [08:ec:a9:50:76:27]: 7, f, 2205
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f8479c rs_disc_pending=1
,W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,I/BooksSync( 4070): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4070): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4070): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4070): Soft error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4070): Sync error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4070): Finished books sync
D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 680438, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btm  ( 3240): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f8479c rs_disc_pending=2
W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f84964 rs_disc_pending=0
W/bt-btif ( 3240): bta_dm_check_av:0
,W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [34:fc:ef:9d:93:0b]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [08:ec:a9:50:76:27]: 6, f, 4106
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f845d4 rs_disc_pending=1
,W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [08:ec:a9:50:76:27]: 6, f, 4106
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f845d4 rs_disc_pending=1
W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3240): tBTM_SEC_DEV:0xa2f8479c rs_disc_pending=0
,W/bt-btif ( 3240): bta_dm_check_av:0
W/bt-btif ( 3240): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [58:3f:54:73:64:c0]: 6, f, 4106
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,I/BooksSync( 4070): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4070): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 4103): Connecting to GoogleApiClient
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 38165(1744KB) AllocSpace objects, 7(300KB) LOS objects, 32% free, 33MB/49MB, paused 1.513ms total 72.442ms
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 4103): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/BooksAccountManager( 4070): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): Soft error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4070): Sync error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4070): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 711343, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4103): IOException
E/KeepSync( 4103): com.google.android.apiary.AuthenticationException: Could not get an auth token
,E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4103): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4103): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4103): 	,at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4103): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4103): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4103): 	... 10 more
,W/KeepSync( 4103): Sync result 2
D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 725222, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/ActivityManager(  821): Start proc 4492:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4492): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4492):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4492):   adb logcat -s GAv4
,W/GAv4    ( 4492): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4492): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4492): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  821): Killing 4007:android.process.acore/u0a5 (adj 15): empty #17
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/Finsky  ( 3930): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3930): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 3930): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3930): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3930): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3930): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3930): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 1751): client connected with version: 7571000
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1401): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1401): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1401): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1401): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1401): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1401): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1401): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3930): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3930): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3930): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3930): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3930): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3930): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3930): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3930): Ignoring header User-Agent because its value was null.,
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag,
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 52205(2MB) AllocSpace objects, 12(1323KB) LOS objects, 36% free, 27MB/43MB, paused 2.259ms total 63.419ms
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3930): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3930): [1] 5.onFinished: Scheduling replication attempt 1.,
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,V/KeepSync( 4103): Connecting to GoogleApiClient
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/HttpOperation( 2951): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at blb.a(PG:3937)
E/HttpOperation( 2951): 	at czp.a(PG:18188)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 12 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 14 more
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 4103): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,I/art     (  821): Explicit concurrent mark sweep GC freed 23674(1004KB) AllocSpace objects, 4(158KB) LOS objects, 31% free, 34MB/50MB, paused 1.890ms total 75.567ms
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at hec.a(PG:42)
E/HttpOperation( 2951): 	at hee.a(PG:102)
E/HttpOperation( 2951): 	at czr.a(PG:65)
E/HttpOperation( 2951): 	at kka.a(PG:108)
E/HttpOperation( 2951): 	at czp.a(PG:19176)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 15 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 17 more
,E/ExperimentLoader( 2951): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): 	at jdm.a(PG:82)
E/ExperimentLoader( 2951): 	at jcs.o(PG:406)
E/ExperimentLoader( 2951): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2951): 	at jcs.i(PG:143)
E/ExperimentLoader( 2951): 	at hec.a(PG:42)
E/ExperimentLoader( 2951): 	at hee.a(PG:102)
E/ExperimentLoader( 2951): 	at czr.a(PG:65)
E/ExperimentLoader( 2951): 	at kka.a(PG:108)
E/ExperimentLoader( 2951): 	at czp.a(PG:19176)
E/ExperimentLoader( 2951): 	at czp.a(PG:9081)
E/ExperimentLoader( 2951): 	at czq.run(PG:1686)
E/ExperimentLoader( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2951): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2951): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2951): 	at jdm.a(PG:77)
E/ExperimentLoader( 2951): 	... 15 more
E/ExperimentLoader( 2951): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2951): 	at fal.a(PG:38)
E/ExperimentLoader( 2951): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2951): 	... 17 more
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 779973, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 4103): IOException
E/KeepSync( 4103): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4103): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4103): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4103): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4103): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4103): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4103): 	... 10 more
W/KeepSync( 4103): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 774190, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 4070): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4070): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4070): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4070): Soft error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4070): Sync error,
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/BooksSync( 4070): Finished books sync
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 801593, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/Finsky  ( 3930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3930): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3930): [1] 5.onFinished: Scheduling replication attempt 2.
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/ProcessCpuTracker(  821): Skipping unknown process pid 4537
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3930): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3930): [1] 5.onFinished: Scheduling replication attempt 3.
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3930): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3930): [1] 5.onFinished: Scheduling replication attempt 4.
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag,
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL,
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3930): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3930): [1] 5.onFinished: Scheduling replication attempt 5.
,V/KeepSync( 4103): Connecting to GoogleApiClient
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 4103): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4103): IOException
E/KeepSync( 4103): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4103): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4103): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4103): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4103): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4103): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4103): 	... 10 more
W/KeepSync( 4103): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 867151, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 30875(1332KB) AllocSpace objects, 8(410KB) LOS objects, 31% free, 34MB/50MB, paused 2.062ms total 86.415ms
,D/Finsky  ( 3930): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3930): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3930): [1] 5.onFinished: Giving up after 6 failures.
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,I/BooksSync( 4070): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4070): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 50791(2MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 2.213ms total 67.360ms,
,E/BooksAccountManager( 4070): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4070): Soft error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4070): Sync error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4070): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 922254, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,I/EventLogService( 1779): Opted in for usage reporting
I/EventLogService( 1779): Aggregate from 1449216317089 (log), 1449215327119 (data)
,I/ServiceDumpSys( 1779): dumping service [account]
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,V/KeepSync( 4103): Connecting to GoogleApiClient
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 4103): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4103): IOException
E/KeepSync( 4103): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4103): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4103): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4103): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4103): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4103): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4103): 	... 10 more
W/KeepSync( 4103): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 998708, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2951): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at blb.a(PG:3937)
E/HttpOperation( 2951): 	at czp.a(PG:18188)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 12 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 14 more
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2951): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at hec.a(PG:42)
E/HttpOperation( 2951): 	at hee.a(PG:102)
E/HttpOperation( 2951): 	at czr.a(PG:65)
E/HttpOperation( 2951): 	at kka.a(PG:108)
E/HttpOperation( 2951): 	at czp.a(PG:19176)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 15 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 17 more
,E/ExperimentLoader( 2951): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 2951): 	at jdm.a(PG:82)
E/ExperimentLoader( 2951): 	at jcs.o(PG:406)
E/ExperimentLoader( 2951): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2951): 	at jcs.i(PG:143)
E/ExperimentLoader( 2951): 	at hec.a(PG:42)
E/ExperimentLoader( 2951): 	at hee.a(PG:102)
E/ExperimentLoader( 2951): 	at czr.a(PG:65)
E/ExperimentLoader( 2951): 	at kka.a(PG:108)
E/ExperimentLoader( 2951): 	at czp.a(PG:19176)
E/ExperimentLoader( 2951): 	at czp.a(PG:9081)
E/ExperimentLoader( 2951): 	at czq.run(PG:1686)
E/ExperimentLoader( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2951): ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2951): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2951): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2951): 	at jdm.a(PG:77)
E/ExperimentLoader( 2951): 	... 15 more
E/ExperimentLoader( 2951): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2951): 	at fal.a(PG:38)
E/ExperimentLoader( 2951): 	,at jdj.a(PG:4089)
E/ExperimentLoader( 2951): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1058912, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 4038): [432] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4038): [432] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4038): [432] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4038): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4038): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4038): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4038): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4038): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 4070): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4070): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 37009(1701KB) AllocSpace objects, 8(410KB) LOS objects, 31% free, 34MB/50MB, paused 1.411ms total 85.832ms
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4070): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4070): Soft error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4070): Sync error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4070): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1168768, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10,
D/        ( 3240): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
D/        ( 3240): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag,
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,V/KeepSync( 4103): Connecting to GoogleApiClient
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 4103): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4103): IOException
E/KeepSync( 4103): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4103): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4103): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4103): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4103): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4103): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4103): 	... 10 more
W/KeepSync( 4103): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1261412, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/GCM     ( 1401): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,W/bt-btif ( 3240): info:x10
,D/        ( 3240): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3240): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3240): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3240): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,I/art     ( 1401): Explicit concurrent mark sweep GC freed 63075(3MB) AllocSpace objects, 10(1102KB) LOS objects, 36% free, 27MB/43MB, paused 2.647ms total 72.540ms
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406)
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at blb.a(PG:3937)
E/HttpOperation( 2951): 	at czp.a(PG:18188)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 12 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 14 more
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2951): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 2951): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2951): 	at jdm.a(PG:82)
E/HttpOperation( 2951): 	at jcs.o(PG:406),
E/HttpOperation( 2951): 	at jcn.a(PG:1379)
E/HttpOperation( 2951): 	at jcs.i(PG:143)
E/HttpOperation( 2951): 	at hec.a(PG:42)
E/HttpOperation( 2951): 	at hee.a(PG:102)
E/HttpOperation( 2951): 	at czr.a(PG:65)
E/HttpOperation( 2951): 	at kka.a(PG:108)
,E/HttpOperation( 2951): 	at czp.a(PG:19176)
E/HttpOperation( 2951): 	at czp.a(PG:9081)
E/HttpOperation( 2951): 	at czq.run(PG:1686)
E/HttpOperation( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2951): 	at jdj.a(PG:4091)
E/HttpOperation( 2951): 	at jdj.a(PG:1125)
E/HttpOperation( 2951): 	at jdm.a(PG:77)
E/HttpOperation( 2951): 	... 15 more
E/HttpOperation( 2951): Caused by: faj: BadAuthentication
E/HttpOperation( 2951): 	at fal.a(PG:38)
E/HttpOperation( 2951): 	at jdj.a(PG:4089)
E/HttpOperation( 2951): 	... 17 more
E/ExperimentLoader( 2951): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 2951): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2951): 	at jdm.a(PG:82)
E/ExperimentLoader( 2951): 	at jcs.o(PG:406)
E/ExperimentLoader( 2951): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2951): 	at jcs.i(PG:143)
E/ExperimentLoader( 2951): 	at hec.a(PG:42)
E/ExperimentLoader( 2951): 	at hee.a(PG:102)
E/ExperimentLoader( 2951): 	at czr.a(PG:65)
E/ExperimentLoader( 2951): 	at kka.a(PG:108)
E/ExperimentLoader( 2951): 	at czp.a(PG:19176)
E/ExperimentLoader( 2951): 	at czp.a(PG:9081)
E/ExperimentLoader( 2951): 	at czq.run(PG:1686)
E/ExperimentLoader( 2951): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2951): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2951): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2951): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2951): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2951): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2951): 	at jdm.a(PG:77)
E/ExperimentLoader( 2951): 	... 15 more
E/ExperimentLoader( 2951): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2951): 	at fal.a(PG:38)
E/ExperimentLoader( 2951): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2951): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1574193, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,I/BooksSync( 4070): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4070): GmsCore Version = 7.8.99 (2134222-430),
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4070): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4070): Soft error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4070): Sync error
E/BooksSync( 4070): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4070): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4070): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1651541, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,V/KeepSync( 4103): Connecting to GoogleApiClient
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 53457(2MB) AllocSpace objects, 13(490KB) LOS objects, 31% free, 34MB/50MB, paused 2.228ms total 100.992ms
,E/ClientConnectionOperation( 1779): Handling authorization failure
E/ClientConnectionOperation( 1779): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1779): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1779): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1779): 	... 7 more
,V/KeepSync( 4103): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4103): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1401): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1401): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1401): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1401): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4103): IOException
E/KeepSync( 4103): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4103): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4103): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4103): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4103): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4103): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4103): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4103): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4103): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4103): 	... 10 more
W/KeepSync( 4103): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1786290, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  821): Prepared write state in 22ms
,I/ProcessStatsService(  821): Prepared write state in 9ms
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3240): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4773): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4773): CheckJNI is OFF
D/AndroidRuntime( 4773): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3182:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  821): Skipping PackageSetting{374dfde1 com.example.hello/10272} due to missing metadata
E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3182
W/ActivityManager(  821): Force removing ActivityRecord{66ebd69 u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
D/WifiService(  821): Client connection lost with reason: 4
V/ActivityManager(  821): Display changed displayId=0
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
I/Keyboard.Facilitator( 1198): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1198): run()
D/TaskPersister(  821): removeObsoleteFile: deleting file=24_task.xml
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1063): Explicit concurrent mark sweep GC freed 84389(3MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 75MB/91MB, paused 1.586ms total 51.403ms
I/art     (  821): Explicit concurrent mark sweep GC freed 19500(1273KB) AllocSpace objects, 8(397KB) LOS objects, 32% free, 33MB/49MB, paused 1.372ms total 74.025ms
I/art     (  821): WaitForGcToComplete blocked for 70.410ms for cause Explicit
I/Decoder ( 1198): createOrResetDecoder
I/art     ( 1523): Explicit concurrent mark sweep GC freed 16752(899KB) AllocSpace objects, 2(32KB) LOS objects, 22% free, 26MB/34MB, paused 329us total 84.632ms
D/BuaReceiver( 3046): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/ActivityManager(  821): Start proc 4789:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/ConfigService( 1401): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1198): run()
W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3182 uid 10265
I/Keyboard.Facilitator( 1198): onFinishInput()
D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/Keyboard.Facilitator.MainLanguageModelLoader( 1198): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1198): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1198): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1198): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1198): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1198): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1198): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1198): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1198): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1198): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1198): run()
I/StatsUtilsManager( 1198): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1198): shouldRecordStats() = Too Soon
I/art     (  821): Explicit concurrent mark sweep GC freed 3546(169KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.730ms total 98.328ms
W/LocationOracleImpl( 1523): Best location was null
I/HotwordRecognitionRnr( 1523): Starting hotword detection.
I/MicrophoneInputStream( 1523): mic_starting com.google.android.apps.gsa.speech.audio.u@b28a3cc
I/art     ( 1293): Explicit concurrent mark sweep GC freed 12367(707KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.008ms total 34.411ms
I/AudioFlinger(  359): AudioFlinger's thread 0xb4093000 ready to run
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1523): mic_started com.google.android.apps.gsa.speech.audio.u@b28a3cc
D/audio_hw_primary(  359): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  359): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  359): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  359): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  359): enable_audio_route: apply and update mixer path: audio-record
W/LocationOracleImpl( 1523): Best location was null
D/VoicemailCleanupService( 4789): Cleaning up data for package: com.test.thalitest
W/LocationOracleImpl( 1523): Best location was null
I/ActivityManager(  821): Start proc 4827:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/WebViewFactory( 1523): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/LocationOracleImpl( 1523): Best location was null
I/LibraryLoader( 1523): Time to load native libraries: 2 ms (timestamps 5624-5626)
I/LibraryLoader( 1523): Expected native library version number "",actual native library version number ""
W/art     ( 1523): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 4773): System.exit called, status: 0
I/AndroidRuntime( 4773): VM exiting with result code 0.
I/ContactLocale( 4789): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/HotwordWorker( 1523): onReady
I/ActivityManager(  821): Start proc 4855:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2bbad07d}
W/art     ( 1523): Attempt to remove local handle scope entry from IRT, ignoring
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.75 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
W/ContextImpl( 4855): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=25.38 rxSuccessRate=241.25 targetRoamBSSID=any RSSI=-127
E/NetworkScheduler.SchedulerReceiver( 1401): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1401): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  821): Killing 3966:com.google.android.gms:car/u0a11 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1702135059
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
D/Launcher.Workspace( 1293): 11683562 - stripEmptyScreens()
D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1779): Module APK com.google.android.play.games already loaded
D/Launcher.Workspace( 1293): 11683562 - stripEmptyScreens()
D/PackageBroadcastService( 1779): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1779): Clearing selected account for com.test.thalitest
E/SQLiteLog( 1293): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
D/ChimeraCfgMgr( 1779): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1779): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1779): Removing dialog suppression flag for package com.test.thalitest
I/UpdateIcingCorporaServi( 1523): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteLog( 1779): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1779): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1779): disk I/O error (code 3850)
E/DriveAsyncService( 1779): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1779): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1779): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1779): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1779): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1779): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1779): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1779): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1779): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1779): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1779): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1779): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 1779): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1779): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1779): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1779): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1779): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1779): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1779): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1779): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1779): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1779): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1779): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1779): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1779): Opened phenotype.db in read-only mode
E/SQLiteDatabase( 1779): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1779): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1779): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1779): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1779): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1779): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1779): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1779): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1779): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1779): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 1779): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1779): Process: com.google.android.gms, PID: 1779
E/AndroidRuntime( 1779): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1779): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1779): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1779): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1779): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1779): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1779): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1779): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1779): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1779): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1779): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1779): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1779): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1779): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1779): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1779): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1779): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1779): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1779): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1779): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1779): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1779): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1779): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1779): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1779): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1779): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1779): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1779): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1779): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1779): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1779): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1779): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
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
W/SQLiteOpenHelper( 1779): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1779): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1779): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1779): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1779): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1779): Sending signal. PID: 1779 SIG: 9
E/SQLiteLog( 1523): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/Launcher( 1293): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2596ca4 new=com.google.android.velvet.VelvetApplication@2596ca4
E/SQLiteLog( 1293): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  821): Validating map...
I/OpenGLRenderer(  821): Initialized EGL, version 1.4
I/ActivityManager(  821): Start proc 4896:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 1523): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 1523): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1523): Process: com.google.android.googlequicksearchbox:search, PID: 1523
E/AndroidRuntime( 1523): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1523): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1523): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1523): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1523): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1523): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1523): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1523): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 1523): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 1523): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 1523): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 1523): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1523): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/OpenGLRenderer(  821): Enabling debug mode 0
I/ActivityManager(  821): Start proc 4915:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
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
D/WifiService(  821): Client connection lost with reason: 4
I/ActivityManager(  821): Process com.google.android.gms (pid 1779) has died
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10999ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
I/ActivityManager(  821): Start proc 4934:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
W/ResourcesManager( 4934): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4934): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/HotwordDetector( 1523): Closing mic
I/MicrophoneInputStream( 1523): mic_close com.google.android.apps.gsa.speech.audio.u@b28a3cc
I/MultiDex( 4934): VM with version 2.1.0 has multidex support
I/MultiDex( 4934): install
I/MultiDex( 4934): VM has multidex support, MultiDex support library is disabled.
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1523): Stopping hotword detection.
I/HotwordRecognitionRnr( 1523): Hotword detection finished
E/SQLiteDatabase( 4934): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4934): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 4934): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 4934): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4934): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4934): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4934): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4934): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4934): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4934): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 4934): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 4934): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4934): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4934): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4934): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4934): 	at java.lang.Thread.run(Thread.java:818)
V/JNIHelp ( 4934): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ProviderInstaller( 4934): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 4934): Failed to open lock file
W/NativeLibraryUtils( 4934): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4934): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4934): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4934): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4934): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4934): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4934): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4934): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4934): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4934): 	... 3 more
I/ActivityManager(  821): Killing 4192:com.android.settings/1000 (adj 15): empty #17
E/SQLiteDatabase( 4934): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 4934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4934): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteDatabase( 4934): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4934): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4934): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 4934): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 4934): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteDatabase( 4934): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteDatabase( 4934): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4934): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4934): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4934): 	at java.lang.Thread.run(Thread.java:818)
I/GAv4    ( 4915): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4915):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4915):   adb logcat -s GAv4
E/SQLiteOpenHelper( 4934): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 4934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4934): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteOpenHelper( 4934): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteOpenHelper( 4934): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteOpenHelper( 4934): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteOpenHelper( 4934): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteOpenHelper( 4934): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteOpenHelper( 4934): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteOpenHelper( 4934): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteOpenHelper( 4934): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4934): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 4934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4934): 	at java.lang.Thread.run(Thread.java:818)
I/Icing   ( 4934): Storage manager: low false usage 1.98MB avail 20.74GB capacity 22.09GB
W/SQLiteOpenHelper( 4934): Opened reminders.db in read-only mode
W/GAv4    ( 4915): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/SQLiteDatabase( 4934): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 4934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4934): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/SQLiteDatabase( 4934): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 4934): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 4934): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4934): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4934): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4934): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4934): FATAL EXCEPTION: AsyncTask #3
E/AndroidRuntime( 4934): Process: com.google.android.gms, PID: 4934
E/AndroidRuntime( 4934): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 4934): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/AndroidRuntime( 4934): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 4934): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 4934): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 4934): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 4934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4934): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4934): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4934): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/AndroidRuntime( 4934): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 4934): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 4934): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AndroidRuntime( 4934): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4934): 	... 4 more
W/GAv4    ( 4915): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
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
D/GFEEDBACK_SendErrorReportOperation( 4934): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 4934): Error saving report: java.io.IOException: failed to create reports directory
W/GAv4    ( 4915): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4915): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4915): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4915): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4915): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4915): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4915): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4915): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4915): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4915): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4915): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4915): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4915): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4915): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4915): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4915): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4915): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4915): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4915): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4915): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4915): 	at gir$c.run(Unknown Source)
E/SQLiteDatabase( 4915): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4915): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4915): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4915): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4915): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4915): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4915): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4915): 	at aen.run(PG:536)
E/GAv4    ( 4915): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4915): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/Icing   ( 4934): Received bad json for section weights override -- ignoring.
E/SQLiteDatabase( 4915): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4915): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4915): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4915): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4915): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4915): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4915): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4915): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4915): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4915): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4915): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4915): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4915): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4915): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4915): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4915): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4915): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/Icing   ( 4934): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 4934): Received bad json for section weights override -- ignoring.
W/Icing   ( 4934): Received bad json for corpus context scoring override -- ignoring.
E/SharedPreferencesImpl( 4915): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4915): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4915): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4915): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4915): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/native  ( 1198): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1198): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1198): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1198): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/GAv4-SVC( 4934): Google Analytics 7.8.99 is starting up.
E/native  ( 1198): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1198): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1198): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1198): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/SQLiteDatabase( 4915): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4915): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4915): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4915): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4915): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4915): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4915): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4915): 	at aej.c(PG:139)
E/SQLiteDatabase( 4915): 	at aej.b(PG:398)
E/SQLiteDatabase( 4915): 	at agf.f(PG:417)
E/SQLiteDatabase( 4915): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4915): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4915): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4915): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4915): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4915): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 49,15): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4915): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4915): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4915): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4915): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4915): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4915): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4915): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4915): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4915): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4915): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4915): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4915): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4915): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4915): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4915): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4915): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4915): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4915): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4915): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4915): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 4915): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4915): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 1401): Explicit concurrent mark sweep GC freed 55231(2MB) AllocSpace objects, 10(914KB) LOS objects, 37% free, 27MB/43MB, paused 1.582ms total 42.814ms
W/GAv4    ( 4915): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4915): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4915): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4915): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/Icing   ( 4934): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids for write failed: Read-only file system
E/Icing   ( 4934): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids
E/Icing   ( 4934): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata for write failed: Read-only file system
E/Icing   ( 4934): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
E/Icing   ( 4934): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring for write failed: Read-only file system
E/Icing   ( 4934): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
E/Icing   ( 4934): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs for write failed: Read-only file system
E/Icing   ( 4934): Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs
E/Icing   ( 4934): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.tags.h for write failed: Read-only file system
E/Icing   ( 4934): Trie initialize fail
E/Icing   ( 4934): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
E/Icing   ( 4934): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h for write failed: Read-only file system
E/Icing   ( 4934): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
E/Icing   ( 4934): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
E/Icing   ( 4934): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
E/Icing   ( 4934): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
E/Icing   ( 4934): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
E/Icing   ( 4934): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage for write failed: Read-only file system
E/Icing   ( 4934): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
E/Icing   ( 4934): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage for write failed: Read-only file system
E/Icing   ( 4934): Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
E/Icing   ( 4934): Init docstore failed
E/Icing   ( 4934): Index init failed, resetting corpora
W/GAv4    ( 4915): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4915): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak

```
