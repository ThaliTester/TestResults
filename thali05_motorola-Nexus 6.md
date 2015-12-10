#### Test 506502784dae475_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2698): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2698): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2698): [1] 5.onFinished: Scheduling replication attempt 2.
,D/AndroidRuntime( 3156): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3156): CheckJNI is OFF
D/AndroidRuntime( 3156): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{21aa6c22 token=Token{368985ed ActivityRecord{1cef0c04 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3156): Shutting down VM
V/WindowManager(  820): Adding window Window{3911eb0f u0 Starting com.test.thalitest} at 3 of 8 (after Window{28f81ef0 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1525): Closing mic
I/MicrophoneInputStream( 1525): mic_close com.google.android.apps.gsa.speech.audio.u@29a10eb1
I/ActivityManager(  820): Start proc 3170:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1525): Hotword detection finished
I/HotwordRecognitionRnr( 1525): Stopping hotword detection.
I/ActivityManager(  820): Killing 2657:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658905875
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/ActivityManager(  820): Killing 2789:com.google.android.gm.exchange/u0a77 (adj 15): empty #18,
,I/WebViewFactory( 3170): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3170): Time to load native libraries: 2 ms (timestamps 459-461)
I/LibraryLoader( 3170): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3170): Binding Chromium to main looper Looper (main, tid 1) {3dfb8f90}
I/LibraryLoader( 3170): Expected native library version number "",actual native library version number ""
I/chromium( 3170): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3170): Initializing chromium process, singleProcess=true
,W/art     ( 3170): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3170): ApplicationContext is null in ApplicationStatus
,W/chromium( 3170): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3170): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3170): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
,E/libEGL  ( 3170): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3170): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fc9b5ff:true
,D/BluetoothAdapter( 3170): 754114763: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3170): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3170): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3170): CordovaWebView is running on device made by: motorola
,W/art     ( 3170): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3170): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3170): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3170): Validating map...
,V/WindowManager(  820): Adding window Window{2e421cef u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{3911eb0f u0 Starting com.test.thalitest})
,W/chromium( 3170): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3170): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3170): Enabling debug mode 0
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +1s45ms (total +1m47s775ms)
,I/Keyboard.Facilitator( 1214): onFinishInput()
,W/BindingManager( 3170): Cannot call determinedVisibility() - never saw a connection for the pid: 3170
,D/JsMessageQueue( 3170): Set native->JS mode to OnlineEventsBridgeMode
,I/kickstart(  871): STATUS: Received file 'm9kefs2'
I/kickstart(  871): STATUS: 950272 bytes transferred in 0.987067 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed
,D/jxcore_app_log( 3170): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576198912
D/JX-Cordova( 3170): jxcore cordova android initializing
,W/jxcore-log( 3170): Initializing JXcore engine
W/jxcore-log( 3170): JXcore engine is ready
,W/jxcore-log( 3170): Starting JXcore engine
,W/.test.thalitest( 3170): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12971]" dev="sockfs" ino=12971 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3170): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3170): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13169]" dev="sockfs" ino=13169 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3170): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20866]" dev="sockfs" ino=20866 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3170): Platform android
W/jxcore-log( 3170): 
,W/jxcore-log( 3170): Process ARCH arm
W/jxcore-log( 3170): 
,I/jxcore-log( 3170): JXcore Cordova bridge is ready!
I/jxcore-log( 3170): 
,W/jxcore-log( 3170): JXcore engine is started
I/Choreographer( 3170): Skipped 128 frames!  The application may be doing too much work on its main thread.
I/chromium( 3170): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3170): Toggling radios to true
I/jxcore-log( 3170): 
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  820): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  820): Message: 1
D/BluetoothManagerService(  820): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  820): New client listening to asynchronous messages
,D/WifiService(  820): setWifiEnabled: true pid=3170, uid=10265
,E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3170): Radios toggled
I/jxcore-log( 3170): 
D/SoftapController(  354): Softap fwReload - Ok
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  820): Start proc 3228:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,D/WifiMonitor(  820): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3235): Successfully initialized wpa_supplicant
,I/ActivityManager(  820): Start proc 3246:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/art     (  820): Explicit concurrent mark sweep GC freed 20071(1008KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.267ms total 51.498ms
,W/ResourcesManager( 3228): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3235): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  820): Start proc 3272:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  820): Killing 2828:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/AdapterServiceConfig( 3228): Adding HeadsetService
,D/AdapterServiceConfig( 3228): Adding A2dpService
,D/AdapterServiceConfig( 3228): Adding HidService
D/AdapterServiceConfig( 3228): Adding HealthService
D/AdapterServiceConfig( 3228): Adding PanService
D/AdapterServiceConfig( 3228): Adding GattService
,D/AdapterServiceConfig( 3228): Adding BluetoothMapService
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32b11800:true
,D/BluetoothAdapterState( 3228): make
,I/bluedroid( 3228): init
I/BluetoothAdapterState( 3228): Entering OffState
,I/bte_conf( 3228): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3228): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3228): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3228): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3228): get_profile_interface socket
I/GKI_LINUX( 3228): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 3228): get_profile_interface map_client
D/BluetoothAdapterProperties( 3228): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  820): Stored Bluetooth name: Nexus 6
,D/BluetoothAdapterProperties( 3228): Name is: Nexus 6
,D/BluetoothManagerService(  820): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  820): Message: 40
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3228): config_hci_snoop_log
,D/BluetoothManagerService(  820): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  820): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3228): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3228): Setting state to 11
I/BluetoothAdapterState( 3228): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3228): make
,I/BluetoothBondStateMachine( 3228): StableState(): Entering Off State,
,I/BluetoothAdapterState( 3228): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/BluetoothAdapterService( 3228): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@233a3089
,D/HeadsetService( 3228): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3228): classInitNative: succeeds
D/HeadsetStateMachine( 3228): make
D/HeadsetStateMachine( 3228): max_hf_connections = 1
I/bluedroid( 3228): get_profile_interface handsfree
D/HeadsetStateMachine( 3228): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 3228): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@233a3089
D/BluetoothA2dp(  820): Proxy object connected
D/A2dpService( 3228): Received start request. Starting profile...
D/BluetoothA2dp( 1065): Proxy object connected
I/BluetoothAvrcpServiceJni( 3228): classInitNative: succeeds
I/bluedroid( 3228): get_profile_interface avrcp
E/RemoteController( 3228): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3228): classInitNative: succeeds
D/A2dpStateMachine( 3228): make
I/bluedroid( 3228): get_profile_interface a2dp
I/art     ( 1497): Explicit concurrent mark sweep GC freed 22221(1157KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.304ms total 22.120ms
I/GKI_LINUX( 3228): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothHidServiceJni( 3228): classInitNative: succeeds
,D/BluetoothAdapterService( 3228): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@233a3089
D/A2dpStateMachine( 3228): Enter Disconnected: -2
,D/BluetoothInputDevice( 1065): Proxy object connected
,D/HidService( 3228): Received start request. Starting profile...
I/bluedroid( 3228): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3228): classInitNative: succeeds
,D/BluetoothAdapterService( 3228): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@233a3089
D/HealthService( 3228): Received start request. Starting profile...
I/bluedroid( 3228): get_profile_interface health
,I/BluetoothPanServiceJni( 3228): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3228): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@233a3089
,D/PanService( 3228): Received start request. Starting profile...
D/BluetoothPan( 1065): BluetoothPAN Proxy object connected
D/BluetoothPanServiceJni( 3228): initializeNative(L110): pan,
I/bluedroid( 3228): get_profile_interface pan
I/BtGatt.JNI( 3228): classInitNative(L873): classInitNative: Success!
,D/BluetoothAdapterService( 3228): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@233a3089
D/BtGatt.DebugUtils( 3228): handleDebugAction() action=null
,D/BtGatt.GattService( 3228): Received start request. Starting profile...
D/BtGatt.GattService( 3228): start()
I/bluedroid( 3228): get_profile_interface gatt
D/BluetoothAdapterService( 3228): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@233a3089
D/BtGatt.AdvertiseManager( 3228): advertise manager created
,D/BluetoothAdapterService( 3228): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@233a3089
,D/BluetoothMap( 1065): Proxy object connected,
D/BluetoothMapService( 3228): Received start request. Starting profile...
D/BluetoothMapService( 3228): start()
,D/BluetoothMapEmailSettingsLoader( 3228): Found 0 applications
D/BluetoothMapEmailAppObserver( 3228): createReceiver()
,D/BluetoothMapEmailAppObserver( 3228): initObservers()
D/BluetoothMapEmailAppObserver( 3228): getEnabledAccountItems()
,D/HeadsetStateMachine( 3228): Proxy object connected
D/HeadsetStateMachine( 3228): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 3228): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3228): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3228): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3228): enable
I/GKI_LINUX( 3228): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3228): btu_task pending for preload complete event
I/bt_hci_bdroid( 3228): init
,I/bt_vendor( 3228): init,
I/bt_vnd_conf( 3228): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3228): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3228): userial_init
,I/ActivityManager(  820): Start proc 3313:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 9.749ms
,I/ActivityManager(  820): Killing 2758:com.google.android.gm/u0a78 (adj 15): empty #17
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 11.245ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 9.013ms
,I/bt_userial_vendor( 3228): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3228): device fd = 53 open
,D/bt_userial( 3228): Entering userial_read_thread()
,I/bt_hwcfg( 3228): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3228): Chipset BCM4354A2
,D/bt_hwcfg( 3228): Target name = [BCM4354A2]
I/bt_hwcfg( 3228): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,D/Tethering(  820): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3235): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3235): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  820): Loading config and enabling all networks 
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3756d178}
,E/WifiConfigStore(  820): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  820): Setting external_sim to 1
,W/Settings( 2626): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  820): Setting OUI to 92-68-C3
I/WifiNative-HAL(  820): startHal
D/wifi    (  820): setting scan oui 0xaec78250
D/WifiHAL (  820): Sending mac address OUI
,E/WifiStateMachine(  820): cancelDelayedScan -> 1
,W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
D/WifiScanningService(  820): SCAN_AVAILABLE : 3
D/RttService(  820): SCAN_AVAILABLE : 3
D/WifiScanningService(  820): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  820): startHal
D/RttService(  820): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  354): Setting iface cfg
D/wifi    (  820): getting scan capabilities on interface[0] = 0xaec78250
D/WifiHAL (  820): Creating message to get scan capablities; iface = 5
D/WifiHAL (  820): In GetCapabilities::handleResponse
D/WifiHAL (  820): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  820): StartedState
E/WifiP2pService(  820): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  820): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  820): p2pGetDeviceAddress
,D/WifiNative-HAL(  820): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/ActivityManager(  820): Killing 2349:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/wpa_supplicant( 3235): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/native  (  820): do suspend false
,I/ActivityManager(  820): Start proc 3332:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/bt_hwcfg( 3228): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3228): Settlement delay -- 100 ms
I/bt_hwcfg( 3228): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3228): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3228): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3228): vendor lib fwcfg completed
I/bt-btu  ( 3228): btu_task received preload complete event
,I/        ( 3228): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3228): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3228): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3228): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3228): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3228): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3228): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3228): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3228): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3228): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3228): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3228): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3228): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3228): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3228): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3228): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e01085 
E/bt-btm  ( 3228): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e01085 
,D/StrictMode( 3332): StrictMode policy violation; ~duration=308 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3332): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3332): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3332): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3332): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3332): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3332): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3332): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3332): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3332): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3332): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3332): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3332): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3332): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3332): StrictMode policy violation; ~duration=307 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3332): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3332): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3332): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3332): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3332): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3332): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3332): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3332): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3332): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3332): StrictMode policy violation; ~duration=304 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3332): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3332): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3332): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3332): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3332): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3332): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3332): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3332): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3332): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3332): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3332): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3332): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3332): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3332): StrictMode policy violation; ~duration=262 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3332): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3332): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3332): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3332): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3332): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3332): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3332): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3332): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3332): StrictMode policy violation; ~duration=245 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3332): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3332): ,	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3332): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3332): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3332): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3332): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3332): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3332): 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3332): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3332): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3332): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3332): 	at android.app.ActivityThread.main(ActivityThread.java:5254),
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3332): StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3332): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3332): ,	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3332): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3332): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3332): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3332): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3332): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3332): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3332): ,	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3332): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3332): # via Binder call with stack:
D/StrictMode( 3332): android.os.StrictMode$LogStackTrace
D/StrictMode( 3332): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3332): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3332): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3332): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3332): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3332): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3332): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3332): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3332): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
,D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3332): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3332): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3332): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3332): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3332): 	,at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3332): StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3332): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3332): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3332): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3332): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3332): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
,D/StrictMode( 3332): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3332): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3332): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3332): 	,at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3332): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3332): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,D/StrictMode( 3332): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3332): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3332): StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3332): 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3332): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3332): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3332): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3332): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3332): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3332): 	,at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3332): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3332): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3332): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3332): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3332): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3332): StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3332): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3332): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3332): 	at libcore.io.IoBridge.open(IoBridge.java:445),
D/StrictMode( 3332): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3332): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3332): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540),
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3332): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3332): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3332): 	at android.os.Looper.loop(Looper.java:135)
,D/StrictMode( 3332): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3332): StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3332): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137),
D/StrictMode( 3332): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3332): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3332): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3332): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3332): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3332): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3332): ,	at com.google.p.j.a(PG:121)
D/StrictMode( 3332): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3332): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3332): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3332): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587),
D/StrictMode( 3332): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3332): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3332): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3332): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151),
D/StrictMode( 3332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3332): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3332): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3332): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3332): ,	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 3332): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c5e5790:true
,I/ActivityManager(  820): Killing 2858:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/BluetoothAdapterProperties( 3228): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3228): Calling BTA_HhEnable
,E/bt-btif ( 3228): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3228): Address is:F8:CF:C5:D9:E5:61
,W/bt-btm  ( 3228): Stopping oneshot timer
,D/AuthorizationBluetoothService( 1497): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapterProperties( 3228): Name is: Nexus 6,
D/BluetoothManagerService(  820): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  820): Stored Bluetooth name: Nexus 6,
,D/BluetoothAdapterProperties( 3228): Scan Mode:20
D/BluetoothAdapterProperties( 3228): Discoverable Timeout:120
,D/bte_conf( 3228): Device ID record 1 : primary,
D/bte_conf( 3228):   vendorId            = 000f
D/bte_conf( 3228):   vendorIdSource      = 0001
D/bte_conf( 3228):   product             = 1200
D/bte_conf( 3228):   version             = 1436
D/bte_conf( 3228):   clientExecutableURL = 
D/bte_conf( 3228):   serviceDescription  = 
D/bte_conf( 3228):   documentationURL    = 
D/bte_conf( 3228): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3228): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothPanServiceJni( 3228): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 3228): ScanMode =  20
D/BluetoothAdapterProperties( 3228): State =  11
D/BluetoothAdapterProperties( 3228): Setting state to 12
I/BluetoothAdapterState( 3228): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterState( 3228): Entering On State
D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  820): Broadcasting onBluetoothStateChange(true) to 13 receivers.
D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothManagerService(  820): Creating new ProfileServiceConnections object for profile: 1
,D/BluetoothAdapterProperties( 3228): Scan Mode:21,
D/BluetoothAdapterProperties( 3228): Discoverable Timeout:120
D/BluetoothInputDevice( 1065): onBluetoothStateChange: up=true
D/BluetoothMap( 1065): onBluetoothStateChange: up=true
,D/BluetoothPan( 1065): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
,D/BluetoothA2dpSink( 1065): onBluetoothStateChange: up=true
E/BluetoothA2dpSink( 1065): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
,D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1065): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1277): onBluetoothStateChange: up=true
,D/BluetoothHeadsetClient( 1065): onBluetoothStateChange: up=true
E/bt_h4   ( 3228): vendor lib postload completed
,E/BluetoothHeadsetClient( 1065): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
,D/BluetoothA2dp( 1065): onBluetoothStateChange: up=true
,D/BluetoothAvrcpController( 1065): onBluetoothStateChange: up=true
,E/BluetoothAvrcpController( 1065): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothA2dp(  820): onBluetoothStateChange: up=true
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  820): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  820): Message: 40
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3228): onReceive
D/BluetoothMapService( 3228): STATE_ON
,D/BluetoothMapMasInstance( 3228): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3228): MAS initSocket()
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3228): Accepting socket connection...
,W/ContextImpl( 3313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c8b66fd:true
,D/LocalBluetoothProfileManager( 3313): Adding local A2DP profile
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/AuthorizationBluetoothService( 1497): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3313): Adding local HEADSET profile
,I/BtOppRfcommListener( 3228): Accept thread started.
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3313): Adding local MAP profile
D/BluetoothMap( 3313): Create BluetoothMap proxy object
D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3313): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3313): finishStartingService: stopping service
D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
,D/BluetoothA2dp( 3313): Proxy object connected
D/A2dpProfile( 3313): Bluetooth service connected
,D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
,D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset( 1065): Proxy object connected
D/BluetoothInputDevice( 3313): Proxy object connected
,D/BluetoothManagerService(  820): Message: 400
D/HidProfile( 3313): Bluetooth service connected
D/BluetoothHeadset( 1277): Proxy object connected
,D/BluetoothPan( 3313): BluetoothPAN Proxy object connected
D/PanProfile( 3313): Bluetooth service connected
D/BluetoothMap( 3313): Proxy object connected
D/MapProfile( 3313): Bluetooth service connected
D/BluetoothMap( 3313): getConnectedDevices()
,D/BluetoothPbap( 3313): Proxy object connected
,D/PbapServerProfile( 3313): Bluetooth service connected
,D/BluetoothManagerService(  820): Message: 400
,D/BluetoothHeadset( 3313): Proxy object connected
,D/HeadsetProfile( 3313): Bluetooth service connected
,I/wpa_supplicant( 3235): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN,
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  820):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  820):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  820): will read network variables netId=0,
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,I/wpa_supplicant( 3235): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3235): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3235): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3235): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING,
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 1,
,E/WifiStateMachine(  820):  WifiLinkLayerStats: ,
E/WifiStateMachine(  820):  my bss beacon rx: 1
E/WifiStateMachine(  820):  RSSI mgmt: -52
E/WifiStateMachine(  820):  BE :  rx=1 tx=3 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 0 tx_time=60 rx_time=136 scan_time=0
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/dhcpcd  ( 3374): version 5.5.6 starting
,I/dhcpcd  ( 3374): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3374): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3374): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 100
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  820): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  820):    accepting network in place of null
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,V/BackupManagerService(  820): Scheduling immediate backup pass
,D/PhoneInterfaceManager( 1277): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1277): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/ActivityManager(  820): Start proc 3411:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,V/BackupManagerService(  820): Running a backup pass
,V/BackupManagerService(  820): clearing pending backups
,V/PerformBackupTask(  820): Beginning backup of 14 targets
,D/AlarmManagerService(  820): Setting time of day to sec=1449751065
W/AlarmManagerService(  820): Unable to set rtc to 1449751065: Invalid argument
E/GpsLocationProvider(  820): No APN found to select.
,D/PerformBackupTask(  820): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  820): doBackup() invoked
,I/PMBA    (  820): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 12:37:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449751065887], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449751065871]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,V/GoogleAuthProtoRequest( 3246): [331] a.<init>: mAccountName set to: thalitester@gmail.com
,I/BackupRestoreController(  820): Getting widget state for user: 0
,D/GpsLocationProvider(  820): NTP server returned: 1449751065837 (Thu Dec 10 13:37:45 GMT+01:00 2015) reference: 149244 certainty: 10 system time offset: -70
,I/MusicStore( 3411): Database version: 120
,W/GmsBackupTransport( 1745): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1745): starting performBackup for @pm@
,V/GmsBackupTransport( 1745): performBackup done for @pm@
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Auth.Api.Credentials( 1780): [CredentialSyncAdapter] Unknown sync event.
,I/art     (  820): Explicit concurrent mark sweep GC freed 47942(2MB) AllocSpace objects, 5(121KB) LOS objects, 32% free, 33MB/49MB, paused 1.824ms total 88.987ms
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1497): Explicit concurrent mark sweep GC freed 9723(485KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 3.187ms total 24.348ms
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DriveInitializer( 1780): Background init thread started
,W/GLSActivity( 1497): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1497): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1497): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1497): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1497): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1497): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1497): 	at android.os.Binder.execTransact(Binder.java:446)
,W/DriveInitializer( 1780): Awaiting to be initialized
,W/GmsBackupTransport( 1745): Error sending final backup to server: 
W/GmsBackupTransport( 1745): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1745): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1745): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1745): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1745): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1745): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1745): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1745): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1745): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1745): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1745): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1745): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1745): 	... 1 more
,D/BackupManagerService(  820): Now staging backup of com.google.android.talk
,D/BackupManagerService(  820): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  820): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  820): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  820): Now staging backup of com.google.android.gm
D/BackupManagerService(  820): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  820): Now staging backup of com.android.nfc
,D/BackupManagerService(  820): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  820): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  820): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  820): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  820): Now staging backup of com.android.vending
,D/BackupManagerService(  820): Now staging backup of android
,W/ResourcesManager( 3411): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3411): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ExperimentUpdateService( 3246): [331] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3246): [331] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3246): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3246): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3246): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3246): 	at com.a.a.k.run(SourceFile:110)
,D/BackupManagerService(  820): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1745): Next backup will happen in 43199896 millis.
,I/BackupManagerService(  820): Backup pass finished.
,W/DriveInitializer( 1780): Background init thread ended
,V/JNIHelp ( 3411): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GoogleAuthProtoRequest( 3246): [332] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ProviderInstaller( 3411): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3411): GMSCore installation verified
,I/ConfigStore( 3411): Config Database version: 1
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/HttpOperation( 2945): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2945): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2945): 	at jdm.a(PG:82)
E/HttpOperation( 2945): 	at jcs.o(PG:406)
E/HttpOperation( 2945): 	at jcn.a(PG:1379)
E/HttpOperation( 2945): 	at jcs.i(PG:143)
E/HttpOperation( 2945): 	at blb.a(PG:3937)
E/HttpOperation( 2945): 	at czp.a(PG:18188)
E/HttpOperation( 2945): 	at czp.a(PG:9081)
E/HttpOperation( 2945): 	at czq.run(PG:1686)
E/HttpOperation( 2945): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2945): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2945): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2945): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2945): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2945): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2945): 	at jdj.a(PG:4091)
E/HttpOperation( 2945): 	at jdj.a(PG:1125)
E/HttpOperation( 2945): 	at jdm.a(PG:77)
E/HttpOperation( 2945): 	... 12 more
E/HttpOperation( 2945): Caused by: faj: BadAuthentication
E/HttpOperation( 2945): 	at fal.a(PG:38)
E/HttpOperation( 2945): 	at jdj.a(PG:4089)
E/HttpOperation( 2945): 	... 14 more
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3246): [332] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3246): [332] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3246): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3246): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3246): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3246): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1497): Vacuum at: now=1449751066500 tag=VacuumService
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2945): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2945): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2945): 	at jdm.a(PG:82)
E/HttpOperation( 2945): 	at jcs.o(PG:406)
E/HttpOperation( 2945): 	at jcn.a(PG:1379)
E/HttpOperation( 2945): 	at jcs.i(PG:143)
E/HttpOperation( 2945): 	at hec.a(PG:42)
E/HttpOperation( 2945): 	at hee.a(PG:102)
E/HttpOperation( 2945): 	at czr.a(PG:65)
E/HttpOperation( 2945): 	at kka.a(PG:108)
E/HttpOperation( 2945): 	at czp.a(PG:19176)
E/HttpOperation( 2945): 	at czp.a(PG:9081)
E/HttpOperation( 2945): 	at czq.run(PG:1686)
E/HttpOperation( 2945): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2945): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2945): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2945): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2945): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2945): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2945): 	at jdj.a(PG:4091)
E/HttpOperation( 2945): 	at jdj.a(PG:1125)
E/HttpOperation( 2945): 	at jdm.a(PG:77)
E/HttpOperation( 2945): 	... 15 more
E/HttpOperation( 2945): Caused by: faj: BadAuthentication
E/HttpOperation( 2945): 	at fal.a(PG:38)
E/HttpOperation( 2945): 	at jdj.a(PG:4089)
E/HttpOperation( 2945): 	... 17 more
,E/ExperimentLoader( 2945): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2945): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2945): 	at jdm.a(PG:82)
E/ExperimentLoader( 2945): 	at jcs.o(PG:406)
E/ExperimentLoader( 2945): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2945): 	at jcs.i(PG:143)
E/ExperimentLoader( 2945): 	at hec.a(PG:42)
E/ExperimentLoader( 2945): 	at hee.a(PG:102)
E/ExperimentLoader( 2945): 	at czr.a(PG:65)
E/ExperimentLoader( 2945): 	at kka.a(PG:108)
E/ExperimentLoader( 2945): 	at czp.a(PG:19176)
E/ExperimentLoader( 2945): 	at czp.a(PG:9081)
E/ExperimentLoader( 2945): 	at czq.run(PG:1686)
E/ExperimentLoader( 2945): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2945): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2945): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2945): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2945): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2945): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2945): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2945): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2945): 	at jdm.a(PG:77)
E/ExperimentLoader( 2945): 	... 15 more
E/ExperimentLoader( 2945): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2945): 	at fal.a(PG:38)
E/ExperimentLoader( 2945): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2945): 	... 17 more
,V/KeepSync( 3272): Connecting to GoogleApiClient
,I/MediaRouter( 3411): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3411): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3411): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 3411): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  820): Start proc 3478:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 36620, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GHttpClientFactory( 3411): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/SprintDMReceiver( 3478): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3478): simOperator:  IMSI: null
D/SprintDMReceiver( 3478): Not Sprint UICC, don't do anything.
,I/ActivityManager(  820): Start proc 3497:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
I/GoogleURLConnFactory( 3411): Using platform SSLCertificateSocketFactory
,I/SystemUpdateService( 1780): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1780): onCreate
,D/SystemUpdateService( 1780): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1780): active receiver: enabled
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,I/SystemUpdateService( 1780): showing system update notification
,I/jxcore-log( 3170): Test app app.js loaded
I/jxcore-log( 3170): 
I/Choreographer( 3170): Skipped 408 frames!  The application may be doing too much work on its main thread.
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/chromium( 3170): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1780): retry (wakeup: false) in 3599929 ms
,I/iu.SyncManager( 1780): SYNC; picasa accounts
,D/NetworkLogImpl( 1780): Loaded NetworkSpeedPredictor
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
I/iu.Environment( 1780): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1780): num queued entries: 0
I/iu.UploadsManager( 1780): num updated entries: 0
,I/iu.SyncManager( 1780): NEXT; no task
,V/KeepSync( 3272): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3272): (284) automatic index on blob_node(is_deleted)
,D/SystemUpdateService( 1780): onDestroy
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/SQLiteLog( 3272): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3272): (284) automatic index on blob_node(is_deleted)
,I/ActivityManager(  820): Start proc 3528:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/art     ( 1497): Explicit concurrent mark sweep GC freed 22379(1369KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.171ms total 43.860ms
,I/Babel   ( 2626): connection state changed from DISCONNECTED to CONNECTED
,I/GoogleURLConnFactory( 1497): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1497): No account for auth token provided
,I/GAv4    ( 3528): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3528):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3528):   adb logcat -s GAv4
,I/art     (  820): Explicit concurrent mark sweep GC freed 28548(1339KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.755ms total 50.501ms
,W/GAv4    ( 3528): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/GCM     ( 1497): Connected
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
D/GCM     ( 1497): Message class com.google.f.a.a.p
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
W/GAv4    ( 3528): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 3528): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/KeepSync( 3272): IOException
E/KeepSync( 3272): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3272): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3272): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3272): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3272): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3272): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3272): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3272): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3272): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3272): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3272): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3272): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3272): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3272): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3272): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3272): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3272): 	... 10 more
W/KeepSync( 3272): Sync result 2
,I/ActivityManager(  820): Killing 2200:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 36622, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/Uploader( 1497): No account for auth token provided
,W/GAV2    ( 3497): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3497): Created application version: 3.6.8 (30608)
,I/WebViewFactory( 3528): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LibraryLoader( 3528): Time to load native libraries: 2 ms (timestamps 645-647)
,I/LibraryLoader( 3528): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3528): Binding Chromium to main looper Looper (main, tid 1) {35a71a4d}
,I/LibraryLoader( 3528): Expected native library version number "",actual native library version number ""
I/chromium( 3528): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3528): Initializing chromium process, singleProcess=true
,W/art     ( 3528): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3528): ApplicationContext is null in ApplicationStatus
,I/BooksSync( 3497): Starting books sync for 61035162, extras: ade
,E/Uploader( 1497): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1497): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1497): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1497): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/chromium( 3528): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3528): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3528): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3528): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3528): Requires BLUETOOTH permission
,I/NSApplication( 3528): Starting up...
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  820): Killing 1391:android.process.acore/u0a5 (adj 15): empty #17
,I/BooksConfig( 3497): GmsCore Version = 7.8.99 (2134222-430)
,E/Uploader( 1497): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1497): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1497): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1497): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  820): Start proc 3606:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1497): No account for auth token provided
,E/BooksAccountManager( 3497): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3497): Soft error
E/BooksSync( 3497): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3497): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3497): Sync error
E/BooksSync( 3497): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3497): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3497): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36623, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 3076:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3054:com.google.android.partnersetup/u0a16 (adj 15): empty #18
,W/Uploader( 1497): No account for auth token provided
,W/Uploader( 1497): No account for auth token provided,
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1497): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1497): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1497): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1497): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1497): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1497): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1497): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1497): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1497): No account for auth token provided
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  820): Start proc 3623:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,I/ActivityManager(  820): Killing 1817:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 3623): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,E/Uploader( 1497): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1497): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1497): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1497): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1497): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1497): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  820): Start proc 3645:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/Uploader( 1497): No account for auth token provided
,W/ResourcesManager( 3645): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/Uploader( 1497): No account for auth token provided
,I/CalendarProvider2( 3645): Created com.android.providers.calendar.CalendarAlarmManager@3c907a53(com.android.providers.calendar.CalendarProvider2@3dfb8f90)
,I/ActivityManager(  820): Start proc 3668:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3623): PlayLogger.onLoggerConnected
,W/Uploader( 1497): No account for auth token provided
,I/ActivityManager(  820): Killing 3102:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/art     (  820): Explicit concurrent mark sweep GC freed 19567(849KB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 34MB/50MB, paused 2.099ms total 86.053ms
,W/Uploader( 1497): No account for auth token provided
,D/TimeService( 3668): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449751069375
D/        ( 3668): TimeServiceNative: User Time to be set is 1449751069375
D/QC-time-services( 3668): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3668): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3668): Lib:time_genoff_operation: pargs->ts_val = 1449751069375
D/QC-time-services( 3668): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  373): Daemon: Connection accepted:time_genoff
D/QC-time-services(  373): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449751069375
D/QC-time-services(  373): Daemon:genoff_opr: Base = 2, val = 1449751069375, operation = 0
D/QC-time-services(  373): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/27/70 8:50:42
D/QC-time-services(  373): Daemon:Value read from RTC seconds = 10054242000
,D/QC-time-services(  373): Daemon:new time 1449751069375 
D/QC-time-services(  373): Daemon: delta 1439696827375 genoff 1439696827375 
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696827375 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  373): Updating the TOD offset,
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696827375 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services( 3668): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  373): Daemon:Update to modem bit set
D/QC-time-services(  373): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  373): Daemon: Base = 2, Value being sent to MODEM = 1133786269375
,W/Uploader( 1497):  no longer exists, so no auth token.
,E/QC-time-services(  373): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  373): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  820): Start proc 3688:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  820): Killing 3010:com.android.defcontainer/u0a7 (adj 15): empty #17
,W/Uploader( 1497): No account for auth token provided
,I/GAv4    ( 3688): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3688):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3688):   adb logcat -s GAv4
,W/Uploader( 1497): No account for auth token provided
,W/GAv4    ( 3688): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3688): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3688): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Killing 2698:com.android.vending/u0a19 (adj 15): empty #17
,I/CalendarProvider2( 3645): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3645): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3756d178}
,I/art     ( 1780): Explicit concurrent mark sweep GC freed 15501(1219KB) AllocSpace objects, 19(304KB) LOS objects, 35% free, 28MB/44MB, paused 1.629ms total 57.315ms
,V/Herrevad( 1780): NQAS connected
,D/WifiService(  820): New client listening to asynchronous messages
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1497): Explicit concurrent mark sweep GC freed 52165(3MB) AllocSpace objects, 8(471KB) LOS objects, 36% free, 28MB/44MB, paused 718us total 25.050ms
,E/Babel   ( 2626): UserRecoverableAuthException.
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
,E/Babel   ( 2626): Error getting auth token
,E/Babel   ( 2626): dvm
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
E/Babel   ( 2626): cyp: null -- null
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
,I/art     ( 2626): Note: end time exceeds epoch: 
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1497): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
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
,E/SQLiteLog( 3645): (284) automatic index on view_events(_id)
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=44.22 rxSuccessRate=35.09 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=44.22 rxSuccessRate=35.09 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,I/ActivityManager(  820): Start proc 3734:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,I/MusicLeanback( 3411): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3411): Stop autocaching.
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 334us total 15.476ms
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 231us total 13.086ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 241us total 12.523ms
,W/ResourcesManager( 3734): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3734): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3734): VM with version 2.1.0 has multidex support
I/MultiDex( 3734): install
I/MultiDex( 3734): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3734): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3734): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1497): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/WearableService( 3734): callingUid 10011, callindPid: 3734
,D/AuthorizationBluetoothService( 1497): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1780): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1745): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1780): Restart initialization of location
,E/GmsUtils( 3411): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3411): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAV2    ( 3497): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  820): Start proc 3769:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,I/GAV2    ( 3623): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 3769): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3769): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  820): Start proc 3807:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3769): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3769): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 3807): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3807): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3807): VM with version 2.1.0 has multidex support
I/MultiDex( 3807): install
I/MultiDex( 3807): VM has multidex support, MultiDex support library is disabled.
,I/art     (  820): Explicit concurrent mark sweep GC freed 14237(666KB) AllocSpace objects, 8(882KB) LOS objects, 32% free, 33MB/49MB, paused 1.337ms total 71.072ms
,D/Finsky  ( 3769): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3769): [1] 2.run: Finished loading 1 libraries.
,V/JNIHelp ( 3807): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 3769): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3769): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ProviderInstaller( 3807): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1497): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1497): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1780): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1745): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1780): Restart initialization of location
,V/Finsky  ( 3769): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3769): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3769): [1] 5.onFinished: Scheduling replication attempt 3.
,D/Finsky  ( 3769): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3769): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3769): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3769): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 3769): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3769): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3769): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,I/ActivityManager(  820): Killing 3332:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/DeviceConnectionService( 1745): client connected with version: 7571000
E/lowmemorykiller(  260): Error writing /proc/3332/oom_score_adj; errno=22
,I/ActivityManager(  820): Killing 3313:com.android.settings/1000 (adj 15): empty #18
,D/Finsky  ( 3769): [390] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3769): [390] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  263): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (219 us)
,I/ActivityManager(  820): Killing 1525:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  820): Client connection lost with reason: 4
,I/ActivityManager(  820): Killing 3478:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS},
V/ActivityManager(  820): Display changed displayId=0
D/SurfaceFlinger(  263): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  263): hwc_setPowerMode: Setting mode 0 on display: 0
E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!,
W/DisplayManagerService(  820): Failed to notify process 3478 that displays changed, assuming it died.
W/DisplayManagerService(  820): android.os.TransactionTooLargeException
,W/DisplayManagerService(  820): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService(  820): 	at android.os.BinderProxy.transact(Binder.java:496)
W/DisplayManagerService(  820): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService(  820): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1094)
,W/DisplayManagerService(  820): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:932)
W/DisplayManagerService(  820): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:112)
W/DisplayManagerService(  820): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1027)
W/DisplayManagerService(  820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/DisplayManagerService(  820): 	at android.os.Looper.loop(Looper.java:135)
W/DisplayManagerService(  820): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService(  820): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,I/qdhwcomposer(  263): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  263): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  820): Excessive delay in setPowerMode(): 286ms
,I/DreamManagerService(  820): Entering dreamland.
,I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,I/PowerManagerService(  820): Dozing...
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 5
,E/native  (  820): do suspend false
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2700bd69}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=3.95 rxSuccessRate=4.51 targetRoamBSSID=any RSSI=-52
,I/Keyboard.Facilitator( 1214): onFinishInput()
,E/WifiStateMachine(  820): cancelDelayedScan -> 7
,E/native  (  820): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2700bd69}
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3d3cd3ee}
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3d3cd3ee}
,V/GoogleAuthProtoRequest( 3246): [333] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3246): [334] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1497): Explicit concurrent mark sweep GC freed 34320(1818KB) AllocSpace objects, 19(2MB) LOS objects, 37% free, 26MB/42MB, paused 1.465ms total 42.293ms
,I/art     (  820): Explicit concurrent mark sweep GC freed 31060(1543KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.294ms total 70.976ms
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3246): [334] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3246): [334] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3246): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3246): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3246): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3246): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3246): [333] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3246): [333] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3246): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3246): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3246): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3246): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3769): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3769): [1] 5.onFinished: Scheduling replication attempt 4.
,D/HeadsetStateMachine( 3228): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3228): Disconnected process message: 10, size: 0
,I/BooksSync( 3497): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3497): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/HttpOperation( 2945): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2945): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2945): 	at jdm.a(PG:82)
E/HttpOperation( 2945): 	at jcs.o(PG:406)
E/HttpOperation( 2945): 	at jcn.a(PG:1379)
E/HttpOperation( 2945): 	at jcs.i(PG:143)
E/HttpOperation( 2945): 	at blb.a(PG:3937)
E/HttpOperation( 2945): 	at czp.a(PG:18188)
E/HttpOperation( 2945): 	at czp.a(PG:9081)
E/HttpOperation( 2945): 	at czq.run(PG:1686)
E/HttpOperation( 2945): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2945): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2945): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2945): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2945): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2945): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2945): 	at jdj.a(PG:4091)
E/HttpOperation( 2945): 	at jdj.a(PG:1125)
E/HttpOperation( 2945): 	at jdm.a(PG:77)
E/HttpOperation( 2945): 	... 12 more
E/HttpOperation( 2945): Caused by: faj: BadAuthentication
E/HttpOperation( 2945): 	at fal.a(PG:38)
E/HttpOperation( 2945): 	at jdj.a(PG:4089)
E/HttpOperation( 2945): 	... 14 more
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3497): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3497): Soft error
E/BooksSync( 3497): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3497): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3497): Sync error
E/BooksSync( 3497): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3497): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3497): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 183108, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2945): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2945): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2945): 	at jdm.a(PG:82)
E/HttpOperation( 2945): 	at jcs.o(PG:406)
E/HttpOperation( 2945): 	at jcn.a(PG:1379)
E/HttpOperation( 2945): 	at jcs.i(PG:143)
E/HttpOperation( 2945): 	at hec.a(PG:42)
E/HttpOperation( 2945): 	at hee.a(PG:102)
E/HttpOperation( 2945): 	at czr.a(PG:65)
E/HttpOperation( 2945): 	at kka.a(PG:108)
E/HttpOperation( 2945): 	at czp.a(PG:19176)
E/HttpOperation( 2945): 	at czp.a(PG:9081)
E/HttpOperation( 2945): 	at czq.run(PG:1686)
E/HttpOperation( 2945): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2945): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2945): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2945): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2945): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2945): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2945): 	at jdj.a(PG:4091)
E/HttpOperation( 2945): 	at jdj.a(PG:1125)
E/HttpOperation( 2945): 	at jdm.a(PG:77)
E/HttpOperation( 2945): 	... 15 more
E/HttpOperation( 2945): Caused by: faj: BadAuthentication
E/HttpOperation( 2945): 	at fal.a(PG:38)
E/HttpOperation( 2945): 	at jdj.a(PG:4089)
E/HttpOperation( 2945): 	... 17 more
,E/ExperimentLoader( 2945): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2945): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2945): 	at jdm.a(PG:82)
E/ExperimentLoader( 2945): 	at jcs.o(PG:406)
E/ExperimentLoader( 2945): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2945): 	at jcs.i(PG:143)
,E/ExperimentLoader( 2945): 	at hec.a(PG:42)
E/ExperimentLoader( 2945): 	at hee.a(PG:102)
E/ExperimentLoader( 2945): 	at czr.a(PG:65)
E/ExperimentLoader( 2945): 	at kka.a(PG:108)
E/ExperimentLoader( 2945): 	at czp.a(PG:19176)
E/ExperimentLoader( 2945): 	at czp.a(PG:9081)
E/ExperimentLoader( 2945): 	at czq.run(PG:1686)
E/ExperimentLoader( 2945): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2945): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2945): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2945): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2945): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2945): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2945): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2945): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2945): 	at jdm.a(PG:77)
E/ExperimentLoader( 2945): 	... 15 more
E/ExperimentLoader( 2945): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2945): 	at fal.a(PG:38)
E/ExperimentLoader( 2945): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2945): 	... 17 more
,V/KeepSync( 3272): Connecting to GoogleApiClient
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 183014, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3272): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3272): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3272): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3272): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3272): IOException
E/KeepSync( 3272): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3272): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3272): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3272): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3272): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3272): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3272): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3272): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3272): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3272): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3272): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3272): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3272): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3272): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3272): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3272): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3272): 	... 10 more
W/KeepSync( 3272): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 183241, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3769): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3769): [1] 5.onFinished: Scheduling replication attempt 5.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1214): run()
,I/Keyboard.Facilitator( 1214): flushDynamicLanguageModels(),
,I/ConfigService( 1497): onCreate
,I/ConfigService( 1497): onDestroy
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3769): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3769): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 3228): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3228): Disconnected process message: 10, size: 0
,I/BooksSync( 3497): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3497): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3497): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3497): Soft error
E/BooksSync( 3497): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3497): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3497): Sync error
E/BooksSync( 3497): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3497): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3497): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 273512, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3246): [335] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3246): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  820): Explicit concurrent mark sweep GC freed 32964(1429KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.630ms total 77.368ms
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3246): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3246): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3246): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3246): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3246): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3246): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3246): [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3246): [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3246): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3246): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3246): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3246): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3246): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3246): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3272): Connecting to GoogleApiClient
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3272): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3272): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3272): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3272): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1497): Explicit concurrent mark sweep GC freed 45753(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.735ms total 47.864ms
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2945): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2945): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2945): 	at jdm.a(PG:82)
E/HttpOperation( 2945): 	at jcs.o(PG:406)
E/HttpOperation( 2945): 	at jcn.a(PG:1379)
E/HttpOperation( 2945): 	at jcs.i(PG:143)
E/HttpOperation( 2945): 	at blb.a(PG:3937)
E/HttpOperation( 2945): 	at czp.a(PG:18188)
E/HttpOperation( 2945): 	at czp.a(PG:9081)
E/HttpOperation( 2945): 	at czq.run(PG:1686)
E/HttpOperation( 2945): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2945): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2945): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2945): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2945): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2945): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2945): 	at jdj.a(PG:4091)
E/HttpOperation( 2945): 	at jdj.a(PG:1125)
E/HttpOperation( 2945): 	at jdm.a(PG:77)
E/HttpOperation( 2945): 	... 12 more
E/HttpOperation( 2945): Caused by: faj: BadAuthentication
E/HttpOperation( 2945): 	at fal.a(PG:38)
E/HttpOperation( 2945): 	at jdj.a(PG:4089)
E/HttpOperation( 2945): 	... 14 more
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1497): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1497): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1497): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1497): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1497): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2945): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2945): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2945): 	at jdm.a(PG:82)
E/HttpOperation( 2945): 	at jcs.o(PG:406)
E/HttpOperation( 2945): 	at jcn.a(PG:1379)
E/HttpOperation( 2945): 	at jcs.i(PG:143)
E/HttpOperation( 2945): 	at hec.a(PG:42)
E/HttpOperation( 2945): 	at hee.a(PG:102)
E/HttpOperation( 2945): 	at czr.a(PG:65)
E/HttpOperation( 2945): 	at kka.a(PG:108)
E/HttpOperation( 2945): 	at czp.a(PG:19176)
E/HttpOperation( 2945): 	at czp.a(PG:9081)
E/HttpOperation( 2945): 	at czq.run(PG:1686)
E/HttpOperation( 2945): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2945): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2945): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2945): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2945): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2945): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2945): 	at jdj.a(PG:4091)
E/HttpOperation( 2945): 	at jdj.a(PG:1125)
E/HttpOperation( 2945): 	at jdm.a(PG:77)
E/HttpOperation( 2945): 	... 15 more
E/HttpOperation( 2945): Caused by: faj: BadAuthentication
E/HttpOperation( 2945): 	at fal.a(PG:38)
E/HttpOperation( 2945): 	at jdj.a(PG:4089)
E/HttpOperation( 2945): 	... 17 more
E/KeepSync( 3272): IOException
E/KeepSync( 3272): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3272): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3272): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3272): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3272): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3272): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3272): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3272): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3272): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3272): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3272): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3272): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3272): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3272): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3272): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3272): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3272): 	... 10 more
W/KeepSync( 3272): Sync result 2
,E/ExperimentLoader( 2945): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2945): java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 2945): 	at jdm.a(PG:82)
E/ExperimentLoader( 2945): 	at jcs.o(PG:406)
E/ExperimentLoader( 2945): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2945): 	at jcs.i(PG:143)
E/ExperimentLoader( 2945): 	at hec.a(PG:42)
E/ExperimentLoader( 2945): 	at hee.a(PG:102)
E/ExperimentLoader( 2945): 	at czr.a(PG:65)
E/ExperimentLoader( 2945): 	at kka.a(PG:108)
E/ExperimentLoader( 2945): 	at czp.a(PG:19176)
E/ExperimentLoader( 2945): 	at czp.a(PG:9081)
E/ExperimentLoader( 2945): 	at czq.run(PG:1686)
E/ExperimentLoader( 2945): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2945): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2945): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2945): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2945): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2945): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2945): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2945): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2945): ,	at jdm.a(PG:77)
E/ExperimentLoader( 2945): 	... 15 more
E/ExperimentLoader( 2945): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2945): 	at fal.a(PG:38)
E/ExperimentLoader( 2945): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2945): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 275559, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 275678, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3228): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3228): Disconnected process message: 10, size: 0

```
