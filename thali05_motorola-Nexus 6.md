#### Test 513350284d87320_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2721): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2721): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2721): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3201): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3201): CheckJNI is OFF
D/AndroidRuntime( 3201): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{26d69f6c token=Token{3088b01f ActivityRecord{347897be u0 com.test.thalitest/.MainActivity t22}}} to stack=1 task=22 at 0
V/WindowManager(  822): Adding window Window{1290f3b1 u0 Starting com.test.thalitest} at 3 of 8 (after Window{2ec3fdb6 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
D/AndroidRuntime( 3201): Shutting down VM
I/HotwordDetector( 1534): Closing mic
I/MicrophoneInputStream( 1534): mic_close com.google.android.apps.gsa.speech.audio.u@1d4ca7d1
I/ActivityManager(  822): Start proc 3216:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1534): Stopping hotword detection.
I/HotwordRecognitionRnr( 1534): Hotword detection finished
I/ActivityManager(  822): Killing 2680:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660314899
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  822): Killing 2812:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,I/WebViewFactory( 3216): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/LibraryLoader( 3216): Time to load native libraries: 5 ms (timestamps 3091-3096)
I/LibraryLoader( 3216): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3216): Binding Chromium to main looper Looper (main, tid 1) {3ad72f2e}
I/LibraryLoader( 3216): Expected native library version number "",actual native library version number ""
I/chromium( 3216): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3216): Initializing chromium process, singleProcess=true
,W/art     ( 3216): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3216): ApplicationContext is null in ApplicationStatus
,W/chromium( 3216): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3216): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 3216): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 3216): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3216): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12d52b21:true
D/BluetoothAdapter( 3216): 129186017: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3216): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3216): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3216): CordovaWebView is running on device made by: motorola
,W/art     ( 3216): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 3216): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3216): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3216): Validating map...
,V/WindowManager(  822): Adding window Window{370e1e91 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{1290f3b1 u0 Starting com.test.thalitest})
,W/chromium( 3216): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3216): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3216): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +883ms (total +1m50s485ms)
,I/Keyboard.Facilitator( 1221): onFinishInput()
,W/BindingManager( 3216): Cannot call determinedVisibility() - never saw a connection for the pid: 3216
,D/JsMessageQueue( 3216): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3216): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576389760
D/JX-Cordova( 3216): jxcore cordova android initializing
,I/kickstart(  871): STATUS: Received file 'm9kefs2'
,I/kickstart(  871): STATUS: 950272 bytes transferred in 0.991889 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed
,W/jxcore-log( 3216): Initializing JXcore engine
W/jxcore-log( 3216): JXcore engine is ready
,W/jxcore-log( 3216): Starting JXcore engine
,W/.test.thalitest( 3216): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11590]" dev="sockfs" ino=11590 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3216): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3216): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[12848]" dev="sockfs" ino=12848 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3216): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19298]" dev="sockfs" ino=19298 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3216): Platform android
W/jxcore-log( 3216): 
W/jxcore-log( 3216): Process ARCH arm,
W/jxcore-log( 3216): 
,I/jxcore-log( 3216): JXcore Cordova bridge is ready!
I/jxcore-log( 3216): 
,W/jxcore-log( 3216): JXcore engine is started
I/Choreographer( 3216): Skipped 128 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3216): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3216): Turning radios to true
I/jxcore-log( 3216): 
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  822): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  822): Message: 1
D/BluetoothManagerService(  822): MESSAGE_ENABLE: mBluetooth = null
,I/jxcore-log( 3216): toggleBluetooth - 
I/jxcore-log( 3216): 
,D/WifiService(  822): New client listening to asynchronous messages
D/WifiService(  822): setWifiEnabled: true pid=3216, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3216): toggleWiFi
I/jxcore-log( 3216): 
D/SoftapController(  353): Softap fwReload - Ok
D/CommandListener(  353): Setting iface cfg
D/CommandListener(  353): Trying to bring down wlan0
D/CommandListener(  353): Clearing all IP addresses on wlan0
,E/WifiMonitor(  822): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  822): Start proc 3272:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,W/ResourcesManager( 3272): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/WifiMonitor(  822): startMonitoring(wlan0) with mConnected = false
,E/WifiHW  (  822): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/ActivityManager(  822): Start proc 3291:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/wpa_supplicant( 3290): Successfully initialized wpa_supplicant
,D/AdapterServiceConfig( 3272): Adding HeadsetService
D/AdapterServiceConfig( 3272): Adding A2dpService
D/AdapterServiceConfig( 3272): Adding HidService
D/AdapterServiceConfig( 3272): Adding HealthService
D/AdapterServiceConfig( 3272): Adding PanService
D/AdapterServiceConfig( 3272): Adding GattService
D/AdapterServiceConfig( 3272): Adding BluetoothMapService
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a48a4da:true
,D/BluetoothAdapterState( 3272): make
,I/bluedroid( 3272): init
I/BluetoothAdapterState( 3272): Entering OffState
,I/bte_conf( 3272): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3272): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3272): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3272): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3272): get_profile_interface socket
,I/GKI_LINUX( 3272): gki_task_entry task_id=1 [BTIF] starting,
I/bluedroid( 3272): get_profile_interface map_client
D/BluetoothAdapterProperties( 3272): Address is:F8:CF:C5:D9:E5:61,
D/BluetoothManagerService(  822): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService,
D/BluetoothManagerService(  822): Message: 40
,D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 3272): Name is: Nexus 6
I/bluedroid( 3272): config_hci_snoop_log
D/BluetoothManagerService(  822): Bluetooth Adapter name changed to Nexus 6,
D/BluetoothManagerService(  822): Stored Bluetooth name: Nexus 6
,I/wpa_supplicant( 3290): rfkill: Cannot open RFKILL control device
,I/art     ( 1506): Explicit concurrent mark sweep GC freed 27235(1444KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 656us total 20.035ms
,I/art     (  822): Explicit concurrent mark sweep GC freed 17115(822KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.732ms total 77.700ms
,D/BluetoothManagerService(  822): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  822): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3272): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3272): Setting state to 11
I/BluetoothAdapterState( 3272): Bluetooth adapter state changed: 10-> 11
,D/BluetoothBondStateMachine( 3272): make
,D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  822): Bluetooth State Change Intent: 10 -> 11
I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,I/ActivityManager(  822): Start proc 3322:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
I/ActivityManager(  822): Killing 2849:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 277us total 9.680ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 191us total 9.163ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 194us total 8.580ms
,I/BluetoothAdapterState( 3272): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9934acf
,D/HeadsetService( 3272): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3272): classInitNative: succeeds
,D/HeadsetStateMachine( 3272): make
,D/HeadsetStateMachine( 3272): max_hf_connections = 1
I/bluedroid( 3272): get_profile_interface handsfree
,D/HeadsetStateMachine( 3272): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9934acf
,D/BluetoothA2dp(  822): Proxy object connected
D/A2dpService( 3272): Received start request. Starting profile...
D/BluetoothA2dp( 1074): Proxy object connected
I/BluetoothAvrcpServiceJni( 3272): classInitNative: succeeds
I/bluedroid( 3272): get_profile_interface avrcp
,E/RemoteController( 3272): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 3272): classInitNative: succeeds
D/A2dpStateMachine( 3272): make
,I/bluedroid( 3272): get_profile_interface a2dp
I/GKI_LINUX( 3272): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3272): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3272): classInitNative: succeeds
D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9934acf
D/BluetoothInputDevice( 1074): Proxy object connected
,D/HidService( 3272): Received start request. Starting profile...
I/bluedroid( 3272): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3272): classInitNative: succeeds
D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9934acf
D/HealthService( 3272): Received start request. Starting profile...
,I/bluedroid( 3272): get_profile_interface health
,I/BluetoothPanServiceJni( 3272): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9934acf
D/BluetoothPan( 1074): BluetoothPAN Proxy object connected
D/PanService( 3272): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3272): initializeNative(L110): pan
I/bluedroid( 3272): get_profile_interface pan
I/BtGatt.JNI( 3272): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9934acf
D/BtGatt.DebugUtils( 3272): handleDebugAction() action=null
D/BtGatt.GattService( 3272): Received start request. Starting profile...
D/BtGatt.GattService( 3272): start()
,I/bluedroid( 3272): get_profile_interface gatt
D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9934acf
D/BtGatt.AdvertiseManager( 3272): advertise manager created
,D/BluetoothAdapterService( 3272): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9934acf
,D/BluetoothMap( 1074): Proxy object connected
,D/BluetoothMapService( 3272): Received start request. Starting profile...
D/BluetoothMapService( 3272): start()
D/BluetoothMapEmailSettingsLoader( 3272): Found 0 applications
D/BluetoothMapEmailAppObserver( 3272): createReceiver()
D/BluetoothMapEmailAppObserver( 3272): initObservers()
D/BluetoothMapEmailAppObserver( 3272): getEnabledAccountItems()
D/HeadsetStateMachine( 3272): Proxy object connected
D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3272): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3272): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3272): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3272): enable
I/GKI_LINUX( 3272): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3272): btu_task pending for preload complete event
I/bt_hci_bdroid( 3272): init
,I/bt_vendor( 3272): init
I/bt_vnd_conf( 3272): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3272): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3272): userial_init
,I/bt_userial_vendor( 3272): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3272): device fd = 53 open
D/bt_userial( 3272): Entering userial_read_thread()
,I/ActivityManager(  822): Start proc 3359:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/bt_hwcfg( 3272): bt vendor lib: set UART baud 3000000
,I/ActivityManager(  822): Killing 2779:com.google.android.gm/u0a78 (adj 15): empty #17
,D/bt_hwcfg( 3272): Chipset BCM4354A2
D/bt_hwcfg( 3272): Target name = [BCM4354A2]
I/bt_hwcfg( 3272): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,D/Tethering(  822): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3290): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant( 3290): Could not read interface p2p-dev-wlan0 flags: No such device
,I/ActivityManager(  822): Killing 2368:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/bt_hwcfg( 3272): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3272): Settlement delay -- 100 ms
,I/bt_hwcfg( 3272): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3272): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3272): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3272): vendor lib fwcfg completed
I/bt-btu  ( 3272): btu_task received preload complete event
,D/WifiConfigStore(  822): Loading config and enabling all networks 
,I/        ( 3272): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3272): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3272): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3272): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3272): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3272): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3272): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3272): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3272): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3272): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3272): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3272): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3272): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3272): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3272): BTE_InitTraceLevels -- TRC_BTIF
,E/WifiConfigStore(  822): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3610f492}
,I/ActivityManager(  822): Start proc 3377:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/WifiNative-HAL(  822): Setting external_sim to 1
,D/WifiStateMachine(  822): Setting OUI to 92-68-C3
I/WifiNative-HAL(  822): startHal
D/wifi    (  822): setting scan oui 0xaec54fd0
D/WifiHAL (  822): Sending mac address OUI
W/Settings( 2642): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine(  822): cancelDelayedScan -> 1
,W/CommandListener(  353): Failed to retrieve HW addr for p2p0 (No such device)
,D/CommandListener(  353): Setting iface cfg
D/WifiScanningService(  822): SCAN_AVAILABLE : 3
,D/RttService(  822): SCAN_AVAILABLE : 3
D/WifiScanningService(  822): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  822): startHal
,D/RttService(  822): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiP2pService(  822): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  822): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 3290): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/wifi    (  822): getting scan capabilities on interface[0] = 0xaec54fd0
,D/WifiHAL (  822): Creating message to get scan capablities; iface = 5
D/WifiHAL (  822): In GetCapabilities::handleResponse
D/WifiHAL (  822): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  822): StartedState
,D/WifiNative-HAL(  822): p2pGetDeviceAddress
,D/WifiNative-HAL(  822): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,E/native  (  822): do suspend false
,E/bt-btm  ( 3272): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2df5085 
E/bt-btm  ( 3272): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2df5085 
,D/BluetoothAdapterProperties( 3272): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3272): Calling BTA_HhEnable
E/bt-btif ( 3272): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3272): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  822): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3272): Name is: Nexus 6
D/BluetoothAdapterProperties( 3272): Scan Mode:20
D/BluetoothAdapterProperties( 3272): Discoverable Timeout:120
,D/bte_conf( 3272): Device ID record 1 : primary
,D/bte_conf( 3272):   vendorId            = 000f
,D/bte_conf( 3272):   vendorIdSource      = 0001
D/bte_conf( 3272):   product             = 1200,
,D/bte_conf( 3272):   version             = 1436
D/bte_conf( 3272):   clientExecutableURL = 
,D/bte_conf( 3272):   serviceDescription  = 
D/bte_conf( 3272):   documentationURL    = 
D/bte_conf( 3272): bte_load_did_conf no section named DID2.,
D/BluetoothAdapterState( 3272): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3272): ScanMode =  20
,D/BluetoothPanServiceJni( 3272): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 3272): State =  11
D/BluetoothAdapterProperties( 3272): Setting state to 12,
I/BluetoothAdapterState( 3272): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterState( 3272): Entering On State
,D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  822): Broadcasting onBluetoothStateChange(true) to 13 receivers.
,D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
D/BluetoothManagerService(  822): Creating new ProfileServiceConnections object for profile: 1
D/BluetoothAvrcpController( 1074): onBluetoothStateChange: up=true,
D/BluetoothAdapterProperties( 3272): Scan Mode:21,
,D/BluetoothAdapterProperties( 3272): Discoverable Timeout:120
E/BluetoothAvrcpController( 1074): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothPan( 1074): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1074): onBluetoothStateChange: up=true
D/BluetoothHeadsetClient( 1074): onBluetoothStateChange: up=true
E/BluetoothHeadsetClient( 1074): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothHeadset( 1284): onBluetoothStateChange: up=true
D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1074): onBluetoothStateChange: up=true
D/BluetoothMap( 1074): onBluetoothStateChange: up=true
D/BluetoothA2dpSink( 1074): onBluetoothStateChange: up=true
,E/BluetoothA2dpSink( 1074): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothInputDevice( 1074): onBluetoothStateChange: up=true
D/BluetoothA2dp(  822): onBluetoothStateChange: up=true
D/BluetoothManagerService(  822): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  822): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3272): onReceive
D/BluetoothMapService( 3272): STATE_ON
D/BluetoothMapMasInstance( 3272): Map Service startRfcommSocketListener
D/BluetoothManagerService(  822): Message: 40
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapMasInstance( 3272): MAS initSocket()
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/StrictMode( 3377): StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3377): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3377): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3377): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3377): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3377): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3377): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3377): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3377): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3377): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3377): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3377): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3377): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3377): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3377): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3377): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3377): StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3377): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3377): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3377): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3377): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3377): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3377): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3377): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3377): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3377): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3377): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3377): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3377): StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3377): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3377): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3377): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3377): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3377): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3377): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3377): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3377): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3377): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3377): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3377): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3377): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3377): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3377): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3377): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3377): StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3377): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3377): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3377): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3377): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3377): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3377): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3377): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3377): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3377): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3377): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3377): StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3377): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3377): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3377): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3377): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3377): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoade,r.java:77)
D/StrictMode( 3377): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3377): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3377): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3377): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3377): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3377): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3377): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3377): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3377): StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3377): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3377): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3377): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3377): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3377): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3377): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3377): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3377): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3377): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3377): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3377): # via Binder call with stack:
D/StrictMode( 3377): android.os.StrictMode$LogStackTrace
D/StrictMode( 3377): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3377): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3377): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3377): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3377): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3377): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3377): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3377): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
,D/StrictMode( 3377): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3377): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3377): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3377): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
,D/StrictMode( 3377): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3377): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3377): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3377): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3377): StrictMode policy violation; ~duration=46 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3377): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3377): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3377): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3377): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3377): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3377): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3377): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3377): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3377): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3377): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3377): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3377): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3377): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3377): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3377): 	,at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3377): StrictMode policy violation; ~duration=45 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3377): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3377): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3377): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3377): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3377): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3377): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3377): 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3377): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3377): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3377): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3377): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3377): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3377): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3377): StrictMode policy violation; ~duration=45 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3377): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3377): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3377): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3377): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3377): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3377): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
,D/StrictMode( 3377): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3377): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3377): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3377): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3377): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3377): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3377): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Native Method)
,D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3377): StrictMode policy violation; ~duration=44 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3377): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3377): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3377): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3377): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3377): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3377): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3377): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3377): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3377): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3377): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3377): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3377): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3377): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3377): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3377): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3377): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3377): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3377): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3377): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3377): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3377): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3377): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/bt_h4   ( 3272): vendor lib postload completed
W/bt-btm  ( 3272): Stopping oneshot timer
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothMapMasInstance( 3272): Accepting socket connection...
,W/bt-btm  ( 3272): Stopping oneshot timer
,W/bt-btm  ( 3272): Stopping oneshot timer
,W/bt-btm  ( 3272): Stopping oneshot timer
,W/bt-btm  ( 3272): Stopping oneshot timer
,W/com.google.a.a.a.b.a( 3377): Application name is not set. Call Builder#setApplicationName.,
,W/bt-btm  ( 3272): Stopping oneshot timer
,W/bt-btm  ( 3272): Stopping oneshot timer
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3067d5b7:true
,I/ActivityManager(  822): Killing 2880:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/BluetoothManagerService(  822): Message: 400
D/BluetoothHeadset(  822): Proxy object connected
,D/BluetoothManagerService(  822): Message: 400
D/BluetoothHeadset(  822): Proxy object connected
D/BluetoothManagerService(  822): Message: 400
D/BluetoothHeadset( 1074): Proxy object connected
,D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset( 1284): Proxy object connected
,D/BluetoothManagerService(  822): Message: 400
D/BluetoothHeadset(  822): Proxy object connected
,D/AuthorizationBluetoothService( 1506): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3359): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  822): Message: 20
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@996e3c1:true
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3359): Adding local A2DP profile
,D/AuthorizationBluetoothService( 1506): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3359): Adding local HEADSET profile
,I/BtOppRfcommListener( 3272): Accept thread started.
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/LocalBluetoothProfileManager( 3359): Adding local MAP profile
,D/BluetoothMap( 3359): Create BluetoothMap proxy object
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/LocalBluetoothProfileManager( 3359): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3359): finishStartingService: stopping service
,D/BluetoothA2dp( 3359): Proxy object connected
D/A2dpProfile( 3359): Bluetooth service connected
,D/BluetoothInputDevice( 3359): Proxy object connected
D/HidProfile( 3359): Bluetooth service connected
,D/BluetoothPan( 3359): BluetoothPAN Proxy object connected
,D/PanProfile( 3359): Bluetooth service connected
D/BluetoothMap( 3359): Proxy object connected
D/MapProfile( 3359): Bluetooth service connected
D/BluetoothMap( 3359): getConnectedDevices()
,D/BluetoothPbap( 3359): Proxy object connected
D/PbapServerProfile( 3359): Bluetooth service connected
,D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset( 3359): Proxy object connected
,D/HeadsetProfile( 3359): Bluetooth service connected
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3216): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): my name is : motorola-Nexus 6_PT5015
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): attempting to connect to test coordinator
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): check test folder
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found test : ./testFindPeers.js
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found test : ./testReConnect.js
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found test : ./testSendData.js
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Test app app.js loaded
I/jxcore-log( 3216): 
,I/Choreographer( 3216): Skipped 130 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): LogCallback not set !!!!,
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3290): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  822):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  822):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): writeKnownNetworkHistory write linked 1
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
E/WifiConfigStore(  822): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  822): will read network variables netId=0
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,I/wpa_supplicant( 3290): wlan0: Trying to associate with SSID 'NG7005g'
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3290): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3290): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3290): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  822): Start Dhcp Watchdog 1
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 1
E/WifiStateMachine(  822):  RSSI mgmt: -45
E/WifiStateMachine(  822):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 0 tx_time=59 rx_time=102 scan_time=0
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting
,I/dhcpcd  ( 3419): version 5.5.6 starting
,I/dhcpcd  ( 3419): wlan0: rebinding lease of 192.168.1.110
,I/dhcpcd  ( 3419): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 3419): wlan0: leased 192.168.1.110 for 86400 seconds
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 100,
E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
D/ConnectivityService(  822): Setting Dns servers for network 100 to [/192.168.1.1]
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100],
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  822):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  822): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1074): CM callback handler got msg 524290
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/Tethering(  822): MasterInitialState.processMessage what=3
,V/BackupManagerService(  822): Scheduling immediate backup pass
,D/PhoneInterfaceManager( 1284): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1284): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,I/ActivityManager(  822): Start proc 3456:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
V/BackupManagerService(  822): Running a backup pass
,V/BackupManagerService(  822): clearing pending backups
,E/GpsLocationProvider(  822): No APN found to select.
,V/PerformBackupTask(  822): Beginning backup of 14 targets
,D/PerformBackupTask(  822): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  822): doBackup() invoked
,I/PMBA    (  822): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  822): Getting widget state for user: 0
,D/AlarmManagerService(  822): Setting time of day to sec=1448274331
W/AlarmManagerService(  822): Unable to set rtc to 1448274331: Invalid argument
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 23 Nov 2015 10:25:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448274331020], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448274330105]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Validated
,D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1074): CM callback handler got msg 524290
,W/GmsBackupTransport( 1759): Unknown package in backup request: @pm@
V/GmsBackupTransport( 1759): starting performBackup for @pm@
V/GmsBackupTransport( 1759): performBackup done for @pm@
,D/GpsLocationProvider(  822): NTP server returned: 1448274331006 (Mon Nov 23 11:25:31 GMT+01:00 2015) reference: 152068 certainty: 18 system time offset: -40
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicStore( 3456): Database version: 120
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1791): [CredentialSyncAdapter] Unknown sync event.
,W/GLSActivity( 1506): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1506): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1506): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1506): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1506): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1506): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1506): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1759): Error sending final backup to server: 
W/GmsBackupTransport( 1759): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1759): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1759): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1759): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1759): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1759): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1759): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1759): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1759): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1759): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1759): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1759): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1759): 	... 1 more
D/BackupManagerService(  822): Now staging backup of com.google.android.talk
,D/BackupManagerService(  822): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  822): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  822): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  822): Now staging backup of com.google.android.gm
,D/BackupManagerService(  822): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  822): Now staging backup of com.android.nfc
,D/BackupManagerService(  822): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  822): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  822): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  822): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  822): Now staging backup of com.android.vending
,D/BackupManagerService(  822): Now staging backup of android
,D/BackupManagerService(  822): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1759): Next backup will happen in 43199925 millis.
,I/BackupManagerService(  822): Backup pass finished.
,I/art     ( 1506): Explicit concurrent mark sweep GC freed 8458(435KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 871us total 22.032ms
,W/DriveInitializer( 1791): Background init thread started
,W/DriveInitializer( 1791): Awaiting to be initialized
,W/ResourcesManager( 3456): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3456): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  822): Explicit concurrent mark sweep GC freed 49213(2MB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.243ms total 54.949ms
,V/JNIHelp ( 3456): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3456): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3456): GMSCore installation verified
,I/ConfigStore( 3456): Config Database version: 1
,W/DriveInitializer( 1791): Background init thread ended
,I/MediaRouter( 3456): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3456): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3456): type=WIFI subType= reason=null isConnected=true
,V/KeepSync( 3322): Connecting to GoogleApiClient
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2988): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at blb.a(PG:3937)
E/HttpOperation( 2988): 	at czp.a(PG:18188)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 12 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 14 more
,I/NetworkMonitor( 3456): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  822): Start proc 3516:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GHttpClientFactory( 3456): Using our fixed implementation of GMSCore's GoogleHttpClient
,E/HttpOperation( 2988): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at hec.a(PG:42)
E/HttpOperation( 2988): 	at hee.a(PG:102)
E/HttpOperation( 2988): 	at czr.a(PG:65)
E/HttpOperation( 2988): 	at kka.a(PG:108)
E/HttpOperation( 2988): 	at czp.a(PG:19176)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 15 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 17 more
E/ExperimentLoader( 2988): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): 	at jdm.a(PG:82)
E/ExperimentLoader( 2988): 	at jcs.o(PG:406)
E/ExperimentLoader( 2988): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2988): 	at jcs.i(PG:143)
E/ExperimentLoader( 2988): 	at hec.a(PG:42)
E/ExperimentLoader( 2988): 	at hee.a(PG:102)
E/ExperimentLoader( 2988): 	at czr.a(PG:65)
E/ExperimentLoader( 2988): 	at kka.a(PG:108)
E/ExperimentLoader( 2988): 	at czp.a(PG:19176)
E/ExperimentLoader( 2988): 	at czp.a(PG:9081)
E/ExperimentLoader( 2988): 	at czq.run(PG:1686)
E/ExperimentLoader( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2988): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2988): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2988): 	at jdm.a(PG:77)
E/ExperimentLoader( 2988): 	... 15 more
E/ExperimentLoader( 2988): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2988): 	at fal.a(PG:38)
E/ExperimentLoader( 2988): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2988): 	... 17 more
,I/GoogleURLConnFactory( 3456): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 3516): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,W/BaseAppContext( 1791): Using Auth Proxy for data requests.
,D/SprintDMHelper( 3516): simOperator:  IMSI: null
D/SprintDMReceiver( 3516): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1791): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1791): onCreate
,D/SystemUpdateService( 1791): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1791): active receiver: enabled
,I/SystemUpdateService( 1791): showing system update notification
,W/BaseAppContext( 1791): Using Auth Proxy for data requests.
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1791): retry (wakeup: false) in 3599974 ms
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.SyncManager( 1791): SYNC; picasa accounts
,E/ClientConnectionOperation( 1791): Handling authorization failure
E/ClientConnectionOperation( 1791): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1791): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1791): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1791): 	... 7 more
,V/KeepSync( 3322): GoogleApiClient failed to connect with error code: 4
,D/NetworkLogImpl( 1791): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1791): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,D/SystemUpdateService( 1791): onDestroy
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,I/iu.UploadsManager( 1791): num queued entries: 0
I/iu.UploadsManager( 1791): num updated entries: 0
I/iu.SyncManager( 1791): NEXT; no task
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 36799, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/ChimeraCfgMgr( 1791): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1791): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  822): Start proc 3549:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  822): Start proc 3568:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
I/Babel   ( 2642): connection state changed from DISCONNECTED to CONNECTED
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1791): [AccountUtils] Account not ready
W/Kids    ( 1791): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1791): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1791): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1791): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1791): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1791): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1791): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1791): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1791): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1791): 	at java.lang.Thread.run(Thread.java:818)
,I/GAv4    ( 3549): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3549):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3549):   adb logcat -s GAv4
,E/KeepSync( 3322): IOException
E/KeepSync( 3322): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3322): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3322): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3322): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3322): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3322): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3322): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3322): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3322): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3322): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3322): 	... 10 more
W/KeepSync( 3322): Sync result 2
,I/ActivityManager(  822): Killing 2221:com.android.providers.calendar/u0a3 (adj 15): empty #17
D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 36802, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/GCM     ( 1506): Connected
,W/GAv4    ( 3549): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GCM     ( 1506): Ack for not saved message 69
,D/GCM     ( 1506): Message class com.google.f.a.a.p
,W/GAv4    ( 3549): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3549): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3549): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3549): Time to load native libraries: 1 ms (timestamps 3138-3139)
I/LibraryLoader( 3549): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3549): Binding Chromium to main looper Looper (main, tid 1) {6d45233}
,I/LibraryLoader( 3549): Expected native library version number "",actual native library version number ""
,I/chromium( 3549): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3549): Initializing chromium process, singleProcess=true
,W/art     ( 3549): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3549): ApplicationContext is null in ApplicationStatus
,W/chromium( 3549): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3549): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3549): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3549): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/art     ( 1506): Explicit concurrent mark sweep GC freed 16987(1064KB) AllocSpace objects, 5(362KB) LOS objects, 37% free, 26MB/42MB, paused 755us total 21.186ms
,W/AudioManagerAndroid( 3549): Requires BLUETOOTH permission
,I/NSApplication( 3549): Starting up...
,W/GAV2    ( 3568): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  822): Killing 1400:android.process.acore/u0a5 (adj 15): empty #17
,I/BooksApp( 3568): Created application version: 3.6.8 (30608)
,I/jxcore-log( 3216): BLE supported!!
I/jxcore-log( 3216): 
,I/art     (  822): Explicit concurrent mark sweep GC freed 27135(1258KB) AllocSpace objects, 4(105KB) LOS objects, 32% free, 33MB/49MB, paused 1.162ms total 63.565ms
,I/ActivityManager(  822): Start proc 3636:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/BooksSync( 3568): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3568): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3568): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3568): Soft error
E/BooksSync( 3568): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3568): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3568): Sync error
E/BooksSync( 3568): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3568): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3568): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36803, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  822): Killing 3120:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3097:com.google.android.partnersetup/u0a16 (adj 15): empty #18
,I/ActivityManager(  822): Start proc 3660:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,I/ActivityManager(  822): Killing 2931:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,E/SQLiteLog( 3660): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  822): Start proc 3680:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3680): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 3660): PlayLogger.onLoggerConnected
,I/ActivityManager(  822): Start proc 3701:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/CalendarProvider2( 3680): Created com.android.providers.calendar.CalendarAlarmManager@17ea7da9(com.android.providers.calendar.CalendarProvider2@3ad72f2e)
,I/ActivityManager(  822): Killing 3055:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3148:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,D/TimeService( 3701): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448274334036
D/        ( 3701): TimeServiceNative: User Time to be set is 1448274334036
D/QC-time-services( 3701): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3701): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3701): Lib:time_genoff_operation: pargs->ts_val = 1448274334036
D/QC-time-services( 3701): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  372): Daemon: Connection accepted:time_genoff
D/QC-time-services(  372): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448274334036
D/QC-time-services(  372): Daemon:genoff_opr: Base = 2, val = 1448274334036, operation = 0
D/QC-time-services(  372): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/10/70 6:38:36
D/QC-time-services(  372): Daemon:Value read from RTC seconds = 8577516000
D/QC-time-services(  372): Daemon:new time 1448274334036 
D/QC-time-services(  372): Daemon: delta 1439696818036 genoff 1439696818036 
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696818036 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  372): Updating the TOD offset
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696818036 to memory
,D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services( 3701): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  372): Daemon:Update to modem bit set
D/QC-time-services(  372): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  372): Daemon: Base = 2, Value being sent to MODEM = 1132309534036
,E/QC-time-services(  372): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  372): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  822): Start proc 3721:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 383us total 27.908ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 479us total 21.605ms
,I/GAv4    ( 3721): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
,I/GAv4    ( 3721):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3721):   adb logcat -s GAv4
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 327us total 19.473ms
,W/GAv4    ( 3721): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3721): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3721): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  822): Killing 2721:com.android.vending/u0a19 (adj 15): empty #17
,V/Herrevad( 1791): NQAS connected
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3610f492}
,I/art     ( 1791): Explicit concurrent mark sweep GC freed 14822(1150KB) AllocSpace objects, 16(256KB) LOS objects, 35% free, 28MB/44MB, paused 1.559ms total 60.272ms
,D/WifiService(  822): New client listening to asynchronous messages
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2642): UserRecoverableAuthException.
,E/Babel   ( 2642): eei: BadAuthentication
E/Babel   ( 2642): 	at eeg.a(Unknown Source)
E/Babel   ( 2642): 	at eeg.a(Unknown Source)
E/Babel   ( 2642): 	at eeg.a(Unknown Source)
E/Babel   ( 2642): 	at g.a(Unknown Source)
E/Babel   ( 2642): 	at cae.a(SourceFile:3089)
E/Babel   ( 2642): 	at cae.a(SourceFile:1131)
E/Babel   ( 2642): 	at cws.a(SourceFile:4333)
E/Babel   ( 2642): 	at cws.a(SourceFile:1419)
E/Babel   ( 2642): 	at crl.a(SourceFile:492)
E/Babel   ( 2642): 	at crl.a(SourceFile:1468)
E/Babel   ( 2642): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2642): 	at cas.b(SourceFile:106)
E/Babel   ( 2642): 	at cap.d(SourceFile:335)
E/Babel   ( 2642): 	at caq.run(SourceFile:81)
E/Babel   ( 2642): Error getting auth token
E/Babel   ( 2642): dvm
E/Babel   ( 2642): 	at g.a(Unknown Source)
E/Babel   ( 2642): 	at cae.a(SourceFile:3089)
E/Babel   ( 2642): 	at cae.a(SourceFile:1131)
E/Babel   ( 2642): 	at cws.a(SourceFile:4333)
E/Babel   ( 2642): 	at cws.a(SourceFile:1419)
E/Babel   ( 2642): 	at crl.a(SourceFile:492)
E/Babel   ( 2642): 	at crl.a(SourceFile:1468)
E/Babel   ( 2642): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2642): 	at cas.b(SourceFile:106)
E/Babel   ( 2642): 	at cap.d(SourceFile:335)
E/Babel   ( 2642): 	at caq.run(SourceFile:81)
,E/Babel   ( 2642): Account registration failed 1-Redacted-21
,E/Babel   ( 2642): cyp: null -- null
E/Babel   ( 2642): 	at cae.a(SourceFile:3121)
E/Babel   ( 2642): 	at cae.a(SourceFile:1131)
E/Babel   ( 2642): 	at cws.a(SourceFile:4333)
E/Babel   ( 2642): 	at cws.a(SourceFile:1419)
E/Babel   ( 2642): 	at crl.a(SourceFile:492)
E/Babel   ( 2642): 	at crl.a(SourceFile:1468)
E/Babel   ( 2642): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2642): 	at cas.b(SourceFile:106)
E/Babel   ( 2642): 	at cap.d(SourceFile:335)
E/Babel   ( 2642): 	at caq.run(SourceFile:81)
,I/art     ( 2642): Note: end time exceeds epoch: 
,I/art     (  822): Explicit concurrent mark sweep GC freed 12504(546KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 1.671ms total 69.165ms
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1506): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2642): Unexpected exception while authenticating.
,E/Babel   ( 2642): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2642): 	at eeg.b(Unknown Source)
E/Babel   ( 2642): 	at eeg.b(Unknown Source)
E/Babel   ( 2642): 	at g.a(Unknown Source)
E/Babel   ( 2642): 	at cae.b(SourceFile:1146)
E/Babel   ( 2642): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2642): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2642): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2642): 	at java.lang.Thread.run(Thread.java:818)
,I/CalendarProvider2( 3680): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3680): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,E/SQLiteLog( 3680): (284) automatic index on view_events(_id)
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=22.47 rxSuccessRate=21.31 targetRoamBSSID=any RSSI=-45
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,I/MusicLeanback( 3456): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3456): Stop autocaching.
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=22.47 rxSuccessRate=21.31 targetRoamBSSID=any RSSI=-45
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,I/ActivityManager(  822): Start proc 3768:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,W/ResourcesManager( 3768): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3768): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3768): VM with version 2.1.0 has multidex support
I/MultiDex( 3768): install
I/MultiDex( 3768): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3768): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3768): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1506): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1506): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1791): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3768): callingUid 10011, callindPid: 3768
,D/LocationInitializer( 1791): Restart initialization of location
,E/MDM     ( 1759): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3456): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3456): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 3568): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 3660): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  822): Start proc 3806:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/Finsky  ( 3806): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3806): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  822): Start proc 3842:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3806): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3806): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 3842): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3842): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 3806): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3806): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 3806): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 3842): VM with version 2.1.0 has multidex support
I/MultiDex( 3842): install
I/MultiDex( 3842): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 3806): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 3842): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
,I/jxcore-log( 3216): ,
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
,I/jxcore-log( 3216): 
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ProviderInstaller( 3842): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1506): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1506): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1791): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1759): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1791): Restart initialization of location
,I/art     ( 1506): Explicit concurrent mark sweep GC freed 18158(1004KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.091ms total 45.770ms
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3806): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,V/Finsky  ( 3806): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/Finsky  ( 3806): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3806): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ActivityManager(  822): Killing 3377:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3359:com.android.settings/1000 (adj 15): empty #18
,D/Finsky  ( 3806): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3806): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PermissionCache(  263): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (169 us)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3806): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3806): [395] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 20499(1023KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 2.214ms total 127.163ms
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  822): Display changed displayId=0
D/SurfaceFlinger(  263): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  263): hwc_setPowerMode: Setting mode 0 on display: 0
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3806): [395] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3806): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3806): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3806): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3806): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1759): client connected with version: 7571000
,I/qdhwcomposer(  263): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  263): hwc_setPowerMode: Done setting mode 0 on display 0,
D/SurfaceControl(  822): Excessive delay in setPowerMode(): 285ms
,I/DreamManagerService(  822): Entering dreamland.
I/PowerManagerService(  822): Dozing...
,I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 5
,E/native  (  822): do suspend false
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@38b88d2e}
,I/Keyboard.Facilitator( 1221): onFinishInput()
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=3.93 rxSuccessRate=4.79 targetRoamBSSID=any RSSI=-45
,E/WifiStateMachine(  822): cancelDelayedScan -> 7
,E/native  (  822): do suspend true
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-45
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/GoogleURLConnFactory( 1759): Using platform SSLCertificateSocketFactory
,W/GoogleHttpClient( 1759): Ignoring unsupported parameter: http.conn-manager.max-per-route
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@38b88d2e}
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  822): Killing 3516:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3549:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-45
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3291): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,I/VacuumService( 1506): Vacuum at: now=1448274352480 tag=VacuumService
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3291): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3291): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3291): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3291): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.g.a(SourceFile:79),
W/ExperimentUpdateService( 3291): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3291): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1506): Using platform SSLCertificateSocketFactory
,W/Uploader( 1506): No account for auth token provided,
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1506): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1506): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1506): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1506): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1506): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1506): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
E/Uploader( 1506): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
,E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1506): ,	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1506): No account for auth token provided,
,W/Uploader( 1506): No account for auth token provided,
,W/Uploader( 1506): No account for auth token provided,
,W/Uploader( 1506): No account for auth token provided,
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1506): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1506): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1506): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1506): ,	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1506): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1506): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1506): No account for auth token provided
,W/Uploader( 1506): No account for auth token provided
,W/Uploader( 1506): No account for auth token provided,
,W/Uploader( 1506): No account for auth token provided
,W/Uploader( 1506):  no longer exists, so no auth token.
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1506): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1506): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1506): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1506): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1506): No account for auth token provided
,W/Uploader( 1506): No account for auth token provided
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1506): Explicit concurrent mark sweep GC freed 67491(3MB) AllocSpace objects, 9(806KB) LOS objects, 37% free, 27MB/43MB, paused 1.430ms total 47.240ms
,E/Uploader( 1506): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1506): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1506): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1506): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1506): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1506): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): ,
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3806): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3806): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3806): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo,
,I/jxcore-log( 3216): ,
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,V/GoogleAuthProtoRequest( 3291): [337] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  822): Explicit concurrent mark sweep GC freed 29823(1393KB) AllocSpace objects, 5(174KB) LOS objects, 31% free, 34MB/50MB, paused 1.898ms total 82.145ms
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3291): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3291): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3291): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3291): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3291): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3806): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 3806): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3806): [1] 5.onFinished: Giving up after 6 failures.
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,V/KeepSync( 3322): Connecting to GoogleApiClient
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2988): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	,at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at blb.a(PG:3937)
E/HttpOperation( 2988): 	at czp.a(PG:18188)
E/HttpOperation( 2988): 	at czp.a(PG:9087),
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 12 more
,E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 14 more
,E/ClientConnectionOperation( 1791): Handling authorization failure
E/ClientConnectionOperation( 1791): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1791): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1791): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1791): 	... 7 more
,V/KeepSync( 3322): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2988): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at blb.a(PG:3937)
E/HttpOperation( 2988): 	at czp.a(PG:18188)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 12 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 14 more
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/KeepSync( 3322): IOException
E/KeepSync( 3322): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3322): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3322): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3322): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3322): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3322): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3322): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3322): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3322): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3322): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3322): 	... 10 more
W/KeepSync( 3322): Sync result 2
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 185649, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/HttpOperation( 2988): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at hec.a(PG:42)
E/HttpOperation( 2988): 	at hee.a(PG:102)
E/HttpOperation( 2988): 	at czr.a(PG:65)
E/HttpOperation( 2988): 	at kka.a(PG:108)
E/HttpOperation( 2988): 	at czp.a(PG:19176)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 15 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 17 more
,E/ExperimentLoader( 2988): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): 	at jdm.a(PG:82)
E/ExperimentLoader( 2988): 	at jcs.o(PG:406)
E/ExperimentLoader( 2988): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2988): 	at jcs.i(PG:143)
E/ExperimentLoader( 2988): 	at hec.a(PG:42)
E/ExperimentLoader( 2988): 	at hee.a(PG:102)
E/ExperimentLoader( 2988): 	at czr.a(PG:65)
E/ExperimentLoader( 2988): 	at kka.a(PG:108)
E/ExperimentLoader( 2988): 	at czp.a(PG:19176)
E/ExperimentLoader( 2988): 	at czp.a(PG:9081),
E/ExperimentLoader( 2988): 	at czq.run(PG:1686)
E/ExperimentLoader( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2988): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2988): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2988): 	at jdm.a(PG:77)
E/ExperimentLoader( 2988): 	... 15 more
E/ExperimentLoader( 2988): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2988): 	at fal.a(PG:38)
E/ExperimentLoader( 2988): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2988): 	... 17 more
,I/BooksSync( 3568): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3568): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 152676, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3568): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3568): Soft error
E/BooksSync( 3568): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3568): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3568): Sync error
E/BooksSync( 3568): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3568): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3568): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 186042, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1221): run()
I/Keyboard.Facilitator( 1221): flushDynamicLanguageModels()
,I/ConfigService( 1506): onCreate
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ConfigService( 1506): onDestroy
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2988): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at blb.a(PG:3937)
E/HttpOperation( 2988): 	at czp.a(PG:18188)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 12 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 14 more
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2988): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at hec.a(PG:42)
E/HttpOperation( 2988): 	at hee.a(PG:102)
E/HttpOperation( 2988): 	at czr.a(PG:65)
E/HttpOperation( 2988): 	at kka.a(PG:108)
E/HttpOperation( 2988): 	at czp.a(PG:19176)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 15 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 17 more
,E/ExperimentLoader( 2988): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): 	at jdm.a(PG:82)
E/ExperimentLoader( 2988): 	at jcs.o(PG:406)
E/ExperimentLoader( 2988): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2988): 	at jcs.i(PG:143)
E/ExperimentLoader( 2988): 	at hec.a(PG:42)
E/ExperimentLoader( 2988): 	at hee.a(PG:102)
E/ExperimentLoader( 2988): 	at czr.a(PG:65)
E/ExperimentLoader( 2988): 	at kka.a(PG:108)
E/ExperimentLoader( 2988): 	at czp.a(PG:19176)
E/ExperimentLoader( 2988): 	at czp.a(PG:9081)
E/ExperimentLoader( 2988): 	at czq.run(PG:1686)
E/ExperimentLoader( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2988): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2988): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2988): 	at jdm.a(PG:77)
E/ExperimentLoader( 2988): 	... 15 more
E/ExperimentLoader( 2988): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2988): 	at fal.a(PG:38)
E/ExperimentLoader( 2988): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2988): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 244805, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,V/GoogleAuthProtoRequest( 3291): [338] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3291): [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3291): [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3291): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3291): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3291): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/BooksSync( 3568): Starting books sync for 61035162, extras: ade
,I/art     (  822): Explicit concurrent mark sweep GC freed 37698(1664KB) AllocSpace objects, 11(647KB) LOS objects, 32% free, 33MB/49MB, paused 1.400ms total 69.192ms
,V/KeepSync( 3322): Connecting to GoogleApiClient
,I/BooksConfig( 3568): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1506): Explicit concurrent mark sweep GC freed 48417(2MB) AllocSpace objects, 10(1015KB) LOS objects, 37% free, 27MB/43MB, paused 1.240ms total 28.667ms
,E/ClientConnectionOperation( 1791): Handling authorization failure
E/ClientConnectionOperation( 1791): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1791): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1791): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1791): 	... 7 more
,V/KeepSync( 3322): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3568): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3568): Soft error
E/BooksSync( 3568): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3568): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3568): Sync error
E/BooksSync( 3568): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3568): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3568): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 277391, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3322): IOException
E/KeepSync( 3322): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3322): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3322): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3322): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3322): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3322): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3322): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3322): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3322): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3322): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3322): 	... 10 more
,W/KeepSync( 3322): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 278178, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/EventLogService( 1791): Opted in for usage reporting
I/EventLogService( 1791): Aggregate from 1448272669867 (log), 1448272669867 (data)
,W/EventLogAggregator( 1791): Unknown tag: snet_gcore
W/EventLogAggregator( 1791): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1791): dumping service [account]
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2988): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143),
E/HttpOperation( 2988): 	at blb.a(PG:3937)
E/HttpOperation( 2988): 	at czp.a(PG:18188)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 12 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 14 more
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2988): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at hec.a(PG:42)
E/HttpOperation( 2988): 	at hee.a(PG:102)
E/HttpOperation( 2988): 	at czr.a(PG:65)
E/HttpOperation( 2988): 	at kka.a(PG:108)
E/HttpOperation( 2988): 	at czp.a(PG:19176)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 15 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 17 more
,E/ExperimentLoader( 2988): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): 	at jdm.a(PG:82)
E/ExperimentLoader( 2988): 	at jcs.o(PG:406)
E/ExperimentLoader( 2988): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2988): 	at jcs.i(PG:143)
E/ExperimentLoader( 2988): 	at hec.a(PG:42)
E/ExperimentLoader( 2988): 	at hee.a(PG:102)
E/ExperimentLoader( 2988): 	at czr.a(PG:65)
E/ExperimentLoader( 2988): 	at kka.a(PG:108)
E/ExperimentLoader( 2988): 	at czp.a(PG:19176)
E/ExperimentLoader( 2988): 	at czp.a(PG:9081)
E/ExperimentLoader( 2988): 	at czq.run(PG:1686)
E/ExperimentLoader( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2988): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2988): ,	at jdj.a(PG:1125)
E/ExperimentLoader( 2988): 	at jdm.a(PG:77)
E/ExperimentLoader( 2988): 	... 15 more
E/ExperimentLoader( 2988): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2988): 	at fal.a(PG:38)
E/ExperimentLoader( 2988): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2988): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 337009, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): DBG, CoordinatorConnector connect called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Coordinator is now connected to the server!,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): printNetworkInfo
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: lo
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): found interfaceName: wlan0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3216): 
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GoogleAuthProtoRequest( 3291): [339] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3291): [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3291): [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3291): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3291): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3291): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/BooksSync( 3568): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3568): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3568): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3568): Soft error
E/BooksSync( 3568): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3568): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3568): Sync error
E/BooksSync( 3568): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3568): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3568): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 431931, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/KeepSync( 3322): Connecting to GoogleApiClient
,W/GLSActivity( 1506): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1506): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1506): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1506): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1506): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1506): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1506): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3806): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3806): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3806): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3806): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3806): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3806): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3806): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3806): Ignoring header User-Agent because its value was null.
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 31369(1392KB) AllocSpace objects, 7(300KB) LOS objects, 32% free, 33MB/49MB, paused 1.662ms total 97.489ms
,E/ClientConnectionOperation( 1791): Handling authorization failure
E/ClientConnectionOperation( 1791): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1791): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1791): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1791): 	... 7 more
,V/KeepSync( 3322): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3322): IOException
E/KeepSync( 3322): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3322): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3322): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3322): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3322): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3322): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3322): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3322): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3322): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3322): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3322): 	... 10 more
,W/KeepSync( 3322): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 433989, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector command called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":20,"addressList":[{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"
,I/jxcore-log( 3216): Start now : testSendData.js
I/jxcore-log( 3216): 
I/jxcore-log( 3216): stop tests now !
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 20
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): check server
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): serverPort is 41537
I/jxcore-log( 3216): ,
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3216): Stoping All
,I/        ( 3216): Stopping services
I/        ( 3216): Stop Bluetooth
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3216): Start-My BT: F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3216):  mInstanceString : {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5015","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3216): All stuff available and enabled
,I/        ( 3216): Stoping All
I/        ( 3216): Stopping services
I/        ( 3216): Stop Bluetooth
I/        ( 3216): Starting All
,I/        ( 3216): Stopping services
I/        ( 3216): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5015","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@2e347bdf
I/        ( 3216): Stopping services
,I/        ( 3216): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5015","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3216): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5015","ra":"F8:CF:C5:D9:E5:61"}, length : 82
,I/        ( 3216): peerDiscoveryTimer timeout value:5969
,I/        ( 3216): Stop Bluetooth
,I/        ( 3216): StartBluetooth listener
I/        ( 3216): StartBluetooth listener
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3216): StartBroadcasting started ok
I/jxcore-log( 3216): 
,I/BTListenerThread( 3216): starting to listen
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
,I/BTListenerThread( 3216): waiting to accept incoming Connection
I/jxcore-log( 3216): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:31:07.677Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:31:07.678Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:31:07.678Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3216): Connecting to null, at 44:80:EB:7B:5A:05,
I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3216): 2015-11-23T10:31:07.687Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/WB      ( 3216): We already were running, thus doing nothing
,I/        ( 3216): Added local service
I/        ( 3216): Cleared service requests
I/        ( 3216): Stopped peer discovery
I/        ( 3216): Started peer discovery
I/        ( 3216): Discovery state changed to Started.
,W/bt-btif ( 3272): No ag scb for peer addr
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config( 3272): btif_get_device_type: Device [44:80:eb:7b:5a:05] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/ActivityManager(  822): Start proc 4004:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@200dc96b:true
,I/ActivityManager(  822): Killing 1534:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  822): Client connection lost with reason: 4
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 2 peers.
I/SS      ( 3216): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(2): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/        ( 3216): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4597","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4597","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4597, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4597, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,E/HttpOperation( 2988): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at blb.a(PG:3937)
E/HttpOperation( 2988): 	at czp.a(PG:18188)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 12 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 14 more
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2988): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at hec.a(PG:42)
E/HttpOperation( 2988): 	at hee.a(PG:102)
E/HttpOperation( 2988): 	at czr.a(PG:65)
E/HttpOperation( 2988): 	at kka.a(PG:108)
E/HttpOperation( 2988): 	at czp.a(PG:19176)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 15 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 17 more
,E/ExperimentLoader( 2988): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): 	at jdm.a(PG:82)
E/ExperimentLoader( 2988): 	at jcs.o(PG:406)
E/ExperimentLoader( 2988): ,	at jcn.a(PG:1379)
E/ExperimentLoader( 2988): 	at jcs.i(PG:143)
E/ExperimentLoader( 2988): 	at hec.a(PG:42)
E/ExperimentLoader( 2988): 	at hee.a(PG:102)
,E/ExperimentLoader( 2988): 	at czr.a(PG:65)
E/ExperimentLoader( 2988): 	at kka.a(PG:108)
E/ExperimentLoader( 2988): 	at czp.a(PG:19176)
E/ExperimentLoader( 2988): 	at czp.a(PG:9081),
E/ExperimentLoader( 2988): 	at czq.run(PG:1686)
E/ExperimentLoader( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2988): 	at java.lang.Thread.run(Thread.java:818)
,E/ExperimentLoader( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2988): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2988): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2988): 	at jdm.a(PG:77)
,E/ExperimentLoader( 2988): 	... 15 more
E/ExperimentLoader( 2988): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2988): 	at fal.a(PG:38)
E/ExperimentLoader( 2988): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2988): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 491318, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,W/bt-btif ( 3272): info:x10,
D/        ( 3272): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL,
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6ceb4 rs_disc_pending=1
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d07c rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/btif_config( 3272): btif_get_device_type: Device [7c:f9:0e:34:8a:a0] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1,
E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255,
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3216): we got incoming connection
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTListenerThread( 3216): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3216): we got incoming connection
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTListenerThread( 3216): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3216): Starting to Handshake
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 81 bytes.,
,I/BTListenerThread( 3216): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3044","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������,
I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3216): Incoming connection Hand Shake finished for : motorola-XT1072_PT3044
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, motorola-XT1072_PT3044
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
,I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BTConnectToThread( 3216): got MESSAGE_READ 81 bytes.,
I/BTConnectToThread( 3216): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3044","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3216): HandshakeOk : motorola-XT1072_PT3044
,I/HS      ( 3216): Hand Shake finished outgoing for : motorola-XT1072_PT3044
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, motorola-XT1072_PT3044
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
,I/jxcore-log( 3216): 2015-11-23T10:31:15.984Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): ,
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 47002
,I/BtConnectorHelper( 3216): Request socket is using : 47002
I/BtToRequestSocket( 3216): Now accepting connections
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d07c rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3216): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3216): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3216): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT2678
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, samsung-SM-G900F_PT2678
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
,I/jxcore-log( 3216): 2015-11-23T10:31:16.239Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :47002
,I/jxcore-log( 3216): 2015-11-23T10:31:16.294Z SendDataConnector.js: CLIENT connected to 47002, error: null
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.295Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 47002
,I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-23T10:31:16.306Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.405Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.409Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.429Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.440Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.448Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.458Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.498Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data,
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24843
,I/jxcore-log( 3216): 2015-11-23T10:31:16.519Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.529Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.537Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.548Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.576Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.580Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.605Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.674Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:31:16.708Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.719Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13953
,I/jxcore-log( 3216): 2015-11-23T10:31:16.738Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.741Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.769Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.797Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.830Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.851Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.890Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.929Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:16.959Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.029Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4053
,I/jxcore-log( 3216): 2015-11-23T10:31:17.041Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.043Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/jxcore-log( 3216): 2015-11-23T10:31:17.124Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.172Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d07c rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3216): 2015-11-23T10:31:17.282Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.339Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.351Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.409Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.461Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.474Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.547Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.588Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.594Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.610Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.614Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.634Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.643Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.647Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.651Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.672Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.688Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.725Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.769Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.774Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.800Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.905Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.912Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.928Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.931Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.962Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.985Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:17.999Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.000Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.021Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.029Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.037Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.044Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.048Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.062Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.070Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.071Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.078Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.079Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: 44:80:EB:7B:5A:05
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/jxcore-log( 3216): 2015-11-23T10:31:18.089Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:31:18.090Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:31:18.091Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.091Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/        ( 3216): Selected device address: 80:01:84:8A:B3:68, name: null
I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at 80:01:84:8A:B3:68
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 10395 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3216): 2015-11-23T10:31:18.101Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:18.262Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d07c rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3216): Found 3 peers.
,I/SS      ( 3216): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(2): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(3): A3-1 0a:ec:a9:50:75:42
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/jxcore-log( 3216): 2015-11-23T10:31:19.112Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:31:19.346Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:19.352Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:19.428Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:19.495Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:19.690Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:19.858Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:20.000Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3216): 
,I/        ( 3216): Started service discovery,
,I/jxcore-log( 3216): 2015-11-23T10:31:20.139Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:20.307Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:20.373Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:20.675Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:20.747Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:20.866Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:20.884Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3216): 2015-11-23T10:31:20.926Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:20.958Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:20.977Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:21.047Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:21.052Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/jxcore-log( 3216): 2015-11-23T10:31:21.220Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:21.644Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:31:21.651Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:31:21.920Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:22.053Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:22.120Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:22.287Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:22.354Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:22.420Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:22.593Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:22.628Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:22.664Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:22.814Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:23.040Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4597","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4597","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4597, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4597, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,W/bt-btif ( 3272): invalid rfc slot id: 4,
I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2678
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2678
,I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
,I/BtToSocketBase( 3216): Close bt socket
I/BtToSocketBase( 3216): Close bt out
,I/BtToSocketBase( 3216): Close bt socket
I/jxcore-log( 3216): 2015-11-23T10:31:23.190Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 8
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:31:23.228Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:23.229Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:23.231Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x45
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6ceb4 rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): invalid rfc slot id: 6,
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT3044
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3216): 2015-11-23T10:31:23.723Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1020"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1020"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1020, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1020, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3216): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5515","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5515","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT5515, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT5515, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6ceb4 rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3041, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3041, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/ActivityManager(  822): Start proc 4043:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@40d62d3:true
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  822): Start proc 4066:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,I/BluetoothClassifier( 4043): Bluetooth Device Name: S5-1
,I/ActivityManager(  822): Killing 3701:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3636:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/jxcore-log( 3216): 2015-11-23T10:31:28.233Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:31:28.234Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: XT1072,
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3216): 2015-11-23T10:31:33.238Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:33.239Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:31:33.239Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:31:33.239Z SendDataConnector.js: do connect now,
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to null, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,W/bt-btif ( 3272): info:x10,
D/        ( 3272): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,I/        ( 3216): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1378"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1378"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT1378, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT1378, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d40c rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 9
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:31:38.382Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:38.383Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:38.384Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,D/btif_config( 3272): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3272): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3216): we got incoming connection
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTListenerThread( 3216): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3216): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3216): Incoming connection Hand Shake finished for : LGE-LG-H815_PT7555
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, LGE-LG-H815_PT7555
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/jxcore-log( 3216): 2015-11-23T10:31:39.043Z SendDataTCPServer.js: TCP/IP server connected,
I/jxcore-log( 3216): 
I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-23T10:31:39.587Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:39.637Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3216): 2015-11-23T10:31:39.963Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:39.974Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:39.979Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.019Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.024Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.060Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.066Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.080Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.119Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.164Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.176Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.239Z SendDataTCPServer.js: TCP/IP server has received 44376 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.244Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.355Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.405Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.794Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.829Z SendDataTCPServer.js: TCP/IP server has received 54276 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.915Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.964Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.972Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:40.979Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.187Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.231Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.239Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:31:41.245Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.261Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.299Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.332Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.342Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.410Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.416Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.437Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.453Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.458Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.465Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:41.498Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): invalid rfc slot id: 7
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT7555
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT7555
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close LocalOutputStream
,I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
,I/BtToSocketBase( 3216): Close bt socket
I/jxcore-log( 3216): 2015-11-23T10:31:41.608Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x49
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3216): 2015-11-23T10:31:43.385Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:43.386Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3216): 2015-11-23T10:31:48.390Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:48.391Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:31:48.392Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:31:48.392Z SendDataConnector.js: do connect now
,I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3216): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/        ( 3216): Cleared service requests
I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started peer discovery
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 11
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:31:53.549Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:53.550Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:31:53.551Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): ,
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3216): Found 10 peers.
,I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3216): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80,
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3216): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3216): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3216): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Started service discovery
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3216): 2015-11-23T10:31:58.552Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:31:58.553Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A,
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/art     ( 1506): Explicit concurrent mark sweep GC freed 46568(2MB) AllocSpace objects, 8(882KB) LOS objects, 36% free, 27MB/43MB, paused 2.140ms total 50.420ms
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8960, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8960, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66,
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:,
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3216): 2015-11-23T10:32:03.559Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:03.560Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:03.561Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:03.561Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3216): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config( 3272): btif_get_device_type: Device [80:01:84:8a:b3:68] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3272): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
I/BTConnectToThread( 3216): Starting to Handshake
,W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started,
,I/BTConnectToThread( 3216): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3216): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1378"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3216): HandshakeOk : HTC-HTC Desire 820_PT1378
,I/HS      ( 3216): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT1378
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT1378
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 40001
,I/BtConnectorHelper( 3216): Request socket is using : 40001
,I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :40001
,I/jxcore-log( 3216): 2015-11-23T10:32:04.797Z SendDataConnector.js: CLIENT connected to 40001, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:04.798Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 40001,
,I/BtToRequestSocket( 3216): Set local streams
,I/BtToRequestSocket( 3216): rin ended ---------------------------;,
,I/jxcore-log( 3216): 2015-11-23T10:32:04.808Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:267,
,I/jxcore-log( 3216): 2015-11-23T10:32:04.928Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:04.974Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:05.044Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:05.086Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:05.097Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:05.189Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:05.238Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:05.292Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:05.371Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:05.415Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:05.417Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:05.421Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:05.422Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/jxcore-log( 3216): 2015-11-23T10:32:05.431Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:05.433Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:05.434Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:05.434Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/        ( 3216): Selected device address: F8:95:C7:87:3C:51, name: G4-1
W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to G4-1, at F8:95:C7:87:3C:51
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 47327 ms, rnd: 4, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,W/bt-btif ( 3272): info:x10,
D/        ( 3272): remote version info [f8:95:c7:87:3c:51]: 7, f, 610c
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config( 3272): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c,
I/BluetoothBondStateMachine( 3272): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3272): Failed to remove device: F8:95:C7:87:3C:51
I/BluetoothBondStateMachine( 3272): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3216): Starting to Handshake
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3216): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3216): HandshakeOk : LGE-LG-H815_PT7555
,I/HS      ( 3216): Hand Shake finished outgoing for : LGE-LG-H815_PT7555
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, LGE-LG-H815_PT7555
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3216): mHTTPPort  set to : 39767
,I/BtConnectorHelper( 3216): Request socket is using : 39767
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :39767
,I/jxcore-log( 3216): 2015-11-23T10:32:07.151Z SendDataConnector.js: CLIENT connected to 39767, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:07.152Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 39767
I/BtToRequestSocket( 3216): Set local streams
,I/jxcore-log( 3216): 2015-11-23T10:32:07.161Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-23T10:32:07.266Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1378"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1378"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT1378, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT1378, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3216): 2015-11-23T10:32:07.367Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:07.422Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:07.475Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:07.482Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:07.517Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:07.593Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:07.644Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:07.685Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:07.748Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:07.749Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:07.752Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:07.753Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: F8:95:C7:87:3C:51
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3216): Close LocalOutputStream
,I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3216): 2015-11-23T10:32:07.766Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:07.772Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:07.772Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:07.773Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at 34:FC:EF:11:B1:66
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 2315 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: HTC Desire 820,
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: G4-1
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,D/btif_config( 3272): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1,
E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State,
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x10  CID 0x40
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 14
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:32:12.995Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:12.996Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:12.997Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3272): Failed to remove device: 34:FC:EF:9D:93:0B,
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200,
I/BTListenerThread( 3216): we got incoming connection
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3216): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 77 bytes.,
I/BTListenerThread( 3216): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3216): Incoming connection Hand Shake finished for : LGE-LG-D802_PT4760
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, LGE-LG-D802_PT4760
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
,I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-23T10:32:13.239Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.639Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.647Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.673Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.697Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.728Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.735Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.747Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.779Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.787Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.815Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.830Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.837Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.869Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.872Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.875Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.920Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.925Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.932Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.968Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:13.984Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.013Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.028Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.112Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.128Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.159Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.162Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.167Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.213Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:32:14.271Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.282Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.287Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.292Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.328Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.334Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.337Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.342Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.347Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.379Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.393Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.421Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.425Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.432Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.468Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.503Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.508Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.514Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.529Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:14.568Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): invalid rfc slot id: 10
I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT4760
I/BtToSocketBase( 3216): Stop ReceivingThread
,I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Close bt out
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close bt socket
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT4760
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/jxcore-log( 3216): 2015-11-23T10:32:14.685Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d79c rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x46
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/jxcore-log( 3216): 2015-11-23T10:32:17.998Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:17.999Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Thali Test's G2
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3216): Found 13 peers.
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3216): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3216): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2,
I/SS      ( 3216): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(9): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3216): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3216): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(12): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3216): Peer(13): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3216): 2015-11-23T10:32:23.003Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:23.004Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:23.004Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:23.005Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to null, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3216): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1378"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1378"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT1378, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT1378, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x10  CID 0x42
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 16
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:32:28.873Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:28.874Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:28.874Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,D/btif_config( 3272): btif_get_device_type: Device [08:ec:a9:50:75:41] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c,
I/BluetoothBondStateMachine( 3272): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3272): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3216): we got incoming connection
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTListenerThread( 3216): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3216): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3216): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT7946
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, samsung-SM-A300FU_PT7946
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/jxcore-log( 3216): 2015-11-23T10:32:32.946Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-23T10:32:33.359Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.363Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.370Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.373Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.377Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.381Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.386Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.418Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.431Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.434Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.447Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.479Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.485Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.519Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.533Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/jxcore-log( 3216): 2015-11-23T10:32:33.579Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.618Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.626Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.630Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.668Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.675Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.680Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.719Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.735Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.742Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.779Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.785Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.875Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:33.875Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): invalid rfc slot id: 15
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT7946
I/BtToSocketBase( 3216): Stop ReceivingThread,
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT7946
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
,I/BtToSocketBase( 3216): Close bt socket
I/jxcore-log( 3216): 2015-11-23T10:32:33.903Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive,
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 4043): Bluetooth Device Name: A3-1,
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/jxcore-log( 3216): 2015-11-23T10:32:38.881Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:38.882Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:38.882Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:38.883Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 34:FC:EF:11:B1:66, name: null,
,I/        ( 3216): Connecting to null, at 34:FC:EF:11:B1:66,
I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3216): Found 13 peers.
,I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3216): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(12): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3216): Peer(13): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x10  CID 0x49
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 18
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:32:44.509Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:44.510Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:44.510Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8960, peerAddress: 34:FC:EF:11:B1:66
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8960, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3216): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1378"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1378"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT1378, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT1378, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3216): 2015-11-23T10:32:49.512Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:49.512Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,D/btif_config( 3272): btif_get_device_type: Device [08:ec:a9:50:76:27] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1,
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c,
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 3272): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3216): we got incoming connection
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3216): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 83 bytes.,
I/BTListenerThread( 3216): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
I/HS      ( 3216): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT3495
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, samsung-SM-A300FU_PT3495
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
,I/jxcore-log( 3216): 2015-11-23T10:32:53.777Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-23T10:32:54.185Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.198Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.203Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.207Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.212Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.220Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.280Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.295Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.329Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.339Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.346Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.353Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.390Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.395Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.405Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.447Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.454Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.466Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.474Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.483Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.518Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.519Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:32:54.520Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.520Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to null, at 34:FC:EF:11:B1:66
,I/jxcore-log( 3216): 2015-11-23T10:32:54.538Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3216): 
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3216): 2015-11-23T10:32:54.548Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6db2c rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3216): 2015-11-23T10:32:54.785Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.819Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.829Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.837Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.850Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.889Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.910Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.925Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:54.941Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
,I/jxcore-log( 3216): 2015-11-23T10:32:54.982Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3216): 
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/jxcore-log( 3216): 2015-11-23T10:32:55.000Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:55.021Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:55.074Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:55.096Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:55.129Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:55.142Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:32:55.145Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6db2c rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): invalid rfc slot id: 17
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT3495
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT3495
,I/BtToSocketBase( 3216): Close LocalOutputStream
I/jxcore-log( 3216): 2015-11-23T10:32:55.526Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket,
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
,I/BtToSocketBase( 3216): Close bt socket
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x4b
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x10  CID 0x4d
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 3272): invalid rfc slot id: 20
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:33:00.085Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:00.087Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:33:00.087Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Thali Test (Galaxy A3),
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3216): Found 7 peers.
,I/SS      ( 3216): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3216): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3216): Started service discovery
,I/jxcore-log( 3216): 2015-11-23T10:33:05.090Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:05.091Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66,
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4597","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4597","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4597, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4597, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3216): 2015-11-23T10:33:10.095Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:10.096Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:33:10.098Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:10.098Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x10  CID 0x4e
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 21
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:33:15.893Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:15.894Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:15.902Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:15.908Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: 7C:F9:0E:34:8A:A0,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:33:15.910Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:33:15.911Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:33:15.911Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1,
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback,
,I/        ( 3216): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 68123 ms, rnd: 5, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [7c:f9:0e:34:8a:a0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 7 peers.,
I/SS      ( 3216): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b,
I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(6): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3216): Starting to Handshake
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3216): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3216): HandshakeOk : samsung-SM-G900F_PT2678
I/HS      ( 3216): Hand Shake finished outgoing for : samsung-SM-G900F_PT2678
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-G900F_PT2678
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 60234
,I/BtConnectorHelper( 3216): Request socket is using : 60234
,I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :60234
,I/jxcore-log( 3216): 2015-11-23T10:33:18.802Z SendDataConnector.js: CLIENT connected to 60234, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:18.803Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 60234
I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-23T10:33:18.815Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3216): 2015-11-23T10:33:19.458Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:19.551Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:19.564Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:19.611Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:19.616Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:19.644Z SendDataConnector.js: CLIENT is data received : 60000
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:19.653Z SendDataConnector.js: CLIENT is data received : 70000,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:19.695Z SendDataConnector.js: CLIENT is data received : 80000,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:19.699Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:19.740Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:19.741Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:19.745Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:19.745Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
,I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
,I/BtToRequestSocket( 3216): Close server socket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3216): 2015-11-23T10:33:19.752Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:33:19.754Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:33:19.755Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:33:19.755Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/        ( 3216): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at F8:95:C7:87:85:54
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 3831 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d07c rs_disc_pending=1
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config( 3272): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1,
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3272): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3216): Starting to Handshake
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3216): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3216): HandshakeOk : LGE-LG-D722_PT9740
I/HS      ( 3216): Hand Shake finished outgoing for : LGE-LG-D722_PT9740
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, LGE-LG-D722_PT9740
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 39992
,I/BtConnectorHelper( 3216): Request socket is using : 39992
,I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :39992
I/jxcore-log( 3216): 2015-11-23T10:33:22.706Z SendDataConnector.js: CLIENT connected to 39992, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:22.707Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 39992
,I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-23T10:33:22.733Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:22.889Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:22.945Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:22.950Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:23.003Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:23.042Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:23.075Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:23.127Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:23.134Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:23.172Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:23.215Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:23.216Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:23.223Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:23.226Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: F8:95:C7:87:85:54
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Close LocalOutputStream
,I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close bt out
,I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/jxcore-log( 3216): 2015-11-23T10:33:23.240Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:33:23.241Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): 2015-11-23T10:33:23.241Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:23.241Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): ,
I/        ( 3216): Selected device address: 34:FC:EF:11:AE:67, name: null
I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at 34:FC:EF:11:AE:67
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 3462 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: S5-1,
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3216): Cleared service requests,
I/        ( 3216): Started peer discovery
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3216): Found 8 peers.
,I/SS      ( 3216): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2,
I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(8): G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/        ( 3216): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1020"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1020"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1020, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1020, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4597","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4597","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4597, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4597, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8960, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8960, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 8 peers.
I/SS      ( 3216): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(8): G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3216): Started service discovery
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6e084 rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/btif_config( 3272): btif_get_device_type: Device [00:f4:6f:30:e0:6c] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3216): we got incoming connection
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3216): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3216): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3216): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT5812
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, samsung-SM-G800F_PT5812
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-23T10:33:52.548Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.073Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.077Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.117Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.121Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.178Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.182Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.254Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.288Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.335Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.344Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.379Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.388Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.390Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.395Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.430Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.471Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.477Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.518Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.564Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.569Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.572Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.609Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.634Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.642Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.646Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.680Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.696Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.716Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.723Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3216): 
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x22  CID 0x40
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 24
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:33:53.755Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:33:53.755Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:33:53.756Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.784Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.817Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.849Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.860Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.867Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.900Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.912Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.915Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.952Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:53.960Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:33:53.999Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:54.039Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:33:54.078Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:54.082Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): invalid rfc slot id: 19
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT5812
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT5812
I/BtToSocketBase( 3216): Close LocalOutputStream
,I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
,I/BtToSocketBase( 3216): Close bt socket
,I/jxcore-log( 3216): 2015-11-23T10:33:54.143Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x45
,I/        ( 3216): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5103","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5103","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT5103, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT5103, WifiDirectName: , WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: S5mini-1,
,I/jxcore-log( 3216): 2015-11-23T10:33:58.757Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:33:58.758Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
,V/GoogleAuthProtoRequest( 3291): [340] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3291): [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3291): [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3291): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3291): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3291): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1506): Using platform SSLCertificateSocketFactory
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,D/btif_config( 3272): btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3216): we got incoming connection
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTListenerThread( 3216): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3216): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5515","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
I/HS      ( 3216): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT5515
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, samsung-SM-N910C_PT5515
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
,I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-23T10:34:02.025Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.472Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.490Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.542Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.578Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.623Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.632Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.639Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.727Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.759Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.776Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.813Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.818Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.827Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.830Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.869Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.894Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.931Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.955Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.989Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.992Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:02.997Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.028Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.034Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.037Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.056Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.065Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.099Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.116Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.123Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.158Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.199Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.215Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.347Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:03.378Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 6 peers.
,I/SS      ( 3216): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,W/bt-btif ( 3272): invalid rfc slot id: 25
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT5515
I/BtToSocketBase( 3216): Stop ReceivingThread
,I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close bt in
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close bt out
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT5515
,I/BtToSocketBase( 3216): Close bt socket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/jxcore-log( 3216): 2015-11-23T10:34:03.517Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x47
,I/jxcore-log( 3216): 2015-11-23T10:34:03.761Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:34:03.762Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:34:03.762Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:34:03.763Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 34:FC:EF:11:AE:67, name: null,
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to null, at 34:FC:EF:11:AE:67
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6e24c rs_disc_pending=1
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3272): onReceive,
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3272): No ag scb for peer addr
,I/        ( 3216): Cleared service requests
I/        ( 3216): Started peer discovery
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 6 peers.
I/SS      ( 3216): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6e414 rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/btif_config( 3272): btif_get_device_type: Device [7c:f9:0e:37:96:ab] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 3272): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3216): we got incoming connection
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3216): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 3216): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������,
,I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3216): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT9488
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, samsung-SM-A500FU_PT9488
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3216): --DoOneRunRound started
I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-23T10:34:21.677Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.058Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.064Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.075Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.082Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.130Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.138Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.169Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.173Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.199Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.211Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.248Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.286Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:34:22.303Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.339Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.349Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.356Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.366Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.400Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.437Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.454Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.465Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.499Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.517Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.530Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.548Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.604Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:34:22.611Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.648Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.702Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.725Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.728Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.792Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.798Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.804Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:34:22.817Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.873Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.909Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.915Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.930Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:22.968Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:23.008Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:34:23.048Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): invalid rfc slot id: 26
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT9488
,I/BtToSocketBase( 3216): Stop ReceivingThread
,I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed,
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT9488
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x4b
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/jxcore-log( 3216): 2015-11-23T10:34:23.110Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: A5-1
,I/BooksSync( 3568): Starting books sync for 61035162, extras: ade
,I/art     (  822): Explicit concurrent mark sweep GC freed 48249(2MB) AllocSpace objects, 7(489KB) LOS objects, 32% free, 33MB/49MB, paused 1.828ms total 98.334ms
,I/BooksConfig( 3568): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3568): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3568): Soft error
E/BooksSync( 3568): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3568): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3568): Sync error
E/BooksSync( 3568): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3568): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3568): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 690950, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/BtConnection( 3216): connectionTimeoutTimer
E/bt-btif ( 3272): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:27, channel:-1
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: Cancelled
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:35:03.772Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:03.773Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:35:03.774Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,W/jxcore-log( 3216): $$jxcore_callback_34 wasn't registered
W/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 27
,I/jxcore-log( 3216): 2015-11-23T10:35:08.775Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:35:08.776Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: G3s-1
,D/btif_config( 3272): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1,
E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3272): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200,
I/BTListenerThread( 3216): we got incoming connection
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3216): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3216): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3216): Incoming connection Hand Shake finished for : LGE-LG-D722_PT9740
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, LGE-LG-D722_PT9740
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
,I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-23T10:35:10.893Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.270Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.302Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.314Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.322Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.332Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.336Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.369Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.374Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.409Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.414Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.449Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.454Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.462Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.498Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.501Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.509Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.549Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.553Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.556Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.563Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:11.598Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): invalid rfc slot id: 28
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT9740
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT9740
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x4e
,I/jxcore-log( 3216): 2015-11-23T10:35:11.682Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): 2015-11-23T10:35:13.781Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:13.781Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:35:13.782Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:13.782Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to null, at 34:FC:EF:11:AE:67
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6dcf4 rs_disc_pending=1,
E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag,
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3272): onReceive,
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: G3s-1
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 4 peers.
I/SS      ( 3216): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,V/KeepSync( 3322): Connecting to GoogleApiClient
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1791): Handling authorization failure
E/ClientConnectionOperation( 1791): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1791): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1791): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1791): 	... 7 more
,V/KeepSync( 3322): GoogleApiClient failed to connect with error code: 4
,E/HttpOperation( 2988): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at blb.a(PG:3937)
E/HttpOperation( 2988): 	at czp.a(PG:18188)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 12 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 14 more
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2988): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at hec.a(PG:42)
E/HttpOperation( 2988): 	at hee.a(PG:102)
E/HttpOperation( 2988): 	at czr.a(PG:65)
E/HttpOperation( 2988): 	at kka.a(PG:108)
E/HttpOperation( 2988): 	at czp.a(PG:19176)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 15 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 17 more
,E/ExperimentLoader( 2988): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): ,	at jdm.a(PG:82)
E/ExperimentLoader( 2988): 	at jcs.o(PG:406)
E/ExperimentLoader( 2988): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2988): 	at jcs.i(PG:143)
E/ExperimentLoader( 2988): 	at hec.a(PG:42)
E/ExperimentLoader( 2988): 	at hee.a(PG:102)
E/ExperimentLoader( 2988): 	at czr.a(PG:65)
E/ExperimentLoader( 2988): 	at kka.a(PG:108)
E/ExperimentLoader( 2988): 	,at czp.a(PG:19176)
E/ExperimentLoader( 2988): 	at czp.a(PG:9081)
E/ExperimentLoader( 2988): 	at czq.run(PG:1686)
E/ExperimentLoader( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2988): 	at jdj.a(PG:4091)
,E/ExperimentLoader( 2988): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2988): 	at jdm.a(PG:77)
E/ExperimentLoader( 2988): 	... 15 more
E/ExperimentLoader( 2988): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2988): 	at fal.a(PG:38)
E/ExperimentLoader( 2988): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2988): 	... 17 more
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3322): IOException,
E/KeepSync( 3322): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3322): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3322): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3322): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3322): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3322): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3322): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3322): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3322): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3322): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3322): 	... 10 more
W/KeepSync( 3322): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 725073, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 749522, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 6 peers.
,I/SS      ( 3216): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3216): Peer(6): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Started service discovery
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x22  CID 0x4c
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 30
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:35:46.359Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:46.360Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:46.364Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/jxcore-log( 3216): 2015-11-23T10:35:51.365Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): 2015-11-23T10:35:51.366Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 6 peers.
,I/SS      ( 3216): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(6): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3216): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/        ( 3216): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3041, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3041, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3216): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT178","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT178","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT178, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT178, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/        ( 3216): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1020"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT1020"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT1020, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT1020, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3216): 2015-11-23T10:35:56.369Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:35:56.370Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:35:56.371Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:56.371Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/        ( 3216): Connecting to null, at 34:FC:EF:11:AE:67
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x9  CID 0x4f
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 31,
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:35:56.972Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:35:56.972Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:35:56.973Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4597","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4597","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4597, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4597, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3216): 2015-11-23T10:36:01.976Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:36:01.978Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): 2015-11-23T10:36:06.983Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:36:06.984Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:36:06.985Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:36:06.985Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to null, at 34:FC:EF:11:AE:67
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3216): Found 7 peers.
,I/SS      ( 3216): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/        ( 3216): Started service discovery
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x22  CID 0x41
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 32
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:36:38.901Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:36:38.902Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:36:38.905Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:36:38.908Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- gotta redo : 34:FC:EF:11:AE:67, try count now: 1
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:36:38.911Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:36:38.912Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:36:38.913Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/        ( 3216): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at B4:CE:F6:AB:A4:6A
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 195662 ms, rnd: 5, ex: Connection to 34:FC:EF:11:AE:67 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 3 peers.
,I/SS      ( 3216): Peer(1): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3216): Peer(2): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x8  CID 0x44
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 33
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:37:11.591Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:11.592Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:11.593Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0,
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A,
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3216): 2015-11-23T10:37:16.595Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:16.596Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests,
,I/        ( 3216): Started peer discovery,
,I/jxcore-log( 3216): 2015-11-23T10:37:21.599Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:37:21.600Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:21.601Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:21.601Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback,
I/        ( 3216): Connecting to null, at B4:CE:F6:AB:A4:6A
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 34
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:37:26.760Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:26.761Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:26.761Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 5 peers.
,I/SS      ( 3216): Peer(1): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3216): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2,
I/SS      ( 3216): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3216): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3216): 2015-11-23T10:37:31.762Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:37:31.763Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3216): 2015-11-23T10:37:36.767Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:36.768Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:36.768Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:36.769Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback,
,I/        ( 3216): Connecting to null, at B4:CE:F6:AB:A4:6A
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 35
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:37:41.926Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:41.927Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:41.928Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3216): Found 6 peers.
,I/SS      ( 3216): Peer(1): G3-1 02:9a:02:7b:60:ac,
I/SS      ( 3216): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Started service discovery
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8960, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8960, WifiDirectName: , WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3216): 2015-11-23T10:37:46.929Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:46.930Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3216): 2015-11-23T10:37:51.934Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:37:51.935Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:37:51.936Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:37:51.936Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3216): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback,
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 36
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:37:57.095Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:37:57.096Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:37:57.097Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3216): Found 6 peers.
I/SS      ( 3216): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4597","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4597","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4597, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4597, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3216): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT178","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT178","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT178, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT178, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/jxcore-log( 3216): 2015-11-23T10:38:02.099Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:38:02.099Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8960, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8960, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3216): 2015-11-23T10:38:07.103Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:38:07.104Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:38:07.104Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:38:07.105Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: B4:CE:F6:AB:A4:6A, name: null,
,I/BTConnectToThread( 3216): Starting to connect
,I/        ( 3216): Connecting to null, at B4:CE:F6:AB:A4:6A
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 3272): invalid rfc slot id: 37
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:38:12.261Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:38:12.262Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:38:12.265Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:38:12.269Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: E0:DB:10:14:E2:C0
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:38:12.272Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:38:12.273Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:38:12.273Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): ,
I/        ( 3216): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3216): Connecting to Note4-1, at E0:DB:10:14:E2:C0,
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 93350 ms, rnd: 5, ex: Connection to B4:CE:F6:AB:A4:6A failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Cleared service requests
I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 8 peers.
I/SS      ( 3216): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Started service discovery,
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x8  CID 0x45
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 38
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:39:04.801Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:39:04.802Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:39:04.803Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): 2015-11-23T10:39:09.804Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:39:09.805Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 9 peers.
,I/SS      ( 3216): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3216): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(8): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3216): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/jxcore-log( 3216): 2015-11-23T10:39:14.808Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:39:14.809Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:39:14.810Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:39:14.810Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [e0:db:10:14:e2:c0]: 6, f, 410d
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80,
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6e24c rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 3272): PORT_StartCnf failed result:5
,W/bt-rfcomm( 3272): PORT_StartCnf failed result:5
W/bt-btif ( 3272): btm_sec_disconnected - 
E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3272): Device not in IRK list
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3272): Do not find the bg connection mask for the remote device
I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 9 Address: E0:DB:10:14:E2:C0 newState: 0
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BluetoothBondStateMachine( 3272): In stable state, received invalid newState: 10
I/jxcore-log( 3216): 2015-11-23T10:39:36.803Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:39:36.804Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:39:36.805Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3216): 2015-11-23T10:39:41.806Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:39:41.807Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:39:46.810Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:39:46.811Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:39:46.812Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:39:46.812Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 40
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:39:51.980Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:39:51.980Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:39:51.981Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:39:56.982Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:39:56.983Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:01.986Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:01.987Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:01.988Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:01.988Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/BTConnectToThread( 3216): Starting to connect,
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to Note4-1, at E0:DB:10:14:E2:C0,
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Note4-1
,D/btif_config( 3272): btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3216): Starting to Handshake
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3216): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5515","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3216): HandshakeOk : samsung-SM-N910C_PT5515
I/HS      ( 3216): Hand Shake finished outgoing for : samsung-SM-N910C_PT5515
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-N910C_PT5515
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3216): mHTTPPort  set to : 55564
I/BtConnectorHelper( 3216): Request socket is using : 55564
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :55564
,I/jxcore-log( 3216): 2015-11-23T10:40:03.667Z SendDataConnector.js: CLIENT connected to 55564, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:03.668Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 55564
I/BtToRequestSocket( 3216): Set local streams
,I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-23T10:40:03.679Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:03.783Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:03.862Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:03.870Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:03.920Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:03.924Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:03.973Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:03.978Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:04.013Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:04.017Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:04.082Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:04.083Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:04.086Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:04.088Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: E0:DB:10:14:E2:C0
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3216): 2015-11-23T10:40:04.097Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:04.098Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:04.098Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:04.098Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: E0:DB:10:1F:C9:5E, name: null
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/        ( 3216): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 111811 ms, rnd: 4, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config( 3272): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3272): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 3272): Failed to remove device: E0:DB:10:1F:C9:5E
I/BluetoothBondStateMachine( 3272): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Note4-1
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 3272): L2CAP - no CCB for conn rsp, LCID: 79 RCID: 74
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3216): we got incoming connection
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTListenerThread( 3216): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,I/BTConnectToThread( 3216): Starting to Handshake
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3216): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
I/HS      ( 3216): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT3041
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, samsung-SM-N9005_PT3041
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-23T10:40:12.677Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/BTConnectToThread( 3216): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3216): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3216): HandshakeOk : samsung-SM-N9005_PT3041
I/HS      ( 3216): Hand Shake finished outgoing for : samsung-SM-N9005_PT3041
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-N9005_PT3041
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 48741
I/BtConnectorHelper( 3216): Request socket is using : 48741
,I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :48741
,I/jxcore-log( 3216): 2015-11-23T10:40:13.006Z SendDataConnector.js: CLIENT connected to 48741, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.007Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 48741
,I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-23T10:40:13.018Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2519
,I/jxcore-log( 3216): 2015-11-23T10:40:13.118Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.157Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.186Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.234Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.258Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.268Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.297Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.328Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.333Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.336Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.345Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.354Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.415Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.457Z SendDataConnector.js: CLIENT is data received : 40000
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.575Z SendDataConnector.js: CLIENT is data received : 50000,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.713Z SendDataConnector.js: CLIENT is data received : 60000,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.786Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.797Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.803Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.838Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.855Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.914Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:13.963Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.100Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/jxcore-log( 3216): 2015-11-23T10:40:14.106Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3216): 
,I/        ( 3216): Started peer discovery
,I/jxcore-log( 3216): 2015-11-23T10:40:14.123Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.125Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.129Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:14.130Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/BtConnectorHelper( 3216): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
,I/BtToRequestSocket( 3216): Close server socket
I/jxcore-log( 3216): 2015-11-23T10:40:14.133Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:14.135Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:14.135Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:14.135Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/        ( 3216): Selected device address: 58:3F:54:73:64:C0, name: null
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at 58:3F:54:73:64:C0
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 10027 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
I/jxcore-log( 3216): 2015-11-23T10:40:14.149Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.153Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.219Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.288Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.355Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.422Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.491Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.558Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.626Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.694Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:14.761Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,I/jxcore-log( 3216): 2015-11-23T10:40:14.963Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:15.025Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:15.047Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:15.051Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:15.056Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:15.063Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:15.099Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:15.107Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:15.139Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:15.147Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): invalid rfc slot id: 29
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT3041
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
,I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
,I/BtToSocketBase( 3216): Close bt socket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3216): 2015-11-23T10:40:15.234Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6e7a4 rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x41
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0,
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3216): Found 4 peers.,
I/SS      ( 3216): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3216): Peer(2): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/        ( 3216): Started service discovery
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Note3-1
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery,
,D/GCM     ( 1506): Message class com.google.f.a.a.i
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3216): Found 5 peers.
I/SS      ( 3216): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3216): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Started service discovery
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/ProcessCpuTracker(  822): Skipping unknown process pid 4297,
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51,
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config( 3272): btif_get_device_type: Device [58:3f:54:73:64:c0] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3216): Starting to Handshake
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 77 bytes.,
I/BTConnectToThread( 3216): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3216): HandshakeOk : LGE-LG-D855_PT6848
I/HS      ( 3216): Hand Shake finished outgoing for : LGE-LG-D855_PT6848
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, LGE-LG-D855_PT6848
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3216): mHTTPPort  set to : 47977
,I/BtConnectorHelper( 3216): Request socket is using : 47977
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :47977
,I/jxcore-log( 3216): 2015-11-23T10:40:42.887Z SendDataConnector.js: CLIENT connected to 47977, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:42.888Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:42.896Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 47977
I/BtToRequestSocket( 3216): Set local streams
,I/BtToRequestSocket( 3216): rin ended ---------------------------;
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24843
,I/jxcore-log( 3216): 2015-11-23T10:40:42.998Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17913
,I/jxcore-log( 3216): 2015-11-23T10:40:43.078Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:43.127Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6033
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4053
,I/jxcore-log( 3216): 2015-11-23T10:40:43.167Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:43.174Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:43.262Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:43.334Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:43.430Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:43.434Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:43.523Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:43.524Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:43.535Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:43.540Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/BtConnectorHelper( 3216): Disconnect outgoing peer: 58:3F:54:73:64:C0
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3216): 2015-11-23T10:40:43.546Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:43.549Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:43.550Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:43.550Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/        ( 3216): Selected device address: 34:FC:EF:9D:93:0B, name: Thali Test's G2
I/        ( 3216): Connecting to Thali Test's G2, at 34:FC:EF:9D:93:0B
I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 29392 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [34:fc:ef:9d:93:0b]: 7, f, 6109
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Thali Test's G2
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config( 3272): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1,
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1,
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3216): Starting to Handshake
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread,
I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 77 bytes.,
I/BTConnectToThread( 3216): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3216): HandshakeOk : LGE-LG-D802_PT4760
I/HS      ( 3216): Hand Shake finished outgoing for : LGE-LG-D802_PT4760
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, LGE-LG-D802_PT4760
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3216): mHTTPPort  set to : 49290
I/BtConnectorHelper( 3216): Request socket is using : 49290
,I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :49290,
I/jxcore-log( 3216): 2015-11-23T10:40:44.972Z SendDataConnector.js: CLIENT connected to 49290, error: null
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): 2015-11-23T10:40:44.972Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 49290,
,I/BtToRequestSocket( 3216): Set local streams
I/jxcore-log( 3216): 2015-11-23T10:40:44.983Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:403,
,I/jxcore-log( 3216): 2015-11-23T10:40:45.225Z SendDataConnector.js: CLIENT is data received : 10000,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:45.325Z SendDataConnector.js: CLIENT is data received : 20000,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:45.431Z SendDataConnector.js: CLIENT is data received : 30000,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:45.836Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3216): Found 7 peers.
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3216): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3216): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(6): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/jxcore-log( 3216): 2015-11-23T10:40:46.070Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:40:46.363Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:46.419Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d79c rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3216): 2015-11-23T10:40:47.124Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:47.477Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: G3-1
,I/jxcore-log( 3216): 2015-11-23T10:40:47.856Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:47.857Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:47.864Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:40:47.865Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: 34:FC:EF:9D:93:0B
I/BtToSocketBase( 3216): Stop ReceivingThread
,I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/jxcore-log( 3216): 2015-11-23T10:40:47.875Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): do fake peer & start,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:47.880Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:47.881Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:40:47.882Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 08:EC:A9:50:75:41, name: A3-1
W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,I/        ( 3216): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 4308 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d79c rs_disc_pending=1,
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d79c rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Thali Test's G2,
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41,
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Cleared service requests
I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3216): Found 8 peers.
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3216): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 3216): Added service request
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/        ( 3216): Started service discovery
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x22  CID 0x48
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 46
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:41:18.910Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:18.911Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:41:18.912Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3216): 2015-11-23T10:41:23.913Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:23.914Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/SS      ( 3216): Found 7 peers.
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): A5-1 7e:f9:0e:37:96:ac,
I/SS      ( 3216): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/jxcore-log( 3216): 2015-11-23T10:41:28.918Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:28.918Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:28.919Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:41:28.919Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to A3-1, at 08:EC:A9:50:75:41,
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Started service discovery
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [08:ec:a9:50:75:41]: 6, 1d, 7d3
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d964 rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3216): Starting to Handshake
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 3216): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3216): HandshakeOk : samsung-SM-A300FU_PT7946
I/HS      ( 3216): Hand Shake finished outgoing for : samsung-SM-A300FU_PT7946
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-A300FU_PT7946
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3216): mHTTPPort  set to : 54696
I/BtConnectorHelper( 3216): Request socket is using : 54696
,I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :54696
,I/jxcore-log( 3216): 2015-11-23T10:41:36.202Z SendDataConnector.js: CLIENT connected to 54696, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:36.203Z SendDataConnector.js: CLIENT starting client ,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:36.212Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 54696
I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23853
,I/jxcore-log( 3216): 2015-11-23T10:41:36.307Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:36.480Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13953
,I/jxcore-log( 3216): 2015-11-23T10:41:36.508Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:36.597Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4053
,I/jxcore-log( 3216): 2015-11-23T10:41:36.692Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:36.816Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:36.927Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:37.051Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:37.237Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:37.321Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:37.322Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:37.327Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:37.329Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: 08:EC:A9:50:75:41
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
,I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
,I/BtToRequestSocket( 3216): Close server socket
I/jxcore-log( 3216): 2015-11-23T10:41:37.337Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:41:37.341Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:37.342Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:37.344Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
,I/        ( 3216): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at F4:F1:E1:5C:3B:E2
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 49441 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d964 rs_disc_pending=1,
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 48
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:41:43.338Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:43.340Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:41:43.341Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3216): 2015-11-23T10:41:48.342Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:48.343Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/jxcore-log( 3216): 2015-11-23T10:41:53.347Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:41:53.347Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:41:53.348Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:41:53.348Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: F4:F1:E1:5C:3B:E2, name: null,
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at F4:F1:E1:5C:3B:E2
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3272): invalid rfc slot id: 49
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:41:56.487Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:41:56.488Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:41:56.489Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3216): Found 8 peers.
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/        ( 3216): Started service discovery
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6ecfc rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,V/GoogleAuthProtoRequest( 3291): [341] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3291): [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3291): [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3291): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3291): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3291): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3291): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3291): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3216): 2015-11-23T10:42:01.491Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:01.492Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): 2015-11-23T10:42:06.496Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:06.497Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:06.498Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:06.498Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at F4:F1:E1:5C:3B:E2
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 3272): process_service_search_attr_rsp,
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 3272): invalid rfc slot id: 50
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:42:08.503Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:08.504Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:08.504Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3216): Found 8 peers.
,I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3272): info:x10,
,D/        ( 3272): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3,
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: G3-1
,I/        ( 3216): Started service discovery,
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3216): 2015-11-23T10:42:13.505Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:13.506Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255,
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200,
I/BTListenerThread( 3216): we got incoming connection
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTListenerThread( 3216): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 77 bytes.,
I/BTListenerThread( 3216): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
I/HS      ( 3216): Incoming connection Hand Shake finished for : LGE-LG-D855_PT6848
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, LGE-LG-D855_PT6848
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
,I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
,I/jxcore-log( 3216): 2015-11-23T10:42:14.153Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-23T10:42:14.642Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:14.648Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:14.737Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:14.743Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:42:14.831Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:14.841Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:14.933Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:14.940Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:14.948Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.034Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.039Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.078Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/jxcore-log( 3216): 2015-11-23T10:42:15.235Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.248Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.335Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.349Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.448Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.537Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.633Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.642Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.739Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.838Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.844Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.934Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.942Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:15.948Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:16.044Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:42:16.052Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:16.144Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:16.241Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:16.251Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:16.341Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:16.378Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:16.637Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:16.940Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3216): 2015-11-23T10:42:17.141Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:17.453Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:17.489Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:17.550Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:17.560Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:17.650Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:17.743Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:17.778Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:17.855Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:17.863Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:17.871Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:17.908Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): invalid rfc slot id: 43
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT6848,
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close bt socket
,I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3216): 2015-11-23T10:42:17.969Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x4e
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/jxcore-log( 3216): 2015-11-23T10:42:18.511Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:18.512Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:18.512Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:18.513Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at F4:F1:E1:5C:3B:E2
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6eb34 rs_disc_pending=1
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: G3-1
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 52
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:42:22.726Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:22.727Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:22.728Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3216): 2015-11-23T10:42:27.729Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:27.730Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 9 peers.
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Started service discovery
,I/jxcore-log( 3216): 2015-11-23T10:42:32.733Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:32.734Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:32.735Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:32.736Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: F4:F1:E1:5C:3B:E2, name: null,
,I/        ( 3216): Connecting to null, at F4:F1:E1:5C:3B:E2
I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 53
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:42:37.891Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:37.892Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:37.895Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:37.898Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:37.898Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:37.899Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:37.899Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/        ( 3216): Connecting to null, at 50:2E:6C:AC:21:50
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 60551 ms, rnd: 5, ex: Connection to F4:F1:E1:5C:3B:E2 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0xd  CID 0x44
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 54
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:42:40.568Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:40.569Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:40.570Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 11 peers.,
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d,
I/SS      ( 3216): Peer(8): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3216): Peer(9): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3216): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/jxcore-log( 3216): 2015-11-23T10:42:45.571Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:45.572Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
,I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3216): 2015-11-23T10:42:50.575Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:50.576Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:50.577Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:50.592Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3216): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 55
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:42:51.280Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:42:51.288Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:51.289Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3216): 2015-11-23T10:42:56.290Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:42:56.290Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/SS      ( 3216): Found 11 peers.
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3216): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3216): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3216): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/art     ( 1506): Explicit concurrent mark sweep GC freed 77241(3MB) AllocSpace objects, 16(1576KB) LOS objects, 36% free, 27MB/43MB, paused 1.142ms total 43.785ms
,I/jxcore-log( 3216): 2015-11-23T10:43:01.292Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:01.293Z SendDataConnector.js: Connect (retry count 2) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:01.294Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:01.294Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to null, at 50:2E:6C:AC:21:50
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 56
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:43:02.796Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:02.798Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:02.799Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/BooksSync( 3568): Starting books sync for 61035162, extras: ade
,I/art     (  822): Explicit concurrent mark sweep GC freed 71356(3MB) AllocSpace objects, 5(174KB) LOS objects, 31% free, 34MB/50MB, paused 2.222ms total 87.281ms
,I/BooksConfig( 3568): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3216): 2015-11-23T10:43:07.800Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:07.800Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3568): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3568): Soft error
E/BooksSync( 3568): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3568): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3568): Sync error
E/BooksSync( 3568): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3568): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3568): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1208576, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/SS      ( 3216): Found 12 peers.
,I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3216): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
I/SS      ( 3216): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3216): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(7): A3-1 0a:ec:a9:50:75:42,
I/SS      ( 3216): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(9): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3216): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3216): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3216): 2015-11-23T10:43:12.805Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:12.806Z SendDataConnector.js: Connect (retry count 3) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:12.807Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:12.807Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3216): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 57
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:43:14.320Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:14.321Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:14.322Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3216): 2015-11-23T10:43:19.324Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:19.324Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/jxcore-log( 3216): 2015-11-23T10:43:24.328Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:24.329Z SendDataConnector.js: Connect (retry count 4) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:24.329Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:24.329Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 50:2E:6C:AC:21:50, name: null,
,I/        ( 3216): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 58
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:43:25.858Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:25.859Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:25.865Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:25.871Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- gotta redo : 50:2E:6C:AC:21:50, try count now: 1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:25.873Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:25.874Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:25.875Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 58:2A:F7:ED:96:BE, name: null,
,I/        ( 3216): Connecting to null, at 58:2A:F7:ED:96:BE,
I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 47961 ms, rnd: 5, ex: Connection to 50:2E:6C:AC:21:50 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6eec4 rs_disc_pending=1,
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL,
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 59
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:43:31.048Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:31.049Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:31.050Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3216): Found 12 peers.
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3216): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3216): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(8): G4-1 a2:39:f7:6f:c9:5d,
I/SS      ( 3216): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3216): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3216): 2015-11-23T10:43:36.051Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:36.052Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3216): 2015-11-23T10:43:41.056Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:41.057Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:41.058Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:41.058Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Cleared service requests
I/        ( 3216): Started peer discovery
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 60,
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:43:46.217Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:46.218Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:46.218Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 12 peers.
,I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3216): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3216): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(8): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3216): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3216): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3216): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
,I/        ( 3216): Added service request,
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3216): 2015-11-23T10:43:51.220Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:51.220Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/jxcore-log( 3216): 2015-11-23T10:43:56.225Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:43:56.226Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:56.227Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:43:56.227Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 58:2A:F7:ED:96:BE, name: null,
,I/BTConnectToThread( 3216): Starting to connect
I/        ( 3216): Connecting to null, at 58:2A:F7:ED:96:BE
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28,
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/SS      ( 3216): Found 10 peers.
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): Note4-1 92:b6:86:43:73:1c,
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3216): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/        ( 3216): Started service discovery
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 61
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:44:01.390Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:01.391Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:01.391Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): 2015-11-23T10:44:06.392Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:06.392Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): ,
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2988): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at blb.a(PG:3937)
E/HttpOperation( 2988): 	at czp.a(PG:18188)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 12 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 14 more
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2988): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2988): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2988): 	at jdm.a(PG:82)
E/HttpOperation( 2988): 	at jcs.o(PG:406)
E/HttpOperation( 2988): 	at jcn.a(PG:1379)
E/HttpOperation( 2988): 	at jcs.i(PG:143)
E/HttpOperation( 2988): 	at hec.a(PG:42)
E/HttpOperation( 2988): 	at hee.a(PG:102)
E/HttpOperation( 2988): 	at czr.a(PG:65)
E/HttpOperation( 2988): 	at kka.a(PG:108)
E/HttpOperation( 2988): 	at czp.a(PG:19176)
E/HttpOperation( 2988): 	at czp.a(PG:9081)
E/HttpOperation( 2988): 	at czq.run(PG:1686)
E/HttpOperation( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2988): 	at jdj.a(PG:4091)
E/HttpOperation( 2988): 	at jdj.a(PG:1125)
E/HttpOperation( 2988): 	at jdm.a(PG:77)
E/HttpOperation( 2988): 	... 15 more
E/HttpOperation( 2988): Caused by: faj: BadAuthentication
E/HttpOperation( 2988): 	at fal.a(PG:38)
E/HttpOperation( 2988): 	at jdj.a(PG:4089)
E/HttpOperation( 2988): 	... 17 more
,E/ExperimentLoader( 2988): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2988): 	at jdm.a(PG:82)
E/ExperimentLoader( 2988): 	at jcs.o(PG:406)
E/ExperimentLoader( 2988): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2988): 	at jcs.i(PG:143)
E/ExperimentLoader( 2988): ,	at hec.a(PG:42)
E/ExperimentLoader( 2988): 	at hee.a(PG:102)
E/ExperimentLoader( 2988): 	at czr.a(PG:65)
E/ExperimentLoader( 2988): 	at kka.a(PG:108)
E/ExperimentLoader( 2988): 	at czp.a(PG:19176)
E/ExperimentLoader( 2988): ,	at czp.a(PG:9081)
E/ExperimentLoader( 2988): 	at czq.run(PG:1686)
E/ExperimentLoader( 2988): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2988): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2988): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ExperimentLoader( 2988): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2988): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2988): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2988): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2988): 	at jdm.a(PG:77)
E/ExperimentLoader( 2988): 	,... 15 more
E/ExperimentLoader( 2988): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2988): 	at fal.a(PG:38)
E/ExperimentLoader( 2988): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2988): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1265518, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/jxcore-log( 3216): 2015-11-23T10:44:11.396Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:11.396Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:11.397Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:11.397Z SendDataConnector.js: do connect now,
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 58:2A:F7:ED:96:BE, name: null,
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 62,
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:44:16.557Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:16.557Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:16.558Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3216): Found 11 peers.
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3216): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3216): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/        ( 3216): Started service discovery
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3216): 2015-11-23T10:44:21.560Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:21.561Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:26.564Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:26.565Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:26.565Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:26.566Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 58:2A:F7:ED:96:BE, name: null,
,I/BTConnectToThread( 3216): Starting to connect,
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/SS      ( 3216): Found 8 peers.
,I/SS      ( 3216): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3216): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3216): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6debc rs_disc_pending=0
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/        ( 3216): Started service discovery
,D/btif_config( 3272): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 3272): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3216): we got incoming connection
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTListenerThread( 3216): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 77 bytes.,
I/BTListenerThread( 3216): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5103","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
I/HS      ( 3216): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT5103
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, LGE-Nexus 5_PT5103
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/jxcore-log( 3216): 2015-11-23T10:44:30.940Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): ,
I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
,I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-23T10:44:31.436Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:31.615Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:31.619Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:31.692Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3216): 
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 63
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:44:31.725Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:31.726Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:31.729Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:31.732Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:31.735Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:31.735Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:31.736Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/        ( 3216): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3216): 2015-11-23T10:44:31.748Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 65852 ms, rnd: 5, ex: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3216): 2015-11-23T10:44:31.773Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:31.778Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6debc rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3216): 2015-11-23T10:44:32.011Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.016Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.021Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.026Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.059Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.070Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.098Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.104Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.139Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.185Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.262Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.266Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.404Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.476Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.509Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.545Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.681Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.728Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.736Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.770Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.774Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.780Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.828Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.896Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.956Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:32.963Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:33.020Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): invalid rfc slot id: 51
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT5103
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3216): 2015-11-23T10:44:33.104Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6debc rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x4d
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Nexus 5
,V/KeepSync( 3322): Connecting to GoogleApiClient
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1791): Handling authorization failure
E/ClientConnectionOperation( 1791): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1791): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1791): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1791): 	... 7 more
,V/KeepSync( 3322): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 3322): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1506): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1506): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1506): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1506): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1506): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3322): IOException
E/KeepSync( 3322): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3322): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3322): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3322): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3322): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3322): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3322): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3322): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3322): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3322): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3322): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3322): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3322): 	... 10 more
,W/KeepSync( 3322): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1276540, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0xd  CID 0x4c
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 65
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:44:42.280Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:42.282Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:42.283Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:44:47.285Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:47.286Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:52.290Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:52.291Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:52.291Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:52.292Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Thali Test (Galaxy A3)
W/bt-sdp  ( 3272): process_service_search_attr_rsp
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3216): Starting to Handshake
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3216): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3216): HandshakeOk : samsung-SM-A300FU_PT3495
I/HS      ( 3216): Hand Shake finished outgoing for : samsung-SM-A300FU_PT3495
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-A300FU_PT3495
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 44822
,I/BtConnectorHelper( 3216): Request socket is using : 44822
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :44822
,I/jxcore-log( 3216): 2015-11-23T10:44:56.902Z SendDataConnector.js: CLIENT connected to 44822, error: null
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:56.902Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 44822
,I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-23T10:44:56.922Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23853
,I/jxcore-log( 3216): 2015-11-23T10:44:57.046Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:57.126Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13953
,I/jxcore-log( 3216): 2015-11-23T10:44:57.208Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:57.285Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3063
,I/jxcore-log( 3216): 2015-11-23T10:44:57.347Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:57.421Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:57.439Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:57.482Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:57.489Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:57.530Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:57.531Z SendDataConnector.js: got all data for this round,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:57.534Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:57.535Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: 08:EC:A9:50:76:27
I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
,I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3216): Close LocalOutputStream
,I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket,
I/jxcore-log( 3216): 2015-11-23T10:44:57.546Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:57.549Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:57.549Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:57.550Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/        ( 3216): Selected device address: 90:E7:C4:F6:69:77, name: null
I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at 90:E7:C4:F6:69:77
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 25797 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6db2c rs_disc_pending=1
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [90:e7:c4:f6:69:77]: 6, f, 4106
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 67
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:44:58.905Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:44:58.905Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:44:58.906Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Thali Test (Galaxy A3),
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d5d4 rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/btif_config( 3272): btif_get_device_type: Device [34:fc:ef:11:b1:66] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
D/BluetoothAdapterProperties( 3272): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3216): we got incoming connection
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3216): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTListenerThread( 3216): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3216): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3216): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3216): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT8960
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : true, LGE-Nexus 5_PT8960
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): Creating BTConnectedThread
I/BtConnectorHelper( 3216): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3216): --DoOneRunRound started
,I/BtToRequestSocket( 3216): LocalHost address: localhost/127.0.0.1, port: 41537
I/BtToRequestSocket( 3216): --DoOneRunRound ended
,I/jxcore-log( 3216): 2015-11-23T10:45:03.658Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:03.908Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:03.908Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.037Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.044Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.129Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.137Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.140Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.147Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.175Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.208Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.236Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.268Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.273Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.277Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.309Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.317Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.349Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.354Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.412Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.414Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.476Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.512Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.517Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.553Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.558Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.597Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.629Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.649Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.688Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.725Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.763Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.767Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.778Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.830Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.867Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.898Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:04.953Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3216): 
,W/bt-btif ( 3272): invalid rfc slot id: 64
,I/BtToSocketBase( 3216): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8960
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3216): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8960
,I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/jxcore-log( 3216): 2015-11-23T10:45:05.058Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3216): 
,W/bt-rfcomm( 3272): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 3272): RFCOMM_DisconnectInd LCID:0x46
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0,
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3216): 2015-11-23T10:45:08.911Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:08.912Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:08.913Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:08.913Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/        ( 3216): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3216): Connecting to null, at 90:E7:C4:F6:69:77
I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d5d4 rs_disc_pending=1,
W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 69
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:45:14.253Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:14.253Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:14.254Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:19.255Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:19.255Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:24.259Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:24.260Z SendDataConnector.js: Connect (retry count 2) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:24.261Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:24.261Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3216): Connecting to null, at 90:E7:C4:F6:69:77
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/SS      ( 3216): Found 2 peers.
,I/SS      ( 3216): Peer(1): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(2): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x42,
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 70
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:45:29.424Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:29.425Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:29.425Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3216): 2015-11-23T10:45:34.427Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:34.427Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5515","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5515","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT5515, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT5515, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3216): 2015-11-23T10:45:39.431Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:39.432Z SendDataConnector.js: Connect (retry count 3) to peer 90:E7:C4:F6:69:77 with availability status: true
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:39.432Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:39.432Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 90:E7:C4:F6:69:77, name: null
I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to null, at 90:E7:C4:F6:69:77
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10,
D/        ( 3272): remote version info [90:e7:c4:f6:69:77]: 6, f, 6109
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 71
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:45:41.505Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:41.506Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:41.506Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3216): 2015-11-23T10:45:46.507Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:46.508Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 8 peers.
I/SS      ( 3216): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3216): 2015-11-23T10:45:51.512Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): ,
I/jxcore-log( 3216): 2015-11-23T10:45:51.512Z SendDataConnector.js: Connect (retry count 4) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:51.513Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:51.513Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Connecting to null, at 90:E7:C4:F6:69:77
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 72
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:45:54.514Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:54.514Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:54.519Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:54.521Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): ---- gotta redo : 90:E7:C4:F6:69:77, try count now: 1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: 00:F4:6F:30:E0:6C,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:54.525Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:54.525Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:54.526Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C,
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 56966 ms, rnd: 5, ex: Connection to 90:E7:C4:F6:69:77 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6e96c rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6e084 rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL,
,W/bt-btif ( 3272): invalid rfc slot id: 73,
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:45:57.855Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:45:57.856Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:45:57.856Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3216): 2015-11-23T10:46:02.857Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:02.857Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/SS      ( 3216): Found 9 peers.
,I/SS      ( 3216): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/jxcore-log( 3216): 2015-11-23T10:46:07.862Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:07.863Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:07.863Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:07.864Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/BTConnectToThread( 3216): Starting to connect
,I/        ( 3216): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/        ( 3216): Started service discovery
,W/bt-btif ( 3272): info:x10,
D/        ( 3272): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,W/bt-btif ( 3272): invalid rfc slot id: 74,
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:46:10.165Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:10.166Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:10.167Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3216): 2015-11-23T10:46:15.168Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:15.169Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: S5mini-1
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/jxcore-log( 3216): 2015-11-23T10:46:20.172Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:20.173Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:20.174Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:20.174Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10,
,D/        ( 3272): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 9 peers.
,I/SS      ( 3216): Peer(1): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3216): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b,
I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3216): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(8): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3216): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,W/bt-btif ( 3272): invalid rfc slot id: 75
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:46:23.872Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:23.873Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:23.875Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3041, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3041, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: S5mini-1,
,I/jxcore-log( 3216): 2015-11-23T10:46:28.876Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:28.877Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/jxcore-log( 3216): 2015-11-23T10:46:33.881Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:33.882Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:33.882Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:33.883Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3216): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: S5mini-1,
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3216): Starting to Handshake
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 82 bytes.,
I/BTConnectToThread( 3216): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3216): HandshakeOk : samsung-SM-G800F_PT5812
I/HS      ( 3216): Hand Shake finished outgoing for : samsung-SM-G800F_PT5812
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-G800F_PT5812
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 44548
,I/BtConnectorHelper( 3216): Request socket is using : 44548
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :44548
,I/jxcore-log( 3216): 2015-11-23T10:46:35.224Z SendDataConnector.js: CLIENT connected to 44548, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:35.224Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 44548
,I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
I/jxcore-log( 3216): 2015-11-23T10:46:35.236Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:35.528Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:35.617Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:35.719Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:35.796Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:35.919Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:35.965Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:36.052Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:36.082Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:36.263Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:36.329Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:36.330Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:36.336Z SendDataConnector.js: CLIENT Stop now
,I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:36.337Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3216): 
,I/BtConnectorHelper( 3216): Disconnect outgoing peer: 00:F4:6F:30:E0:6C
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/jxcore-log( 3216): 2015-11-23T10:46:36.350Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:36.351Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:36.352Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:36.352Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3216): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 41806 ms, rnd: 4, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6e084 rs_disc_pending=1
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-btif ( 3272): info:x10,
D/        ( 3272): remote version info [7c:f9:0e:37:96:ab]: 6, f, 410d
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: A5-1,
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3216): Starting to Handshake
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 3216): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3216): HandshakeOk : samsung-SM-A500FU_PT9488
I/HS      ( 3216): Hand Shake finished outgoing for : samsung-SM-A500FU_PT9488
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, samsung-SM-A500FU_PT9488
,I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3216): mHTTPPort  set to : 47695
,I/BtConnectorHelper( 3216): Request socket is using : 47695
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :47695
,I/jxcore-log( 3216): 2015-11-23T10:46:38.107Z SendDataConnector.js: CLIENT connected to 47695, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:38.107Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 47695
I/BtToRequestSocket( 3216): Set local streams
,I/jxcore-log( 3216): 2015-11-23T10:46:38.119Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): rin ended ---------------------------;
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3216): 2015-11-23T10:46:38.390Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3216): Found 11 peers.
,I/SS      ( 3216): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3216): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3216): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(9): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3216): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3216): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6e084 rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3216): 2015-11-23T10:46:39.013Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): ,
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3216): 2015-11-23T10:46:39.173Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:39.277Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 3216): 2015-11-23T10:46:39.480Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3216): 2015-11-23T10:46:39.596Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:39.715Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3041, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3041, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/jxcore-log( 3216): 2015-11-23T10:46:39.880Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3216): 2015-11-23T10:46:39.987Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:40.074Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:40.074Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:40.077Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:40.078Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/BtConnectorHelper( 3216): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Close bt out
,I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/jxcore-log( 3216): 2015-11-23T10:46:40.088Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): ---- round done--------
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3216): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:40.093Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:40.093Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:40.094Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
I/        ( 3216): Selected device address: 34:FC:EF:11:B1:66, name: Nexus 5
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to Nexus 5, at 34:FC:EF:11:B1:66
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 3723 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [34:fc:ef:11:b1:66]: 6, f, 410d
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Nexus 5
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6d5d4 rs_disc_pending=1
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200,
I/BTConnectToThread( 3216): Starting to Handshake
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 77 bytes.,
I/BTConnectToThread( 3216): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3216): HandshakeOk : LGE-Nexus 5_PT8960
I/HS      ( 3216): Hand Shake finished outgoing for : LGE-Nexus 5_PT8960
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, LGE-Nexus 5_PT8960
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 36478
,I/BtConnectorHelper( 3216): Request socket is using : 36478
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :36478
,I/jxcore-log( 3216): 2015-11-23T10:46:42.122Z SendDataConnector.js: CLIENT connected to 36478, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:42.123Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:42.130Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 36478
,I/BtToRequestSocket( 3216): Set local streams
I/BtToRequestSocket( 3216): rin ended ---------------------------;
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23853
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11973
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:93
,I/jxcore-log( 3216): 2015-11-23T10:46:43.895Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:43.899Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:43.960Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:43.964Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:43.991Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:43.991Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:43.995Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:43.996Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/BtConnectorHelper( 3216): Disconnect outgoing peer: 34:FC:EF:11:B1:66
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
,I/jxcore-log( 3216): 2015-11-23T10:46:44.006Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3216): 
W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:44.010Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:44.010Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
,I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:44.011Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: 34:FC:EF:11:AE:67, name: Nexus 5
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to Nexus 5, at 34:FC:EF:11:AE:67,
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 3899 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: A5-1
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [34:fc:ef:11:ae:67]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6debc rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6debc rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3216): Starting to Handshake
I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 77 bytes.,
I/BTConnectToThread( 3216): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5103","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3216): HandshakeOk : LGE-Nexus 5_PT5103
,I/HS      ( 3216): Hand Shake finished outgoing for : LGE-Nexus 5_PT5103
I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, LGE-Nexus 5_PT5103
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 37536
,I/BtConnectorHelper( 3216): Request socket is using : 37536
I/BtToRequestSocket( 3216): Now accepting connections
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :37536
,I/jxcore-log( 3216): 2015-11-23T10:46:50.549Z SendDataConnector.js: CLIENT connected to 37536, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:50.549Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 37536
I/BtToRequestSocket( 3216): Set local streams
,I/jxcore-log( 3216): 2015-11-23T10:46:50.559Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): rin ended ---------------------------;
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3216): 2015-11-23T10:46:50.956Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:51.203Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3216): 2015-11-23T10:46:51.337Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:51.552Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3216): 
,D/        ( 3272): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3199
,I/jxcore-log( 3216): 2015-11-23T10:46:51.740Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:51.785Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:51.866Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:52.039Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:52.164Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:52.289Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:52.290Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:52.293Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:52.294Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/BtConnectorHelper( 3216): Disconnect outgoing peer: 34:FC:EF:11:AE:67
I/BtToSocketBase( 3216): Stop ReceivingThread,
I/BtToSocketBase( 3216): Stop SendingThread,
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3216): Close bt in
,I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3216): Close bt out
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
I/jxcore-log( 3216): 2015-11-23T10:46:52.302Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:52.304Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:52.305Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:46:52.306Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/        ( 3216): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to null, at B4:CE:F6:AB:A4:6A
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 8280 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6debc rs_disc_pending=1
W/bt-btif ( 3272): bta_dm_check_av:0
,W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6debc rs_disc_pending=0
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive,
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 80
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:46:57.669Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:57.671Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:46:57.672Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 11 peers.
,I/SS      ( 3216): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3216): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(8): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3216): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3216): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0,
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0,
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8960, peerAddress: 34:FC:EF:11:B1:66
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8960, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/jxcore-log( 3216): 2015-11-23T10:47:02.673Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:02.674Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0,
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/jxcore-log( 3216): 2015-11-23T10:47:07.678Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:07.678Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:07.679Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:07.679Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/        ( 3216): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at B4:CE:F6:AB:A4:6A
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,W/bt-btif ( 3272): info:x10,
D/        ( 3272): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,D/btif_config( 3272): btif_get_device_type: Device [b4:ce:f6:ab:a4:6a] type 1
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
,E/bt-btif ( 3272): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3272): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3272): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 3272): Failed to remove device: B4:CE:F6:AB:A4:6A,
,I/BluetoothBondStateMachine( 3272): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3272): StableState(): Entering Off State
,W/bt-btif ( 3272): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3272): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3272): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3216): Starting to Handshake
,I/BTHandshakeSocketThread( 3216): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3216): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread started
,I/BTConnectToThread( 3216): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 3216): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3216): HandshakeOk : HTC-HTC Desire 820_PT515
I/HS      ( 3216): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT515
,I/BTHandshakeSocketThread( 3216): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3216): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT515
I/BtToSocketBase( 3216): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3216): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3216): mHTTPPort  set to : 35396
,I/BtConnectorHelper( 3216): Request socket is using : 35396
I/BtToRequestSocket( 3216): Now accepting connections
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/BtConnectorHelper( 3216): Calling ConnectionStatusUpdate with port :35396
,I/jxcore-log( 3216): 2015-11-23T10:47:14.912Z SendDataConnector.js: CLIENT connected to 35396, error: null
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:14.912Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:14.920Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3216): 
,I/BtToRequestSocket( 3216): incoming data from: /127.0.0.1, port: 35396
I/BtToRequestSocket( 3216): Set local streams
,I/BtToRequestSocket( 3216): rin ended ---------------------------;
,I/jxcore-log( 3216): 2015-11-23T10:47:15.125Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:15.322Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:15.523Z SendDataConnector.js: CLIENT is data received : 30000,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:15.624Z SendDataConnector.js: CLIENT is data received : 40000,
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:15.826Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3216): ,
,I/jxcore-log( 3216): 2015-11-23T10:47:16.027Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3216): ,
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 11 peers.
,I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(6): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3216): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(9): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3216): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3216): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/jxcore-log( 3216): 2015-11-23T10:47:16.731Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:16.840Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:17.033Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3216): 2015-11-23T10:47:17.234Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:17.235Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:17.239Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:17.239Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3216): 
I/BtConnectorHelper( 3216): Disconnect outgoing peer: B4:CE:F6:AB:A4:6A
,I/BtToSocketBase( 3216): Stop ReceivingThread
I/BtToSocketBase( 3216): Stop SendingThread
I/BtToSocketBase( 3216): Close local in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3216): Close LocalOutputStream
I/BtToSocketBase( 3216): Close localHostSocket
,I/BtToSocketBase( 3216): Close bt in
I/BtToSocketBase( 3216): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3216): Close bt out,
I/BtToSocketBase( 3216): Close bt socket
I/BtToRequestSocket( 3216): Close server socket
,I/jxcore-log( 3216): 2015-11-23T10:47:17.251Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ---- round done--------
I/jxcore-log( 3216): 
I/jxcore-log( 3216): do fake peer & start
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:17.253Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:17.253Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:17.254Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
I/        ( 3216): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to null, at F4:F1:E1:5C:3B:E2
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback round[0] time: 24931 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3216): Started service discovery
,E/bt-btm  ( 3272): tBTM_SEC_DEV:0xa2f6e5dc rs_disc_pending=1
,W/bt-btif ( 3272): bta_dm_check_av:0
W/bt-btif ( 3272): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3272): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3272): onReceive
,I/BTConnectionReceiver( 4043): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4043): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3272): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3272): invalid rfc slot id: 82
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:47:23.081Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:23.081Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:23.082Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:28.084Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:28.085Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/jxcore-log( 3216): 2015-11-23T10:47:33.089Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:33.090Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:33.090Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:33.091Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/BTConnectToThread( 3216): Starting to connect
,W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at F4:F1:E1:5C:3B:E2
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [f4:f1:e1:5c:3b:e2]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL,
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 83
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:47:37.541Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:37.542Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:37.543Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3216): 2015-11-23T10:47:42.544Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:42.544Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:47.548Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2,
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:47.549Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:47.550Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:47.550Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/BTConnectToThread( 3216): Starting to connect,
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at F4:F1:E1:5C:3B:E2
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3216): timeout now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): dun
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): weAreDoneNow , resultArray.length: 16
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): done, now sending data to server
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): -- RESULT DATA {"name:":"motorola-Nexus 6_PT5015","time":1000089,"result":"TIMEOUT","sendList":[{"name":"44:80:EB:7B:5A:05","time":10395,"result":"OK","connections":1,"tryCount":1},{"name":"80:01:84:8A:B3:68","time":47327,"result":"OK","connections":4,"tryCount":1},{"name":"F8:95:C7:87:3C:51","time":2315,"result":"OK","connections":1,"tryCount":1},{"name":"7C:F9:0E:34:8A:A0","time":3831,"result":"OK","connections":1,"tryCount":1},{"name":"F8:95:C7:87:85:54","time":3462,"result":"OK","connections":1,"tryCount":1},{"name":"E0:DB:10:14:E2:C0","time":111811,"result":"OK","connections":4,"tryCount":1},{"name":"E0:DB:10:1F:C9:5E","time":10027,"result":"OK","connections":1,"tryCount":1},{"name":"58:3F:54:73:64:C0","time":29392,"result":"OK","connections":1,"tryCount":1},{"name":"34:FC:EF:9D:93:0B","time":4308,"result":"OK","connections":1,"tryCount":1},{"name":"08:EC:A9:50:75:41","time":49441,"result":"OK","connections":2,"tryCount":1},{"name":"08:EC:A9:50:76:27","time":25797,"result":"OK","connections":2,"tryCount
,I/jxcore-log( 3216): sendList : 100% : 111811 ms, 99% : 111811 ms, 95 : 49441 ms, 90% : 47327 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): Result count 16, range 2315 ms to  111811 ms.
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): sendList failed peers count : 4 [20 %]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : F4:F1:E1:5C:3B:E2, Tried : 2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : 50:2E:6C:AC:21:50, Tried : 1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): - Peer ID : 90:E7:C4:F6:69:77, Tried : 1
I/jxcore-log( 3216): 
I/jxcore-log( 3216): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:47.719Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:47.720Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3272): info:x10,
D/        ( 3272): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 84
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:47:51.565Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:51.567Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:47:51.568Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3216): 2015-11-23T10:47:56.570Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:47:56.571Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/jxcore-log( 3216): 2015-11-23T10:48:01.575Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:48:01.576Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:48:01.576Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:48:01.577Z SendDataConnector.js: do connect now
I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3216): Connecting to null, at F4:F1:E1:5C:3B:E2
D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3272): info:x10
D/        ( 3272): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 85
I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3216): 2015-11-23T10:48:03.044Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:48:03.044Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:48:03.045Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3216): 
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3216): 2015-11-23T10:48:08.046Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:48:08.046Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:48:13.049Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:48:13.050Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:48:13.050Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:48:13.051Z SendDataConnector.js: do connect now
,I/jxcore-log( 3216): 
,I/        ( 3216): Selected device address: F4:F1:E1:5C:3B:E2, name: null
I/BTConnectToThread( 3216): Starting to connect
W/BluetoothAdapter( 3216): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3216): Connecting to null, at F4:F1:E1:5C:3B:E2
,D/BTIF_SOCK( 3272): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3272): info:x10
,D/        ( 3272): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3272): process_service_search_attr_rsp
,E/bt-btif ( 3272): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3272): invalid rfc slot id: 86
,I/BTConnectToThread( 3216): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3216): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3216): 2015-11-23T10:48:14.697Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:48:14.698Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3216): 
I/jxcore-log( 3216): 2015-11-23T10:48:14.699Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): 2015-11-23T10:48:14.701Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3216): 
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3216): Found 6 peers.
,I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0,
I/SS      ( 3216): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(6): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Started service discovery
,E/bt-btm  ( 3272): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3272): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3216): Cleared service requests
I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/SS      ( 3216): Found 7 peers.
,I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3216): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8960, peerAddress: 34:FC:EF:11:B1:66
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8960, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/        ( 3216): Cleared service requests
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 10 peers.
,I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3216): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(9): G3-1 02:9a:02:7b:60:ac,
I/SS      ( 3216): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9488","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT9488, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT9488, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8960, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8960, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5515","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5515","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT5515, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT5515, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3216): Found 12 peers.
,I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3216): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(7): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3216): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(10): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3216): Started service discovery
,I/        ( 3216): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3041, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3041, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3216): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5515","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5515","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT5515, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT5515, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3216): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5103","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5103","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT5103, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT5103, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 12 peers.
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3216): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3216): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3216): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(7): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3216): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(10): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0,
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3216): Started service discovery
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3041","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT3041, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT3041, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3216): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5103","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5103","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT5103, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT5103, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3216): Cleared service requests,
I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3216): Found 14 peers.
,I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2,
I/SS      ( 3216): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3216): Peer(7): G3-1 02:9a:02:7b:60:ac,
I/SS      ( 3216): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3216): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
,I/SS      ( 3216): Peer(10): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3216): Peer(11): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(12): G3s-1 a2:39:f7:70:12:80,
I/SS      ( 3216): Peer(13): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(14): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 13 peers.
I/SS      ( 3216): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3216): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3216): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3216): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3216): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(10): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(11): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3216): Peer(12): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(13): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3216): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,W/bt-btm  ( 3272): Stopping oneshot timer
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 5 peers.
,I/SS      ( 3216): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3216): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3216): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5103","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5103","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT5103, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT5103, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery,
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 11 peers.
I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3216): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3216): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(8): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3216): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3216): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3216): Added service request
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8960, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8960, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3216): Cleared service requests
,I/        ( 3216): Started peer discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3216): Found 11 peers.
,I/SS      ( 3216): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3216): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3216): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3216): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3216): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3216): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3216): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3216): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3216): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3216): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3216): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3216): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3216): Added service request
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3216): Started service discovery
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3216): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5812"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5812, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5812, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7555","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT7555, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT7555, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3216): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2678","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2678, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2678, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3495","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT3495, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT3495, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3216): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9740","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9740, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9740, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3216): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7946","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT7946, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT7946, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"}, typeCordovap2p._tcp.local.:,
I/        ( 3216): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8960"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8960, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8960, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3216): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4760"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4760, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4760, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3216): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT515"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT515, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT515, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3216): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5103","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5103","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT5103, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT5103, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3216): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3216): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6848","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6848, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3216): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6848, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 3272): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3290): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3216): DBG, CoordinatorConnector command called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): stop tests now !
I/jxcore-log( 3216): 
I/jxcore-log( 3216): stop current!
I/jxcore-log( 3216): 
I/jxcore-log( 3216): testSendData stopped
I/jxcore-log( 3216): 
,I/        ( 3216): Stoping All
I/        ( 3216): Stopping services
,I/        ( 3216): Stopping services
,I/        ( 3216): Stop Bluetooth
,I/        ( 3216): Stop Bluetooth
I/BTListenerThread( 3216): Stopped
,I/jxcore-log( 3216): StopBroadcasting went ok
I/jxcore-log( 3216): 
,I/wpa_supplicant( 3290): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/jxcore-log( 3216): 2015-11-23T10:52:07.504Z SendDataTCPServer.js: TCP/IP server  socket is disconnected,
I/jxcore-log( 3216): 
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/        ( 3216): Cleared local services
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/        ( 3216): Cleared service requests,
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 3290): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/        ( 3216): Stopped peer discovery
,I/jxcore-log( 3216): DBG, CoordinatorConnector command called
I/jxcore-log( 3216): 
,I/jxcore-log( 3216): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"F8:95:C7:87:3C:51\",\"time\":2315,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:95:C7:87:85:54\",\"time\":3462,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:37:96:AB\",\"time\":3723,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":3831,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"34:FC:EF:11:B1:66\",\"time\":3899,\"result\":\"OK\",\"connections\":1,\"tryCount\":2},{\"name\":\"34:FC:EF:9D:93:0B\",\"time\":4308,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"34:FC:EF:11:AE:67\",\"time\":8280,\"result\":\"OK\",\"connections\":1,\"tryCount\":2},{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":10027,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"44:80:EB:7B:5A:05\",\"time\":10395,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"B4:CE:F6:AB:A4:6A\",\"time\":24
,I/jxcore-log( 3216): ****TEST TOOK:  ms ****
I/jxcore-log( 3216): 
I/jxcore-log( 3216): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3216): 
I/jxcore-log( 3216): stop tests now !
I/jxcore-log( 3216): 
I/jxcore-log( 3216): end, event received
I/jxcore-log( 3216): 
I/jxcore-log( 3216): CoordinatorConnector close called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3216): 
I/jxcore-log( 3216): The Coordinator has disconnected!
I/jxcore-log( 3216): 
I/jxcore-log( 3216): The Coordinator has closed!
I/jxcore-log( 3216): 
I/jxcore-log( 3216): stop tests now !
I/jxcore-log( 3216): 
I/jxcore-log( 3216): turning Radios off
I/jxcore-log( 3216): 
I/jxcore-log( 3216): Turning radios to false
I/jxcore-log( 3216): 
D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  822): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3fc778ca mBinding = false
,D/BluetoothManagerService(  822): Message: 2
D/BluetoothManagerService(  822): Sending off request.
D/BluetoothAdapterState( 3272): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3272): Setting state to 13
I/BluetoothAdapterState( 3272): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3272): onBluetoothDisable()
I/BluetoothAdapterState( 3272): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  822): Bluetooth State Change Intent: 12 -> 13
I/jxcore-log( 3216): toggleBluetooth - 
I/jxcore-log( 3216): 
D/WifiService(  822): setWifiEnabled: false pid=3216, uid=10265
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothMapService( 3272): onReceive
D/BluetoothMapService( 3272): STATE_TURNING_OFF
D/BluetoothMapService( 3272): MAP Service closeService in
D/BluetoothMapMasInstance( 3272): MAP Service shutdown
,V/BluetoothMapMasInstance( 3272): Accept exception: (expected at shutdown),
V/BluetoothMapMasInstance( 3272): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3272): ,	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3272): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3272): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3272): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3272): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3272): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
I/BtOppRfcommListener( 3272): stopping Accept Thread
E/BtOppRfcommListener( 3272): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 3272): BluetoothSocket listen thread finished
D/BluetoothAdapterProperties( 3272): Scan Mode:20
D/BluetoothAdapterState( 3272): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
W/bt-btif ( 3272): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/btif_config_util( 3272): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 3272): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3272): L2CAP - PSM: 0x0017 not found for deregistration
I/jxcore-log( 3216): toggleWiFi
I/jxcore-log( 3216): 
E/WifiStateMachine(  822): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  822): do suspend true
I/chromium( 3216): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1506): Read error: ssl=0xaeca3e00: I/O error during system call, Connection timed out
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  822): scanCount==0 - aborting
,D/WifiScanningService(  822): SCAN_AVAILABLE : 1
D/RttService(  822): SCAN_AVAILABLE : 1
D/WifiScanningService(  822): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  822): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  822): DefaultState
,D/WifiNetworkAgent(  822): NetworkAgent: NetworkAgent channel lost
E/native  (  822): do suspend true
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  822): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/ConnectivityService(  822): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1074): CM callback handler got msg 524292
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Disconnected - quitting
,D/CSLegacyTypeTracker(  822): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  822): MasterInitialState.processMessage what=3
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  822): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/NetworkMonitor( 3456): type=WIFI subType= reason=null isConnected=false
,E/ConnectivityService(  822): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/art     (  822): Explicit concurrent mark sweep GC freed 86750(3MB) AllocSpace objects, 11(364KB) LOS objects, 31% free, 34MB/50MB, paused 1.354ms total 84.337ms
,W/ContextImpl( 4004): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,V/NativeCrypto( 1506): SSL shutdown failed: ssl=0xaeca3e00: I/O error during system call, Broken pipe
,D/Tethering(  822): MasterInitialState.processMessage what=3
D/PhoneInterfaceManager( 1284): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1284): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,I/ActivityManager(  822): Start proc 4530:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/LocalBluetoothProfileManager( 4004): Adding local MAP profile
,D/BluetoothMap( 4004): Create BluetoothMap proxy object
,D/BluetoothManagerService(  822): Message: 30
,E/GpsLocationProvider(  822): No APN found to select.
,I/wpa_supplicant( 3290): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,D/BluetoothManagerService(  822): Message: 30
,I/wpa_supplicant( 3290): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/LocalBluetoothProfileManager( 4004): LocalBluetoothProfileManager construction complete
,D/PhoneInterfaceManager( 1284): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1284): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  822): getDataEnabled: retVal=false
,E/GpsLocationProvider(  822): No APN found to select.
,D/DockEventReceiver( 4004): finishStartingService: stopping service
,D/BluetoothInputDevice( 4004): Proxy object connected
,D/HidProfile( 4004): Bluetooth service connected
,D/BluetoothPan( 4004): BluetoothPAN Proxy object connected
,D/PanProfile( 4004): Bluetooth service connected
D/BluetoothMap( 4004): Proxy object connected
,D/MapProfile( 4004): Bluetooth service connected
D/BluetoothMap( 4004): getConnectedDevices()
D/BluetoothMap( 4004): Bluetooth is Not enabled
,D/AndroidRuntime( 4524): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,W/bt-btif ( 3272): ag scb idx 1 not allocated
E/bt-btif ( 3272): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3272): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3272): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3272): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3272): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3272): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3272): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3272): RX termination
W/bt_userial( 3272): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3272): Leaving userial_read_thread()
D/bt_userial( 3272): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3272): hw_epilog_process
I/bt_userial_vendor( 3272): device fd = 53 close
,D/AndroidRuntime( 4524): CheckJNI is OFF
,D/AndroidRuntime( 4524): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  822): Killing 3216:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,I/GKI_LINUX( 3272): gki_task task_id=0 [BTU] terminating
,W/PackageSettings(  822): Skipping PackageSetting{1632020a com.example.hello/10272} due to missing metadata
,I/wpa_supplicant( 3290): wlan0: CTRL-EVENT-TERMINATING ,
D/Tethering(  822): InitialState.processMessage what=4
E/WifiMonitor(  822): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/GKI_LINUX( 3272): GKI_exit_task 0 done
I/GKI_LINUX( 3272): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3272): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/StrictMode( 4530): StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4530): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4530): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4530): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4530): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4530): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4530): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4530): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 4530): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 4530): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4530): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 4530): StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4530): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4530): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4530): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4530): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4530): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4530): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4530): StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4530): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4530): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4530): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4530): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4530): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4530): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4530): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4530): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 4530): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4530): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4530): StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4530): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4530): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4530): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 4530): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4530): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4530): StrictMode policy violation; ~duration=184 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4530): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4530): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4530): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4530): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4530): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4530): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4530): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4530): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4530): StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 4530): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4530): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 4530): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 4530): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 4530): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 4530): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 4530): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 4530): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 4530): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 4530): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 4530): # via Binder call with stack:
D/StrictMode( 4530): android.os.StrictMode$LogStackTrace
D/StrictMode( 4530): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 4530): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 4530): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 4530): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 4530): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 4530): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 4530): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 4530): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 4530): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4530): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4530): StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4530): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4530): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4530): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4530): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4530): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4530): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4530): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 4530): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4530): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4530): StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4530): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4530): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4530): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4530): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4530): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4530): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4530): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4530): StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4530): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4530): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4530): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4530): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4530): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4530): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4530): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4530): StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4530): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4530): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4530): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4530): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4530): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4530): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4530): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 4530): 	at com.google.p.j.a(PG:121)
D/StrictMode( 4530): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 4530): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 4530): 	at com.google.p.e.a(PG:170)
D/StrictMode( 4530): 	at com.google.p.e.b(PG:21)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4530): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4530): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4530): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4530): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4530): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4530): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4530): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4530): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 4530): Application name is not set. Call Builder#setApplicationName.
,I/WindowState(  822): WIN DEATH: Window{370e1e91 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  822): Client connection lost with reason: 4
,E/libprocessgroup(  822): failed to kill 1 processes for processgroup 3216
,W/ActivityManager(  822): Force removing ActivityRecord{347897be u0 com.test.thalitest/.MainActivity t22}: app died, no saved state
,V/ActivityManager(  822): Display changed displayId=0
,I/ActivityManager(  822): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/Tethering(  822): sendTetherStateChangedBroadcast 0, 0, 0
,W/ActivityManager(  822): Spurious death for ProcessRecord{12ea0c07 3216:com.test.thalitest/u0a265}, curProc for 3216: null
,D/TaskPersister(  822): removeObsoleteFile: deleting file=22_task.xml
,D/HeadsetService( 3272): Received stop request...Stopping profile...
D/HeadsetStateMachine( 3272): Exit Disconnected: -1
,D/BluetoothHeadset( 1074): Proxy object disconnected
D/A2dpService( 3272): Received stop request...Stopping profile...
D/A2dpStateMachine( 3272): Exit Disconnected: -1
D/BluetoothHeadset( 1284): Proxy object disconnected
D/BluetoothHeadset(  822): Proxy object disconnected
D/BluetoothHeadset(  822): Proxy object disconnected
D/BluetoothHeadset(  822): Proxy object disconnected
D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20386ca0:true
,D/BluetoothAdapterState( 3272): Stopping profile services that were post enabled
,D/HidService( 3272): Received stop request...Stopping profile...
D/HealthService( 3272): Received stop request...Stopping profile...
D/PanService( 3272): Received stop request...Stopping profile...
W/Settings( 1759): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 2642): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 3272): Unbinding service...
,I/Keyboard.Facilitator( 1221): resetDictionaries() : en_US
,D/BluetoothInputDevice( 4004): Proxy object disconnected
I/Keyboard.Facilitator.DecoderInitializer( 1221): run()
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,D/HidProfile( 4004): Bluetooth service disconnected
,I/Decoder ( 1221): createOrResetDecoder
D/BluetoothPan( 4004): BluetoothPAN Proxy object disconnected
D/PanProfile( 4004): Bluetooth service disconnected
,W/BluetoothHeadsetServiceJni( 3272): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3272): Cleaning up Bluetooth Handsfree callback object
,D/BtGatt.DebugUtils( 3272): handleDebugAction() action=null
D/BtGatt.GattService( 3272): Received stop request...Stopping profile...
D/BtGatt.GattService( 3272): stop()
D/BtGatt.AdvertiseManager( 3272): advertise clients cleared
,I/ActivityManager(  822): Killing 2642:com.google.android.talk/u0a61 (adj 15): empty #17
,I/art     ( 1074): Explicit concurrent mark sweep GC freed 73305(2MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 73MB/89MB, paused 968us total 65.537ms
,D/BluetoothA2dp( 1074): Proxy object disconnected
,D/BluetoothInputDevice( 1074): Proxy object disconnected
D/BluetoothPan( 1074): BluetoothPAN Proxy object disconnected
,D/JobSchedulerService(  822): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/art     (  822): Explicit concurrent mark sweep GC freed 19060(1298KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.788ms total 119.038ms
,D/AuthorizationBluetoothService( 1506): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/InputMethodManagerService(  822): Got RemoteException sending setActive(false) notification to pid 3216 uid 10265
,I/ConfigService( 1506): onCreate
D/BluetoothA2dp(  822): Proxy object disconnected
I/GKI_LINUX( 3272): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3272): GKI_exit_task 2 done
I/GKI_LINUX( 3272): GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothMapService( 3272): Received stop request...Stopping profile...
D/BluetoothMapService( 3272): stop()
,D/BluetoothMapEmailAppObserver( 3272): deinitObservers()
D/BluetoothMapEmailAppObserver( 3272): removeReceiver()
,D/BluetoothMap( 4004): Proxy object disconnected
D/MapProfile( 4004): Bluetooth service disconnected
,D/BluetoothMap( 1074): Proxy object disconnected
,W/BluetoothHidServiceJni( 3272): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3272): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3272): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3272): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3272): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3272): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3272): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 3272): MAP Service closeService in
D/BluetoothAdapterState( 3272): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3272): Setting state to 10
I/BluetoothAdapterState( 3272): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 3272): cleanup()
D/BluetoothMapService( 3272): MAP Service closeService in
,D/BluetoothManagerService(  822): Message: 60
I/BluetoothAdapterState( 3272): Entering OffState
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  822): Broadcasting onBluetoothStateChange(false) to 17 receivers.
D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
,D/BluetoothAvrcpController( 1074): onBluetoothStateChange: up=false
I/Keyboard.Facilitator( 1221): onFinishInput()
E/BluetoothAvrcpController( 1074): 
E/BluetoothAvrcpController( 1074): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@1bb9fc18
E/BluetoothAvrcpController( 1074): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1074): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1074): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1074): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1074): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1074): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1074): onBluetoothStateChange: up=false
,D/BluetoothHeadsetClient( 1074): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1074): 
E/BluetoothHeadsetClient( 1074): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@b8fd671
E/BluetoothHeadsetClient( 1074): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1074): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1074): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1074): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1074): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1074): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothPbap( 4004): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1284): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  822): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1074): onBluetoothStateChange: up=false
,D/BluetoothMap( 4004): onBluetoothStateChange: up=false
,D/BluetoothMap( 1074): onBluetoothStateChange: up=false
,D/BluetoothA2dpSink( 1074): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1074): 
E/BluetoothA2dpSink( 1074): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@bfaec56
E/BluetoothA2dpSink( 1074): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1074): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1074): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1074): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1074): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1074): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothInputDevice( 1074): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 4004): onBluetoothStateChange: up=false
D/BluetoothA2dp(  822): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  822): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  822): Broadcasting onBluetoothServiceDown() to 9 receivers.
,V/MusicLeanback( 3456): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/BluetoothManagerService(  822): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3fc778ca mBinding = false
D/BluetoothManagerService(  822): Sending unbind request.
D/BluetoothManagerService(  822): Bluetooth State Change Intent: 13 -> 10
I/GKI_LINUX( 3272): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3272): GKI_exit_task 1 done
I/GKI_LINUX( 3272): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3272): cleanupNative: return from cleanup
,I/art     ( 3272): System.exit called, status: 0
I/AndroidRuntime( 3272): VM exiting with result code 0, cleanup skipped.
,D/Launcher.Workspace( 1325): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1325): 11683562 - stripEmptyScreens()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1221): run()
,I/art     ( 4524): System.exit called, status: 0
I/AndroidRuntime( 4524): VM exiting with result code 0.
D/BluetoothAdapter( 1074): 778559135: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1074): 778559135: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1074): 778559135: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  822): Start proc 4576:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1221): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1221): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1221): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1221): run()
I/StatsUtilsManager( 1221): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1221): shouldRecordStats() = Too Soon
,I/art     ( 1325): Explicit concurrent mark sweep GC freed 10895(612KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 693us total 21.595ms
,I/ActivityManager(  822): Process com.android.bluetooth (pid 3272) has died
,D/SprintDMReceiver( 4576): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4576): simOperator:  IMSI: null
D/SprintDMReceiver( 4576): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1791): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1791): onCreate
,D/SystemUpdateService( 1791): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1791): active receiver: enabled
,I/SystemUpdateService( 1791): showing system update notification
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1791): retry (wakeup: false) in 3599987 ms
,I/iu.Environment( 1791): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1791): num queued entries: 0
E/SQLiteLog( 1791): (3850) statement aborts at 61: [UPDATE media_record SET upload_state=? WHERE upload_account_id != -1 AND upload_state = 200] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 1791): FATAL EXCEPTION: iu-sync-manager
E/AndroidRuntime( 1791): Process: com.google.android.gms, PID: 1791
E/AndroidRuntime( 1791): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1791): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1791): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1791): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1791): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1791): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1576)
E/AndroidRuntime( 1791): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1522)
E/AndroidRuntime( 1791): 	at com.google.android.libraries.social.autobackup.ad.a(SourceFile:403)
E/AndroidRuntime( 1791): 	at com.google.android.libraries.social.autobackup.i.a(SourceFile:307)
E/AndroidRuntime( 1791): 	at com.google.android.libraries.social.autobackup.i.b(SourceFile:43)
E/AndroidRuntime( 1791): 	at com.google.android.libraries.social.autobackup.k.handleMessage(SourceFile:218)
E/AndroidRuntime( 1791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1791): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1791): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/SystemUpdateService( 1791): onDestroy,
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
,D/ChimeraCfgMgr( 1791): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  822): Start proc 4606:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,W/ResourcesManager(  822): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  822): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/OpenGLRenderer(  822): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  822): Validating map...
,W/ResourcesManager( 4606): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/OpenGLRenderer(  822): Initialized EGL, version 1.4
,D/OpenGLRenderer(  822): Enabling debug mode 0
,W/LocationOracleImpl( 4043): Best location was null
,E/SQLiteDatabase( 4043): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/jar_store.db'.
E/SQLiteDatabase( 4043): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4043): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4043): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4043): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4043): 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
E/SQLiteDatabase( 4043): 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
E/SQLiteDatabase( 4043): 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
E/SQLiteDatabase( 4043): 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
E/SQLiteDatabase( 4043): 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
E/SQLiteDatabase( 4043): 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
E/SQLiteDatabase( 4043): 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
E/SQLiteDatabase( 4043): 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
E/SQLiteDatabase( 4043): 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
E/SQLiteDatabase( 4043): 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
E/SQLiteDatabase( 4043): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4043): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4043): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/SQLiteOpenHelper( 4043): Couldn't open jar_store.db for writing (will try read-only):
E/SQLiteOpenHelper( 4043): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4043): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4043): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4043): 	at android.database.sqlite.SQLiteDatabase.openInner(SQL,iteDatabase.java:806)
E/SQLiteOpenHelper( 4043): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4043): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4043): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4043): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4043): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4043): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4043): 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
E/SQLiteOpenHelper( 4043): 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
E/SQLiteOpenHelper( 4043): 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
E/SQLiteOpenHelper( 4043): 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
E/SQLiteOpenHelper( 4043): 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
E/SQLiteOpenHelper( 4043): 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
E/SQLiteOpenHelper( 4043): 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
E/SQLiteOpenHelper( 4043): 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
E/SQLiteOpenHelper( 4043): 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
E/SQLiteOpenHelper( 4043): 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
E/SQLiteOpenHelper( 4043): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4043): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 4043): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
I/VS.Container( 4043): create_recognizer
W/SQLiteOpenHelper( 4043): Opened jar_store.db in read-only mode
,I/HotwordRecognitionRnr( 4043): Starting hotword detection.
,I/MicrophoneInputStream( 4043): mic_starting com.google.android.apps.gsa.speech.audio.u@24ac4be0
,I/AudioFlinger(  357): AudioFlinger's thread 0xb2003000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 4043): mic_started com.google.android.apps.gsa.speech.audio.u@24ac4be0
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,I/HotwordDetector( 4043): Closing mic
I/MicrophoneInputStream( 4043): mic_close com.google.android.apps.gsa.speech.audio.u@24ac4be0
,I/Babel_SMS( 4606): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4606): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4606): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 4606): MmsConfig.loadFromDatabase
,W/FileUtils( 4043): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/FileBytesWriter( 4043): Failed to write new file: loracle.new
W/LocationOracleImpl( 4043): Best location was null
,W/TRUiThreadExecutor( 4043): Task does not implement UiTask: com.google.common.g.a.p@b2e720e
,E/SQLiteDatabase( 4606): Failed to open database '/data/data/com.google.android.talk/databases/apn.db'.
E/SQLiteDatabase( 4606): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4606): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4606): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4606): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4606): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4606): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4606): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4606): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4606): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4606): 	at alg.<init>(SourceFile:161)
E/SQLiteDatabase( 4606): 	at alj.a(SourceFile:1015)
E/SQLiteDatabase( 4606): 	at gen_binder.root.RootModule$Generated.a(SourceFile:662)
E/SQLiteDatabase( 4606): 	at gvf.d(SourceFile:408)
E/SQLiteDatabase( 4606): 	at gvf.b(SourceFile:238)
E/SQLiteDatabase( 4606): 	at gvf.a(SourceFile:204)
E/SQLiteDatabase( 4606): 	at gvf.a(SourceFile:485)
E/SQLiteDatabase( 4606): 	at alg.a(SourceFile:167)
E/SQLiteDatabase( 4606): 	at dnm.c(SourceFile:606)
E/SQLiteDatabase( 4606): 	at dnm.b(SourceFile:570)
E/SQLiteDatabase( 4606): 	at dnn.run(SourceFile:221)
,E/AndroidRuntime( 4606): FATAL EXCEPTION: Thread-436
E/AndroidRuntime( 4606): Process: com.google.android.talk, PID: 4606
E/AndroidRuntime( 4606): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4606): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4606): 	at alg.<init>(SourceFile:161)
E/AndroidRuntime( 4606): 	at alj.a(SourceFile:1015)
E/AndroidRuntime( 4606): 	at gen_binder.root.RootModule$Generated.a(SourceFile:662)
E/AndroidRuntime( 4606): 	at gvf.d(SourceFile:408)
E/AndroidRuntime( 4606): 	at gvf.b(SourceFile:238)
E/AndroidRuntime( 4606): 	at gvf.a(SourceFile:204)
E/AndroidRuntime( 4606): 	at gvf.a(SourceFile:485)
E/AndroidRuntime( 4606): 	at alg.a(SourceFile:167)
E/AndroidRuntime( 4606): 	at dnm.c(SourceFile:606)
E/AndroidRuntime( 4606): 	at dnm.b(SourceFile:570)
E/AndroidRuntime( 4606): 	at dnn.run(SourceFile:221)
,E/DropBoxManagerService(  822): Can't write: system_app_crash
E/DropBoxManagerService(  822): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  822): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  822): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  822): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  822): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  822): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  822): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  822): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  822): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  822): 	... 5 more
,I/ActivityManager(  822): Start proc 4655:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,W/FileUtils( 4043): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/FileBytesWriter( 4043): Failed to write new file: loracle.new
W/LocationOracleImpl( 4043): Best location was null
I/ActivityManager(  822): Killing 3660:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 4043): Hotword detection finished
I/HotwordRecognitionRnr( 4043): Stopping hotword detection.

```
