#### Test 5065027857de7f1_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2698): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2698): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2698): [1] 5.onFinished: Scheduling replication attempt 2.
,D/AndroidRuntime( 3168): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3168): CheckJNI is OFF
D/AndroidRuntime( 3168): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{1467704a token=Token{2ed4e1b5 ActivityRecord{372d9ec u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3168): Shutting down VM
V/WindowManager(  821): Adding window Window{e6f2897 u0 Starting com.test.thalitest} at 3 of 8 (after Window{38bdefba u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/MicrophoneInputStream( 1527): mic_close com.google.android.apps.gsa.speech.audio.u@26484263
I/HotwordDetector( 1527): Closing mic
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
I/ActivityManager(  821): Start proc 3182:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1527): Stopping hotword detection.
I/HotwordRecognitionRnr( 1527): Hotword detection finished
I/ActivityManager(  821): Killing 2657:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1692484883
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  821): Killing 2387:com.google.android.keep/u0a79 (adj 15): empty #18
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3182): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3182): Time to load native libraries: 3 ms (timestamps 8249-8252)
,I/LibraryLoader( 3182): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3182): Binding Chromium to main looper Looper (main, tid 1) {256b037b}
,I/LibraryLoader( 3182): Expected native library version number "",actual native library version number ""
I/chromium( 3182): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3182): Initializing chromium process, singleProcess=true
W/art     ( 3182): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3182): ApplicationContext is null in ApplicationStatus
W/chromium( 3182): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3182): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3182): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3182): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3182): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f556587:true
,D/BluetoothAdapter( 3182): 713032516: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3182): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3182): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3182): CordovaWebView is running on device made by: motorola
,W/art     ( 3182): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3182): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3182): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3182): Validating map...
,V/WindowManager(  821): Adding window Window{217cbe77 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{e6f2897 u0 Starting com.test.thalitest}),
,W/chromium( 3182): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3182): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3182): Enabling debug mode 0
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +894ms (total +1m44s615ms)
,I/Keyboard.Facilitator( 1201): onFinishInput()
,W/BindingManager( 3182): Cannot call determinedVisibility() - never saw a connection for the pid: 3182
,D/JsMessageQueue( 3182): Set native->JS mode to OnlineEventsBridgeMode
,I/kickstart(  872): STATUS: Received file 'm9kefs2'
,I/kickstart(  872): STATUS: 950272 bytes transferred in 0.994932 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,D/jxcore_app_log( 3182): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576190336
,D/JX-Cordova( 3182): jxcore cordova android initializing
,W/jxcore-log( 3182): Initializing JXcore engine
W/jxcore-log( 3182): JXcore engine is ready
,W/jxcore-log( 3182): Starting JXcore engine
,W/.test.thalitest( 3182): type=1400 audit(0.0:17): avc: denied { ioctl } for path="socket:[10028]" dev="sockfs" ino=10028 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3182): type=1400 audit(0.0:18): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
W/.test.thalitest( 3182): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[11519]" dev="sockfs" ino=11519 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3182): type=1400 audit(0.0:20): avc: denied { ioctl } for path="socket:[20288]" dev="sockfs" ino=20288 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3182): Platform android
,W/jxcore-log( 3182): 
W/jxcore-log( 3182): Process ARCH arm
W/jxcore-log( 3182): 
,I/jxcore-log( 3182): JXcore Cordova bridge is ready!
I/jxcore-log( 3182): 
,W/jxcore-log( 3182): JXcore engine is started
I/Choreographer( 3182): Skipped 132 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3182): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3182): Toggling radios to true
I/jxcore-log( 3182): 
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  821): Message: 1
D/BluetoothManagerService(  821): MESSAGE_ENABLE: mBluetooth = null
D/WifiService(  821): New client listening to asynchronous messages
D/WifiService(  821): setWifiEnabled: true pid=3182, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  821): Start proc 3237:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,D/SoftapController(  353): Softap fwReload - Ok
I/jxcore-log( 3182): Radios toggled
I/jxcore-log( 3182): ,
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3182): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3182): 
,D/CommandListener(  353): Setting iface cfg
D/CommandListener(  353): Trying to bring down wlan0
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,I/jxcore-log( 3182): Perf Test app loaded loaded
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): check test folder
I/jxcore-log( 3182): 
E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/jxcore-log( 3182): found test : ./testFindPeers.js
I/jxcore-log( 3182): 
,I/jxcore-log( 3182): found test : ./testSendData.js
I/jxcore-log( 3182): 
,I/wpa_supplicant( 3253): Successfully initialized wpa_supplicant
,I/art     (  821): Explicit concurrent mark sweep GC freed 18549(901KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.469ms total 58.616ms
,D/WifiMonitor(  821): startMonitoring(wlan0) with mConnected = false
,W/ResourcesManager( 3237): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/ActivityManager(  821): Start proc 3255:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/Choreographer( 3182): Skipped 71 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3182): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3253): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  821): Start proc 3282:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  821): Killing 2820:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/AdapterServiceConfig( 3237): Adding HeadsetService,
D/AdapterServiceConfig( 3237): Adding A2dpService,
D/AdapterServiceConfig( 3237): Adding HidService
,D/AdapterServiceConfig( 3237): Adding HealthService
,D/AdapterServiceConfig( 3237): Adding PanService
D/AdapterServiceConfig( 3237): Adding GattService
D/AdapterServiceConfig( 3237): Adding BluetoothMapService
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33d1a68:true
D/BluetoothAdapterState( 3237): make
,I/bluedroid( 3237): init
I/BluetoothAdapterState( 3237): Entering OffState
I/bte_conf( 3237): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 3237): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3237): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3237): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3237): get_profile_interface socket
I/bluedroid( 3237): get_profile_interface map_client
I/GKI_LINUX( 3237): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 3237): Address is:F8:CF:C5:D9:E5:61
D/BluetoothAdapterProperties( 3237): Name is: Nexus 6
D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  821): Message: 40
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
I/bluedroid( 3237): config_hci_snoop_log
D/BluetoothManagerService(  821): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  821): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3237): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3237): Setting state to 11
I/BluetoothAdapterState( 3237): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  821): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3237): make
,I/BluetoothBondStateMachine( 3237): StableState(): Entering Off State
,I/BluetoothAdapterState( 3237): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3237): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c22598
D/HeadsetService( 3237): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3237): classInitNative: succeeds
D/HeadsetStateMachine( 3237): make
,D/HeadsetStateMachine( 3237): max_hf_connections = 1
I/bluedroid( 3237): get_profile_interface handsfree
D/HeadsetStateMachine( 3237): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 3237): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c22598
D/BluetoothA2dp(  821): Proxy object connected
,D/A2dpService( 3237): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3237): classInitNative: succeeds
I/bluedroid( 3237): get_profile_interface avrcp
E/RemoteController( 3237): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3237): classInitNative: succeeds
D/A2dpStateMachine( 3237): make
,I/bluedroid( 3237): get_profile_interface a2dp
I/GKI_LINUX( 3237): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothHidServiceJni( 3237): classInitNative: succeeds,
D/BluetoothAdapterService( 3237): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c22598
D/A2dpStateMachine( 3237): Enter Disconnected: -2
,D/HidService( 3237): Received start request. Starting profile...
I/bluedroid( 3237): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3237): classInitNative: succeeds
D/BluetoothAdapterService( 3237): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c22598
D/HealthService( 3237): Received start request. Starting profile...
,I/bluedroid( 3237): get_profile_interface health
I/BluetoothPanServiceJni( 3237): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3237): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c22598
,D/PanService( 3237): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3237): initializeNative(L110): pan
I/bluedroid( 3237): get_profile_interface pan
I/BtGatt.JNI( 3237): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3237): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c22598
D/BtGatt.DebugUtils( 3237): handleDebugAction() action=null
,D/BtGatt.GattService( 3237): Received start request. Starting profile...
D/BtGatt.GattService( 3237): start()
I/bluedroid( 3237): get_profile_interface gatt
D/BluetoothAdapterService( 3237): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c22598
,D/BtGatt.AdvertiseManager( 3237): advertise manager created
,D/BluetoothA2dp( 1098): Proxy object connected
,D/BluetoothInputDevice( 1098): Proxy object connected
D/BluetoothPan( 1098): BluetoothPAN Proxy object connected
,D/BluetoothAdapterService( 3237): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c22598
,D/BluetoothMap( 1098): Proxy object connected
,D/BluetoothMapService( 3237): Received start request. Starting profile...
D/BluetoothMapService( 3237): start()
,D/BluetoothMapEmailSettingsLoader( 3237): Found 0 applications
D/BluetoothMapEmailAppObserver( 3237): createReceiver()
,D/BluetoothMapEmailAppObserver( 3237): initObservers()
D/BluetoothMapEmailAppObserver( 3237): getEnabledAccountItems()
,D/HeadsetStateMachine( 3237): Proxy object connected
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3237): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3237): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3237): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3237): enable
I/GKI_LINUX( 3237): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3237): btu_task pending for preload complete event
,I/bt_hci_bdroid( 3237): init
,I/bt_vendor( 3237): init
I/bt_vnd_conf( 3237): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,I/bt_vnd_conf( 3237): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3237): userial_init
,I/art     ( 1431): Explicit concurrent mark sweep GC freed 23737(1178KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.094ms total 28.206ms
,D/Tethering(  821): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_userial_vendor( 3237): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3237): device fd = 53 open
,D/bt_userial( 3237): Entering userial_read_thread()
,I/bt_hwcfg( 3237): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3237): Chipset BCM4354A2
D/bt_hwcfg( 3237): Target name = [BCM4354A2]
,I/bt_hwcfg( 3237): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/ActivityManager(  821): Start proc 3324:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
I/wpa_supplicant( 3253): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3253): Could not read interface p2p-dev-wlan0 flags: No such device
,I/ActivityManager(  821): Killing 2754:com.google.android.gm/u0a78 (adj 15): empty #17
,D/WifiConfigStore(  821): Loading config and enabling all networks 
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@7b8ce0}
,E/WifiConfigStore(  821): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  821): Setting external_sim to 1
,W/Settings( 2596): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  821): Setting OUI to 92-68-C3
I/WifiNative-HAL(  821): startHal
D/wifi    (  821): setting scan oui 0xaec86538
D/WifiHAL (  821): Sending mac address OUI
,E/WifiStateMachine(  821): cancelDelayedScan -> 1
,D/WifiScanningService(  821): SCAN_AVAILABLE : 3
W/CommandListener(  353): Failed to retrieve HW addr for p2p0 (No such device)
D/RttService(  821): SCAN_AVAILABLE : 3
D/WifiScanningService(  821): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  821): startHal
D/RttService(  821): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/wifi    (  821): getting scan capabilities on interface[0] = 0xaec86538
D/WifiHAL (  821): Creating message to get scan capablities; iface = 5
D/WifiHAL (  821): In GetCapabilities::handleResponse
D/WifiHAL (  821): Id = 0, subcmd = 0, len = 28, expected len = 32
,D/CommandListener(  353): Setting iface cfg
,D/WifiScanningService(  821): StartedState
,E/WifiP2pService(  821): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
,D/WifiMonitor(  821): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 3253): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  821): p2pGetDeviceAddress
,D/WifiNative-HAL(  821): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,E/native  (  821): do suspend false
,I/ActivityManager(  821): Killing 2303:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/bt_hwcfg( 3237): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3237): Settlement delay -- 100 ms
I/bt_hwcfg( 3237): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3237): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3237): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3237): vendor lib fwcfg completed
,I/bt-btu  ( 3237): btu_task received preload complete event
,I/        ( 3237): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3237): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3237): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3237): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3237): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3237): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3237): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3237): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3237): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3237): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3237): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3237): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3237): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3237): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3237): BTE_InitTraceLevels -- TRC_BTIF
,I/ActivityManager(  821): Start proc 3342:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 342us total 15.697ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 468us total 16.595ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 335us total 16.304ms
,E/bt-btm  ( 3237): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2de8085 
E/bt-btm  ( 3237): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2de8085 
,D/BluetoothAdapterProperties( 3237): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3237): Calling BTA_HhEnable
E/bt-btif ( 3237): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3237): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6,
D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3237): Name is: Nexus 6
,D/BluetoothAdapterProperties( 3237): Scan Mode:20,
,D/BluetoothAdapterProperties( 3237): Discoverable Timeout:120
,W/bt-btm  ( 3237): Stopping oneshot timer
,D/bte_conf( 3237): Device ID record 1 : primary
D/bte_conf( 3237):   vendorId            = 000f,
D/bte_conf( 3237):   vendorIdSource      = 0001
D/bte_conf( 3237):   product             = 1200,
D/bte_conf( 3237):   version             = 1436
D/bte_conf( 3237):   clientExecutableURL = 
D/bte_conf( 3237):   serviceDescription  = 
D/bte_conf( 3237):   documentationURL    = 
D/bte_conf( 3237): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 3237): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false,
D/BluetoothAdapterProperties( 3237): ScanMode =  20
D/BluetoothAdapterProperties( 3237): State =  11
D/BluetoothAdapterProperties( 3237): Setting state to 12
I/BluetoothAdapterState( 3237): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  821): Message: 60,
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothPanServiceJni( 3237): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  821): Broadcasting onBluetoothStateChange(true) to 13 receivers.
I/BluetoothAdapterState( 3237): Entering On State
D/BluetoothHeadset( 1291): onBluetoothStateChange: up=true
D/BluetoothManagerService(  821): Creating new ProfileServiceConnections object for profile: 1
D/BluetoothAdapterProperties( 3237): Scan Mode:21
D/BluetoothAdapterProperties( 3237): Discoverable Timeout:120
D/BluetoothA2dpSink( 1098): onBluetoothStateChange: up=true
,E/BluetoothA2dpSink( 1098): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink },
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothPan( 1098): onBluetoothStateChange(on) call bindService
,D/BluetoothA2dp(  821): onBluetoothStateChange: up=true
,E/bt_h4   ( 3237): vendor lib postload completed
D/BluetoothA2dp( 1098): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 1098): onBluetoothStateChange: up=true
D/BluetoothAvrcpController( 1098): onBluetoothStateChange: up=true
,E/BluetoothAvrcpController( 1098): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothHeadset( 1098): onBluetoothStateChange: up=true
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
,D/BluetoothMap( 1098): onBluetoothStateChange: up=true
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothHeadsetClient( 1098): onBluetoothStateChange: up=true
,E/BluetoothHeadsetClient( 1098): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
,D/BluetoothManagerService(  821): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 3237): onReceive
D/BluetoothMapService( 3237): STATE_ON,
D/BluetoothManagerService(  821): Message: 40
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapMasInstance( 3237): Map Service startRfcommSocketListener,
,D/BluetoothMapMasInstance( 3237): MAS initSocket()
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3237): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3237): Accepting socket connection...
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 1291): Proxy object connected
,D/StrictMode( 3342): StrictMode policy violation; ~duration=245 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3342): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3342): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3342): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3342): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3342): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3342): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3342): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3342): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3342): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3342): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3342): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3342): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3342): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3342): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3342): StrictMode policy violation; ~duration=244 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3342): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3342): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3342): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3342): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3342): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3342): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3342): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3342): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3342): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3342): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3342): StrictMode policy violation; ~duration=242 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3342): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3342): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
,D/StrictMode( 3342): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3342): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3342): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3342): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3342): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3342): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3342): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3342): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3342): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3342): ,	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3342): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3342): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Method.java:372),
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3342): StrictMode policy violation; ~duration=237 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3342): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3342): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3342): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3342): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3342): ,	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3342): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3342): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3342): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,D/StrictMode( 3342): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3342): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3342): StrictMode policy violation; ~duration=227 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3342): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137),
D/StrictMode( 3342): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3342): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3342): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3342): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3342): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3342): 	at java.lang.System.loadLibrary(System.java:988),
D/StrictMode( 3342): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3342): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3342): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553),
D/StrictMode( 3342): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3342): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3342): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Native Method)
,D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3342): StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2,
D/StrictMode( 3342): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3342): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3342): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3342): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3342): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
,D/StrictMode( 3342): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3342): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3342): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3342): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3342): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3342): # via Binder call with stack:
D/StrictMode( 3342): android.os.StrictMode$LogStackTrace
D/StrictMode( 3342): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3342): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3342): ,	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3342): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3342): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3342): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3342): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3342): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3342): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.map.n.f.a(PG:323),
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3342): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3342): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3342): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364),
D/StrictMode( 3342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3342): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3342): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3342): ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3342): StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3342): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3342): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67),
D/StrictMode( 3342): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3342): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3342): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3342): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3342): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3342): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
,D/StrictMode( 3342): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3342): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
,D/StrictMode( 3342): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3342): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3342): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3342): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
,D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3342): StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3342): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3342): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3342): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3342): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3342): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3342): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3342): ,	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3342): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3342): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3342): ,	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3342): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3342): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3342): StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3342): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3342): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3342): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3342): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3342): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3342): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3342): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3342): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3342): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3342): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3342): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3342): StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3342): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3342): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3342): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3342): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3342): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3342): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3342): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3342): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3342): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3342): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3342): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3342): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3342): 	at com.google.android.apps.gmm.base.,app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3342): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3342): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3342): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3342): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3342): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3342): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset( 1098): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
W/com.google.a.a.a.b.a( 3342): Application name is not set. Call Builder#setApplicationName.
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2247392f:true
I/ActivityManager(  821): Killing 2874:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1431): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3324): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21af1f27:true
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3237): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1431): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LocalBluetoothProfileManager( 3324): Adding local A2DP profile
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3237): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3237): Accept thread started.
,D/LocalBluetoothProfileManager( 3324): Adding local HEADSET profile
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3324): Adding local MAP profile
D/BluetoothMap( 3324): Create BluetoothMap proxy object
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3324): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3324): finishStartingService: stopping service
,D/BluetoothA2dp( 3324): Proxy object connected
D/A2dpProfile( 3324): Bluetooth service connected
,D/BluetoothInputDevice( 3324): Proxy object connected
,D/HidProfile( 3324): Bluetooth service connected
,D/BluetoothPan( 3324): BluetoothPAN Proxy object connected
,D/PanProfile( 3324): Bluetooth service connected
D/BluetoothMap( 3324): Proxy object connected
,D/MapProfile( 3324): Bluetooth service connected
D/BluetoothMap( 3324): getConnectedDevices()
,D/BluetoothPbap( 3324): Proxy object connected
,D/PbapServerProfile( 3324): Bluetooth service connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 3324): Proxy object connected
,D/HeadsetProfile( 3324): Bluetooth service connected
,I/wpa_supplicant( 3253): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000,
E/WifiConfigStore(  821):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  821):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  821): will read network variables netId=0
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,I/wpa_supplicant( 3253): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3253): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3253): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3253): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 1
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
,E/WifiStateMachine(  821):  my bss beacon rx: 2
E/WifiStateMachine(  821):  RSSI mgmt: -52
E/WifiStateMachine(  821):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=2 tx=0 lost=0 retries=0
,E/WifiStateMachine(  821):  on_time : 0 tx_time=67 rx_time=121 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 3385): version 5.5.6 starting
,I/dhcpcd  ( 3385): wlan0: rebinding lease of 192.168.1.122,
,I/dhcpcd  ( 3385): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/jxcore-log( 3182): BLE supported!!
I/jxcore-log( 3182): 
,I/dhcpcd  ( 3385): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  821): Adding iface wlan0 to network 100
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  821): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1098): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,V/BackupManagerService(  821): Scheduling immediate backup pass
,I/ActivityManager(  821): Start proc 3425:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,V/BackupManagerService(  821): Running a backup pass
,V/BackupManagerService(  821): clearing pending backups
,V/PerformBackupTask(  821): Beginning backup of 14 targets
,D/PerformBackupTask(  821): invokeAgentForBackup on @pm@
V/BackupServiceBinder(  821): doBackup() invoked
,I/PMBA    (  821): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/AlarmManagerService(  821): Setting time of day to sec=1449832370
,W/AlarmManagerService(  821): Unable to set rtc to 1449832370: Invalid argument
,I/BackupRestoreController(  821): Getting widget state for user: 0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 11 Dec 2015 11:12:50 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449832370724], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449832370915]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1098): CM callback handler got msg 524290
,D/PhoneInterfaceManager( 1291): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1291): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,I/GoogleURLConnFactory( 1431): Using platform SSLCertificateSocketFactory
,D/GpsLocationProvider(  821): NTP server returned: 1449832370715 (Fri Dec 11 12:12:50 GMT+01:00 2015) reference: 148167 certainty: 9 system time offset: -104
,I/MusicStore( 3425): Database version: 120
,W/GmsBackupTransport( 1768): Unknown package in backup request: @pm@
V/GmsBackupTransport( 1768): starting performBackup for @pm@
,V/GmsBackupTransport( 1768): performBackup done for @pm@
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1809): [CredentialSyncAdapter] Unknown sync event.
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1431): Explicit concurrent mark sweep GC freed 16223(968KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 1.205ms total 26.829ms
,W/GLSActivity( 1431): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1431): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1431): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1431): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1431): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1431): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1431): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1768): Error sending final backup to server: 
W/GmsBackupTransport( 1768): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1768): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1768): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1768): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1768): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1768): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1768): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1768): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1768): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1768): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1768): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1768): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1768): 	... 1 more
,D/NetworkChangeNotifierAutoDetect( 1527): Network connectivity changed, type is: 2
,D/BackupManagerService(  821): Now staging backup of com.google.android.talk
,W/DriveInitializer( 1809): Background init thread started
,D/BackupManagerService(  821): Now staging backup of com.google.android.dialer
,I/ConfigFetchService( 1809): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigService( 1431): onCreate
,I/ConfigFetchService( 1809): running network task: configservice_periodic
,E/WakeLock( 1809): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1809): launchTask
,D/BackupManagerService(  821): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  821): Now staging backup of com.android.sharedstoragebackup
,W/ResourcesManager( 3425): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3425): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ConfigFetchService( 1809): service connected
,D/ConfigFetchService( 1809): ConfigApi connection successful.
,D/BackupManagerService(  821): Now staging backup of com.google.android.gm
,D/BackupManagerService(  821): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  821): Now staging backup of com.android.nfc
,D/BackupManagerService(  821): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  821): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  821): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  821): Now staging backup of com.google.android.calendar
,V/JNIHelp ( 3425): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/BackupManagerService(  821): Now staging backup of com.android.vending
,D/BackupManagerService(  821): Now staging backup of android
,I/art     (  821): Explicit concurrent mark sweep GC freed 51232(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.811ms total 160.086ms
,W/DriveInitializer( 1809): Background init thread ended
,D/BackupManagerService(  821): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1768): Next backup will happen in 43199906 millis.
,I/BackupManagerService(  821): Backup pass finished.
,I/ProviderInstaller( 3425): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3425): GMSCore installation verified
,I/ConfigStore( 3425): Config Database version: 1
,I/MediaRouter( 3425): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3425): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3425): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 3425): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  821): Start proc 3488:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/GHttpClientFactory( 3425): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3425): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 3488): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3488): simOperator:  IMSI: null
,D/SprintDMReceiver( 3488): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1809): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1809): onCreate
,D/SystemUpdateService( 1809): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1809): active receiver: enabled
,E/HttpOperation( 2953): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at blb.a(PG:3937)
E/HttpOperation( 2953): 	at czp.a(PG:18188)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 12 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 14 more
,I/SystemUpdateService( 1809): showing system update notification
,V/GoogleAuthProtoRequest( 3255): [327] a.<init>: mAccountName set to: thalitester@gmail.com
,I/iu.SyncManager( 1809): SYNC; picasa accounts
,V/KeepSync( 3282): Connecting to GoogleApiClient
,D/NetworkLogImpl( 1809): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1809): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ValidateNoPeople(  821): skipping global notification
,I/iu.UploadsManager( 1809): num queued entries: 0
,I/iu.UploadsManager( 1809): num updated entries: 0
,V/SystemUpdateService( 1809): retry (wakeup: false) in 3599953 ms
,D/ChimeraCfgMgr( 1809): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.SyncManager( 1809): NEXT; no task
,D/SystemUpdateService( 1809): onDestroy
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  821): Start proc 3522:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 1809): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/HttpOperation( 2953): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at hec.a(PG:42)
E/HttpOperation( 2953): 	at hee.a(PG:102)
E/HttpOperation( 2953): 	at czr.a(PG:65)
E/HttpOperation( 2953): 	at kka.a(PG:108)
E/HttpOperation( 2953): 	at czp.a(PG:19176)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 15 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 17 more
E/ExperimentLoader( 2953): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): 	at jdm.a(PG:82)
E/ExperimentLoader( 2953): 	at jcs.o(PG:406)
E/ExperimentLoader( 2953): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2953): 	at jcs.i(PG:143)
E/ExperimentLoader( 2953): 	at hec.a(PG:42)
E/ExperimentLoader( 2953): 	at hee.a(PG:102)
E/ExperimentLoader( 2953): 	at czr.a(PG:65)
E/ExperimentLoader( 2953): 	at kka.a(PG:108)
E/ExperimentLoader( 2953): 	at czp.a(PG:19176)
E/ExperimentLoader( 2953): 	at czp.a(PG:9081)
E/ExperimentLoader( 2953): 	at czq.run(PG:1686)
E/ExperimentLoader( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2953): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2953): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2953): 	at jdm.a(PG:77)
E/ExperimentLoader( 2953): 	... 15 more
E/ExperimentLoader( 2953): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2953): 	at fal.a(PG:38)
E/ExperimentLoader( 2953): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2953): 	... 17 more
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1809): Using Auth Proxy for data requests.
,W/BaseAppContext( 1809): Using Auth Proxy for data requests.
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1809): [AccountUtils] Account not ready
W/Kids    ( 1809): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1809): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1809): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1809): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1809): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1809): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1809): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1809): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1809): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1809): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1809): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1809): 	at java.lang.Thread.run(Thread.java:818)
,E/ClientConnectionOperation( 1809): Handling authorization failure
E/ClientConnectionOperation( 1809): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1809): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1809): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1809): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1809): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1809): 	... 7 more
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/KeepSync( 3282): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,I/Babel   ( 2596): connection state changed from DISCONNECTED to CONNECTED
,W/ExperimentUpdateService( 3255): [327] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3255): [327] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3255): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3255): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3255): 	at com.a.a.k.run(SourceFile:110)
,I/art     ( 1431): Explicit concurrent mark sweep GC freed 31196(1719KB) AllocSpace objects, 4(87KB) LOS objects, 37% free, 26MB/42MB, paused 1.176ms total 25.765ms
,I/GAv4    ( 3522): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3522):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3522):   adb logcat -s GAv4
,I/ActivityManager(  821): Start proc 3552:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,W/GAv4    ( 3522): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/GCM     ( 1431): Connected
,D/GCM     ( 1431): Message class com.google.f.a.a.p
,W/GAv4    ( 3522): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 39158, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/GAv4    ( 3522): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 3552): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3552): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  821): Start proc 3570:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 3552): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3552): Installed default security provider GmsCore_OpenSSL
,E/KeepSync( 3282): IOException
E/KeepSync( 3282): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3282): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3282): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3282): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3282): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3282): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3282): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3282): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3282): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3282): 	... 10 more
W/KeepSync( 3282): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 39162, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Killing 2152:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/art     (  821): Explicit concurrent mark sweep GC freed 27178(1300KB) AllocSpace objects, 5(121KB) LOS objects, 32% free, 33MB/49MB, paused 1.154ms total 53.609ms
,I/WebViewFactory( 3522): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3522): Time to load native libraries: 2 ms (timestamps 9311-9313)
,I/LibraryLoader( 3522): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3522): Binding Chromium to main looper Looper (main, tid 1) {3a0f436c}
I/LibraryLoader( 3522): Expected native library version number "",actual native library version number ""
I/chromium( 3522): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3522): Initializing chromium process, singleProcess=true
W/art     ( 3522): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3522): ApplicationContext is null in ApplicationStatus
,E/YouTube MDX( 3552): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/chromium( 3522): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3522): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3522): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3522): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/dex2oat ( 3613): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1010720272.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-1010720272.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/AudioManagerAndroid( 3522): Requires BLUETOOTH permission
,I/dex2oat ( 3613): dex2oat took 71.060ms (threads: 4) arena alloc=124KB java alloc=12KB native alloc=1223KB free=6MB
,I/NSApplication( 3522): Starting up...
,I/ActivityManager(  821): Killing 1365:android.process.acore/u0a5 (adj 15): empty #17
,W/InstanceID/Rpc( 3552): Found 10011
,W/GAV2    ( 3570): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3570): Created application version: 3.6.8 (30608)
,I/ActivityManager(  821): Start proc 3687:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/BooksSync( 3570): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3570): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3570): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3570): Soft error
E/BooksSync( 3570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3570): Sync error
E/BooksSync( 3570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3570): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 39163, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Killing 3062:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3718:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
I/ActivityManager(  821): Killing 3085:com.android.musicfx/u0a18 (adj 15): empty #17
,E/SQLiteLog( 3718): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  821): Start proc 3738:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3738): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3738): Created com.android.providers.calendar.CalendarAlarmManager@19c4ef0a(com.android.providers.calendar.CalendarProvider2@256b037b)
,I/ActivityManager(  821): Killing 1847:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3761:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3718): PlayLogger.onLoggerConnected
,D/TimeService( 3761): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449832373689
D/        ( 3761): TimeServiceNative: User Time to be set is 1449832373689
D/QC-time-services( 3761): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3761): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3761): Lib:time_genoff_operation: pargs->ts_val = 1449832373689
D/QC-time-services(  372): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3761): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  372): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449832373689
D/QC-time-services(  372): Daemon:genoff_opr: Base = 2, val = 1449832373689, operation = 0
D/QC-time-services(  372): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/28/70 7:25:46
D/QC-time-services(  372): Daemon:Value read from RTC seconds = 10135546000
,D/QC-time-services(  372): Daemon:new time 1449832373689 
D/QC-time-services(  372): Daemon: delta 1439696827689 genoff 1439696827689 
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696827689 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  372): Updating the TOD offset
,D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696827689 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  372): Daemon:Update to modem bit set
E/QC-time-services( 3761): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  372): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  372): Daemon: Base = 2, Value being sent to MODEM = 1133867573689
I/ActivityManager(  821): Killing 3112:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,E/QC-time-services(  372): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  372): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  821): Start proc 3780:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/GAv4    ( 3780): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3780):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3780):   adb logcat -s GAv4
,W/GAv4    ( 3780): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3780): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3780): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  821): Killing 3016:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/art     ( 1809): Explicit concurrent mark sweep GC freed 14909(1147KB) AllocSpace objects, 16(256KB) LOS objects, 35% free, 28MB/44MB, paused 1.469ms total 60.772ms
,I/ActivityManager(  821): Killing 2698:com.android.vending/u0a19 (adj 15): empty #17
,I/CalendarProvider2( 3738): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3738): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,V/Herrevad( 1809): NQAS connected
,I/art     (  821): Explicit concurrent mark sweep GC freed 17137(700KB) AllocSpace objects, 4(346KB) LOS objects, 32% free, 33MB/49MB, paused 2.580ms total 92.361ms
,D/WifiService(  821): New client listening to asynchronous messages
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@7b8ce0}
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2596): UserRecoverableAuthException.
,E/Babel   ( 2596): eei: BadAuthentication
E/Babel   ( 2596): 	at eeg.a(Unknown Source)
E/Babel   ( 2596): 	at eeg.a(Unknown Source)
E/Babel   ( 2596): 	at eeg.a(Unknown Source)
E/Babel   ( 2596): 	at g.a(Unknown Source)
E/Babel   ( 2596): 	at cae.a(SourceFile:3089)
E/Babel   ( 2596): 	at cae.a(SourceFile:1131)
E/Babel   ( 2596): 	at cws.a(SourceFile:4333)
E/Babel   ( 2596): 	at cws.a(SourceFile:1419)
E/Babel   ( 2596): 	at crl.a(SourceFile:492)
E/Babel   ( 2596): 	at crl.a(SourceFile:1468)
E/Babel   ( 2596): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2596): 	at cas.b(SourceFile:106)
E/Babel   ( 2596): 	at cap.d(SourceFile:335)
E/Babel   ( 2596): 	at caq.run(SourceFile:81)
E/Babel   ( 2596): Error getting auth token
E/Babel   ( 2596): dvm
E/Babel   ( 2596): 	at g.a(Unknown Source)
E/Babel   ( 2596): 	at cae.a(SourceFile:3089)
E/Babel   ( 2596): 	at cae.a(SourceFile:1131)
E/Babel   ( 2596): 	at cws.a(SourceFile:4333)
E/Babel   ( 2596): 	at cws.a(SourceFile:1419)
E/Babel   ( 2596): 	at crl.a(SourceFile:492)
E/Babel   ( 2596): 	at crl.a(SourceFile:1468)
E/Babel   ( 2596): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2596): 	at cas.b(SourceFile:106)
E/Babel   ( 2596): 	at cap.d(SourceFile:335)
E/Babel   ( 2596): 	at caq.run(SourceFile:81)
,E/Babel   ( 2596): Account registration failed 1-Redacted-21
E/Babel   ( 2596): cyp: null -- null
E/Babel   ( 2596): 	at cae.a(SourceFile:3121)
E/Babel   ( 2596): 	at cae.a(SourceFile:1131)
E/Babel   ( 2596): 	at cws.a(SourceFile:4333)
E/Babel   ( 2596): 	at cws.a(SourceFile:1419)
E/Babel   ( 2596): 	at crl.a(SourceFile:492)
E/Babel   ( 2596): 	at crl.a(SourceFile:1468)
E/Babel   ( 2596): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2596): 	at cas.b(SourceFile:106)
E/Babel   ( 2596): 	at cap.d(SourceFile:335)
E/Babel   ( 2596): 	at caq.run(SourceFile:81)
,I/art     ( 2596): Note: end time exceeds epoch: 
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1431): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2596): Unexpected exception while authenticating.
E/Babel   ( 2596): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2596): 	at eeg.b(Unknown Source)
E/Babel   ( 2596): 	at eeg.b(Unknown Source)
E/Babel   ( 2596): 	at g.a(Unknown Source)
E/Babel   ( 2596): 	at cae.b(SourceFile:1146)
E/Babel   ( 2596): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2596): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2596): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2596): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 3738): (284) automatic index on view_events(_id)
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=34.41 rxSuccessRate=30.06 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=34.41 rxSuccessRate=30.06 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,I/ActivityManager(  821): Start proc 3829:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,I/MusicLeanback( 3425): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3425): Stop autocaching.
,I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 355us total 25.725ms
,W/ResourcesManager( 3829): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3829): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 336us total 14.520ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 318us total 15.334ms
,I/MultiDex( 3829): VM with version 2.1.0 has multidex support
I/MultiDex( 3829): install
I/MultiDex( 3829): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3829): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3829): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1431): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1431): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/WearableService( 3829): callingUid 10011, callindPid: 3829
,V/GmsCoreStatsServiceLauncher( 1809): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/LocationInitializer( 1809): Restart initialization of location
,E/MDM     ( 1768): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3425): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3425): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/art     ( 1431): Explicit concurrent mark sweep GC freed 19009(1072KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 27MB/43MB, paused 935us total 25.263ms
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 3570): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 3718): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  821): Start proc 3866:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/Finsky  ( 3866): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3866): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  821): Start proc 3902:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3866): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3866): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 3902): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3902): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 3866): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3866): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 3866): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/MultiDex( 3902): VM with version 2.1.0 has multidex support
I/MultiDex( 3902): install
I/MultiDex( 3902): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3902): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 3866): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ProviderInstaller( 3902): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1431): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1431): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1809): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1768): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1809): Restart initialization of location
,V/Finsky  ( 3866): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/ActivityManager(  821): Killing 3324:com.android.settings/1000 (adj 15): empty #17
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3866): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/art     (  821): Explicit concurrent mark sweep GC freed 18487(914KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 3.012ms total 118.558ms
,D/Finsky  ( 3866): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3866): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3866): [1] 5.onFinished: Scheduling replication attempt 3.
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3866): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3866): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/ConfigFetchTask( 1809): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WrPk_P1wn4eed6AzJ0Bu3kUKnm1gCjsiFtALk8jr-LJSsusIZRxUtHq9hxyg5yZ_oNv7xNZ2ok8F3M9bRHsQRFp-Y2CGFWtZ70YKsZWdWjHNyzkBHc78yMFzXIqFcSOmWC4JIjAbCjXPGZbAydSkrpxJeeeDpTKcrkCTShSOzdDXqwB2ht0KRPrvBykGGl7aVuJ823KskTElGYXkOmeMLA6_50Q0trkC-yxhnNnpg8KzoMVBA
,I/GoogleURLConnFactory( 1809): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3866): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3866): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3866): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3866): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/DeviceConnectionService( 1768): client connected with version: 7571000
,I/ActivityManager(  821): Killing 1527:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,I/ConfigFetchTask( 1809): updating config table for com.google.android.gms
,D/WifiService(  821): Client connection lost with reason: 4
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (259 us)
,I/ActivityManager(  821): Killing 3342:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,I/ConfigFetchService( 1809): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1809): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1809): GmsCore config value changed; rescheduling
I/ConfigFetchService( 1809): fetch service done; releasing wakelock
,I/ConfigFetchService( 1809): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1809): stopping self
,V/GoogleAuthProtoRequest( 3255): [328] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3255): [328] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3255): [328] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3255): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3255): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3255): 	at com.a.a.k.run(SourceFile:110)
,E/Ads     ( 1809): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  821): Display changed displayId=0
,D/Finsky  ( 3866): [389] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  821): Excessive delay in setPowerMode(): 259ms
,I/DreamManagerService(  821): Entering dreamland.
,I/PowerManagerService(  821): Dozing...
,I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 5,
,I/VacuumService( 1431): Vacuum at: now=1449832382329 tag=VacuumService
,E/native  (  821): do suspend false
,I/GoogleURLConnFactory( 1431): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@e6383f6}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=13.30 rxSuccessRate=12.63 targetRoamBSSID=any RSSI=-51
V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator( 1201): onFinishInput()
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
E/WifiStateMachine(  821): cancelDelayedScan -> 7
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/Finsky  ( 3866): [389] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
E/native  (  821): do suspend true
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1431): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1431): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1431): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1431): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1431): Explicit concurrent mark sweep GC freed 44859(2MB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 26MB/42MB, paused 2.182ms total 75.273ms
,E/Uploader( 1431): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1431): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1431): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1431): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431): No account for auth token provided
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@e6383f6}
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431): No account for auth token provided,
,I/art     (  821): Explicit concurrent mark sweep GC freed 25921(1252KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.771ms total 100.002ms
,I/ActivityManager(  821): Killing 3488:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3522:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1431): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1431): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1431): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1431): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431):  no longer exists, so no auth token.,
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1431): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1431): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1431): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1431): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1431): No account for auth token provided
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1431): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1431): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1431): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1431): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431): No account for auth token provided
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ConfigService( 1431): onDestroy
,E/Uploader( 1431): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1431): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1431): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1431): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1431): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1431): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1431): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1431): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1431): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1431): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431): No account for auth token provided
,W/Uploader( 1431): No account for auth token provided
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=15.50 rxSuccessRate=9.00 targetRoamBSSID=any RSSI=-51
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3866): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3866): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3866): [1] 5.onFinished: Scheduling replication attempt 4.
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3255): [329] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3255): [330] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3255): [329] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3255): [329] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3255): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3255): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3255): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3255): [330] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3255): [330] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3255): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3255): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3255): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3866): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3866): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3866): [1] 5.onFinished: Scheduling replication attempt 5.
,I/BooksSync( 3570): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3570): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/HttpOperation( 2953): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at blb.a(PG:3937)
E/HttpOperation( 2953): 	at czp.a(PG:18188)
E/HttpOperation( 2953): 	at czp.a(PG:9087)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 12 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 14 more
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3570): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3570): Soft error
E/BooksSync( 3570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3570): Sync error
E/BooksSync( 3570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3570): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 180337, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2953): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at blb.a(PG:3937)
E/HttpOperation( 2953): 	at czp.a(PG:18188)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 12 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 14 more
,V/KeepSync( 3282): Connecting to GoogleApiClient
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2953): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at hec.a(PG:42)
E/HttpOperation( 2953): 	at hee.a(PG:102)
E/HttpOperation( 2953): 	at czr.a(PG:65)
E/HttpOperation( 2953): 	at kka.a(PG:108)
E/HttpOperation( 2953): 	at czp.a(PG:19176)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 15 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 17 more
E/ExperimentLoader( 2953): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): 	at jdm.a(PG:82)
E/ExperimentLoader( 2953): 	at jcs.o(PG:406)
E/ExperimentLoader( 2953): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2953): 	at jcs.i(PG:143)
E/ExperimentLoader( 2953): 	at hec.a(PG:42)
E/ExperimentLoader( 2953): 	at hee.a(PG:102)
E/ExperimentLoader( 2953): 	at czr.a(PG:65)
E/ExperimentLoader( 2953): 	at kka.a(PG:108)
E/ExperimentLoader( 2953): 	at czp.a(PG:19176)
E/ExperimentLoader( 2953): 	at czp.a(PG:9081)
E/ExperimentLoader( 2953): 	at czq.run(PG:1686)
E/ExperimentLoader( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2953): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2953): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2953): 	at jdm.a(PG:77)
E/ExperimentLoader( 2953): 	... 15 more
E/ExperimentLoader( 2953): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2953): 	at fal.a(PG:38)
E/ExperimentLoader( 2953): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2953): 	... 17 more
,I/art     (  821): Explicit concurrent mark sweep GC freed 31546(1382KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.583ms total 82.252ms
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1809): Handling authorization failure
E/ClientConnectionOperation( 1809): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1809): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1809): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1809): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1809): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1809): 	... 7 more
,V/KeepSync( 3282): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 149036, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3282): IOException,
E/KeepSync( 3282): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3282): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3282): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3282): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3282): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305),
E/KeepSync( 3282): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3282): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3282): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3282): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
,E/KeepSync( 3282): 	... 10 more
W/KeepSync( 3282): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 181946, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1431): Explicit concurrent mark sweep GC freed 87946(5MB) AllocSpace objects, 8(642KB) LOS objects, 36% free, 28MB/44MB, paused 2.091ms total 62.055ms
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3866): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3866): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3866): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1201): run()
I/Keyboard.Facilitator( 1201): flushDynamicLanguageModels()
,I/ConfigService( 1431): onCreate
,I/ConfigService( 1431): onDestroy
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2953): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at blb.a(PG:3937)
E/HttpOperation( 2953): 	at czp.a(PG:18188)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/HttpOperation( 2953): 	at jdj.a(PG:4091)
,E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	,at jdm.a(PG:77)
E/HttpOperation( 2953): ,	... 12 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 14 more
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2953): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at hec.a(PG:42)
E/HttpOperation( 2953): 	at hee.a(PG:102)
E/HttpOperation( 2953): 	at czr.a(PG:65)
E/HttpOperation( 2953): 	at kka.a(PG:108)
E/HttpOperation( 2953): 	at czp.a(PG:19176)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 15 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 17 more
E/ExperimentLoader( 2953): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): 	at jdm.a(PG:82)
E/ExperimentLoader( 2953): 	at jcs.o(PG:406)
E/ExperimentLoader( 2953): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2953): 	at jcs.i(PG:143)
E/ExperimentLoader( 2953): 	at hec.a(PG:42)
E/ExperimentLoader( 2953): 	at hee.a(PG:102)
E/ExperimentLoader( 2953): 	at czr.a(PG:65)
E/ExperimentLoader( 2953): 	at kka.a(PG:108)
E/ExperimentLoader( 2953): 	at czp.a(PG:19176)
E/ExperimentLoader( 2953): 	at czp.a(PG:9081)
E/ExperimentLoader( 2953): 	at czq.run(PG:1686)
E/ExperimentLoader( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2953): ,	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2953): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2953): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2953): 	,at jdm.a(PG:77)
E/ExperimentLoader( 2953): 	... 15 more
E/ExperimentLoader( 2953): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2953): 	at fal.a(PG:38)
E/ExperimentLoader( 2953): 	at jdj.a(PG:4089),
E/ExperimentLoader( 2953): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 240533, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3255): [331] a.<init>: mAccountName set to: thalitester@gmail.com,
,V/GoogleAuthProtoRequest( 3255): [332] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3255): [332] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3255): [332] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3255): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3255): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3255): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3255): [331] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3255): [331] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3255): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3255): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3255): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 3570): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3282): Connecting to GoogleApiClient
,I/BooksConfig( 3570): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1809): Handling authorization failure
E/ClientConnectionOperation( 1809): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1809): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1809): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1809): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1809): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1809): 	... 7 more
,V/KeepSync( 3282): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3570): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3570): Soft error
E/BooksSync( 3570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3570): Sync error
E/BooksSync( 3570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3570): Finished books sync
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 269154, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3282): IOException
E/KeepSync( 3282): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3282): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3282): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3282): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3282): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3282): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3282): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3282): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3282): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3282): 	... 10 more
W/KeepSync( 3282): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 274519, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3182): Connected to the server!
I/jxcore-log( 3182): 
,I/chromium( 3182): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,I/art     (  821): Explicit concurrent mark sweep GC freed 35877(1574KB) AllocSpace objects, 12(757KB) LOS objects, 31% free, 34MB/50MB, paused 1.879ms total 81.795ms
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2953): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at blb.a(PG:3937)
E/HttpOperation( 2953): 	at czp.a(PG:18188)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 12 more
,E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 14 more
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2953): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at hec.a(PG:42)
E/HttpOperation( 2953): 	at hee.a(PG:102)
E/HttpOperation( 2953): 	at czr.a(PG:65)
E/HttpOperation( 2953): 	at kka.a(PG:108)
E/HttpOperation( 2953): 	at czp.a(PG:19176)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 15 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 17 more
,E/ExperimentLoader( 2953): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): 	at jdm.a(PG:82)
E/ExperimentLoader( 2953): 	at jcs.o(PG:406)
E/ExperimentLoader( 2953): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2953): 	at jcs.i(PG:143)
E/ExperimentLoader( 2953): 	at hec.a(PG:42)
E/ExperimentLoader( 2953): 	at hee.a(PG:102)
E/ExperimentLoader( 2953): 	at czr.a(PG:65)
E/ExperimentLoader( 2953): 	at kka.a(PG:108)
E/ExperimentLoader( 2953): 	at czp.a(PG:19176)
E/ExperimentLoader( 2953): 	at czp.a(PG:9081)
E/ExperimentLoader( 2953): 	at czq.run(PG:1686)
E/ExperimentLoader( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2953): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2953): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2953): 	at jdm.a(PG:77)
E/ExperimentLoader( 2953): 	... 15 more
E/ExperimentLoader( 2953): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2953): 	at fal.a(PG:38)
E/ExperimentLoader( 2953): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2953): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 332147, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3255): [333] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3255): [334] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3255): [333] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3255): [333] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3255): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3255): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3255): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3255): [334] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3255): [334] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3255): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3255): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3255): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 3570): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3570): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3570): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3570): Soft error
E/BooksSync( 3570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3570): Sync error,
E/BooksSync( 3570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3570): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 419848, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,I/art     ( 1431): Explicit concurrent mark sweep GC freed 53538(2MB) AllocSpace objects, 19(2MB) LOS objects, 37% free, 27MB/43MB, paused 1.202ms total 45.526ms
,V/KeepSync( 3282): Connecting to GoogleApiClient
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1809): Handling authorization failure
E/ClientConnectionOperation( 1809): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1809): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1809): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1809): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1809): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1809): 	... 7 more
,V/KeepSync( 3282): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3282): IOException
E/KeepSync( 3282): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3282): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3282): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3282): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3282): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3282): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3282): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3282): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3282): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3282): 	... 10 more
W/KeepSync( 3282): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 429684, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1431): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1431): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1431): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1431): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1431): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1431): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1431): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3866): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3866): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3866): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3866): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3866): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3866): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3866): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3866): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2953): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at blb.a(PG:3937)
E/HttpOperation( 2953): 	at czp.a(PG:18188)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 12 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 14 more
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2953): [getmobileexperiments] Unexpected exception
,E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): ,	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
,E/HttpOperation( 2953): 	at hec.a(PG:42)
E/HttpOperation( 2953): 	at hee.a(PG:102)
E/HttpOperation( 2953): 	at czr.a(PG:65)
E/HttpOperation( 2953): 	at kka.a(PG:108),
E/HttpOperation( 2953): 	at czp.a(PG:19176)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686),
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): ,	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 15 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
,E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 17 more,
E/ExperimentLoader( 2953): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): 	at jdm.a(PG:82)
,E/ExperimentLoader( 2953): 	at jcs.o(PG:406)
E/ExperimentLoader( 2953): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2953): 	at jcs.i(PG:143)
,E/ExperimentLoader( 2953): 	at hec.a(PG:42)
E/ExperimentLoader( 2953): 	at hee.a(PG:102)
E/ExperimentLoader( 2953): 	,at czr.a(PG:65)
E/ExperimentLoader( 2953): 	at kka.a(PG:108)
E/ExperimentLoader( 2953): 	at czp.a(PG:19176)
E/ExperimentLoader( 2953): 	at czp.a(PG:9081),
E/ExperimentLoader( 2953): 	at czq.run(PG:1686)
E/ExperimentLoader( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ExperimentLoader( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2953): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2953): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2953): 	at jdm.a(PG:77)
E/ExperimentLoader( 2953): 	... 15 more
E/ExperimentLoader( 2953): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2953): 	at fal.a(PG:38)
E/ExperimentLoader( 2953): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2953): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 485422, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,I/art     (  821): Explicit concurrent mark sweep GC freed 40428(1791KB) AllocSpace objects, 8(410KB) LOS objects, 31% free, 34MB/50MB, paused 2.589ms total 59.668ms
,I/BooksSync( 3570): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3570): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3570): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3570): Soft error
E/BooksSync( 3570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3570): Sync error
E/BooksSync( 3570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3570): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 662727, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,V/KeepSync( 3282): Connecting to GoogleApiClient
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1809): Handling authorization failure
E/ClientConnectionOperation( 1809): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1809): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1809): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1809): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1809): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1809): 	... 7 more
,V/KeepSync( 3282): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3282): IOException
E/KeepSync( 3282): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3282): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3282): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3282): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3282): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3282): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3282): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3282): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3282): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3282): 	... 10 more
W/KeepSync( 3282): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 712458, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2953): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at blb.a(PG:3937)
E/HttpOperation( 2953): 	at czp.a(PG:18188)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 12 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 14 more
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2953): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at hec.a(PG:42)
E/HttpOperation( 2953): 	at hee.a(PG:102)
E/HttpOperation( 2953): 	at czr.a(PG:65)
E/HttpOperation( 2953): 	at kka.a(PG:108)
E/HttpOperation( 2953): 	at czp.a(PG:19176)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 15 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 17 more
E/ExperimentLoader( 2953): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 2953): 	at jdm.a(PG:82)
E/ExperimentLoader( 2953): 	at jcs.o(PG:406)
E/ExperimentLoader( 2953): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2953): 	at jcs.i(PG:143)
E/ExperimentLoader( 2953): 	at hec.a(PG:42)
E/ExperimentLoader( 2953): 	at hee.a(PG:102)
E/ExperimentLoader( 2953): 	at czr.a(PG:65)
E/ExperimentLoader( 2953): 	at kka.a(PG:108)
E/ExperimentLoader( 2953): 	,at czp.a(PG:19176)
E/ExperimentLoader( 2953): 	at czp.a(PG:9081)
E/ExperimentLoader( 2953): 	at czq.run(PG:1686)
E/ExperimentLoader( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2953): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2953): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2953): 	at jdm.a(PG:77)
E/ExperimentLoader( 2953): 	... 15 more
E/ExperimentLoader( 2953): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2953): 	at fal.a(PG:38)
E/ExperimentLoader( 2953): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2953): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 763621, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/Finsky  ( 3866): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GoogleAuthProtoRequest( 3255): [335] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3255): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1431): Explicit concurrent mark sweep GC freed 56801(2MB) AllocSpace objects, 8(882KB) LOS objects, 36% free, 27MB/43MB, paused 2.387ms total 42.680ms
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 3866): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3255): [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3255): [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3255): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3255): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3255): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3255): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3255): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3255): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3255): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3255): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3866): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3866): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3866): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3866): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3866): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1768): client connected with version: 7571000
,I/art     (  821): Explicit concurrent mark sweep GC freed 32748(1436KB) AllocSpace objects, 7(394KB) LOS objects, 31% free, 34MB/50MB, paused 2.361ms total 88.096ms
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3866): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3866): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3866): [1] 5.onFinished: Scheduling replication attempt 1.
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3866): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3866): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3866): [1] 5.onFinished: Scheduling replication attempt 2.
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3866): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3866): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3866): [1] 5.onFinished: Scheduling replication attempt 3.
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3866): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 3866): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3866): [1] 5.onFinished: Scheduling replication attempt 4.
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3866): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3866): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3866): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3866): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3866): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3866): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3237): Stopping oneshot timer
,D/GCM     ( 1431): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,I/BooksSync( 3570): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3570): GmsCore Version = 7.8.99 (2134222-430),
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1431): Explicit concurrent mark sweep GC freed 63728(3MB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 26MB/42MB, paused 2.276ms total 65ms
,E/BooksAccountManager( 3570): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3570): Soft error
E/BooksSync( 3570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3570): Sync error
E/BooksSync( 3570): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3570): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3570): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1148052, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,V/KeepSync( 3282): Connecting to GoogleApiClient
,I/art     (  821): Explicit concurrent mark sweep GC freed 36002(1645KB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 1.469ms total 96.764ms
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1809): Handling authorization failure
E/ClientConnectionOperation( 1809): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1809): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1809): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1809): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1809): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1809): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1809): 	... 7 more
,V/KeepSync( 3282): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3282): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3282): IOException
E/KeepSync( 3282): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3282): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3282): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3282): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3282): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3282): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3282): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3282): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3282): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3282): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3282): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3282): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3282): 	... 10 more
W/KeepSync( 3282): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1247293, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2953): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at blb.a(PG:3937)
E/HttpOperation( 2953): 	at czp.a(PG:18188)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 12 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 14 more
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2953): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2953): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2953): 	at jdm.a(PG:82)
E/HttpOperation( 2953): 	at jcs.o(PG:406)
E/HttpOperation( 2953): 	at jcn.a(PG:1379)
E/HttpOperation( 2953): 	at jcs.i(PG:143)
E/HttpOperation( 2953): 	at hec.a(PG:42)
E/HttpOperation( 2953): 	at hee.a(PG:102)
E/HttpOperation( 2953): 	at czr.a(PG:65)
E/HttpOperation( 2953): 	at kka.a(PG:108)
E/HttpOperation( 2953): 	at czp.a(PG:19176)
E/HttpOperation( 2953): 	at czp.a(PG:9081)
E/HttpOperation( 2953): 	at czq.run(PG:1686)
E/HttpOperation( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2953): 	at jdj.a(PG:4091)
E/HttpOperation( 2953): 	at jdj.a(PG:1125)
E/HttpOperation( 2953): 	at jdm.a(PG:77)
E/HttpOperation( 2953): 	... 15 more
E/HttpOperation( 2953): Caused by: faj: BadAuthentication
E/HttpOperation( 2953): 	at fal.a(PG:38)
E/HttpOperation( 2953): 	at jdj.a(PG:4089)
E/HttpOperation( 2953): 	... 17 more
,E/ExperimentLoader( 2953): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2953): 	at jdm.a(PG:82)
E/ExperimentLoader( 2953): 	at jcs.o(PG:406)
E/ExperimentLoader( 2953): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2953): 	at jcs.i(PG:143)
E/ExperimentLoader( 2953): 	at hec.a(PG:42)
E/ExperimentLoader( 2953): 	at hee.a(PG:102)
E/ExperimentLoader( 2953): 	at czr.a(PG:65)
E/ExperimentLoader( 2953): 	at kka.a(PG:108)
E/ExperimentLoader( 2953): 	at czp.a(PG:19176)
E/ExperimentLoader( 2953): 	at czp.a(PG:9081)
E/ExperimentLoader( 2953): 	at czq.run(PG:1686)
E/ExperimentLoader( 2953): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2953): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2953): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2953): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2953): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2953): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2953): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2953): 	at jdm.a(PG:77)
E/ExperimentLoader( 2953): 	... 15 more
E/ExperimentLoader( 2953): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2953): 	at fal.a(PG:38)
E/ExperimentLoader( 2953): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2953): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1289896, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3255): [337] a.<init>: mAccountName set to: thalitester@gmail.com
,I/EventLogService( 1809): Opted in for usage reporting
,I/EventLogService( 1809): Aggregate from 1449831834967 (log), 1449831834967 (data)
,V/GoogleAuthProtoRequest( 3255): [338] a.<init>: mAccountName set to: thalitester@gmail.com
,W/EventLogAggregator( 1809): Unknown tag: snet_gcore
,W/EventLogAggregator( 1809): Unknown tag: snet_launch_service
,I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1431): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1431): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1431): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1431): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ServiceDumpSys( 1809): dumping service [account]
,V/GLSActivity( 1431): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3255): [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3255): [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3255): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3255): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3255): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3255): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3255): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3255): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3255): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3255): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3255): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3255): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  821): Prepared write state in 17ms
,I/ProcessStatsService(  821): Prepared write state in 19ms
,I/ProcessStatsService(  821): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-09-51.bin
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3237): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3237): Stopping oneshot timer
,TIME-OUT KILL (timeout was 1800000ms)
```
