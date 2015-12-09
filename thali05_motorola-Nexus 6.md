#### Test 50650278b28a87a_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2699): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2699): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2699): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3179): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3179): CheckJNI is OFF
D/AndroidRuntime( 3179): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{38ce4d04 token=Token{2672b517 ActivityRecord{33943596 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3179): Shutting down VM
V/WindowManager(  823): Adding window Window{380010e9 u0 Starting com.test.thalitest} at 3 of 8 (after Window{302a399a u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/MicrophoneInputStream( 1496): mic_close com.google.android.apps.gsa.speech.audio.u@1a9e954b
I/HotwordDetector( 1496): Closing mic
I/ActivityManager(  823): Start proc 3194:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1496): Hotword detection finished
I/HotwordRecognitionRnr( 1496): Stopping hotword detection.
I/ActivityManager(  823): Killing 2658:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1701897491
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  823): Killing 2790:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  873): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  873): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  873): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  873): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3194): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3194): Time to load native libraries: 1 ms (timestamps 5000-5001)
I/LibraryLoader( 3194): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3194): Binding Chromium to main looper Looper (main, tid 1) {3aef01e1}
I/LibraryLoader( 3194): Expected native library version number "",actual native library version number ""
,I/chromium( 3194): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3194): Initializing chromium process, singleProcess=true
,W/art     ( 3194): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3194): ApplicationContext is null in ApplicationStatus
,W/chromium( 3194): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3194): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3194): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3194): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3194): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  823): Message: 20
,D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22120ad2:true
,D/BluetoothAdapter( 3194): 37664756: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3194): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3194): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3194): CordovaWebView is running on device made by: motorola
,W/art     ( 3194): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3194): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3194): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3194): Validating map...,
,V/WindowManager(  823): Adding window Window{2a6437c9 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{380010e9 u0 Starting com.test.thalitest})
,W/chromium( 3194): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  823): Explicit concurrent mark sweep GC freed 16431(771KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 2.215ms total 56.593ms
,I/OpenGLRenderer( 3194): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3194): Enabling debug mode 0
,I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +961ms (total +2m2s845ms)
,I/Keyboard.Facilitator( 1214): onFinishInput()
,W/BindingManager( 3194): Cannot call determinedVisibility() - never saw a connection for the pid: 3194
,D/JsMessageQueue( 3194): Set native->JS mode to OnlineEventsBridgeMode
,I/kickstart(  873): STATUS: Received file 'm9kefs2'
,I/kickstart(  873): STATUS: 950272 bytes transferred in 1.004548 seconds
I/kickstart(  873): STATUS: Successfully downloaded files from target 
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_unlock
,D/jxcore_app_log( 3194): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576184960
D/JX-Cordova( 3194): jxcore cordova android initializing
I/kickstart(  873): STATUS: Sahara protocol completed
,W/jxcore-log( 3194): Initializing JXcore engine
W/jxcore-log( 3194): JXcore engine is ready
,W/jxcore-log( 3194): Starting JXcore engine
,W/.test.thalitest( 3194): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12476]" dev="sockfs" ino=12476 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3194): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3194): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10166]" dev="sockfs" ino=10166 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3194): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[22674]" dev="sockfs" ino=22674 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
,W/jxcore-log( 3194): Platform android
,W/jxcore-log( 3194): 
W/jxcore-log( 3194): Process ARCH arm
W/jxcore-log( 3194): 
,I/jxcore-log( 3194): JXcore Cordova bridge is ready!
I/jxcore-log( 3194): 
,W/jxcore-log( 3194): JXcore engine is started
I/Choreographer( 3194): Skipped 132 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3194): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3194): Toggling radios to true
I/jxcore-log( 3194): 
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  823): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  823): Message: 1
D/BluetoothManagerService(  823): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  823): New client listening to asynchronous messages
,D/WifiService(  823): setWifiEnabled: true pid=3194, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3194): Radios toggled
I/jxcore-log( 3194): 
,D/SoftapController(  355): Softap fwReload - Ok
,D/CommandListener(  355): Setting iface cfg
D/CommandListener(  355): Trying to bring down wlan0
D/CommandListener(  355): Clearing all IP addresses on wlan0
E/WifiMonitor(  823): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  823): Start proc 3252:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService,
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3194): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3194): 
,I/jxcore-log( 3194): Perf Test app loaded loaded
I/jxcore-log( 3194): 
I/Choreographer( 3194): Skipped 69 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 3194): check test folder
I/jxcore-log( 3194): 
,I/jxcore-log( 3194): found test : ./testFindPeers.js
I/jxcore-log( 3194): 
,W/ResourcesManager( 3252): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3258): Successfully initialized wpa_supplicant
,I/jxcore-log( 3194): found test : ./testSendData.js
I/jxcore-log( 3194): 
,D/WifiMonitor(  823): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3258): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  823): Start proc 3270:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/chromium( 3194): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/AdapterServiceConfig( 3252): Adding HeadsetService
,D/AdapterServiceConfig( 3252): Adding A2dpService
D/AdapterServiceConfig( 3252): Adding HidService
D/AdapterServiceConfig( 3252): Adding HealthService
D/AdapterServiceConfig( 3252): Adding PanService
,D/AdapterServiceConfig( 3252): Adding GattService
,D/AdapterServiceConfig( 3252): Adding BluetoothMapService
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fd75a32:true
,D/BluetoothAdapterState( 3252): make
,I/bluedroid( 3252): init
I/BluetoothAdapterState( 3252): Entering OffState
,I/bte_conf( 3252): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3252): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3252): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3252): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,I/bluedroid( 3252): get_profile_interface socket
I/GKI_LINUX( 3252): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 3252): get_profile_interface map_client
,D/BluetoothAdapterProperties( 3252): Address is:F8:CF:C5:D9:E5:61
D/BluetoothAdapterProperties( 3252): Name is: Nexus 6
D/BluetoothManagerService(  823): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  823): Stored Bluetooth name: Nexus 6
,D/BluetoothManagerService(  823): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  823): Message: 40
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3252): config_hci_snoop_log
D/BluetoothManagerService(  823): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  823): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3252): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3252): Setting state to 11
,I/BluetoothAdapterState( 3252): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  823): Message: 60
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  823): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3252): make
,I/BluetoothBondStateMachine( 3252): StableState(): Entering Off State
,I/BluetoothAdapterState( 3252): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3252): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c8b06
,D/HeadsetService( 3252): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3252): classInitNative: succeeds
D/HeadsetStateMachine( 3252): make
,D/HeadsetStateMachine( 3252): max_hf_connections = 1
I/bluedroid( 3252): get_profile_interface handsfree
,D/HeadsetStateMachine( 3252): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3252): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c8b06
,D/BluetoothA2dp(  823): Proxy object connected
,D/BluetoothA2dp( 1063): Proxy object connected,
,D/A2dpService( 3252): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3252): classInitNative: succeeds
I/bluedroid( 3252): get_profile_interface avrcp
E/RemoteController( 3252): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3252): classInitNative: succeeds
D/A2dpStateMachine( 3252): make
I/bluedroid( 3252): get_profile_interface a2dp
I/GKI_LINUX( 3252): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3252): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3252): classInitNative: succeeds
D/BluetoothAdapterService( 3252): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c8b06
D/BluetoothInputDevice( 1063): Proxy object connected
D/HidService( 3252): Received start request. Starting profile...
I/bluedroid( 3252): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3252): classInitNative: succeeds
D/BluetoothAdapterService( 3252): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c8b06
D/HealthService( 3252): Received start request. Starting profile...
,I/bluedroid( 3252): get_profile_interface health
I/art     ( 1536): Explicit concurrent mark sweep GC freed 24111(1274KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 770us total 24.709ms
I/BluetoothPanServiceJni( 3252): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3252): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c8b06
D/PanService( 3252): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3252): initializeNative(L110): pan
I/bluedroid( 3252): get_profile_interface pan
D/BluetoothPan( 1063): BluetoothPAN Proxy object connected
,I/BtGatt.JNI( 3252): classInitNative(L873): classInitNative: Success!
,D/BluetoothAdapterService( 3252): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c8b06
D/BtGatt.DebugUtils( 3252): handleDebugAction() action=null
,D/BtGatt.GattService( 3252): Received start request. Starting profile...
D/BtGatt.GattService( 3252): start()
I/bluedroid( 3252): get_profile_interface gatt
D/BluetoothAdapterService( 3252): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c8b06
D/BtGatt.AdvertiseManager( 3252): advertise manager created
,D/BluetoothAdapterService( 3252): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c8b06
,D/BluetoothMap( 1063): Proxy object connected
,D/BluetoothMapService( 3252): Received start request. Starting profile...
D/BluetoothMapService( 3252): start()
,D/BluetoothMapEmailSettingsLoader( 3252): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3252): createReceiver()
,D/BluetoothMapEmailAppObserver( 3252): initObservers()
D/BluetoothMapEmailAppObserver( 3252): getEnabledAccountItems()
,D/HeadsetStateMachine( 3252): Proxy object connected
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3252): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3252): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3252): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3252): enable
I/GKI_LINUX( 3252): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3252): btu_task pending for preload complete event
I/bt_hci_bdroid( 3252): init
,I/bt_vendor( 3252): init
I/bt_vnd_conf( 3252): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3252): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3252): userial_init
,I/ActivityManager(  823): Start proc 3314:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  823): Killing 2823:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 248us total 10.407ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 193us total 9.141ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 192us total 8.393ms
,I/bt_userial_vendor( 3252): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3252): device fd = 53 open
D/bt_userial( 3252): Entering userial_read_thread()
,I/bt_hwcfg( 3252): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3252): Chipset BCM4354A2
D/bt_hwcfg( 3252): Target name = [BCM4354A2]
I/bt_hwcfg( 3252): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/ActivityManager(  823): Start proc 3337:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  823): Killing 2757:com.google.android.gm/u0a78 (adj 15): empty #17
,D/Tethering(  823): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  823): Killing 2355:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/wpa_supplicant( 3258): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3258): Could not read interface p2p-dev-wlan0 flags: No such device
,I/bt_hwcfg( 3252): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3252): Settlement delay -- 100 ms
I/bt_hwcfg( 3252): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3252): bt vendor lib: set UART baud 3000000,
I/bt_hwcfg( 3252): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3252): vendor lib fwcfg completed,
I/bt-btu  ( 3252): btu_task received preload complete event
,I/        ( 3252): BTE_InitTraceLevels -- TRC_HCI,
,I/        ( 3252): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3252): BTE_InitTraceLevels -- TRC_RFCOMM
,I/        ( 3252): BTE_InitTraceLevels -- TRC_AVDT
,I/        ( 3252): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3252): BTE_InitTraceLevels -- TRC_A2D
,I/        ( 3252): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3252): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3252): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3252): BTE_InitTraceLevels -- TRC_PAN
,I/        ( 3252): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3252): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3252): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3252): BTE_InitTraceLevels -- TRC_BTAPP,
I/        ( 3252): BTE_InitTraceLevels -- TRC_BTIF
,D/WifiConfigStore(  823): Loading config and enabling all networks ,
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@396108ea}
,E/WifiConfigStore(  823): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  823): Start proc 3356:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/WifiNative-HAL(  823): Setting external_sim to 1
,W/Settings( 2627): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  823): Setting OUI to 92-68-C3
I/WifiNative-HAL(  823): startHal
,D/wifi    (  823): setting scan oui 0xb4b203a0
D/WifiHAL (  823): Sending mac address OUI
,E/WifiStateMachine(  823): cancelDelayedScan -> 1
D/WifiScanningService(  823): SCAN_AVAILABLE : 3
D/RttService(  823): SCAN_AVAILABLE : 3
W/CommandListener(  355): Failed to retrieve HW addr for p2p0 (No such device)
,D/RttService(  823): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  823): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  823): startHal
D/CommandListener(  355): Setting iface cfg
,D/wifi    (  823): getting scan capabilities on interface[0] = 0xb4b203a0
D/WifiHAL (  823): Creating message to get scan capablities; iface = 5
E/WifiP2pService(  823): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiHAL (  823): In GetCapabilities::handleResponse
D/WifiMonitor(  823): startMonitoring(p2p0) with mConnected = true
D/WifiHAL (  823): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  823): StartedState
,I/wpa_supplicant( 3258): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  823): p2pGetDeviceAddress
,D/WifiNative-HAL(  823): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,E/native  (  823): do suspend false
,E/bt-btm  ( 3252): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e4f085 
E/bt-btm  ( 3252): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e4f085 
,D/BluetoothAdapterProperties( 3252): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3252): Calling BTA_HhEnable
E/bt-btif ( 3252): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 3252): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothAdapterProperties( 3252): Name is: Nexus 6
D/BluetoothManagerService(  823): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  823): Stored Bluetooth name: Nexus 6
,D/BluetoothAdapterProperties( 3252): Scan Mode:20
,D/BluetoothAdapterProperties( 3252): Discoverable Timeout:120
,W/bt-btm  ( 3252): Stopping oneshot timer
,D/bte_conf( 3252): Device ID record 1 : primary
D/bte_conf( 3252):   vendorId            = 000f
,D/bte_conf( 3252):   vendorIdSource      = 0001
D/bte_conf( 3252):   product             = 1200
,D/bte_conf( 3252):   version             = 1436
D/bte_conf( 3252):   clientExecutableURL = 
D/bte_conf( 3252):   serviceDescription  = 
D/bte_conf( 3252):   documentationURL    = 
D/bte_conf( 3252): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3252): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3252): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3252): ScanMode =  20
D/BluetoothAdapterProperties( 3252): State =  11
D/BluetoothAdapterProperties( 3252): Scan Mode:21
D/BluetoothAdapterProperties( 3252): Setting state to 12
D/BluetoothAdapterProperties( 3252): Discoverable Timeout:120
I/BluetoothAdapterState( 3252): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterState( 3252): Entering On State
D/BluetoothManagerService(  823): Message: 60
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  823): Broadcasting onBluetoothStateChange(true) to 13 receivers.
,E/bt_h4   ( 3252): vendor lib postload completed
,D/BluetoothPan( 1063): onBluetoothStateChange(on) call bindService
,D/BluetoothAvrcpController( 1063): onBluetoothStateChange: up=true
,E/BluetoothAvrcpController( 1063): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
,D/BluetoothHeadset(  823): onBluetoothStateChange: up=true
D/BluetoothManagerService(  823): Creating new ProfileServiceConnections object for profile: 1
,D/BluetoothHeadsetClient( 1063): onBluetoothStateChange: up=true
,E/BluetoothHeadsetClient( 1063): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothHeadset(  823): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1277): onBluetoothStateChange: up=true
D/BluetoothA2dp(  823): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1063): onBluetoothStateChange: up=true
,D/BluetoothA2dpSink( 1063): onBluetoothStateChange: up=true
,E/BluetoothA2dpSink( 1063): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothInputDevice( 1063): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  823): onBluetoothStateChange: up=true
D/BluetoothMap( 1063): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1063): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  823): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothMapService( 3252): onReceive
D/BluetoothMapService( 3252): STATE_ON
D/BluetoothManagerService(  823): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  823): Message: 40
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapMasInstance( 3252): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3252): MAS initSocket()
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3252): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3252): Accepting socket connection...
,D/StrictMode( 3356): StrictMode policy violation; ~duration=245 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3356): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3356): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3356): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3356): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3356): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3356): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3356): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3356): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3356): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3356): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3356): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3356): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3356): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3356): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3356): StrictMode policy violation; ~duration=244 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3356): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3356): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3356): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3356): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3356): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3356): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3356): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3356): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3356): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3356): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3356): StrictMode policy violation; ~duration=242 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3356): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3356): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3356): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3356): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3356): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3356): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3356): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3356): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3356): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3356): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3356): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3356): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3356): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3356): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3356): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3356): StrictMode policy violation; ~duration=238 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3356): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3356): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3356): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3356): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3356): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3356): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3356): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3356): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3356): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3356): StrictMode policy violation; ~duration=228 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3356): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3356): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3356): 	at android.app.SharedPreferencesImpl.getInt(SharedPreferencesImpl.java:238)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.shared.b.a.a(PG:1035)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.shared.b.a.a(PG:944)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3356): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3356): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3356): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3356): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3356): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3356): StrictMode policy violation; ~duration=223 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3356): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3356): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3356): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3356): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3356): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3356): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3356): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3356): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3356): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3356): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3356): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3356): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3356): StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3356): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3356): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3356): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3356): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3356): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3356): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3356): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3356): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3356): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3356): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3356): # via Binder call with stack:
D/StrictMode( 3356): android.os.StrictMode$LogStackTrace
D/StrictMode( 3356): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3356): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3356): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3356): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3356): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3356): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3356): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3356): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3356): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3356): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3356): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3356): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3356): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3356): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3356): StrictMode policy violation; ~duration=44 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3356): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3356): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3356): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3356): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3356): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3356): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3356): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3356): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3356): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3356): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3356): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3356): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3356): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3356): StrictMode policy violation; ~duration=43 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3356): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3356): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3356): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3356): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3356): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3356): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3356): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3356): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3356): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3356): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3356): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3356): StrictMode policy violation; ~duration=43 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3356): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3356): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3356): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3356): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3356): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3356): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3356): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3356): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3356): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3356): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3356): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3356): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3356): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/BluetoothManagerService(  823): Message: 400
D/BluetoothHeadset(  823): Proxy object connected
D/BluetoothManagerService(  823): Message: 400
D/BluetoothHeadset(  823): Proxy object connected
D/BluetoothManagerService(  823): Message: 400
D/BluetoothHeadset( 1277): Proxy object connected
D/BluetoothManagerService(  823): Message: 400
D/BluetoothHeadset( 1063): Proxy object connected
D/BluetoothManagerService(  823): Message: 400
D/BluetoothHeadset(  823): Proxy object connected
W/com.google.a.a.a.b.a( 3356): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ecb2cc1:true
,I/ActivityManager(  823): Killing 2856:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1536): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  823): Message: 20
,D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e7b2f9:true
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3252): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1536): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LocalBluetoothProfileManager( 3337): Adding local A2DP profile
,D/BluetoothManagerService(  823): Message: 30
,D/LocalBluetoothProfileManager( 3337): Adding local HEADSET profile
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3252): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3252): Accept thread started.
,D/BluetoothManagerService(  823): Message: 30
,D/BluetoothManagerService(  823): Message: 30
,D/BluetoothManagerService(  823): Message: 30
,D/LocalBluetoothProfileManager( 3337): Adding local MAP profile
,D/BluetoothMap( 3337): Create BluetoothMap proxy object
,D/BluetoothManagerService(  823): Message: 30
,D/BluetoothManagerService(  823): Message: 30
,D/LocalBluetoothProfileManager( 3337): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3337): finishStartingService: stopping service
,D/BluetoothA2dp( 3337): Proxy object connected
D/A2dpProfile( 3337): Bluetooth service connected
,D/BluetoothInputDevice( 3337): Proxy object connected
D/HidProfile( 3337): Bluetooth service connected
,D/BluetoothPan( 3337): BluetoothPAN Proxy object connected,
D/PanProfile( 3337): Bluetooth service connected
D/BluetoothMap( 3337): Proxy object connected
D/MapProfile( 3337): Bluetooth service connected
D/BluetoothMap( 3337): getConnectedDevices()
,D/BluetoothPbap( 3337): Proxy object connected
,D/PbapServerProfile( 3337): Bluetooth service connected
,D/BluetoothManagerService(  823): Message: 400
,D/BluetoothHeadset( 3337): Proxy object connected
,D/HeadsetProfile( 3337): Bluetooth service connected
,I/wpa_supplicant( 3258): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000,
E/WifiConfigStore(  823):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  823):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  823): will read network variables netId=0
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
E/WifiConfigStore(  823): will read network variables netId=0
,I/wpa_supplicant( 3258): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3258): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3258): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3258): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 1
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
,E/WifiStateMachine(  823):  my bss beacon rx: 0
E/WifiStateMachine(  823):  RSSI mgmt: -52
E/WifiStateMachine(  823):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 0 tx_time=59 rx_time=75 scan_time=0
,D/ConnectivityService(  823): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  823): do suspend false
,E/WifiStateMachine(  823): scanCount==0 - aborting
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (382 us)
,I/dhcpcd  ( 3400): version 5.5.6 starting
,I/dhcpcd  ( 3400): wlan0: rebinding lease of 192.168.1.122
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  823): Display changed displayId=0,
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  823): Excessive delay in setPowerMode(): 278ms
,I/DreamManagerService(  823): Entering dreamland.
I/PowerManagerService(  823): Dozing...,
I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  823): cancelDelayedScan -> 4
,E/native  (  823): do suspend false
,I/Keyboard.Facilitator( 1214): onFinishInput()
,E/WifiStateMachine(  823): cancelDelayedScan -> 5
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,I/dhcpcd  ( 3400): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/jxcore-log( 3194): BLE supported!!
I/jxcore-log( 3194): 
,I/dhcpcd  ( 3400): wlan0: leased 192.168.1.122 for 86400 seconds
,E/native  (  823): do suspend true,
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  823): Adding iface wlan0 to network 100
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 100
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  823): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  823): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524290
,D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1277): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1277): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,D/Tethering(  823): MasterInitialState.processMessage what=3
,V/BackupManagerService(  823): Scheduling immediate backup pass
,I/ActivityManager(  823): Start proc 3443:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
V/BackupManagerService(  823): Running a backup pass
V/BackupManagerService(  823): clearing pending backups
,V/PerformBackupTask(  823): Beginning backup of 14 targets
,D/PerformBackupTask(  823): invokeAgentForBackup on @pm@
,E/GpsLocationProvider(  823): No APN found to select.
,V/BackupServiceBinder(  823): doBackup() invoked
,I/PMBA    (  823): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  823): Getting widget state for user: 0
,I/MusicStore( 3443): Database version: 120,
,D/AlarmManagerService(  823): Setting time of day to sec=1449671306
W/AlarmManagerService(  823): Unable to set rtc to 1449671306: Invalid argument
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 14:28:26 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449671306195], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449671306361]}
,I/art     (  823): Explicit concurrent mark sweep GC freed 51217(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.786ms total 118.979ms
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Validated
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1063): CM callback handler got msg 524290
,I/ConfigFetchService( 1780): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1780): running network task: configservice_periodic
,E/WakeLock( 1780): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1780): launchTask
,I/GoogleURLConnFactory( 1536): Using platform SSLCertificateSocketFactory
,I/ConfigService( 1536): onCreate
,D/GpsLocationProvider(  823): NTP server returned: 1449671306180 (Wed Dec 09 15:28:26 GMT+01:00 2015) reference: 165447 certainty: 60 system time offset: -159
,W/GmsBackupTransport( 1748): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1748): starting performBackup for @pm@
,V/GmsBackupTransport( 1748): performBackup done for @pm@
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1780): [CredentialSyncAdapter] Unknown sync event.
,W/ResourcesManager( 3443): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3443): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1536): Explicit concurrent mark sweep GC freed 13314(736KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 1.245ms total 26.285ms
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 3443): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/DriveInitializer( 1780): Background init thread started
,I/ConfigFetchService( 1780): service connected
,D/ConfigFetchService( 1780): ConfigApi connection successful.
,W/GLSActivity( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1536): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1536): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1536): 	at android.os.Binder.execTransact(Binder.java:446)
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
,W/DriveInitializer( 1780): Awaiting to be initialized
,D/BackupManagerService(  823): Now staging backup of com.google.android.dialer
,W/DriveInitializer( 1780): Background init thread ended
,D/BackupManagerService(  823): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  823): Now staging backup of com.android.sharedstoragebackup
,I/ProviderInstaller( 3443): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3443): GMSCore installation verified
,D/BackupManagerService(  823): Now staging backup of com.google.android.gm
,D/BackupManagerService(  823): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  823): Now staging backup of com.android.nfc
,D/BackupManagerService(  823): Now staging backup of com.google.android.apps.genie.geniewidget
I/ConfigStore( 3443): Config Database version: 1
,D/BackupManagerService(  823): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  823): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  823): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  823): Now staging backup of com.android.vending
,D/BackupManagerService(  823): Now staging backup of android
,D/BackupManagerService(  823): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1748): Next backup will happen in 43199881 millis.
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BackupManagerService(  823): Backup pass finished.
,E/HttpOperation( 2963): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2963): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2963): 	at jdm.a(PG:82)
E/HttpOperation( 2963): 	at jcs.o(PG:406)
E/HttpOperation( 2963): 	at jcn.a(PG:1379)
E/HttpOperation( 2963): 	at jcs.i(PG:143)
E/HttpOperation( 2963): 	at blb.a(PG:3937)
E/HttpOperation( 2963): 	at czp.a(PG:18188)
E/HttpOperation( 2963): 	at czp.a(PG:9081)
E/HttpOperation( 2963): 	at czq.run(PG:1686)
E/HttpOperation( 2963): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2963): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2963): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2963): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2963): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2963): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2963): 	at jdj.a(PG:4091)
E/HttpOperation( 2963): 	at jdj.a(PG:1125)
E/HttpOperation( 2963): 	at jdm.a(PG:77)
E/HttpOperation( 2963): 	... 12 more
E/HttpOperation( 2963): Caused by: faj: BadAuthentication
E/HttpOperation( 2963): 	at fal.a(PG:38)
E/HttpOperation( 2963): 	at jdj.a(PG:4089)
E/HttpOperation( 2963): 	... 14 more
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MediaRouter( 3443): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3443): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/HttpOperation( 2963): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2963): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2963): 	at jdm.a(PG:82)
E/HttpOperation( 2963): 	at jcs.o(PG:406)
E/HttpOperation( 2963): 	at jcn.a(PG:1379)
E/HttpOperation( 2963): 	at jcs.i(PG:143)
E/HttpOperation( 2963): 	at hec.a(PG:42)
E/HttpOperation( 2963): 	at hee.a(PG:102)
E/HttpOperation( 2963): 	at czr.a(PG:65)
E/HttpOperation( 2963): 	at kka.a(PG:108)
E/HttpOperation( 2963): 	at czp.a(PG:19176)
E/HttpOperation( 2963): 	at czp.a(PG:9081)
E/HttpOperation( 2963): 	at czq.run(PG:1686)
E/HttpOperation( 2963): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2963): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2963): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2963): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2963): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2963): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2963): 	at jdj.a(PG:4091)
E/HttpOperation( 2963): 	at jdj.a(PG:1125)
E/HttpOperation( 2963): 	at jdm.a(PG:77)
E/HttpOperation( 2963): 	... 15 more
E/HttpOperation( 2963): Caused by: faj: BadAuthentication
E/HttpOperation( 2963): 	at fal.a(PG:38)
E/HttpOperation( 2963): 	at jdj.a(PG:4089)
E/HttpOperation( 2963): 	... 17 more
I/NetworkMonitor( 3443): type=WIFI subType= reason=null isConnected=true
,E/ExperimentLoader( 2963): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2963): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2963): 	at jdm.a(PG:82)
E/ExperimentLoader( 2963): 	at jcs.o(PG:406)
E/ExperimentLoader( 2963): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2963): 	at jcs.i(PG:143)
E/ExperimentLoader( 2963): 	at hec.a(PG:42)
E/ExperimentLoader( 2963): 	at hee.a(PG:102)
E/ExperimentLoader( 2963): 	at czr.a(PG:65)
E/ExperimentLoader( 2963): 	at kka.a(PG:108)
E/ExperimentLoader( 2963): 	at czp.a(PG:19176)
E/ExperimentLoader( 2963): 	at czp.a(PG:9081)
E/ExperimentLoader( 2963): 	at czq.run(PG:1686)
E/ExperimentLoader( 2963): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2963): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2963): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2963): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2963): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2963): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2963): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2963): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2963): 	at jdm.a(PG:77)
E/ExperimentLoader( 2963): 	... 15 more
E/ExperimentLoader( 2963): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2963): 	at fal.a(PG:38)
E/ExperimentLoader( 2963): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2963): 	... 17 more
,I/NetworkMonitor( 3443): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  823): Start proc 3509:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/GHttpClientFactory( 3443): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3443): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 3509): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3509): simOperator:  IMSI: null
D/SprintDMReceiver( 3509): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1780): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1780): onCreate
,D/SystemUpdateService( 1780): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1780): active receiver: enabled
,I/CheckinService( 1780): Checking schedule, now: 1449671306808 next: 1449617697905
I/CheckinService( 1780): active receiver: enabled
,I/CheckinService( 1780): Preparing to send checkin request
I/EventLogService( 1780): Accumulating logs since 1449670630333
,I/SystemUpdateService( 1780): showing system update notification
,I/EventLogService( 1780): Opted in for usage reporting
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 36363, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3314): Connecting to GoogleApiClient
,I/iu.SyncManager( 1780): SYNC; picasa accounts
,I/ValidateNoPeople(  823): skipping global notification
,D/NetworkLogImpl( 1780): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1780): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,V/SystemUpdateService( 1780): retry (wakeup: false) in 3599969 ms
,I/ActivityManager(  823): Start proc 3538:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/SystemUpdateService( 1780): onDestroy
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1780): num queued entries: 0
I/iu.UploadsManager( 1780): num updated entries: 0
,I/iu.SyncManager( 1780): NEXT; no task
,W/EventLogAggregator( 1780): Unknown tag: snet_gcore
W/EventLogAggregator( 1780): Unknown tag: snet_launch_service
,I/ActivityManager(  823): Start proc 3562:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GcmGroups( 1780): Failed to subscribe to group.
I/GcmGroups( 1780): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 1780): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 1780): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 1780): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 1780): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 1780): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 1780): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 1780): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 1780): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 1780): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/art     (  823): Explicit concurrent mark sweep GC freed 29682(1398KB) AllocSpace objects, 5(121KB) LOS objects, 32% free, 33MB/49MB, paused 1.224ms total 52.676ms
,I/GcmGroups( 1780): Groups upload failed, retrying in 24000:00:00
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,I/CheckinRequestBuilder( 1780): Checkin reason type: 12 attempt count: 1
,D/WifiService(  823): New client listening to asynchronous messages
,E/ActivityThread( 1780): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  823): Start proc 3582:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,I/Babel   ( 2627): connection state changed from DISCONNECTED to CONNECTED
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1780): Handling authorization failure
E/ClientConnectionOperation( 1780): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1780): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1780): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1780): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1780): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1780): 	... 7 more
,V/KeepSync( 3314): GoogleApiClient failed to connect with error code: 4
W/Kids    ( 1780): [AccountUtils] Account not ready
W/Kids    ( 1780): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1780): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1780): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1780): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1780): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1780): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1780): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1780): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1780): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1780): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1780): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1780): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 3314): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3314): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3314): (284) automatic index on blob_node(is_deleted)
,W/ResourcesManager( 3582): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3582): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1536): Explicit concurrent mark sweep GC freed 30483(1724KB) AllocSpace objects, 2(55KB) LOS objects, 37% free, 26MB/42MB, paused 1.625ms total 74.800ms
,I/GAv4    ( 3562): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3562):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3562):   adb logcat -s GAv4
,V/JNIHelp ( 3582): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/GAv4    ( 3562): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3562): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3562): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ProviderInstaller( 3582): Installed default security provider GmsCore_OpenSSL
,I/art     ( 1780): Explicit concurrent mark sweep GC freed 12796(1046KB) AllocSpace objects, 14(224KB) LOS objects, 35% free, 29MB/45MB, paused 1.119ms total 86.481ms
,W/GAV2    ( 3538): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/YouTube MDX( 3582): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3621): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads282648255.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads282648255.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/BooksApp( 3538): Created application version: 3.6.8 (30608)
,I/dex2oat ( 3621): dex2oat took 57.545ms (threads: 4) arena alloc=114KB java alloc=12KB native alloc=834KB free=7MB
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 3562): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3562): Time to load native libraries: 1 ms (timestamps 6751-6752)
I/LibraryLoader( 3562): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3562): Binding Chromium to main looper Looper (main, tid 1) {3098cbfa}
,I/LibraryLoader( 3562): Expected native library version number "",actual native library version number ""
I/chromium( 3562): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BooksSync( 3538): Starting books sync for 61035162, extras: ade
,I/BrowserStartupController( 3562): Initializing chromium process, singleProcess=true
W/art     ( 3562): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3562): ApplicationContext is null in ApplicationStatus
,W/chromium( 3562): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,W/InstanceID/Rpc( 3582): Found 10011
,E/libEGL  ( 3562): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3562): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3562): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/KeepSync( 3314): IOException
E/KeepSync( 3314): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3314): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3314): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3314): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3314): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3314): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3314): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3314): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3314): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3314): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3314): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3314): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3314): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3314): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3314): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3314): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3314): 	... 10 more
W/KeepSync( 3314): Sync result 2
,I/ActivityManager(  823): Killing 2906:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 36365, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/AudioManagerAndroid( 3562): Requires BLUETOOTH permission
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 3562): Starting up...
,I/ActivityManager(  823): Killing 1394:android.process.acore/u0a5 (adj 15): empty #17
,D/GCM     ( 1536): Connected
,I/BooksConfig( 3538): GmsCore Version = 7.8.99 (2134222-430)
,D/GCM     ( 1536): Message class com.google.f.a.a.p
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1780): awaiting user notification for token
,I/art     (  823): Explicit concurrent mark sweep GC freed 18243(827KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.277ms total 46.987ms
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  823): Start proc 3731:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  823): Start proc 3748:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,W/ResourcesManager( 3748): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3748): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GoogleURLConnFactory( 1748): Using platform SSLCertificateSocketFactory
,W/GoogleHttpClient( 1748): Ignoring unsupported parameter: http.conn-manager.max-per-route
I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3538): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3538): Soft error
E/BooksSync( 3538): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3538): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3538): Sync error
E/BooksSync( 3538): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3538): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3538): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36366, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Killing 3073:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/MultiDex( 3748): VM with version 2.1.0 has multidex support
I/MultiDex( 3748): install
I/MultiDex( 3748): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  823): Killing 3095:com.android.musicfx/u0a18 (adj 15): empty #17
,V/JNIHelp ( 3748): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3748): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  823): Start proc 3772:com.google.android.apps.docs.editors.sheets/u0a48 for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@396108ea}
,V/GoogleAuthProtoRequest( 3270): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/WVCdm   (  359): Instantiating CDM.
,I/WVCdm   (  359): CdmEngine::OpenSession
,I/WVCdm   (  359): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  359): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  359): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  359): Service_Initialize: starts!
D/QSEECOMAPI: (  359): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  359): App is not loaded in QSEE
,I/PeopleSync( 1780): onPerformSync() [5005f081]
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 3748): Using platform SSLCertificateSocketFactory
,W/ExperimentUpdateService( 3270): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3270): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3270): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3270): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3270): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3270): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3270): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3270): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3270): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3270): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3270): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3270): 	at com.a.a.k.run(SourceFile:110)
,I/art     ( 1536): Explicit concurrent mark sweep GC freed 18323(1010KB) AllocSpace objects, 7(583KB) LOS objects, 37% free, 27MB/43MB, paused 774us total 25.013ms
,I/PeopleDatabaseHelper( 1780): cleanUpNonGplusAccounts done.
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QSEECOMAPI: (  359): Loaded image: APP id = 3
,D/DrmWidevineDash(  359): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3c8e000
E/DrmWidevineDash(  359): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3c8e000
,D/DrmLibTime(  314): got the req here! ret=0
D/DrmLibTime(  314): command id, time_cmd_id = 770
D/DrmLibTime(  314): time_getutcsec starts!
D/DrmLibTime(  314): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  314): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  314): QSEE Time Listener: seconds: 1449671308
D/DrmLibTime(  314): QSEE Time Listener: nano seconds: 581247811
D/DrmLibTime(  314): time_getutcsec returns 0, sec = 1449671308; nsec = 581247811
D/DrmLibTime(  314): time_getutcsec finished! 
D/DrmLibTime(  314): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  314): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  359): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  359): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  359): hlos api version =  9
,D/DrmWidevineDash(  359): tz api version =  9
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  359): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  359): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  359): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  359): OEMCrypto_OpenSession: starts! SID=0xb3f01940
,D/DrmWidevineDash(  359): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  359): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_GetRandom: starts! randomData=0xb4c4e230, dataLength=8
,D/DrmWidevineDash(  359): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  359): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4cac800, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  359): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  359): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  359): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  359): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  359): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  359): OEMCrypto_GetDeviceID: starts! deviceID=0xb583ec40, idLength=0xbee032f0
,I/PeopleSync( 1780): Setting subscription: result=true [5005f081]
I/PeopleSync( 1780): Starting sync, feed=null [5005f081]
,D/DrmWidevineDash(  359): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  359): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  359): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  359): hlos api version =  9
D/DrmWidevineDash(  359): tz api version =  9
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  359): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  359): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  359): PrepareKeyRequest: nonce=1440536877
D/DrmWidevineDash(  359): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb405d600
D/DrmWidevineDash(  359): message_length=1599, signature=0xb5880100, signature_length=3202364116
,D/DrmWidevineDash(  359): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  359): CdmEngine::CloseSession
D/DrmWidevineDash(  359): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  359): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  359): L3 Terminate.
D/DrmWidevineDash(  359): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  359): Service_Uninitialize: starts!
D/QSEECOMAPI: (  359): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  359): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  359): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  359): OEMCrypto_Terminate: ends! returns 0
W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,I/ActivityManager(  823): Start proc 3803:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
I/ActivityManager(  823): Killing 1808:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 10.077ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 222us total 10.429ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 255us total 9.414ms
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,E/SQLiteLog( 3803): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/PeopleSync( 1780): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/dex2oat ( 3821): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3821): dex2oat took 31.133ms (threads: 4) arena alloc=107KB java alloc=18KB native alloc=1112KB free=6MB
,I/ActivityManager(  823): Start proc 3830:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,I/Adreno  ( 3748): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/ResourcesManager( 3830): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3830): Created com.android.providers.calendar.CalendarAlarmManager@2d15ef48(com.android.providers.calendar.CalendarProvider2@3aef01e1)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleSync( 1780): Sync finished, successful=false, took 146ms
,I/Adreno  ( 3748): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/GAv4    ( 3772): Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3772):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3772):   adb logcat -s GAv4
,I/ActivityManager(  823): Start proc 3858:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3803): PlayLogger.onLoggerConnected
W/GAv4    ( 3772): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3772): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  823): Killing 3125:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/PeopleSync( 1780): Cannot authenticate [5005f081]
I/PeopleSync( 1780): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 1780): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 1780): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 1780): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 1780): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 1780): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 1780): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 1780): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 1780): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 1780): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 1780): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 1780): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 1780): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/TimeService( 3858): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449671309214
,D/        ( 3858): TimeServiceNative: User Time to be set is 1449671309214
D/QC-time-services( 3858): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3858): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3858): Lib:time_genoff_operation: pargs->ts_val = 1449671309214
D/QC-time-services( 3858): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  374): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  374): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449671309214
D/QC-time-services(  374): Daemon:genoff_opr: Base = 2, val = 1449671309214, operation = 0
D/QC-time-services(  374): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/26/70 10:41:22
D/QC-time-services(  374): Daemon:Value read from RTC seconds = 9974482000
,D/QC-time-services(  374): Daemon:new time 1449671309214 
D/QC-time-services(  374): Daemon: delta 1439696827214 genoff 1439696827214 
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696827214 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  374): Updating the TOD offset,
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696827214 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  374): Daemon:Update to modem bit set
E/QC-time-services( 3858): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  374): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  374): Daemon: Base = 2, Value being sent to MODEM = 1133706509214
,W/GAv4    ( 3772): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  359): CdmEngine::OpenSession
,I/WVCdm   (  359): Level3 Library Dec 11 2014 16:13:16
W/AnalyticsTrackerProxyImpl( 3772): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.332.11.30
,W/WVCdm   (  359): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  359): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  359): Service_Initialize: starts!
D/QSEECOMAPI: (  359): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  359): App is not loaded in QSEE
,I/ActivityManager(  823): Killing 3030:com.android.defcontainer/u0a7 (adj 15): empty #17
,E/QC-time-services(  374): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  374): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/art     (  823): Explicit concurrent mark sweep GC freed 18579(917KB) AllocSpace objects, 7(394KB) LOS objects, 32% free, 33MB/49MB, paused 7.336ms total 99.557ms
,I/PeopleSync( 1780): ***Sync finished***, duration: 1112 [5005f081]
,D/QSEECOMAPI: (  359): Loaded image: APP id = 3
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@6b183b8}
,D/DrmWidevineDash(  359): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3c8e000
E/DrmWidevineDash(  359): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3c8e000
,D/DrmLibTime(  314): got the req here! ret=0
D/DrmLibTime(  314): command id, time_cmd_id = 770
D/DrmLibTime(  314): time_getutcsec starts!
D/DrmLibTime(  314): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  314): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  314): QSEE Time Listener: seconds: 1449671309
D/DrmLibTime(  314): QSEE Time Listener: nano seconds: 500877082
D/DrmLibTime(  314): time_getutcsec returns 0, sec = 1449671309; nsec = 500877082
D/DrmLibTime(  314): time_getutcsec finished! 
D/DrmLibTime(  314): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  314): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  359): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  359): hlos api version =  9
D/DrmWidevineDash(  359): tz api version =  9
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  359): OEMCrypto_IsKeyboxValid: starts!
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 36382, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  823): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 200547, reason: Periodic
,D/DrmWidevineDash(  359): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  359): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  359): OEMCrypto_OpenSession: starts! SID=0xb3f01940
,D/DrmWidevineDash(  359): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  359): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_GetRandom: starts! randomData=0xb40a4348, dataLength=8
,D/DrmWidevineDash(  359): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  359): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4cac200, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  359): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  359): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  359): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  359): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  359): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  359): OEMCrypto_GetDeviceID: starts! deviceID=0xb583ec80, idLength=0xb36a8710
,D/DrmWidevineDash(  359): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  359): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  359): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  359): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  359): hlos api version =  9
D/DrmWidevineDash(  359): tz api version =  9
D/DrmWidevineDash(  359): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  359): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  359): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  359): PrepareKeyRequest: nonce=2287450344
D/DrmWidevineDash(  359): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4cca600
D/DrmWidevineDash(  359): message_length=1634, signature=0xb4c52dc0, signature_length=3010103028
,I/ActivityManager(  823): Start proc 3897:com.google.android.apps.docs.editors.docs/u0a47 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,I/ActivityManager(  823): Start proc 3916:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,D/DrmWidevineDash(  359): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  359): CdmEngine::CloseSession
D/DrmWidevineDash(  359): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  359): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  359): L3 Terminate.
D/DrmWidevineDash(  359): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  359): Service_Uninitialize: starts!
D/QSEECOMAPI: (  359): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  359): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  359): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  359): OEMCrypto_Terminate: ends! returns 0
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4    ( 3916): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3916):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3916):   adb logcat -s GAv4
,W/GAv4    ( 3916): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3916): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3916): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 3772): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3772): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3772): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 3772): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3772): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  823): Killing 2699:com.android.vending/u0a19 (adj 15): empty #17
,I/ProviderInstaller( 3772): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,V/Herrevad( 1780): NQAS connected
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/DefaultHttpIssuer( 3772): Attempt to close HttpIssuer when no request is executing.
D/AuthorizationBluetoothService( 1536): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/BaseSyncManager( 3772): ClientFlagSyncException
E/BaseSyncManager( 3772): com.google.android.apps.docs.flags.f$a: IO Exception opening: https://ssl.gstatic.com/docs/android/editors/sheets/client_flags?1449671309640= Socket is closed
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.flags.f.a(PG:1108)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.sync.syncadapter.n.a(PG:23060)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.sync.syncadapter.n.c(PG:612)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.sync.syncadapter.q.run(PG:3508)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.sync.syncadapter.o.run(PG:3031)
E/BaseSyncManager( 3772): Caused by: java.net.SocketException: Socket is closed
E/BaseSyncManager( 3772): 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.checkOpen(SourceFile:245)
E/BaseSyncManager( 3772): 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.access$000(SourceFile:56)
E/BaseSyncManager( 3772): 	at com.google.android.gms.org.conscrypt.s.write(SourceFile:749)
E/BaseSyncManager( 3772): 	at okio.q.a_(PG:78)
E/BaseSyncManager( 3772): 	at okio.b.a_(PG:155)
E/BaseSyncManager( 3772): 	at okio.t.flush(PG:221)
E/BaseSyncManager( 3772): 	at com.squareup.okhttp.internal.spdy.e$d.b(PG:381)
E/BaseSyncManager( 3772): 	at com.squareup.okhttp.internal.spdy.q.a(PG:279)
E/BaseSyncManager( 3772): 	at com.squareup.okhttp.internal.http.u.a(PG:10245)
E/BaseSyncManager( 3772): 	at com.squareup.okhttp.internal.http.h$a.a(PG:890)
E/BaseSyncManager( 3772): 	at com.squareup.okhttp.e.a(PG:50089)
E/BaseSyncManager( 3772): 	at com.squareup.okhttp.e$a.a(PG:230)
E/BaseSyncManager( 3772): 	at com.squareup.okhttp.e.a(PG:3201)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.net.okhttp.c.a(PG:156)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.http.executors.b.a(PG:47)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.http.executors.a.a(PG:22)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.http.executors.c.a(PG:69)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.http.issuers.c.b(PG:96)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.http.issuers.c.a(PG:84)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.http.issuers.a.b(PG:6140)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.http.issuers.a.a(PG:2096)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.http.issuers.a.a(PG:1062)
E/BaseSyncManager( 3772): 	at com.google.android.apps.docs.flags.f.a(PG:1106)
E/BaseSyncManager( 3772): 	... 4 more
,V/GmsCoreStatsServiceLauncher( 1780): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  823): Start proc 3951:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,D/LocationInitializer( 1780): Restart initialization of location
,W/ResourcesManager( 3951): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3951): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3951): VM with version 2.1.0 has multidex support
I/MultiDex( 3951): install
I/MultiDex( 3951): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3951): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     ( 1780): Explicit concurrent mark sweep GC freed 16999(1053KB) AllocSpace objects, 12(192KB) LOS objects, 35% free, 29MB/45MB, paused 2.417ms total 46.028ms
,I/CalendarProvider2( 3830): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3830): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ProviderInstaller( 3951): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 3951): callingUid 10011, callindPid: 3951
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,E/MDM     ( 1748): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1780): Module APK com.google.android.play.games already loaded
,W/PlaySystemBroadcastReceiver( 1780): Processed handlePeopleChanged at 169457
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3270): [337] a.<init>: mAccountName set to: thalitester@gmail.com
D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1780): Module APK com.google.android.play.games already loaded
,W/DataBroker( 1780): No player ID found and calling context is not the dest app
,I/art     ( 1536): Explicit concurrent mark sweep GC freed 16508(931KB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 26MB/42MB, paused 3.170ms total 26.478ms
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/Babel   ( 2627): UserRecoverableAuthException.
,D/AuthorizationBluetoothService( 1536): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/Babel   ( 2627): eei: BadAuthentication
E/Babel   ( 2627): 	at eeg.a(Unknown Source)
E/Babel   ( 2627): 	at eeg.a(Unknown Source)
E/Babel   ( 2627): 	at eeg.a(Unknown Source)
E/Babel   ( 2627): 	at g.a(Unknown Source)
E/Babel   ( 2627): 	at cae.a(SourceFile:3089)
E/Babel   ( 2627): 	at cae.a(SourceFile:1131)
E/Babel   ( 2627): 	at cws.a(SourceFile:4333)
E/Babel   ( 2627): 	at cws.a(SourceFile:1419)
E/Babel   ( 2627): 	at crl.a(SourceFile:492)
E/Babel   ( 2627): 	at crl.a(SourceFile:1468)
E/Babel   ( 2627): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2627): 	at cas.b(SourceFile:106)
E/Babel   ( 2627): 	at cap.d(SourceFile:335)
E/Babel   ( 2627): 	at caq.run(SourceFile:81)
E/Babel   ( 2627): Error getting auth token
E/Babel   ( 2627): dvm
E/Babel   ( 2627): 	at g.a(Unknown Source)
E/Babel   ( 2627): 	at cae.a(SourceFile:3089)
E/Babel   ( 2627): 	at cae.a(SourceFile:1131)
E/Babel   ( 2627): 	at cws.a(SourceFile:4333)
E/Babel   ( 2627): 	at cws.a(SourceFile:1419)
E/Babel   ( 2627): 	at crl.a(SourceFile:492)
E/Babel   ( 2627): 	at crl.a(SourceFile:1468)
E/Babel   ( 2627): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2627): 	at cas.b(SourceFile:106)
E/Babel   ( 2627): 	at cap.d(SourceFile:335)
E/Babel   ( 2627): 	at caq.run(SourceFile:81)
,E/Babel   ( 2627): Account registration failed 1-Redacted-21
E/Babel   ( 2627): cyp: null -- null
E/Babel   ( 2627): 	at cae.a(SourceFile:3121)
E/Babel   ( 2627): 	at cae.a(SourceFile:1131)
E/Babel   ( 2627): 	at cws.a(SourceFile:4333)
E/Babel   ( 2627): 	at cws.a(SourceFile:1419)
E/Babel   ( 2627): 	at crl.a(SourceFile:492)
E/Babel   ( 2627): 	at crl.a(SourceFile:1468)
E/Babel   ( 2627): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2627): 	at cas.b(SourceFile:106)
E/Babel   ( 2627): 	at cap.d(SourceFile:335)
E/Babel   ( 2627): 	at caq.run(SourceFile:81)
,V/GmsCoreStatsServiceLauncher( 1780): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/SQLiteLog( 1780): (284) automatic index on invitations(external_inviter_id)
,E/MDM     ( 1748): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/art     ( 2627): Note: end time exceeds epoch: 
,D/LocationInitializer( 1780): Restart initialization of location
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1536): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2627): Unexpected exception while authenticating.
E/Babel   ( 2627): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2627): 	at eeg.b(Unknown Source)
E/Babel   ( 2627): 	at eeg.b(Unknown Source)
E/Babel   ( 2627): 	at g.a(Unknown Source)
E/Babel   ( 2627): 	at cae.b(SourceFile:1146)
E/Babel   ( 2627): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2627): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2627): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2627): 	at java.lang.Thread.run(Thread.java:818)
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs.editors.sheets, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3270): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3270): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3270): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3270): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3270): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3270): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3270): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3270): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3270): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3270): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3270): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3270): 	at com.a.a.k.run(SourceFile:110)
,W/GLSActivity( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1536): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1536): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1536): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DefaultHttpIssuer( 3772): Attempt to consume entity of HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 3772): Attempt to close HttpIssuer when no request is executing.
,E/BaseSyncManager( 3772): AuthenticatorException
E/BaseSyncManager( 3772): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 3772): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/BaseSyncManager( 3772): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 3772): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/BaseSyncManager( 3772): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 3772): 	at android.os.Binder.execTransact(Binder.java:446)
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@6b183b8}
,I/ActivityManager(  823): Start proc 4002:com.google.android.apps.docs/u0a46 for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4    ( 3897): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3897):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3897):   adb logcat -s GAv4
,W/GAv4    ( 3897): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  823): Explicit concurrent mark sweep GC freed 22768(1106KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.416ms total 54.589ms
,W/GAv4    ( 3897): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 3897): Analytics setup for ID UA-21125203-4, app name Docs, version 1.4.292.15.30
,W/GAv4    ( 3897): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Ads     ( 1780): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,W/ResourcesManager( 3897): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3897): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 3897): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3897): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3897): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3897): Installed default security provider GmsCore_OpenSSL
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@29d33933}
,I/GAv4    ( 4002): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4002):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4002):   adb logcat -s GAv4
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 4002): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4002): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4002): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
W/GAv4    ( 4002): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/EventLogService( 1780): Opted in for usage reporting
,W/ResourcesManager( 4002): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4002): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 4002): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4002): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4002): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4002): Installed default security provider GmsCore_OpenSSL
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@2fd4787}
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinTask( 1780): Sending checkin request (10137 bytes)
,E/DefaultHttpIssuer( 3897): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 3897): java.io.IOException
E/DefaultHttpIssuer( 3897): 	at fur.b(PG:162)
E/DefaultHttpIssuer( 3897): 	at fup.b(PG:6072)
E/DefaultHttpIssuer( 3897): 	at com.google.android.apps.docs.flags.ClientFlagSynchronizer.a(PG:1080)
E/DefaultHttpIssuer( 3897): 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.c(PG:26263)
E/DefaultHttpIssuer( 3897): 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.b(PG:611)
E/DefaultHttpIssuer( 3897): 	at gtm.run(PG:2507)
E/DefaultHttpIssuer( 3897): 	at gtk.run(PG:3031)
,E/BaseSyncManager( 3897): ClientFlagSyncException
E/BaseSyncManager( 3897): com.google.android.apps.docs.flags.ClientFlagSynchronizer$ClientFlagSyncException: IO Exception opening: https://ssl.gstatic.com/docs/android/editors/docs/client_flags Socket is closed
E/BaseSyncManager( 3897): 	at com.google.android.apps.docs.flags.ClientFlagSynchronizer.b(PG:4108)
E/BaseSyncManager( 3897): 	at com.google.android.apps.docs.flags.ClientFlagSynchronizer.a(PG:1060)
E/BaseSyncManager( 3897): 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.c(PG:26263)
E/BaseSyncManager( 3897): 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.b(PG:611)
E/BaseSyncManager( 3897): 	at gtm.run(PG:2507)
E/BaseSyncManager( 3897): 	at gtk.run(PG:3031)
E/BaseSyncManager( 3897): Caused by: java.net.SocketException: Socket is closed
E/BaseSyncManager( 3897): 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.checkOpen(SourceFile:245)
E/BaseSyncManager( 3897): 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.access$000(SourceFile:56)
E/BaseSyncManager( 3897): 	at com.google.android.gms.org.conscrypt.s.write(SourceFile:749)
E/BaseSyncManager( 3897): 	at kcm.a_(PG:78)
E/BaseSyncManager( 3897): 	at kby.a_(PG:155)
E/BaseSyncManager( 3897): 	at kcp.flush(PG:221)
E/BaseSyncManager( 3897): 	at kab$d.b(PG:381)
E/BaseSyncManager( 3897): 	at kan.a(PG:279)
E/BaseSyncManager( 3897): 	at jzu.a(PG:10245)
E/BaseSyncManager( 3897): 	at jzj$a.a(PG:890)
E/BaseSyncManager( 3897): 	at jxv.a(PG:50089)
E/BaseSyncManager( 3897): 	at jxv$a.a(PG:230)
E/BaseSyncManager( 3897): 	at jxv.a(PG:3201)
E/BaseSyncManager( 3897): 	at fxi.a(PG:127)
E/BaseSyncManager( 3897): 	at fun.a(PG:47)
E/BaseSyncManager( 3897): 	at fum.a(PG:22)
E/BaseSyncManager( 3897): 	at fuo.a(PG:68)
E/BaseSyncManager( 3897): 	at fur.b(PG:92)
E/BaseSyncManager( 3897): 	at fur.a(PG:80)
E/BaseSyncManager( 3897): 	at fup.b(PG:6140)
E/BaseSyncManager( 3897): 	at fup.a(PG:2096)
E/BaseSyncManager( 3897): 	at fup.a(PG:1062)
E/BaseSyncManager( 3897): 	at com.google.android.apps.docs.flags.ClientFlagSynchronizer.b(PG:4106)
E/BaseSyncManager( 3897): 	... 5 more
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=42.50 rxSuccessRate=39.00 targetRoamBSSID=any RSSI=-52
,E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 5 -> obsolete
,E/SQLiteLog( 3830): (284) automatic index on view_events(_id)
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=42.50 rxSuccessRate=39.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 5 -> obsolete
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs.editors.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1536): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1536): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1536): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DefaultHttpIssuer( 3897): Attempt to consume entity of HttpIssuer when no request is executing.
,E/DefaultHttpIssuer( 3897): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 3897): java.io.IOException
E/DefaultHttpIssuer( 3897): 	at fur.b(PG:162)
E/DefaultHttpIssuer( 3897): 	at fup.b(PG:6072)
E/DefaultHttpIssuer( 3897): 	at gtb.b(PG:213)
E/DefaultHttpIssuer( 3897): 	at gtb.a(PG:125)
E/DefaultHttpIssuer( 3897): 	at gyh.a(PG:224)
E/DefaultHttpIssuer( 3897): 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.b(PG:618)
E/DefaultHttpIssuer( 3897): 	at gtm.run(PG:2507)
E/DefaultHttpIssuer( 3897): 	at gtk.run(PG:3031)
,E/BaseSyncManager( 3897): AuthenticatorException
E/BaseSyncManager( 3897): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 3897): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/BaseSyncManager( 3897): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 3897): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/BaseSyncManager( 3897): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 3897): 	at android.os.Binder.execTransact(Binder.java:446)
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@29d33933}
,I/ActivityManager(  823): Killing 3337:com.android.settings/1000 (adj 15): empty #17
,I/CheckinRequestBuilder( 1780): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1780): Failed to find provider info for com.google.android.wearable.settings,
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1536): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1536): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1536): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DefaultHttpIssuer( 4002): Attempt to consume entity of HttpIssuer when no request is executing.
,E/DefaultHttpIssuer( 4002): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 4002): java.io.IOException
E/DefaultHttpIssuer( 4002): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 4002): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 4002): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 4002): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 4002): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 4002): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 4002): 	at dlr.run(PG:3031)
,E/BaseSyncManager( 4002): AuthenticatorException
E/BaseSyncManager( 4002): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 4002): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/BaseSyncManager( 4002): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 4002): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/BaseSyncManager( 4002): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 4002): 	at android.os.Binder.execTransact(Binder.java:446)
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@2fd4787}
,I/ActivityManager(  823): Killing 3356:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicLeanback( 3443): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3443): Stop autocaching.
,W/CheckinRequestBuilder( 1780): awaiting user notification for token
,E/GmsUtils( 3443): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3443): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/EventLogService( 1780): Opted in for usage reporting
,I/CheckinTask( 1780): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1780): Checking schedule, now: 1449671311923 next: 1449712454919
I/CheckinService( 1780): active receiver: disabled
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1780): [AccountUtils] Account not ready
W/Kids    ( 1780): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1780): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1780): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1780): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1780): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1780): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1780): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1780): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1780): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1780): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1780): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1780): 	at java.lang.Thread.run(Thread.java:818)
,I/GAV2    ( 3538): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 3803): Thread[GAThread,5,main]: No campaign data found.
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,I/ActivityManager(  823): Start proc 4107:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,I/ActivityManager(  823): Killing 1496:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  823): Client connection lost with reason: 4
,I/art     (  823): Explicit concurrent mark sweep GC freed 23767(1202KB) AllocSpace objects, 9(332KB) LOS objects, 32% free, 33MB/49MB, paused 1.641ms total 72.063ms
,D/Finsky  ( 4107): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager(  823): Killing 3509:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
E/lowmemorykiller(  257): Error writing /proc/3509/oom_score_adj; errno=22
,D/Finsky  ( 4107): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  823): Killing 3562:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/ActivityManager(  823): Start proc 4143:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 4107): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4107): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  823): Killing 2963:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,W/ResourcesManager( 4143): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4143): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4107): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4107): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4107): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4107): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 4143): VM with version 2.1.0 has multidex support
I/MultiDex( 4143): install
I/MultiDex( 4143): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 4143): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4143): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1536): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1536): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1780): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1748): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1780): Restart initialization of location
,I/art     ( 1536): Explicit concurrent mark sweep GC freed 34041(1990KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 28MB/44MB, paused 980us total 24.438ms
,V/ConfigFetchTask( 1780): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XLMhlofUCIkxQeeNuRDfpZg_XYNB0GvyUzK-TQcJMfIYVIMOuESeoiSVvXEBqmNOOnr4aX7nwgXhJcYKaM8F4TsW-hyc3AvapedJw38F6CLRFQAc2Bm_FpPutuVSUwyl5Pbw6SYlx2H8v5Nq_cojcuUtHPYz91CRUq0irIZfCc5dBLebT-lu7CTq96jWl3S8WsVh5O
,I/GoogleURLConnFactory( 1780): Using platform SSLCertificateSocketFactory
,V/Finsky  ( 4107): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4107): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4107): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4107): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ActivityManager(  823): Killing 3538:com.google.android.apps.books/u0a34 (adj 15): empty #17
,I/ConfigFetchTask( 1780): updating config table for com.google.android.gms
,D/Finsky  ( 4107): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/ConfigFetchService( 1780): fetch service done; releasing wakelock
,I/ConfigFetchService( 1780): stopping self,
,I/ConfigFetchService( 1780): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ConfigFetchService( 1780): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1780): GmsCore config value changed; rescheduling
W/ConfigFetchService( 1780): ConfigApi client is not connected. Falling back to defaultfetch interval.
,I/ConfigFetchService( 1780): service connected
,D/ConfigFetchService( 1780): ConfigApi connection successful.
,I/ConfigFetchService( 1780): stopping self
,I/VacuumService( 1536): Vacuum at: now=1449671316903 tag=VacuumService
,I/GoogleURLConnFactory( 1536): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4107): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/Uploader( 1536): No account for auth token provided
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4107): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4107): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4107): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4107): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4107): [1] DailyHygiene.reschedule: Scheduling new run in 97 minutes (failures=3)
,D/DeviceConnectionService( 1748): client connected with version: 7571000
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided,
,W/Uploader( 1536): No account for auth token provided
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1536): Failed to get auth token: User intervention required. Notification has been pushed.
,E/Uploader( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
,E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
,E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1536): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1536): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1536): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1536): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1536): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536):  no longer exists, so no auth token.
,W/Uploader( 1536): No account for auth token provided
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1536): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1536): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided,
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1536): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1536): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  823): Killing 3582:com.google.android.youtube/u0a86 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3314:com.google.android.keep/u0a79 (adj 15): empty #17
,W/Uploader( 1536): No account for auth token provided
,W/Uploader( 1536): No account for auth token provided
,I/ConfigService( 1536): onDestroy
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1536): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1536): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/InputReader(  823): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  823): Start proc 4187:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsNetworkLocationProvi( 1748): DISABLE
,D/BackupManagerService(  823): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  823): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  823): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/art     (  823): Explicit concurrent mark sweep GC freed 30485(1406KB) AllocSpace objects, 4(441KB) LOS objects, 31% free, 34MB/50MB, paused 1.881ms total 72.294ms
,E/Uploader( 1536): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1536): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1536): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1536): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/BackupManagerService(  823): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  823): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@dd2fac
,V/GmsNetworkLocationProvi( 1748): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/BackupManagerService(  823): Scheduling immediate backup pass
,V/BackupManagerService(  823): Running a backup pass
V/GmsNetworkLocationProvi( 1748): ENABLE
,V/BackupManagerService(  823): clearing pending backups
V/GmsNetworkLocationProvi( 1748): SET-REQUEST
,V/GmsNetworkLocationProvi( 1748): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/PerformBackupTask(  823): Beginning backup of 14 targets
,D/PerformBackupTask(  823): invokeAgentForBackup on @pm@
,I/Launcher( 1315): Deferring update until onResume
,V/BackupServiceBinder(  823): doBackup() invoked
,I/PMBA    (  823): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  823): Getting widget state for user: 0
,W/Uploader( 1536): No account for auth token provided
W/GmsBackupTransport( 1748): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1748): starting performBackup for @pm@,
,V/GmsBackupTransport( 1748): performBackup done for @pm@
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1536): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1536): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1536): 	at android.os.Binder.execTransact(Binder.java:446)
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
,W/Uploader( 1536): No account for auth token provided
,D/BackupManagerService(  823): Now staging backup of com.google.android.talk
,D/BackupManagerService(  823): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  823): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  823): Now staging backup of com.android.sharedstoragebackup,
,D/BackupManagerService(  823): Now staging backup of com.google.android.gm,
,D/BackupManagerService(  823): Now staging backup of com.android.providers.userdictionary,
,D/BackupManagerService(  823): Now staging backup of com.google.android.apps.genie.geniewidget,
,D/BackupManagerService(  823): Now staging backup of com.android.nfc
,D/BackupManagerService(  823): Now staging backup of com.google.android.marvin.talkback,
,D/BackupManagerService(  823): Now staging backup of com.android.vending,
,D/BackupManagerService(  823): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  823): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  823): Now staging backup of android
,D/BackupManagerService(  823): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1748): Next backup will happen in 43199925 millis.
,I/BackupManagerService(  823): Backup pass finished.
,I/ActivityManager(  823): Start proc 4212:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider,
,W/Uploader( 1536): No account for auth token provided
,I/ActivityManager(  823): Start proc 4231:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 333us total 14.596ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 354us total 13.681ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 304us total 13.476ms
,I/ActivityManager(  823): Killing 3858:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ContactLocale( 4231): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/PackageBroadcastService( 1780): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1780): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1315): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1895f60 new=com.google.android.velvet.VelvetApplication@1895f60
I/Icing   ( 1780): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 4187): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  823): Start proc 4259:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,W/ResourcesManager( 4259): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4187): UpdateCorporaTask done [took 115 ms] updated apps [took 115 ms] 
,I/ActivityManager(  823): Killing 3916:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3731:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3270:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1536): Explicit concurrent mark sweep GC freed 128338(7MB) AllocSpace objects, 33(2MB) LOS objects, 36% free, 28MB/44MB, paused 1.908ms total 72.288ms
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 4107): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4107): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4107): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ActivityManager(  823): Start proc 4287:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,I/ActivityManager(  823): Start proc 4306:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,W/ResourcesManager( 4306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GoogleAuthProtoRequest( 4287): [460] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 4306): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ProviderInstaller( 4306): Installed default security provider GmsCore_OpenSSL
,I/art     (  823): Explicit concurrent mark sweep GC freed 22026(1126KB) AllocSpace objects, 6(661KB) LOS objects, 32% free, 33MB/49MB, paused 1.074ms total 54.252ms
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4107): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4107): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4107): [1] 5.onFinished: Giving up after 6 failures.
,W/ExperimentUpdateService( 4287): [460] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4287): [460] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4287): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4287): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4287): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4287): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  823): Killing 3803:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/dex2oat ( 4342): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads282648255.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads282648255.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4342): dex2oat took 21.515ms (threads: 4) arena alloc=135KB java alloc=12KB native alloc=1223KB free=6MB
,E/YouTube MDX( 4306): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/InstanceID/Rpc( 4306): Found 10011
,V/GoogleAuthProtoRequest( 4287): [461] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4287): [461] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4287): [461] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4287): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4287): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4287): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4287): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  823): Killing 3772:com.google.android.apps.docs.editors.sheets/u0a48 (adj 15): empty #17
,I/Keyboard.Facilitator.LanguageModelFlusher( 1214): run()
,I/Keyboard.Facilitator( 1214): flushDynamicLanguageModels()
,I/ConfigService( 1536): onCreate
,I/ActivityManager(  823): Start proc 4405:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/GAV2    ( 4405): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksApp( 4405): Created application version: 3.6.8 (30608)
,E/HttpOperation( 4259): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4259): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4259): 	at jdm.a(PG:82)
E/HttpOperation( 4259): 	at jcs.o(PG:406)
E/HttpOperation( 4259): 	at jcn.a(PG:1379)
E/HttpOperation( 4259): 	at jcs.i(PG:143)
E/HttpOperation( 4259): 	at blb.a(PG:3937)
E/HttpOperation( 4259): 	at czp.a(PG:18188)
E/HttpOperation( 4259): 	at czp.a(PG:9081)
E/HttpOperation( 4259): 	at czq.run(PG:1686)
E/HttpOperation( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4259): 	at jdj.a(PG:4091)
E/HttpOperation( 4259): 	at jdj.a(PG:1125)
E/HttpOperation( 4259): 	at jdm.a(PG:77)
E/HttpOperation( 4259): 	... 12 more
E/HttpOperation( 4259): Caused by: faj: BadAuthentication
E/HttpOperation( 4259): 	at fal.a(PG:38)
E/HttpOperation( 4259): 	at jdj.a(PG:4089)
E/HttpOperation( 4259): 	... 14 more
,I/BooksSync( 4405): Starting books sync for 61035162, extras: ade
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4259): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4259): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4259): 	at jdm.a(PG:82)
E/HttpOperation( 4259): 	at jcs.o(PG:406)
E/HttpOperation( 4259): 	at jcn.a(PG:1379)
E/HttpOperation( 4259): 	at jcs.i(PG:143)
E/HttpOperation( 4259): 	at hec.a(PG:42)
E/HttpOperation( 4259): 	at hee.a(PG:102)
E/HttpOperation( 4259): 	at czr.a(PG:65)
E/HttpOperation( 4259): 	at kka.a(PG:108)
E/HttpOperation( 4259): 	at czp.a(PG:19176)
E/HttpOperation( 4259): 	at czp.a(PG:9081)
E/HttpOperation( 4259): 	at czq.run(PG:1686)
E/HttpOperation( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4259): 	at jdj.a(PG:4091)
E/HttpOperation( 4259): 	at jdj.a(PG:1125)
E/HttpOperation( 4259): 	at jdm.a(PG:77)
E/HttpOperation( 4259): 	... 15 more
E/HttpOperation( 4259): Caused by: faj: BadAuthentication
E/HttpOperation( 4259): 	at fal.a(PG:38)
E/HttpOperation( 4259): 	at jdj.a(PG:4089)
E/HttpOperation( 4259): 	... 17 more
E/ExperimentLoader( 4259): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4259): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4259): 	,at jdm.a(PG:82)
E/ExperimentLoader( 4259): 	at jcs.o(PG:406)
E/ExperimentLoader( 4259): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4259): 	at jcs.i(PG:143)
E/ExperimentLoader( 4259): 	at hec.a(PG:42)
E/ExperimentLoader( 4259): 	at hee.a(PG:102)
E/ExperimentLoader( 4259): 	at czr.a(PG:65)
E/ExperimentLoader( 4259): 	at kka.a(PG:108)
E/ExperimentLoader( 4259): 	at czp.a(PG:19176)
E/ExperimentLoader( 4259): 	at czp.a(PG:9081)
E/ExperimentLoader( 4259): 	at czq.run(PG:1686)
E/ExperimentLoader( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4259): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4259): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4259): 	at jdm.a(PG:77),
E/ExperimentLoader( 4259): 	... 15 more
E/ExperimentLoader( 4259): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4259): 	at fal.a(PG:38)
E/ExperimentLoader( 4259): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4259): 	... 17 more
,I/BooksConfig( 4405): GmsCore Version = 7.8.99 (2134222-430)
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 196529, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Start proc 4439:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4405): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4405): Soft error
E/BooksSync( 4405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4405): Sync error
E/BooksSync( 4405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4405): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 198112, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Killing 3830:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/ActivityManager(  823): Start proc 4458:com.google.android.apps.docs.editors.sheets/u0a48 for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,I/art     ( 1536): Explicit concurrent mark sweep GC freed 27343(1682KB) AllocSpace objects, 17(1874KB) LOS objects, 37% free, 26MB/42MB, paused 1.453ms total 40.503ms
,V/KeepSync( 4439): Connecting to GoogleApiClient
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1780): Handling authorization failure
E/ClientConnectionOperation( 1780): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1780): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1780): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1780): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1780): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1780): 	... 7 more
,V/KeepSync( 4439): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,I/art     (  823): Explicit concurrent mark sweep GC freed 24108(1085KB) AllocSpace objects, 5(268KB) LOS objects, 32% free, 33MB/49MB, paused 1.333ms total 47.189ms
,I/GAv4    ( 4458): Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4458):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4458):   adb logcat -s GAv4
,W/GAv4    ( 4458): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4458): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4458): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4458): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.332.11.30
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1780): Module APK com.google.android.play.games already loaded
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4439): IOException
E/KeepSync( 4439): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4439): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4439): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4439): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4439): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4439): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4439): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4439): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4439): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4439): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4439): 	... 10 more
,W/KeepSync( 4439): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 198139, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Killing 3897:com.google.android.apps.docs.editors.docs/u0a47 (adj 15): empty #17
,W/ResourcesManager( 4458): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4458): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  823): Start proc 4513:com.google.android.apps.docs.editors.docs/u0a47 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 1780): 0 accounts found with uca feature
I/GamesSyncAdapter( 1780): Starting sync for 3a3529a
,I/GamesSyncAdapter( 1780): Sync duration for 3a3529a: 8
,V/JNIHelp ( 4458): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1780): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  823): Killing 4002:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1780): Module APK com.google.android.play.games already loaded
,I/ProviderInstaller( 4458): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  823): Start proc 4532:com.google.android.apps.docs/u0a46 for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService
,I/GAv4    ( 4513): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4513):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4513):   adb logcat -s GAv4
,W/GAv4    ( 4513): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4513): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4513): Analytics setup for ID UA-21125203-4, app name Docs, version 1.4.292.15.30
,I/GAv4    ( 4532): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4532):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4532):   adb logcat -s GAv4
,W/GAv4    ( 4513): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4532): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4532): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4532): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4532): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,W/ResourcesManager( 4513): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4513): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 4513): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4513): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 4532): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4532): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4513): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/JNIHelp ( 4532): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4513): Installed default security provider GmsCore_OpenSSL
,I/ProviderInstaller( 4532): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  823): Killing 3443:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3748:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ConfigService( 1536): onDestroy
,I/GAV2    ( 4405): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 4107): [420] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4107): [420] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/ActivityManager(  823): Start proc 4610:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4610): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4610):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4610):   adb logcat -s GAv4
,W/GAv4    ( 4610): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4610): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4610): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  823): Killing 4143:com.google.android.gms:car/u0a11 (adj 15): empty #17
,V/GoogleAuthProtoRequest( 4287): [462] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4287): [462] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4287): [462] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4287): 	,at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4287): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4287): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4287): 	at com.a.a.k.run(SourceFile:110)
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3b885f27}
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3b885f27}
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4259): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4259): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4259): 	at jdm.a(PG:82)
E/HttpOperation( 4259): 	at jcs.o(PG:406)
E/HttpOperation( 4259): 	at jcn.a(PG:1379)
E/HttpOperation( 4259): 	at jcs.i(PG:143)
E/HttpOperation( 4259): 	at blb.a(PG:3937)
E/HttpOperation( 4259): 	at czp.a(PG:18188)
E/HttpOperation( 4259): 	at czp.a(PG:9081)
E/HttpOperation( 4259): 	at czq.run(PG:1686)
E/HttpOperation( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4259): 	at jdj.a(PG:4091)
E/HttpOperation( 4259): 	at jdj.a(PG:1125)
E/HttpOperation( 4259): 	at jdm.a(PG:77)
E/HttpOperation( 4259): 	... 12 more
E/HttpOperation( 4259): Caused by: faj: BadAuthentication
E/HttpOperation( 4259): 	at fal.a(PG:38)
E/HttpOperation( 4259): 	at jdj.a(PG:4089)
E/HttpOperation( 4259): 	... 14 more
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 24784(1080KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.236ms total 65.652ms
,E/HttpOperation( 4259): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4259): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4259): 	at jdm.a(PG:82)
E/HttpOperation( 4259): 	at jcs.o(PG:406)
E/HttpOperation( 4259): 	at jcn.a(PG:1379)
E/HttpOperation( 4259): 	at jcs.i(PG:143)
E/HttpOperation( 4259): 	at hec.a(PG:42)
E/HttpOperation( 4259): 	at hee.a(PG:102)
E/HttpOperation( 4259): 	at czr.a(PG:65)
E/HttpOperation( 4259): 	at kka.a(PG:108)
E/HttpOperation( 4259): 	at czp.a(PG:19176)
E/HttpOperation( 4259): 	at czp.a(PG:9081)
E/HttpOperation( 4259): 	at czq.run(PG:1686)
E/HttpOperation( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4259): 	at jdj.a(PG:4091)
E/HttpOperation( 4259): 	at jdj.a(PG:1125)
E/HttpOperation( 4259): 	at jdm.a(PG:77)
E/HttpOperation( 4259): 	... 15 more
E/HttpOperation( 4259): Caused by: faj: BadAuthentication
E/HttpOperation( 4259): 	at fal.a(PG:38)
E/HttpOperation( 4259): 	at jdj.a(PG:4089)
E/HttpOperation( 4259): 	... 17 more
E/ExperimentLoader( 4259): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4259): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4259): 	at jdm.a(PG:82)
E/ExperimentLoader( 4259): 	at jcs.o(PG:406)
E/ExperimentLoader( 4259): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4259): 	at jcs.i(PG:143)
E/ExperimentLoader( 4259): 	at hec.a(PG:42)
E/ExperimentLoader( 4259): 	at hee.a(PG:102)
E/ExperimentLoader( 4259): 	at czr.a(PG:65)
E/ExperimentLoader( 4259): 	at kka.a(PG:108)
E/ExperimentLoader( 4259): 	at czp.a(PG:19176)
E/ExperimentLoader( 4259): 	at czp.a(PG:9081)
E/ExperimentLoader( 4259): 	at czq.run(PG:1686)
E/ExperimentLoader( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4259): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4259): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4259): 	at jdm.a(PG:77)
E/ExperimentLoader( 4259): 	... 15 more
E/ExperimentLoader( 4259): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4259): 	at fal.a(PG:38)
E/ExperimentLoader( 4259): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4259): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 286953, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,I/jxcore-log( 3194): Connected to the server!
I/jxcore-log( 3194): 
,I/chromium( 3194): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,I/art     ( 1536): Explicit concurrent mark sweep GC freed 21735(1223KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 2.003ms total 40.488ms
,I/BooksSync( 4405): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4439): Connecting to GoogleApiClient
,I/BooksConfig( 4405): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1780): Handling authorization failure
E/ClientConnectionOperation( 1780): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1780): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1780): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1780): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1780): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1780): 	... 7 more
,V/KeepSync( 4439): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4405): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4405): Soft error
E/BooksSync( 4405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4405): Sync error
E/BooksSync( 4405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4405): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 288125, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4439): IOException
E/KeepSync( 4439): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4439): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4439): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4439): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4439): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4439): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4439): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4439): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4439): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4439): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4439): 	... 10 more
,W/KeepSync( 4439): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 289751, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0,
,V/GoogleAuthProtoRequest( 4287): [463] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4287): [463] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4287): [463] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4287): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4287): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4287): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4287): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4259): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4259): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4259): 	at jdm.a(PG:82)
E/HttpOperation( 4259): 	at jcs.o(PG:406)
E/HttpOperation( 4259): 	at jcn.a(PG:1379)
E/HttpOperation( 4259): 	at jcs.i(PG:143)
E/HttpOperation( 4259): 	at blb.a(PG:3937)
E/HttpOperation( 4259): 	at czp.a(PG:18188)
E/HttpOperation( 4259): 	at czp.a(PG:9081)
E/HttpOperation( 4259): 	at czq.run(PG:1686)
E/HttpOperation( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4259): 	at jdj.a(PG:4091)
E/HttpOperation( 4259): 	at jdj.a(PG:1125)
E/HttpOperation( 4259): 	at jdm.a(PG:77)
E/HttpOperation( 4259): 	... 12 more
E/HttpOperation( 4259): Caused by: faj: BadAuthentication
E/HttpOperation( 4259): 	at fal.a(PG:38)
E/HttpOperation( 4259): 	at jdj.a(PG:4089)
E/HttpOperation( 4259): 	... 14 more
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4259): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4259): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4259): 	at jdm.a(PG:82)
E/HttpOperation( 4259): 	at jcs.o(PG:406)
E/HttpOperation( 4259): 	at jcn.a(PG:1379)
E/HttpOperation( 4259): 	at jcs.i(PG:143)
E/HttpOperation( 4259): 	at hec.a(PG:42)
E/HttpOperation( 4259): 	at hee.a(PG:102)
E/HttpOperation( 4259): 	at czr.a(PG:65)
E/HttpOperation( 4259): 	at kka.a(PG:108)
E/HttpOperation( 4259): 	at czp.a(PG:19176)
E/HttpOperation( 4259): 	at czp.a(PG:9081)
E/HttpOperation( 4259): 	at czq.run(PG:1686)
E/HttpOperation( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4259): 	at jdj.a(PG:4091)
E/HttpOperation( 4259): 	at jdj.a(PG:1125)
E/HttpOperation( 4259): 	at jdm.a(PG:77)
E/HttpOperation( 4259): 	... 15 more
E/HttpOperation( 4259): Caused by: faj: BadAuthentication
E/HttpOperation( 4259): 	at fal.a(PG:38)
E/HttpOperation( 4259): 	at jdj.a(PG:4089)
E/HttpOperation( 4259): 	... 17 more
E/ExperimentLoader( 4259): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4259): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4259): 	at jdm.a(PG:82)
E/ExperimentLoader( 4259): 	at jcs.o(PG:406)
E/ExperimentLoader( 4259): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4259): 	at jcs.i(PG:143)
E/ExperimentLoader( 4259): 	at hec.a(PG:42)
E/ExperimentLoader( 4259): 	at hee.a(PG:102)
E/ExperimentLoader( 4259): 	at czr.a(PG:65)
E/ExperimentLoader( 4259): 	at kka.a(PG:108)
E/ExperimentLoader( 4259): 	at czp.a(PG:19176)
E/ExperimentLoader( 4259): 	at czp.a(PG:9081)
E/ExperimentLoader( 4259): 	at czq.run(PG:1686)
E/ExperimentLoader( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4259): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4259): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4259): 	at jdm.a(PG:77)
E/ExperimentLoader( 4259): 	... 15 more
E/ExperimentLoader( 4259): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4259): 	at fal.a(PG:38)
E/ExperimentLoader( 4259): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4259): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 409205, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,I/BooksSync( 4405): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4439): Connecting to GoogleApiClient
,I/BooksConfig( 4405): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1780): Handling authorization failure
E/ClientConnectionOperation( 1780): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1780): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1780): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1780): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1780): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1780): 	... 7 more
,V/KeepSync( 4439): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4405): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4405): Soft error
E/BooksSync( 4405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4405): Sync error
E/BooksSync( 4405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4405): Finished books sync
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 440996, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 34559(1498KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 1.812ms total 73.416ms,
,E/KeepSync( 4439): IOException
E/KeepSync( 4439): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4439): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4439): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4439): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4439): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4439): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4439): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4439): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4439): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4439): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4439): 	... 10 more
W/KeepSync( 4439): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 442697, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1536): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1536): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1536): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1536): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1536): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1536): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4107): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4107): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4107): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 4107): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4107): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 4107): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4107): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 4107): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 4287): [464] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4287): [464] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4287): [464] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4287): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4287): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4287): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4287): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4259): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4259): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4259): 	at jdm.a(PG:82)
E/HttpOperation( 4259): 	at jcs.o(PG:406)
E/HttpOperation( 4259): 	at jcn.a(PG:1379)
E/HttpOperation( 4259): 	at jcs.i(PG:143)
E/HttpOperation( 4259): 	at blb.a(PG:3937)
E/HttpOperation( 4259): 	at czp.a(PG:18188)
E/HttpOperation( 4259): 	at czp.a(PG:9081)
E/HttpOperation( 4259): 	at czq.run(PG:1686)
E/HttpOperation( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4259): 	at jdj.a(PG:4091)
E/HttpOperation( 4259): 	at jdj.a(PG:1125)
E/HttpOperation( 4259): 	at jdm.a(PG:77)
E/HttpOperation( 4259): 	... 12 more
E/HttpOperation( 4259): Caused by: faj: BadAuthentication
E/HttpOperation( 4259): 	at fal.a(PG:38)
E/HttpOperation( 4259): 	at jdj.a(PG:4089)
E/HttpOperation( 4259): 	... 14 more
,I/art     ( 1536): Explicit concurrent mark sweep GC freed 55788(2MB) AllocSpace objects, 3(330KB) LOS objects, 36% free, 27MB/43MB, paused 1.586ms total 58.659ms
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4259): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4259): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4259): 	at jdm.a(PG:82)
E/HttpOperation( 4259): 	at jcs.o(PG:406)
E/HttpOperation( 4259): 	at jcn.a(PG:1379)
E/HttpOperation( 4259): 	at jcs.i(PG:143)
E/HttpOperation( 4259): 	at hec.a(PG:42)
E/HttpOperation( 4259): 	at hee.a(PG:102)
E/HttpOperation( 4259): 	at czr.a(PG:65)
E/HttpOperation( 4259): 	at kka.a(PG:108)
E/HttpOperation( 4259): 	at czp.a(PG:19176)
E/HttpOperation( 4259): 	at czp.a(PG:9081)
E/HttpOperation( 4259): 	at czq.run(PG:1686)
E/HttpOperation( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4259): 	at jdj.a(PG:4091)
E/HttpOperation( 4259): 	at jdj.a(PG:1125)
E/HttpOperation( 4259): 	at jdm.a(PG:77)
E/HttpOperation( 4259): 	... 15 more
E/HttpOperation( 4259): Caused by: faj: BadAuthentication
E/HttpOperation( 4259): 	at fal.a(PG:38)
E/HttpOperation( 4259): 	at jdj.a(PG:4089)
E/HttpOperation( 4259): 	... 17 more
,E/ExperimentLoader( 4259): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 4259): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4259): 	at jdm.a(PG:82)
E/ExperimentLoader( 4259): 	at jcs.o(PG:406)
E/ExperimentLoader( 4259): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4259): 	at jcs.i(PG:143)
E/ExperimentLoader( 4259): 	at hec.a(PG:42)
E/ExperimentLoader( 4259): 	at hee.a(PG:102)
E/ExperimentLoader( 4259): 	at czr.a(PG:65)
E/ExperimentLoader( 4259): 	at kka.a(PG:108)
E/ExperimentLoader( 4259): 	at czp.a(PG:19176)
,E/ExperimentLoader( 4259): 	at czp.a(PG:9081)
E/ExperimentLoader( 4259): 	at czq.run(PG:1686)
E/ExperimentLoader( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4259): 	at jdj.a(PG:4091),
E/ExperimentLoader( 4259): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4259): 	at jdm.a(PG:77)
E/ExperimentLoader( 4259): 	... 15 more
E/ExperimentLoader( 4259): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4259): 	at fal.a(PG:38)
E/ExperimentLoader( 4259): ,	at jdj.a(PG:4089)
E/ExperimentLoader( 4259): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 653207, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,I/BooksSync( 4405): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4405): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4405): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4405): Soft error
E/BooksSync( 4405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4405): Sync error
E/BooksSync( 4405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4405): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 716901, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,V/KeepSync( 4439): Connecting to GoogleApiClient
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1780): Handling authorization failure
E/ClientConnectionOperation( 1780): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
,E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1780): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1780): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1780): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1780): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.c.b(SourceFile:109),
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1780): 	,at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1780): 	... 7 more
,V/KeepSync( 4439): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4439): IOException
E/KeepSync( 4439): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4439): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4439): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4439): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4439): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4439): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4439): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4439): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4439): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4439): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4439): 	... 10 more
W/KeepSync( 4439): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 720245, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3252): Stopping oneshot timer
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,I/art     (  823): Explicit concurrent mark sweep GC freed 49432(2MB) AllocSpace objects, 12(474KB) LOS objects, 31% free, 34MB/50MB, paused 1.573ms total 100.650ms
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4259): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4259): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4259): 	at jdm.a(PG:82)
E/HttpOperation( 4259): 	at jcs.o(PG:406)
E/HttpOperation( 4259): 	at jcn.a(PG:1379)
E/HttpOperation( 4259): 	at jcs.i(PG:143)
E/HttpOperation( 4259): 	at blb.a(PG:3937)
E/HttpOperation( 4259): 	at czp.a(PG:18188)
E/HttpOperation( 4259): 	at czp.a(PG:9081)
E/HttpOperation( 4259): 	at czq.run(PG:1686)
E/HttpOperation( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4259): 	at jdj.a(PG:4091)
E/HttpOperation( 4259): 	at jdj.a(PG:1125)
E/HttpOperation( 4259): 	at jdm.a(PG:77)
E/HttpOperation( 4259): 	... 12 more
E/HttpOperation( 4259): Caused by: faj: BadAuthentication
E/HttpOperation( 4259): 	at fal.a(PG:38)
E/HttpOperation( 4259): 	at jdj.a(PG:4089)
E/HttpOperation( 4259): 	... 14 more
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4259): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 4259): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4259): 	at jdm.a(PG:82)
E/HttpOperation( 4259): 	at jcs.o(PG:406)
E/HttpOperation( 4259): 	at jcn.a(PG:1379)
E/HttpOperation( 4259): 	at jcs.i(PG:143)
E/HttpOperation( 4259): 	at hec.a(PG:42)
E/HttpOperation( 4259): 	,at hee.a(PG:102)
E/HttpOperation( 4259): 	at czr.a(PG:65)
E/HttpOperation( 4259): 	at kka.a(PG:108)
E/HttpOperation( 4259): 	at czp.a(PG:19176)
E/HttpOperation( 4259): 	at czp.a(PG:9081)
E/HttpOperation( 4259): 	at czq.run(PG:1686)
E/HttpOperation( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/HttpOperation( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4259): 	at jdj.a(PG:4091)
E/HttpOperation( 4259): 	at jdj.a(PG:1125)
E/HttpOperation( 4259): 	at jdm.a(PG:77)
E/HttpOperation( 4259): 	... 15 more
E/HttpOperation( 4259): Caused by: faj: BadAuthentication
E/HttpOperation( 4259): 	at fal.a(PG:38)
E/HttpOperation( 4259): 	at jdj.a(PG:4089)
E/HttpOperation( 4259): 	... 17 more
E/ExperimentLoader( 4259): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4259): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4259): 	at jdm.a(PG:82),
E/ExperimentLoader( 4259): 	at jcs.o(PG:406)
E/ExperimentLoader( 4259): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4259): 	at jcs.i(PG:143)
E/ExperimentLoader( 4259): 	at hec.a(PG:42)
E/ExperimentLoader( 4259): 	at hee.a(PG:102)
E/ExperimentLoader( 4259): 	at czr.a(PG:65)
E/ExperimentLoader( 4259): 	at kka.a(PG:108)
E/ExperimentLoader( 4259): 	at czp.a(PG:19176)
E/ExperimentLoader( 4259): 	at czp.a(PG:9081)
E/ExperimentLoader( 4259): 	at czq.run(PG:1686)
E/ExperimentLoader( 4259): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4259): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/ExperimentLoader( 4259): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4259): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4259): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4259): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4259): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4259): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4259): 	at jdm.a(PG:77)
E/ExperimentLoader( 4259): 	... 15 more
E/ExperimentLoader( 4259): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4259): 	at fal.a(PG:38)
E/ExperimentLoader( 4259): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4259): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1140709, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,I/BooksSync( 4405): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4405): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 4405): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4405): Soft error,
E/BooksSync( 4405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4405): Sync error
E/BooksSync( 4405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4405): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1211682, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/UsageStatsService(  823): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,V/KeepSync( 4439): Connecting to GoogleApiClient
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1780): Handling authorization failure
E/ClientConnectionOperation( 1780): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1780): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1780): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1780): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1780): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1780): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1780): 	... 7 more
,V/KeepSync( 4439): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4439): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4439): IOException
E/KeepSync( 4439): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4439): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4439): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4439): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4439): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4439): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4439): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4439): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4439): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4439): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4439): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4439): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4439): 	... 10 more
W/KeepSync( 4439): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1248289, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 4287): [465] a.<init>: mAccountName set to: thalitester@gmail.com
,D/GCM     ( 1536): Message class com.google.f.a.a.i
,I/GCM     ( 1780): Message from null null
,E/GCM     ( 1780): Dropping message from null
,I/EventLogService( 1780): Opted in for usage reporting
,I/EventLogService( 1780): Aggregate from 1449671306940 (log), 1449670630333 (data)
,I/GLSUser ( 1536): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1536): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1536): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1536): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1536): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceDumpSys( 1780): dumping service [account]
,I/art     ( 1536): Explicit concurrent mark sweep GC freed 67223(3MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 1.832ms total 63.906ms
,W/ExperimentUpdateService( 4287): [465] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4287): [465] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4287): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4287): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4287): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4287): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4287): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4287): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  823): Prepared write state in 20ms
I/ProcessStatsService(  823): Prepared write state in 6ms
,I/ProcessStatsService(  823): Prepared write state in 7ms
,I/ProcessStatsService(  823): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-44-09.bin
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3252): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3252): Stopping oneshot timer
,I/art     (  823): Explicit concurrent mark sweep GC freed 55400(2MB) AllocSpace objects, 16(720KB) LOS objects, 32% free, 33MB/49MB, paused 1.677ms total 88.074ms
,TIME-OUT KILL (timeout was 1800000ms)
```
