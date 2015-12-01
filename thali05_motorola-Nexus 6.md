#### Test 52320939cae1769_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2723): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2723): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2723): [1] 5.onFinished: Scheduling replication attempt 2.
,D/AndroidRuntime( 3203): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3203): CheckJNI is OFF
D/AndroidRuntime( 3203): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{12eb48f5 token=Token{2e51562c ActivityRecord{1a7509df u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3203): Shutting down VM
V/WindowManager(  823): Adding window Window{554e156 u0 Starting com.test.thalitest} at 3 of 8 (after Window{b634c81 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/MicrophoneInputStream( 1509): mic_close com.google.android.apps.gsa.speech.audio.u@13522be7
I/HotwordDetector( 1509): Closing mic
I/ActivityManager(  823): Start proc 3217:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1509): Stopping hotword detection.
I/HotwordRecognitionRnr( 1509): Hotword detection finished
I/ActivityManager(  823): Killing 2682:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659610387
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  823): Killing 2814:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  873): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  873): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  873): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/WebViewFactory( 3217): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3217): Time to load native libraries: 1 ms (timestamps 6031-6032)
I/LibraryLoader( 3217): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3217): Binding Chromium to main looper Looper (main, tid 1) {1a8af4a1}
,I/LibraryLoader( 3217): Expected native library version number "",actual native library version number ""
I/chromium( 3217): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3217): Initializing chromium process, singleProcess=true
,W/art     ( 3217): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3217): ApplicationContext is null in ApplicationStatus,
,W/chromium( 3217): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3217): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3217): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3217): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3217): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f064c06:true
,D/BluetoothAdapter( 3217): 851524061: getState() :  mService = null. Returning STATE_OFF,
,W/art     ( 3217): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3217): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3217): CordovaWebView is running on device made by: motorola
,W/art     ( 3217): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3217): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3217): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3217): Validating map...
,V/WindowManager(  823): Adding window Window{24ffc2b6 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{554e156 u0 Starting com.test.thalitest})
W/chromium( 3217): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3217): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3217): Enabling debug mode 0
,I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +806ms (total +1m42s953ms)
,I/Keyboard.Facilitator( 1214): onFinishInput()
,W/BindingManager( 3217): Cannot call determinedVisibility() - never saw a connection for the pid: 3217
,D/JsMessageQueue( 3217): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3217): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576264320
D/JX-Cordova( 3217): jxcore cordova android initializing
,I/kickstart(  873): STATUS: Received file 'm9kefs1'
I/kickstart(  873): STATUS: 950272 bytes transferred in 0.984052 seconds
I/kickstart(  873): STATUS: Successfully downloaded files from target 
,I/kickstart(  873): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  873): STATUS: Sahara protocol completed
,W/jxcore-log( 3217): Initializing JXcore engine
W/jxcore-log( 3217): JXcore engine is ready
,W/jxcore-log( 3217): Starting JXcore engine
,W/.test.thalitest( 3217): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12876]" dev="sockfs" ino=12876 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3217): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3217): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11029]" dev="sockfs" ino=11029 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3217): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19046]" dev="sockfs" ino=19046 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3217): Platform android
W/jxcore-log( 3217): 
W/jxcore-log( 3217): Process ARCH arm
W/jxcore-log( 3217): 
,I/jxcore-log( 3217): JXcore Cordova bridge is ready!
I/jxcore-log( 3217): 
W/jxcore-log( 3217): JXcore engine is started
I/Choreographer( 3217): Skipped 142 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3217): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3217): Toggling radios to true
I/jxcore-log( 3217): 
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  823): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  823): Message: 1
,D/BluetoothManagerService(  823): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  823): setWifiEnabled: true pid=3217, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  823): New client listening to asynchronous messages
,D/SoftapController(  354): Softap fwReload - Ok
I/jxcore-log( 3217): Radios toggled
I/jxcore-log( 3217): 
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiMonitor(  823): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  823): Start proc 3271:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,D/WifiMonitor(  823): startMonitoring(wlan0) with mConnected = false
E/WifiHW  (  823): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/ActivityManager(  823): Start proc 3288:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/wpa_supplicant( 3285): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3285): rfkill: Cannot open RFKILL control device
,I/art     (  823): Explicit concurrent mark sweep GC freed 18113(880KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.216ms total 60.784ms
,W/ResourcesManager( 3271): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/art     ( 1534): Explicit concurrent mark sweep GC freed 24081(1271KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 711us total 20.077ms
,I/ActivityManager(  823): Start proc 3315:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  823): Killing 2847:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 219us total 10.198ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 9.084ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 191us total 8.583ms
,D/AdapterServiceConfig( 3271): Adding HeadsetService
,D/AdapterServiceConfig( 3271): Adding A2dpService
,D/AdapterServiceConfig( 3271): Adding HidService
,D/AdapterServiceConfig( 3271): Adding HealthService
D/AdapterServiceConfig( 3271): Adding PanService
D/AdapterServiceConfig( 3271): Adding GattService
D/AdapterServiceConfig( 3271): Adding BluetoothMapService
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ddbd2cb:true
,D/BluetoothAdapterState( 3271): make
,I/bluedroid( 3271): init
I/BluetoothAdapterState( 3271): Entering OffState
,I/bte_conf( 3271): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3271): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3271): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3271): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3271): get_profile_interface socket
I/bluedroid( 3271): get_profile_interface map_client
,D/BluetoothManagerService(  823): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  823): Message: 40
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3271): config_hci_snoop_log
,I/GKI_LINUX( 3271): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService(  823): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  823): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterProperties( 3271): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothAdapterProperties( 3271): Name is: Nexus 6
D/BluetoothManagerService(  823): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  823): Stored Bluetooth name: Nexus 6
,D/BluetoothAdapterState( 3271): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3271): Setting state to 11
I/BluetoothAdapterState( 3271): Bluetooth adapter state changed: 10-> 11
,D/BluetoothBondStateMachine( 3271): make
,D/BluetoothManagerService(  823): Message: 60
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  823): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3271): StableState(): Entering Off State
,D/BluetoothAdapterService( 3271): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@393966c6
,D/HeadsetService( 3271): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3271): classInitNative: succeeds
D/HeadsetStateMachine( 3271): make
,I/BluetoothAdapterState( 3271): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3271): max_hf_connections = 1
I/bluedroid( 3271): get_profile_interface handsfree
D/HeadsetStateMachine( 3271): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3271): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@393966c6
,D/BluetoothA2dp(  823): Proxy object connected
,D/A2dpService( 3271): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3271): classInitNative: succeeds
,I/bluedroid( 3271): get_profile_interface avrcp
D/BluetoothA2dp( 1064): Proxy object connected
,E/RemoteController( 3271): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3271): classInitNative: succeeds
D/A2dpStateMachine( 3271): make
I/bluedroid( 3271): get_profile_interface a2dp
I/GKI_LINUX( 3271): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/A2dpStateMachine( 3271): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3271): classInitNative: succeeds
D/BluetoothAdapterService( 3271): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@393966c6
,D/HidService( 3271): Received start request. Starting profile...
I/bluedroid( 3271): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3271): classInitNative: succeeds
D/BluetoothAdapterService( 3271): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@393966c6
D/HealthService( 3271): Received start request. Starting profile...
,I/bluedroid( 3271): get_profile_interface health
I/BluetoothPanServiceJni( 3271): classInitNative(L105): succeeds
D/BluetoothInputDevice( 1064): Proxy object connected
D/BluetoothAdapterService( 3271): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@393966c6
,D/PanService( 3271): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3271): initializeNative(L110): pan
I/bluedroid( 3271): get_profile_interface pan
D/BluetoothPan( 1064): BluetoothPAN Proxy object connected
,I/BtGatt.JNI( 3271): classInitNative(L873): classInitNative: Success!
,D/BluetoothAdapterService( 3271): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@393966c6
,D/BtGatt.DebugUtils( 3271): handleDebugAction() action=null
D/BtGatt.GattService( 3271): Received start request. Starting profile...
D/BtGatt.GattService( 3271): start()
I/bluedroid( 3271): get_profile_interface gatt
,D/BluetoothAdapterService( 3271): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@393966c6
D/BtGatt.AdvertiseManager( 3271): advertise manager created
,D/BluetoothAdapterService( 3271): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@393966c6
,D/BluetoothMapService( 3271): Received start request. Starting profile...
D/BluetoothMap( 1064): Proxy object connected
D/BluetoothMapService( 3271): start()
,D/BluetoothMapEmailSettingsLoader( 3271): Found 0 applications
D/BluetoothMapEmailAppObserver( 3271): createReceiver()
,D/BluetoothMapEmailAppObserver( 3271): initObservers()
,D/BluetoothMapEmailAppObserver( 3271): getEnabledAccountItems(),
,D/HeadsetStateMachine( 3271): Proxy object connected
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3271): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3271): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3271): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3271): enable
I/GKI_LINUX( 3271): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3271): btu_task pending for preload complete event
I/bt_hci_bdroid( 3271): init
,I/bt_vendor( 3271): init
I/bt_vnd_conf( 3271): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3271): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3271): userial_init
,I/ActivityManager(  823): Start proc 3357:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  823): Killing 2783:com.google.android.gm/u0a78 (adj 15): empty #17
,I/bt_userial_vendor( 3271): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3271): device fd = 53 open
D/bt_userial( 3271): Entering userial_read_thread()
,I/bt_hwcfg( 3271): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3271): Chipset BCM4354A2
,D/bt_hwcfg( 3271): Target name = [BCM4354A2]
I/bt_hwcfg( 3271): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,D/Tethering(  823): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3285): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3285): Could not read interface p2p-dev-wlan0 flags: No such device
,I/ActivityManager(  823): Killing 2351:com.google.android.calendar/u0a37 (adj 15): empty #17,
,D/WifiConfigStore(  823): Loading config and enabling all networks 
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@fb4ac23}
,E/WifiConfigStore(  823): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  823): Start proc 3376:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/WifiNative-HAL(  823): Setting external_sim to 1
,D/WifiStateMachine(  823): Setting OUI to 92-68-C3
I/WifiNative-HAL(  823): startHal
,D/wifi    (  823): setting scan oui 0xb4b6ecd0
D/WifiHAL (  823): Sending mac address OUI
,W/Settings( 2627): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine(  823): cancelDelayedScan -> 1
,W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
,D/CommandListener(  354): Setting iface cfg
,D/WifiScanningService(  823): SCAN_AVAILABLE : 3
D/RttService(  823): SCAN_AVAILABLE : 3
D/WifiScanningService(  823): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  823): startHal
D/RttService(  823): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiP2pService(  823): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  823): startMonitoring(p2p0) with mConnected = true
D/wifi    (  823): getting scan capabilities on interface[0] = 0xb4b6ecd0
D/WifiHAL (  823): Creating message to get scan capablities; iface = 5
,D/WifiHAL (  823): In GetCapabilities::handleResponse
D/WifiHAL (  823): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  823): StartedState
,I/bt_hwcfg( 3271): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3271): Settlement delay -- 100 ms
I/bt_hwcfg( 3271): Setting fw settlement delay to 100 
,I/wpa_supplicant( 3285): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/native  (  823): do suspend false
D/WifiNative-HAL(  823): p2pGetDeviceAddress
,D/WifiNative-HAL(  823): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/bt_hwcfg( 3271): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg( 3271): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3271): vendor lib fwcfg completed
I/bt-btu  ( 3271): btu_task received preload complete event
,I/        ( 3271): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 3271): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3271): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3271): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3271): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3271): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3271): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3271): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3271): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3271): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3271): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3271): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3271): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3271): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3271): BTE_InitTraceLevels -- TRC_BTIF
,D/StrictMode( 3376): StrictMode policy violation; ~duration=245 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3376): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3376): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3376): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3376): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3376): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3376): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3376): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3376): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3376): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3376): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3376): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3376): StrictMode policy violation; ~duration=245 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3376): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3376): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3376): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3376): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3376): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3376): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3376): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3376): StrictMode policy violation; ~duration=243 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3376): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3376): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3376): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3376): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3376): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3376): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3376): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3376): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3376): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3376): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3376): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3376): StrictMode policy violation; ~duration=237 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3376): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3376): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3376): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3376): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3376): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3376): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3376): StrictMode policy violation; ~duration=232 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3376): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3376): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3376): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3376): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3376): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoade,r.java:77)
D/StrictMode( 3376): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3376): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3376): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3376): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3376): StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3376): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3376): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3376): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3376): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3376): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3376): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3376): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3376): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3376): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3376): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3376): # via Binder call with stack:
D/StrictMode( 3376): android.os.StrictMode$LogStackTrace
D/StrictMode( 3376): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3376): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3376): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3376): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3376): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3376): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3376): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3376): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3376): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java,:1012)
D/StrictMode( 3376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3376): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3376): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3376): StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3376): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3376): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3376): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3376): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3376): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3376): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3376): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3376): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3376): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3376): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3376): StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3376): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3376): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3376): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3376): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3376): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3376): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplicatio,n.onCreate(PG:84)
D/StrictMode( 3376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3376): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3376): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3376): StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3376): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3376): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3376): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3376): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3376): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3376): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3376): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3376): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3376): StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3376): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3376): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3376): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3376): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3376): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3376): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3376): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3376): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3376): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3376): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3376): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3376): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3376): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3376): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3376): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3376): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/bt-btm  ( 3271): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2d8d085 
E/bt-btm  ( 3271): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2d8d085 
W/com.google.a.a.a.b.a( 3376): Application name is not set. Call Builder#setApplicationName.
D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c917c9b:true
I/ActivityManager(  823): Killing 2883:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/BluetoothAdapterProperties( 3271): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3271): Calling BTA_HhEnable
E/bt-btif ( 3271): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3271): Address is:F8:CF:C5:D9:E5:61
,W/bt-btm  ( 3271): Stopping oneshot timer
,D/AuthorizationBluetoothService( 1534): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothAdapterProperties( 3271): Name is: Nexus 6
,D/BluetoothManagerService(  823): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  823): Stored Bluetooth name: Nexus 6
,D/BluetoothAdapterProperties( 3271): Scan Mode:20
D/BluetoothAdapterProperties( 3271): Discoverable Timeout:120
,D/bte_conf( 3271): Device ID record 1 : primary
D/bte_conf( 3271):   vendorId            = 000f
D/bte_conf( 3271):   vendorIdSource      = 0001
D/bte_conf( 3271):   product             = 1200
,D/bte_conf( 3271):   version             = 1436
D/bte_conf( 3271):   clientExecutableURL = 
,D/bte_conf( 3271):   serviceDescription  = 
D/bte_conf( 3271):   documentationURL    = 
D/bte_conf( 3271): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3271): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3271): ScanMode =  20
D/BluetoothAdapterProperties( 3271): State =  11
D/BluetoothAdapterProperties( 3271): Setting state to 12
I/BluetoothAdapterState( 3271): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 3271): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/BluetoothAdapterState( 3271): Entering On State
D/BluetoothManagerService(  823): Message: 60
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  823): Broadcasting onBluetoothStateChange(true) to 13 receivers.
,D/BluetoothHeadsetClient( 1064): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3271): Scan Mode:21
D/BluetoothAdapterProperties( 3271): Discoverable Timeout:120
E/BluetoothHeadsetClient( 1064): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
E/bt_h4   ( 3271): vendor lib postload completed
D/BluetoothHeadset(  823): onBluetoothStateChange: up=true
D/BluetoothManagerService(  823): Creating new ProfileServiceConnections object for profile: 1
,D/BluetoothMap( 1064): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  823): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  823): onBluetoothStateChange: up=true
,D/BluetoothAvrcpController( 1064): onBluetoothStateChange: up=true
,E/BluetoothAvrcpController( 1064): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
,D/BluetoothHeadset(  823): onBluetoothStateChange: up=true
D/BluetoothPan( 1064): onBluetoothStateChange(on) call bindService
,D/BluetoothA2dp( 1064): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1276): onBluetoothStateChange: up=true
,D/BluetoothA2dpSink( 1064): onBluetoothStateChange: up=true
E/BluetoothA2dpSink( 1064): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
,D/BluetoothHeadset( 1064): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 1064): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  823): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  823): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3271): onReceive
D/BluetoothMapService( 3271): STATE_ON
,D/BluetoothMapMasInstance( 3271): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3271): MAS initSocket()
,D/BluetoothManagerService(  823): Message: 40
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3271): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3271): Accepting socket connection...
,W/ContextImpl( 3357): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2251477c:true
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3271): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1534): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LocalBluetoothProfileManager( 3357): Adding local A2DP profile
,D/BluetoothManagerService(  823): Message: 30
,D/LocalBluetoothProfileManager( 3357): Adding local HEADSET profile
,D/BluetoothManagerService(  823): Message: 30
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  823): Message: 30
,W/BluetoothAdapter( 3271): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3271): Accept thread started.
,D/BluetoothManagerService(  823): Message: 30
,D/LocalBluetoothProfileManager( 3357): Adding local MAP profile
,D/BluetoothMap( 3357): Create BluetoothMap proxy object
,D/BluetoothManagerService(  823): Message: 30
,D/BluetoothManagerService(  823): Message: 30
,D/LocalBluetoothProfileManager( 3357): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3357): finishStartingService: stopping service
,D/BluetoothA2dp( 3357): Proxy object connected
,D/BluetoothManagerService(  823): Message: 400
D/BluetoothHeadset(  823): Proxy object connected
D/A2dpProfile( 3357): Bluetooth service connected
,D/BluetoothManagerService(  823): Message: 400
D/BluetoothHeadset(  823): Proxy object connected
,D/BluetoothInputDevice( 3357): Proxy object connected
D/HidProfile( 3357): Bluetooth service connected
,D/BluetoothPan( 3357): BluetoothPAN Proxy object connected
,D/PanProfile( 3357): Bluetooth service connected
D/BluetoothMap( 3357): Proxy object connected
D/MapProfile( 3357): Bluetooth service connected
D/BluetoothMap( 3357): getConnectedDevices()
,D/BluetoothManagerService(  823): Message: 400
,D/BluetoothHeadset(  823): Proxy object connected
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothPbap( 3357): Proxy object connected
,I/jxcore-log( 3217): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): my name is : motorola-Nexus 6_PT8212
I/jxcore-log( 3217): 
,D/BluetoothManagerService(  823): Message: 400
,D/BluetoothHeadset( 1276): Proxy object connected
,D/BluetoothManagerService(  823): Message: 400
,D/BluetoothHeadset( 1064): Proxy object connected
D/PbapServerProfile( 3357): Bluetooth service connected
,I/jxcore-log( 3217): attempting to connect to test coordinator
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): check test folder
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): found test : ./testFindPeers.js
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): found test : ./testReConnect.js
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): found test : ./testSendData.js
I/jxcore-log( 3217): 
,D/BluetoothManagerService(  823): Message: 400
,D/BluetoothHeadset( 3357): Proxy object connected
,D/HeadsetProfile( 3357): Bluetooth service connected
,I/jxcore-log( 3217): Test app app.js loaded
I/jxcore-log( 3217): 
,I/Choreographer( 3217): Skipped 126 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3217): 
,I/chromium( 3217): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3285): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  823):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  823):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,I/wpa_supplicant( 3285): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3285): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3285): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3285): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 1,
,E/WifiStateMachine(  823):  WifiLinkLayerStats: ,
E/WifiStateMachine(  823):  my bss beacon rx: 1
E/WifiStateMachine(  823):  RSSI mgmt: -46
E/WifiStateMachine(  823):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0,
E/WifiStateMachine(  823):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 0 tx_time=58 rx_time=101 scan_time=0
,D/ConnectivityService(  823): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60,
,E/native  (  823): do suspend false,
,E/WifiStateMachine(  823): scanCount==0 - aborting,
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/dhcpcd  ( 3419): version 5.5.6 starting
,I/dhcpcd  ( 3419): wlan0: rebinding lease of 192.168.1.110
,I/dhcpcd  ( 3419): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 3419): wlan0: leased 192.168.1.110 for 86400 seconds,
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  823): Adding iface wlan0 to network 100
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  823): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823):    accepting network in place of null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  823): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,D/Tethering(  823): MasterInitialState.processMessage what=3
,V/BackupManagerService(  823): Scheduling immediate backup pass
,D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
,I/ActivityManager(  823): Start proc 3456:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,V/BackupManagerService(  823): Running a backup pass
,V/BackupManagerService(  823): clearing pending backups
,D/NetworkChangeNotifierAutoDetect( 1509): Network connectivity changed, type is: 2
,E/GpsLocationProvider(  823): No APN found to select.
,D/AlarmManagerService(  823): Setting time of day to sec=1449007413
W/AlarmManagerService(  823): Unable to set rtc to 1449007413: Invalid argument
V/PerformBackupTask(  823): Beginning backup of 14 targets
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 01 Dec 2015 22:03:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449007413423], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449007413415]}
,D/PerformBackupTask(  823): invokeAgentForBackup on @pm@
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Validated
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,V/BackupServiceBinder(  823): doBackup() invoked
,I/PMBA    (  823): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/GpsLocationProvider(  823): NTP server returned: 1449007413416 (Tue Dec 01 23:03:33 GMT+01:00 2015) reference: 145039 certainty: 12 system time offset: -41
,I/GoogleURLConnFactory( 1534): Using platform SSLCertificateSocketFactory
,I/BackupRestoreController(  823): Getting widget state for user: 0
,W/GmsBackupTransport( 1747): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1747): starting performBackup for @pm@
V/GmsBackupTransport( 1747): performBackup done for @pm@
,E/Auth.Api.Credentials( 1775): [CredentialSyncAdapter] Unknown sync event.
,I/MusicStore( 3456): Database version: 120
V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 48495(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.577ms total 57.120ms
,I/art     ( 1534): Explicit concurrent mark sweep GC freed 14944(812KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 26MB/42MB, paused 1.115ms total 38.180ms
,W/GLSActivity( 1534): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1534): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1534): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1534): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1534): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1534): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1534): 	at android.os.Binder.execTransact(Binder.java:446)
,W/DriveInitializer( 1775): Background init thread started
W/GmsBackupTransport( 1747): Error sending final backup to server: 
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
,D/BackupManagerService(  823): Now staging backup of com.google.android.talk
,D/BackupManagerService(  823): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  823): Now staging backup of com.android.providers.settings
,W/DriveInitializer( 1775): Awaiting to be initialized
,D/BackupManagerService(  823): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  823): Now staging backup of com.google.android.gm
,D/BackupManagerService(  823): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  823): Now staging backup of com.android.nfc
,D/BackupManagerService(  823): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  823): Now staging backup of com.google.android.marvin.talkback
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,D/BackupManagerService(  823): Now staging backup of com.google.android.inputmethod.latin
,W/DriveInitializer( 1775): Background init thread ended
,D/BackupManagerService(  823): Now staging backup of com.google.android.calendar
,W/ResourcesManager( 3456): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3456): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BackupManagerService(  823): Now staging backup of com.android.vending
,D/BackupManagerService(  823): Now staging backup of android
,D/BackupManagerService(  823): Now staging backup of com.google.android.googlequicksearchbox
,V/JNIHelp ( 3456): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GmsBackupTransport( 1747): Next backup will happen in 43199873 millis.
,I/ProviderInstaller( 3456): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3456): GMSCore installation verified
,I/BackupManagerService(  823): Backup pass finished.
,I/ConfigStore( 3456): Config Database version: 1
,I/ActivityManager(  823): Start proc 3512:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/ConfigFetchService( 1775): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1775): running network task: configservice_periodic
,E/WakeLock( 1775): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1775): launchTask
,I/ConfigService( 1534): onCreate
,I/ConfigFetchService( 1775): service connected
,D/ConfigFetchService( 1775): ConfigApi connection successful.
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/MediaRouter( 3456): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/MusicLeanback( 3456): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3456): type=WIFI subType= reason=null isConnected=true
,E/HttpOperation( 2990): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2990): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2990): 	at jdm.a(PG:82)
E/HttpOperation( 2990): 	at jcs.o(PG:406)
E/HttpOperation( 2990): 	at jcn.a(PG:1379)
E/HttpOperation( 2990): 	at jcs.i(PG:143)
E/HttpOperation( 2990): 	at blb.a(PG:3937)
E/HttpOperation( 2990): 	at czp.a(PG:18188)
E/HttpOperation( 2990): 	at czp.a(PG:9081)
E/HttpOperation( 2990): 	at czq.run(PG:1686)
E/HttpOperation( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2990): 	at jdj.a(PG:4091)
E/HttpOperation( 2990): 	at jdj.a(PG:1125)
E/HttpOperation( 2990): 	at jdm.a(PG:77)
E/HttpOperation( 2990): 	... 12 more
E/HttpOperation( 2990): Caused by: faj: BadAuthentication
E/HttpOperation( 2990): 	at fal.a(PG:38)
E/HttpOperation( 2990): 	at jdj.a(PG:4089)
E/HttpOperation( 2990): 	... 14 more
,I/NetworkMonitor( 3456): type=WIFI subType= reason=null isConnected=true
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  823): Start proc 3538:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/HttpOperation( 2990): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2990): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2990): 	at jdm.a(PG:82)
E/HttpOperation( 2990): 	at jcs.o(PG:406)
E/HttpOperation( 2990): 	at jcn.a(PG:1379)
E/HttpOperation( 2990): 	at jcs.i(PG:143)
E/HttpOperation( 2990): 	at hec.a(PG:42)
E/HttpOperation( 2990): 	at hee.a(PG:102)
E/HttpOperation( 2990): 	at czr.a(PG:65)
E/HttpOperation( 2990): 	at kka.a(PG:108)
E/HttpOperation( 2990): 	at czp.a(PG:19176)
E/HttpOperation( 2990): 	at czp.a(PG:9081)
E/HttpOperation( 2990): 	at czq.run(PG:1686)
E/HttpOperation( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2990): 	at jdj.a(PG:4091)
E/HttpOperation( 2990): 	at jdj.a(PG:1125)
E/HttpOperation( 2990): 	at jdm.a(PG:77)
E/HttpOperation( 2990): 	... 15 more
E/HttpOperation( 2990): Caused by: faj: BadAuthentication
E/HttpOperation( 2990): 	at fal.a(PG:38)
E/HttpOperation( 2990): 	at jdj.a(PG:4089)
E/HttpOperation( 2990): 	... 17 more
E/ExperimentLoader( 2990): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2990): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2990): 	at jdm.a(PG:82)
E/ExperimentLoader( 2990): 	at jcs.o(PG:406)
E/ExperimentLoader( 2990): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2990): 	at jcs.i(PG:143)
E/ExperimentLoader( 2990): 	at hec.a(PG:42)
E/ExperimentLoader( 2990): 	at hee.a(PG:102)
E/ExperimentLoader( 2990): 	at czr.a(PG:65)
E/ExperimentLoader( 2990): 	at kka.a(PG:108)
E/ExperimentLoader( 2990): 	at czp.a(PG:19176)
E/ExperimentLoader( 2990): 	at czp.a(PG:9081)
E/ExperimentLoader( 2990): 	at czq.run(PG:1686)
E/ExperimentLoader( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2990): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2990): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2990): 	at jdm.a(PG:77)
E/ExperimentLoader( 2990): 	... 15 more
E/ExperimentLoader( 2990): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2990): 	at fal.a(PG:38)
E/ExperimentLoader( 2990): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2990): 	... 17 more
,I/GHttpClientFactory( 3456): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3456): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 3538): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3538): simOperator:  IMSI: null
D/SprintDMReceiver( 3538): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1775): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1775): onCreate
,D/SystemUpdateService( 1775): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1775): active receiver: enabled
,I/SystemUpdateService( 1775): showing system update notification
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1775): retry (wakeup: false) in 3599977 ms
,I/iu.SyncManager( 1775): SYNC; picasa accounts
,D/NetworkLogImpl( 1775): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1775): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/SystemUpdateService( 1775): onDestroy
,D/ChimeraCfgMgr( 1775): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1775): num queued entries: 0
,D/ChimeraCfgMgr( 1775): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1775): num updated entries: 0
,I/iu.SyncManager( 1775): NEXT; no task
,I/ActivityManager(  823): Start proc 3571:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 37111, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1775): [AccountUtils] Account not ready
W/Kids    ( 1775): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1775): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1775): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1775): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1775): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1775): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1775): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1775): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1775): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1775): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1775): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1775): 	at java.lang.Thread.run(Thread.java:818)
,I/Babel   ( 2627): connection state changed from DISCONNECTED to CONNECTED
,V/KeepSync( 3315): Connecting to GoogleApiClient
,W/BaseAppContext( 1775): Using Auth Proxy for data requests.
,W/BaseAppContext( 1775): Using Auth Proxy for data requests.
,I/art     ( 1534): Explicit concurrent mark sweep GC freed 28753(1646KB) AllocSpace objects, 4(87KB) LOS objects, 37% free, 26MB/42MB, paused 2.205ms total 33.463ms
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4    ( 3571): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3571):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3571):   adb logcat -s GAv4
,D/GCM     ( 1534): Connected
,E/ClientConnectionOperation( 1775): Handling authorization failure
E/ClientConnectionOperation( 1775): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1775): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1775): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1775): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1775): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1775): 	... 7 more
,V/KeepSync( 3315): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
,D/GCM     ( 1534): Message class com.google.f.a.a.p
,W/GAv4    ( 3571): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
W/GAV2    ( 3512): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAv4    ( 3571): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/BooksApp( 3512): Created application version: 3.6.8 (30608)
,W/GAv4    ( 3571): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/GoogleAuthProtoRequest( 3288): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  823): Explicit concurrent mark sweep GC freed 26234(1248KB) AllocSpace objects, 4(105KB) LOS objects, 32% free, 33MB/49MB, paused 1.105ms total 49.763ms
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3288): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3288): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3288): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3288): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3288): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3288): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 3512): Starting books sync for 61035162, extras: ade
,I/jxcore-log( 3217): BLE supported!!
I/jxcore-log( 3217): 
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 3571): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3571): Time to load native libraries: 1 ms (timestamps 6322-6323)
I/LibraryLoader( 3571): Expected native library version number "",actual native library version number ""
,E/KeepSync( 3315): IOException
E/KeepSync( 3315): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3315): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3315): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3315): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3315): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3315): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3315): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3315): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3315): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3315): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3315): 	... 10 more
W/KeepSync( 3315): Sync result 2
,V/WebViewChromiumFactoryProvider( 3571): Binding Chromium to main looper Looper (main, tid 1) {23112bba}
I/LibraryLoader( 3571): Expected native library version number "",actual native library version number ""
I/chromium( 3571): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 37113, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Killing 2932:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/BrowserStartupController( 3571): Initializing chromium process, singleProcess=true
,W/art     ( 3571): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3571): ApplicationContext is null in ApplicationStatus
,W/chromium( 3571): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3571): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3571): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3571): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/BooksConfig( 3512): GmsCore Version = 7.8.99 (2134222-430)
,W/AudioManagerAndroid( 3571): Requires BLUETOOTH permission
,I/NSApplication( 3571): Starting up...
,I/ActivityManager(  823): Killing 1393:android.process.acore/u0a5 (adj 15): empty #17
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  823): Start proc 3652:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3512): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3512): Soft error
E/BooksSync( 3512): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3512): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3512): Sync error
E/BooksSync( 3512): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3512): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3512): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37113, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Killing 3099:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3120:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  823): Start proc 3669:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,I/art     ( 1775): Explicit concurrent mark sweep GC freed 14022(1109KB) AllocSpace objects, 16(256KB) LOS objects, 35% free, 28MB/44MB, paused 2.399ms total 46.227ms
,D/WifiService(  823): New client listening to asynchronous messages
,V/Herrevad( 1775): NQAS connected
,E/SQLiteLog( 3669): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  823): Start proc 3691:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3691): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3691): Created com.android.providers.calendar.CalendarAlarmManager@3a32f508(com.android.providers.calendar.CalendarProvider2@1a8af4a1)
,I/ActivityManager(  823): Start proc 3713:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3669): PlayLogger.onLoggerConnected
,I/ActivityManager(  823): Killing 1802:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/TimeService( 3713): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449007416542
D/        ( 3713): TimeServiceNative: User Time to be set is 1449007416542
,D/QC-time-services( 3713): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3713): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3713): Lib:time_genoff_operation: pargs->ts_val = 1449007416542
D/QC-time-services( 3713): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  374): Daemon: Connection accepted:time_genoff
D/QC-time-services(  374): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449007416542
D/QC-time-services(  374): Daemon:genoff_opr: Base = 2, val = 1449007416542, operation = 0
D/QC-time-services(  374): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/18/70 18:16:34
D/QC-time-services(  374): Daemon:Value read from RTC seconds = 9310594000
D/QC-time-services(  374): Daemon:new time 1449007416542 
D/QC-time-services(  374): Daemon: delta 1439696822542 genoff 1439696822542 
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696822542 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  374): Updating the TOD offset
,D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696822542 to memory
D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  374): Daemon:Update to modem bit set,
D/QC-time-services(  374): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  374): Daemon: Base = 2, Value being sent to MODEM = 1133042616542
E/QC-time-services( 3713): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  374): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  374): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
,I/ActivityManager(  823): Killing 3150:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/art     (  823): Explicit concurrent mark sweep GC freed 18421(766KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 2.039ms total 70.528ms
,I/ActivityManager(  823): Start proc 3733:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 334us total 16.593ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 283us total 12.644ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 215us total 10.992ms
,I/GAv4    ( 3733): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
,I/GAv4    ( 3733):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3733):   adb logcat -s GAv4
,W/GAv4    ( 3733): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3733): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3733): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  823): Killing 3057:com.android.defcontainer/u0a7 (adj 15): empty #17
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@fb4ac23}
,I/CalendarProvider2( 3691): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3691): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2627): UserRecoverableAuthException.
,E/Babel   ( 2627): eei: BadAuthentication
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
,E/Babel   ( 2627): Error getting auth token
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
,E/Babel   ( 2627): cyp: null -- null
E/Babel   ( 2627): 	at cae.a(SourceFile:3121)
E/Babel   ( 2627): 	,at cae.a(SourceFile:1131)
E/Babel   ( 2627): 	at cws.a(SourceFile:4333)
E/Babel   ( 2627): 	at cws.a(SourceFile:1419)
E/Babel   ( 2627): 	at crl.a(SourceFile:492)
E/Babel   ( 2627): 	at crl.a(SourceFile:1468)
E/Babel   ( 2627): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2627): 	at cas.b(SourceFile:106)
E/Babel   ( 2627): 	at cap.d(SourceFile:335)
E/Babel   ( 2627): ,	at caq.run(SourceFile:81)
,I/art     ( 2627): Note: end time exceeds epoch: 
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ResourcesManager( 1534): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/Babel   ( 2627): Unexpected exception while authenticating.
,E/Babel   ( 2627): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2627): 	at eeg.b(Unknown Source)
E/Babel   ( 2627): 	at eeg.b(Unknown Source)
E/Babel   ( 2627): 	at g.a(Unknown Source)
E/Babel   ( 2627): 	at cae.b(SourceFile:1146)
E/Babel   ( 2627): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2627): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2627): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2627): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 3691): (284) automatic index on view_events(_id)
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=26.72 rxSuccessRate=25.06 targetRoamBSSID=any RSSI=-46
,E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=26.72 rxSuccessRate=25.06 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,I/ActivityManager(  823): Start proc 3776:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,I/MusicLeanback( 3456): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3456): Stop autocaching.
,W/ResourcesManager( 3776): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3776): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3776): VM with version 2.1.0 has multidex support
I/MultiDex( 3776): install
I/MultiDex( 3776): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3776): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3776): Installed default security provider GmsCore_OpenSSL,
,D/GCM     ( 1534): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1534): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1775): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 3776): callingUid 10011, callindPid: 3776
,D/LocationInitializer( 1775): Restart initialization of location
,E/MDM     ( 1747): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3456): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3456): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/art     ( 1534): Explicit concurrent mark sweep GC freed 20602(1186KB) AllocSpace objects, 5(551KB) LOS objects, 37% free, 27MB/43MB, paused 1.077ms total 33.349ms
,I/GAV2    ( 3512): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 3669): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2723): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2723): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2723): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ActivityManager(  823): Killing 3357:com.android.settings/1000 (adj 15): empty #17
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,V/ConfigFetchTask( 1775): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VsbxPrz5IUi1DNtU3kJWWYukvEXW7Cyh-cvYtouzx6a6bAY3jVoKa9Y0uMFCJDebmfjm1jcHjpiJtzch9Ve1_qj6mUSU_l1d5lHoIzD4AWqEPQUaEvybyUP8z1cxIrHv3CoRBBEik4t8PVTX4kIQ4ND63AG3C1-EEzCMVtQE_BmmRkrifpokGFKMv5NOwj_i5lCBKZrGyfJilILa43w0rre6M8kFg5AK3R7o8Yk6j1OcIXnfUf_YuY-jLFwmA_Q9u_1gijLLjq8qPWE_aGA3b9nB-1PHmHyka797H5OiGhC1eOSHQ
,I/GoogleURLConnFactory( 1775): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  823): Killing 3376:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ConfigFetchTask( 1775): updating config table for com.google.android.gms
,I/ConfigFetchService( 1775): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1775): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1775): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1775): fetch service done; releasing wakelock
,D/Finsky  ( 2723): [249] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,I/ConfigFetchService( 1775): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1775): stopping self
,I/ActivityManager(  823): Killing 1509:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  823): Client connection lost with reason: 4
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1534): Vacuum at: now=1449007425134 tag=VacuumService
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2723): [249] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/GoogleURLConnFactory( 1534): Using platform SSLCertificateSocketFactory
,W/Uploader( 1534): No account for auth token provided
,I/art     (  823): Explicit concurrent mark sweep GC freed 19450(882KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 1.447ms total 51.846ms
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1534): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1534): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1534): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1534): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534): No account for auth token provided
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1534): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1534): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1534): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1534): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1534): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1534): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1534): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1534): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1534): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1534): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1534): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1534): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534):  no longer exists, so no auth token.
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534): No account for auth token provided,
,W/Uploader( 1534): No account for auth token provided,
,W/Uploader( 1534): No account for auth token provided,
,W/Uploader( 1534): No account for auth token provided,
,W/Uploader( 1534): No account for auth token provided,
,W/Uploader( 1534): No account for auth token provided,
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,W/Uploader( 1534): No account for auth token provided
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1534): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1534): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1534): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1534): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1534): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1534): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1534): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1534): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1534): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1534): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1534): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1534): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1534): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1534): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1534): No account for auth token provided
,W/Uploader( 1534): No account for auth token provided
,I/ConfigService( 1534): onDestroy
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (220 us)
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  823): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  823): Excessive delay in setPowerMode(): 285ms
,I/DreamManagerService(  823): Entering dreamland.
,I/PowerManagerService(  823): Dozing...
,I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  823): cancelDelayedScan -> 5
,E/native  (  823): do suspend false
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@18f3057f}
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=29.24 rxSuccessRate=19.91 targetRoamBSSID=any RSSI=-46
,I/Keyboard.Facilitator( 1214): onFinishInput()
,E/WifiStateMachine(  823): cancelDelayedScan -> 7
,E/native  (  823): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off,
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off,
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/GoogleURLConnFactory( 1747): Using platform SSLCertificateSocketFactory
,W/GoogleHttpClient( 1747): Ignoring unsupported parameter: http.conn-manager.max-per-route
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@18f3057f}
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2723): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2723): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2723): [1] 5.onFinished: Scheduling replication attempt 4.
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,V/GoogleAuthProtoRequest( 3288): [337] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3288): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3288): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3288): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3288): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3288): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3288): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2723): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2723): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2723): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/art     (  823): Explicit concurrent mark sweep GC freed 31735(1536KB) AllocSpace objects, 6(190KB) LOS objects, 31% free, 34MB/50MB, paused 2.032ms total 130.436ms
,V/KeepSync( 3315): Connecting to GoogleApiClient
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2990): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2990): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2990): 	at jdm.a(PG:82)
E/HttpOperation( 2990): 	at jcs.o(PG:406)
E/HttpOperation( 2990): 	at jcn.a(PG:1379)
E/HttpOperation( 2990): 	at jcs.i(PG:143)
E/HttpOperation( 2990): 	at blb.a(PG:3937)
E/HttpOperation( 2990): 	at czp.a(PG:18188)
E/HttpOperation( 2990): 	at czp.a(PG:9087)
E/HttpOperation( 2990): 	at czq.run(PG:1686)
E/HttpOperation( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2990): 	at jdj.a(PG:4091)
E/HttpOperation( 2990): 	at jdj.a(PG:1125)
E/HttpOperation( 2990): 	at jdm.a(PG:77)
E/HttpOperation( 2990): 	... 12 more
E/HttpOperation( 2990): Caused by: faj: BadAuthentication
E/HttpOperation( 2990): 	at fal.a(PG:38)
E/HttpOperation( 2990): 	at jdj.a(PG:4089)
E/HttpOperation( 2990): 	... 14 more
,E/ClientConnectionOperation( 1775): Handling authorization failure
E/ClientConnectionOperation( 1775): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1775): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1775): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1775): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1775): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1775): 	... 7 more
,V/KeepSync( 3315): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1534): Explicit concurrent mark sweep GC freed 87120(5MB) AllocSpace objects, 19(1494KB) LOS objects, 36% free, 27MB/43MB, paused 1.242ms total 50.532ms
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2990): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2990): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2990): 	at jdm.a(PG:82)
E/HttpOperation( 2990): 	at jcs.o(PG:406)
E/HttpOperation( 2990): 	at jcn.a(PG:1379)
E/HttpOperation( 2990): 	at jcs.i(PG:143)
E/HttpOperation( 2990): 	at blb.a(PG:3937)
E/HttpOperation( 2990): 	at czp.a(PG:18188)
E/HttpOperation( 2990): 	at czp.a(PG:9081)
E/HttpOperation( 2990): 	at czq.run(PG:1686)
E/HttpOperation( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2990): 	at jdj.a(PG:4091)
E/HttpOperation( 2990): 	at jdj.a(PG:1125)
E/HttpOperation( 2990): 	at jdm.a(PG:77)
E/HttpOperation( 2990): 	... 12 more
E/HttpOperation( 2990): Caused by: faj: BadAuthentication
E/HttpOperation( 2990): 	at fal.a(PG:38)
E/HttpOperation( 2990): 	at jdj.a(PG:4089)
E/HttpOperation( 2990): 	... 14 more
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3315): IOException
E/KeepSync( 3315): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3315): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3315): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3315): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3315): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3315): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3315): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3315): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3315): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3315): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3315): 	... 10 more
W/KeepSync( 3315): Sync result 2
,E/HttpOperation( 2990): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2990): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2990): 	at jdm.a(PG:82)
E/HttpOperation( 2990): 	at jcs.o(PG:406)
E/HttpOperation( 2990): 	at jcn.a(PG:1379)
E/HttpOperation( 2990): 	at jcs.i(PG:143)
E/HttpOperation( 2990): 	at hec.a(PG:42)
E/HttpOperation( 2990): 	at hee.a(PG:102)
E/HttpOperation( 2990): 	at czr.a(PG:65)
E/HttpOperation( 2990): 	at kka.a(PG:108)
E/HttpOperation( 2990): 	at czp.a(PG:19176)
E/HttpOperation( 2990): 	at czp.a(PG:9081)
E/HttpOperation( 2990): 	at czq.run(PG:1686)
E/HttpOperation( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2990): 	at jdj.a(PG:4091)
E/HttpOperation( 2990): 	at jdj.a(PG:1125)
E/HttpOperation( 2990): 	at jdm.a(PG:77)
E/HttpOperation( 2990): 	... 15 more
E/HttpOperation( 2990): Caused by: faj: BadAuthentication
E/HttpOperation( 2990): 	at fal.a(PG:38)
E/HttpOperation( 2990): 	at jdj.a(PG:4089)
E/HttpOperation( 2990): 	... 17 more
,E/ExperimentLoader( 2990): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2990): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2990): 	at jdm.a(PG:82)
E/ExperimentLoader( 2990): 	at jcs.o(PG:406)
E/ExperimentLoader( 2990): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2990): 	at jcs.i(PG:143)
E/ExperimentLoader( 2990): 	at hec.a(PG:42)
E/ExperimentLoader( 2990): 	at hee.a(PG:102)
E/ExperimentLoader( 2990): 	at czr.a(PG:65)
E/ExperimentLoader( 2990): 	at kka.a(PG:108)
E/ExperimentLoader( 2990): 	at czp.a(PG:19176)
E/ExperimentLoader( 2990): 	at czp.a(PG:9081)
E/ExperimentLoader( 2990): 	at czq.run(PG:1686)
E/ExperimentLoader( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2990): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2990): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2990): 	at jdm.a(PG:77)
E/ExperimentLoader( 2990): 	... 15 more
E/ExperimentLoader( 2990): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2990): 	at fal.a(PG:38)
E/ExperimentLoader( 2990): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2990): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 176772, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3512): Starting books sync for 61035162, extras: ade
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/BooksConfig( 3512): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 145933, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3512): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3512): Soft error
E/BooksSync( 3512): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3512): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3512): Sync error
E/BooksSync( 3512): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3512): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3512): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 178235, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2723): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2723): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2723): [1] 5.onFinished: Giving up after 6 failures.
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1214): run()
I/Keyboard.Facilitator( 1214): flushDynamicLanguageModels()
,I/ConfigService( 1534): onCreate
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,I/ConfigService( 1534): onDestroy
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3217): 
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2990): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2990): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2990): 	at jdm.a(PG:82)
E/HttpOperation( 2990): 	at jcs.o(PG:406)
E/HttpOperation( 2990): 	at jcn.a(PG:1379)
E/HttpOperation( 2990): 	at jcs.i(PG:143)
E/HttpOperation( 2990): 	at blb.a(PG:3937)
E/HttpOperation( 2990): 	at czp.a(PG:18188)
E/HttpOperation( 2990): 	at czp.a(PG:9081)
E/HttpOperation( 2990): 	at czq.run(PG:1686)
E/HttpOperation( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2990): 	at jdj.a(PG:4091)
E/HttpOperation( 2990): 	at jdj.a(PG:1125)
E/HttpOperation( 2990): 	at jdm.a(PG:77)
E/HttpOperation( 2990): 	... 12 more
E/HttpOperation( 2990): Caused by: faj: BadAuthentication
E/HttpOperation( 2990): 	at fal.a(PG:38)
E/HttpOperation( 2990): 	at jdj.a(PG:4089)
E/HttpOperation( 2990): 	... 14 more
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2990): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2990): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2990): 	at jdm.a(PG:82)
E/HttpOperation( 2990): 	at jcs.o(PG:406)
E/HttpOperation( 2990): 	at jcn.a(PG:1379)
E/HttpOperation( 2990): 	at jcs.i(PG:143)
E/HttpOperation( 2990): 	at hec.a(PG:42)
E/HttpOperation( 2990): 	at hee.a(PG:102)
E/HttpOperation( 2990): 	at czr.a(PG:65)
E/HttpOperation( 2990): 	at kka.a(PG:108)
E/HttpOperation( 2990): 	at czp.a(PG:19176)
E/HttpOperation( 2990): 	at czp.a(PG:9081)
E/HttpOperation( 2990): 	at czq.run(PG:1686)
E/HttpOperation( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2990): 	at jdj.a(PG:4091)
E/HttpOperation( 2990): 	at jdj.a(PG:1125)
E/HttpOperation( 2990): 	at jdm.a(PG:77)
E/HttpOperation( 2990): 	... 15 more
E/HttpOperation( 2990): Caused by: faj: BadAuthentication
E/HttpOperation( 2990): 	at fal.a(PG:38)
E/HttpOperation( 2990): 	at jdj.a(PG:4089)
E/HttpOperation( 2990): 	... 17 more
,E/ExperimentLoader( 2990): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2990): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2990): 	at jdm.a(PG:82)
E/ExperimentLoader( 2990): 	at jcs.o(PG:406)
E/ExperimentLoader( 2990): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2990): 	at jcs.i(PG:143)
E/ExperimentLoader( 2990): 	at hec.a(PG:42)
E/ExperimentLoader( 2990): 	at hee.a(PG:102)
E/ExperimentLoader( 2990): 	at czr.a(PG:65)
E/ExperimentLoader( 2990): 	at kka.a(PG:108)
E/ExperimentLoader( 2990): 	at czp.a(PG:19176)
E/ExperimentLoader( 2990): 	at czp.a(PG:9081)
E/ExperimentLoader( 2990): 	at czq.run(PG:1686)
E/ExperimentLoader( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2990): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2990): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2990): 	at jdm.a(PG:77)
E/ExperimentLoader( 2990): 	... 15 more
E/ExperimentLoader( 2990): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2990): 	at fal.a(PG:38)
E/ExperimentLoader( 2990): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2990): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 237639, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,V/GoogleAuthProtoRequest( 3288): [338] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3288): [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3288): [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3288): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3288): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3288): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3288): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3217): 
,I/BooksSync( 3512): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3315): Connecting to GoogleApiClient
,I/BooksConfig( 3512): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  823): Explicit concurrent mark sweep GC freed 33994(1477KB) AllocSpace objects, 12(851KB) LOS objects, 32% free, 33MB/49MB, paused 2.407ms total 71.071ms
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1775): Handling authorization failure
E/ClientConnectionOperation( 1775): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1775): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1775): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1775): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1775): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1775): 	... 7 more
,V/KeepSync( 3315): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3512): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3512): Soft error
E/BooksSync( 3512): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3512): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3512): Sync error
E/BooksSync( 3512): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3512): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3512): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 269112, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3315): IOException
E/KeepSync( 3315): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3315): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3315): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3315): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3315): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3315): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3315): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3315): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3315): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3315): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3315): 	... 10 more
W/KeepSync( 3315): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 266576, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): Coordinator is now connected to the server!
I/jxcore-log( 3217): 
,I/chromium( 3217): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63),
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1534): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1534): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1534): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1534): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1534): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1534): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1534): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2723): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2723): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2723): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2723): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2723): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2723): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2723): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2723): Ignoring header User-Agent because its value was null.
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2990): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2990): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2990): 	at jdm.a(PG:82)
E/HttpOperation( 2990): 	at jcs.o(PG:406)
,E/HttpOperation( 2990): 	at jcn.a(PG:1379)
E/HttpOperation( 2990): 	at jcs.i(PG:143)
E/HttpOperation( 2990): 	at blb.a(PG:3937)
E/HttpOperation( 2990): 	at czp.a(PG:18188)
E/HttpOperation( 2990): 	at czp.a(PG:9081)
E/HttpOperation( 2990): 	at czq.run(PG:1686)
E/HttpOperation( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2990): 	at jdj.a(PG:4091)
E/HttpOperation( 2990): 	at jdj.a(PG:1125)
E/HttpOperation( 2990): 	at jdm.a(PG:77)
E/HttpOperation( 2990): 	... 12 more
E/HttpOperation( 2990): Caused by: faj: BadAuthentication
E/HttpOperation( 2990): 	at fal.a(PG:38)
E/HttpOperation( 2990): 	at jdj.a(PG:4089)
E/HttpOperation( 2990): 	... 14 more
,I/art     ( 1534): Explicit concurrent mark sweep GC freed 51679(2MB) AllocSpace objects, 15(1653KB) LOS objects, 36% free, 27MB/43MB, paused 1.877ms total 45.252ms
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2990): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2990): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2990): 	at jdm.a(PG:82)
E/HttpOperation( 2990): 	at jcs.o(PG:406)
E/HttpOperation( 2990): 	at jcn.a(PG:1379)
E/HttpOperation( 2990): 	at jcs.i(PG:143)
E/HttpOperation( 2990): 	at hec.a(PG:42)
E/HttpOperation( 2990): 	at hee.a(PG:102)
E/HttpOperation( 2990): 	at czr.a(PG:65)
E/HttpOperation( 2990): 	at kka.a(PG:108)
E/HttpOperation( 2990): 	at czp.a(PG:19176)
E/HttpOperation( 2990): 	at czp.a(PG:9081)
E/HttpOperation( 2990): 	at czq.run(PG:1686)
E/HttpOperation( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2990): 	at jdj.a(PG:4091)
E/HttpOperation( 2990): 	at jdj.a(PG:1125)
E/HttpOperation( 2990): 	at jdm.a(PG:77)
E/HttpOperation( 2990): 	... 15 more
E/HttpOperation( 2990): Caused by: faj: BadAuthentication
E/HttpOperation( 2990): 	at fal.a(PG:38)
E/HttpOperation( 2990): 	at jdj.a(PG:4089)
E/HttpOperation( 2990): 	... 17 more
E/ExperimentLoader( 2990): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2990): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2990): 	at jdm.a(PG:82)
E/ExperimentLoader( 2990): 	at jcs.o(PG:406)
E/ExperimentLoader( 2990): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2990): 	at jcs.i(PG:143)
E/ExperimentLoader( 2990): 	at hec.a(PG:42)
E/ExperimentLoader( 2990): 	at hee.a(PG:102)
E/ExperimentLoader( 2990): 	at czr.a(PG:65)
E/ExperimentLoader( 2990): 	at kka.a(PG:108)
E/ExperimentLoader( 2990): 	at czp.a(PG:19176)
E/ExperimentLoader( 2990): 	at czp.a(PG:9081)
E/ExperimentLoader( 2990): 	at czq.run(PG:1686)
E/ExperimentLoader( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2990): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2990): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2990): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2990): 	at jdm.a(PG:77)
E/ExperimentLoader( 2990): 	... 15 more
E/ExperimentLoader( 2990): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2990): 	at fal.a(PG:38)
E/ExperimentLoader( 2990): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2990): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 329527, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3288): [339] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3288): [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3288): [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3288): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3288): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3288): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3288): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3315): Connecting to GoogleApiClient
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1775): Handling authorization failure
E/ClientConnectionOperation( 1775): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1775): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1775): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1775): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1775): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1775): 	... 7 more
,V/KeepSync( 3315): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3315): IOException
E/KeepSync( 3315): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3315): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3315): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3315): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3315): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3315): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3315): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3315): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3315): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3315): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3315): 	... 10 more
W/KeepSync( 3315): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 417482, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,I/jxcore-log( 3217): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): DBG, CoordinatorConnector command called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"90:E7:C4:F6:69,
I/jxcore-log( 3217): Start now : testSendData.js
I/jxcore-log( 3217): 
W/bt-btif ( 3271): info:x10
,D/        ( 3271): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3217): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 3217): ,
,I/jxcore-log( 3217): check server
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): serverPort is 48280
I/jxcore-log( 3217): 
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3217): Stoping All
I/        ( 3217): Stopping services
I/        ( 3217): Stop Bluetooth
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3217): Start-My BT: F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3217):  mInstanceString : {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3217): All stuff available and enabled
,I/        ( 3217): Stoping All
I/        ( 3217): Stopping services
I/        ( 3217): Stop Bluetooth
I/        ( 3217): Starting All
I/        ( 3217): Stopping services
,I/        ( 3217): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@189b43d3
I/        ( 3217): Stopping services
I/        ( 3217): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3217): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}, length : 82,
I/        ( 3217): peerDiscoveryTimer timeout value:8853
,I/        ( 3217): Stop Bluetooth
I/        ( 3217): StartBluetooth listener
,I/        ( 3217): StartBluetooth listener
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3217): StartBroadcasting started ok
I/jxcore-log( 3217): 
,I/BTListenerThread( 3217): starting to listen
I/BTListenerThread( 3217): waiting to accept incoming Connection
I/jxcore-log( 3217): do fake peer & start
I/jxcore-log( 3217): 
I/jxcore-log( 3217): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:08:17.294Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:08:17.294Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:08:17.295Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3217): Starting to connect
W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3217): Connecting to null, at 08:EC:A9:50:75:41
I/jxcore-log( 3217): 2015-12-01T22:08:17.306Z SendDataTCPServer.js: TCP/IP server is bound to port: 48280
I/jxcore-log( 3217): 
D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
I/chromium( 3217): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3217): We already were running, thus doing nothing
I/        ( 3217): Added local service
I/        ( 3217): Cleared service requests
I/        ( 3217): Stopped peer discovery
,I/        ( 3217): Started peer discovery
I/        ( 3217): Discovery state changed to Started.
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3217): Found 1 peers.
I/SS      ( 3217): Peer(1): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3217): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3217): Added service request
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3217): Started service discovery
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/        ( 3217): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
,I/        ( 3217): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3584, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3584, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/        ( 3217): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2504, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2504, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,I/        ( 3217): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 3271): info:x10
,D/        ( 3271): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f05244 rs_disc_pending=0
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3271): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
,E/bt-btif ( 3271): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3271): invalid rfc slot id: 5
I/BTConnectToThread( 3217): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3217): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3217): 2015-12-01T22:08:22.619Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:22.620Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:22.621Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3217): 
,W/bt-btif ( 3271): info:x10
D/        ( 3271): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,D/btif_config( 3271): btif_get_device_type: Device [b4:ce:f6:ab:a4:6a] type 1
,I/BluetoothBondStateMachine( 3271): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
,E/bt-btif ( 3271): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3271): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3271): Entering PendingCommandState State
,I/ActivityManager(  823): Start proc 3929:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,I/BluetoothBondStateMachine( 3271): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
D/BluetoothAdapterProperties( 3271): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 3271): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3271): StableState(): Entering Off State
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e0c5ad1:true
,I/ActivityManager(  823): Killing 3538:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f05244 rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3217): we got incoming connection
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3217): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/BTListenerThread( 3217): got MESSAGE_READ 84 bytes.
,I/BTListenerThread( 3217): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
I/HS      ( 3217): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT5834
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT5834,
,I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3217): Creating BTConnectedThread
I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
,I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:08:24.909Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:25.722Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:25.733Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:25.748Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:25.756Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:25.769Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f05244 rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3217): 2015-12-01T22:08:25.808Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:25.896Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:25.936Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:25.943Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:25.958Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:25.996Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.013Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.021Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.045Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.052Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.085Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.095Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.135Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.164Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.204Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.210Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.231Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.238Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.275Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.311Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.323Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.355Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.369Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.375Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.383Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.416Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.455Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.465Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.473Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.505Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:26.545Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:27.623Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:27.624Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41,
I/jxcore-log( 3217): 
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0540c rs_disc_pending=0
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/        ( 3217): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT7532, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT7532, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-btif ( 3271): info:x10,
D/        ( 3271): remote version info [34:fc:ef:11:ae:67]: 0, 0, 0
,E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,I/        ( 3217): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT371, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT371, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f05244 rs_disc_pending=1,
W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0540c rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,D/btif_config( 3271): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1
,I/BluetoothBondStateMachine( 3271): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 3271): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3271): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3271): Entering PendingCommandState State
,I/jxcore-log( 3217): 2015-12-01T22:08:32.631Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:08:32.632Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:32.633Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:32.634Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: 08:EC:A9:50:75:41, name: null,
I/BTConnectToThread( 3217): Starting to connect
W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3217): Connecting to null, at 08:EC:A9:50:75:41
I/        ( 3217): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8736, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8736, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 3271): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 3271): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 3271): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3271): StableState(): Entering Off State
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/        ( 3217): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:,
I/        ( 3217): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,W/bt-btif ( 3271): dm_pm_timer expires
W/bt-btif ( 3271): dm_pm_timer expires 0
W/bt-btif ( 3271): proc dm_pm_timer expires
,W/bt-btif ( 3271): info:x10
,D/        ( 3271): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3271): process_service_search_attr_rsp
,D/btif_config( 3271): btif_get_device_type: Device [08:ec:a9:50:75:41] type 1
,I/BluetoothBondStateMachine( 3271): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3271): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3271): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 3271): Entering PendingCommandState State
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f05244 rs_disc_pending=1,
W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3217): we got incoming connection
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
I/BTListenerThread( 3217): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/BluetoothBondStateMachine( 3271): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3271): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3271): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3271): StableState(): Entering Off State
,I/BooksSync( 3512): Starting books sync for 61035162, extras: ade
,I/        ( 3217): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/BooksConfig( 3512): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f05244 rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/art     (  823): Explicit concurrent mark sweep GC freed 34311(1483KB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 1.784ms total 88.345ms
,I/        ( 3217): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT384, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT384, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3512): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3512): Soft error
E/BooksSync( 3512): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3512): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3512): Sync error
E/BooksSync( 3512): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3512): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3512): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 422217, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,E/bt-btm  ( 3271): invalid rfc slot id: 4
W/bt-btif ( 3271): invalid rfc slot id: 4
,I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT5834
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread,
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
,I/BtToSocketBase( 3217): Close bt out
I/BtToSocketBase( 3217): Close bt socket
,I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,D/BluetoothMapService( 3271): onReceive
,I/jxcore-log( 3217): 2015-12-01T22:08:37.242Z SendDataTCPServer.js: TCP/IP server is ended
,I/jxcore-log( 3217): 
,I/ActivityManager(  823): Start proc 3959:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27b55079:true
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  823): Start proc 3982:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,I/BluetoothClassifier( 3959): Bluetooth Device Name: HTC Desire 820
,I/ActivityManager(  823): Killing 3571:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3713:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f05244 rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=0
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3271): invalid rfc slot id: 7
W/bt-btif ( 3271): invalid rfc slot id: 7
I/BTConnectToThread( 3217): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3217): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3217): 2015-12-01T22:08:41.070Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:41.071Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:08:41.072Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3217): 
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: A3-1
,I/BTListenerThread( 3217): got MESSAGE_READ 77 bytes.,
I/BTListenerThread( 3217): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8176","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3217): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT8176
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, LGE-Nexus 5_PT8176
,I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3217): Creating BTConnectedThread
,I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
,I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:08:41.357Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f05244 rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3217): 2015-12-01T22:08:42.425Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.433Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.440Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.458Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.465Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.474Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.494Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.536Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.540Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.575Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.593Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.599Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.603Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.635Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.647Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.651Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.685Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.693Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.725Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.733Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.806Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.810Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.818Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.854Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.877Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.915Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.919Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.924Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:42.979Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:43.015Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3217): Cleared service requests
,I/        ( 3217): Started peer discovery,
,I/jxcore-log( 3217): 2015-12-01T22:08:46.074Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:46.075Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3217): Found 9 peers.
,I/SS      ( 3217): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3217): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3217): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3217): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3217): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3217): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3217): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3217): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3217): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3217): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3217): Added service request
,I/        ( 3217): Started service discovery
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51,
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 3271): info:x10
,D/        ( 3271): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: HTC Desire 820
,I/        ( 3217): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f05244 rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/        ( 3217): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8736, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8736, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3217): 2015-12-01T22:08:51.079Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:51.080Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:08:51.081Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:51.082Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/BTConnectToThread( 3217): Starting to connect
,W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3217): Connecting to A3-1, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL,
,W/bt-btif ( 3271): invalid rfc slot id: 6,
,I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8176
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
,I/BtToSocketBase( 3217): Close bt socket
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3217): 2015-12-01T22:08:53.042Z SendDataTCPServer.js: TCP/IP server is ended,
I/jxcore-log( 3217): 
,W/bt-rfcomm( 3271): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3271): RFCOMM_DisconnectInd LCID:0x49
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3271): info:x10
,D/        ( 3271): remote version info [08:ec:a9:50:75:41]: 7, f, 610c
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 3271): process_service_search_attr_rsp
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:1
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3217): Starting to Handshake
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3217): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/BTConnectToThread( 3217): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 3217): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3217): HandshakeOk : samsung-SM-A300FU_PT6174
I/HS      ( 3217): Hand Shake finished outgoing for : samsung-SM-A300FU_PT6174
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3217): Starting the connected thread incoming : false, samsung-SM-A300FU_PT6174
,I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3217): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3217): mHTTPPort  set to : 42679,
I/BtConnectorHelper( 3217): Request socket is using : 42679
I/BtToRequestSocket( 3217): Now accepting connections
,I/BtConnectorHelper( 3217): Calling ConnectionStatusUpdate with port :42679
,I/jxcore-log( 3217): 2015-12-01T22:08:55.694Z SendDataConnector.js: CLIENT connected to 42679, error: null
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:55.695Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3217): 
,I/BtToRequestSocket( 3217): incoming data from: /127.0.0.1, port: 42679,
I/BtToRequestSocket( 3217): Set local streams
,I/BtToRequestSocket( 3217): rin ended ---------------------------;
,I/jxcore-log( 3217): 2015-12-01T22:08:55.715Z SendDataConnector.js: CLIENT now sending 100000 bytes of data,
I/jxcore-log( 3217): 
,D/        ( 3271): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16792,
,I/jxcore-log( 3217): 2015-12-01T22:08:56.399Z SendDataConnector.js: CLIENT is data received : 10000,
I/jxcore-log( 3217): 
,D/        ( 3271): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19038,
,I/jxcore-log( 3217): 2015-12-01T22:08:56.478Z SendDataConnector.js: CLIENT is data received : 20000,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:56.519Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3217): 
,D/        ( 3271): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8148
,I/jxcore-log( 3217): 2015-12-01T22:08:56.572Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:56.634Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:56.680Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:56.717Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:56.773Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:08:56.817Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: Nexus 5
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3217): Cleared service requests
,I/        ( 3217): Started peer discovery
,W/bt-btif ( 3271): dm_pm_timer expires
W/bt-btif ( 3271): dm_pm_timer expires 0
W/bt-btif ( 3271): proc dm_pm_timer expires
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3217): Found 10 peers.
,I/SS      ( 3217): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3217): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3217): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3217): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3217): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3217): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3217): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3217): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3217): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3217): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3217): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3217): Added service request
,W/bt-btif ( 3271): info:x10,
D/        ( 3271): remote version info [34:fc:ef:11:ae:67]: 7, 1d, 7d3
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: Nexus 5,
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3217): we got incoming connection
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3217): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/BTListenerThread( 3217): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3217): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8176","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3217): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT8176
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, LGE-Nexus 5_PT8176
I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3217): Creating BTConnectedThread
I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:09:04.526Z SendDataTCPServer.js: TCP/IP server connected,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:04.982Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:05.005Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:05.040Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:05.044Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3217): 
,I/        ( 3217): Started service discovery
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0507c rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/        ( 3217): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3217): 2015-12-01T22:09:06.819Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3217): ,
I/jxcore-log( 3217): 2015-12-01T22:09:06.820Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:09:06.822Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:09:06.823Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:06.831Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3217): 
,I/BtToSocketBase( 3217): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3217): Disconnect outgoing peer: samsung-SM-A300FU_PT6174
,I/BtToSocketBase( 3217): Stop ReceivingThread
,I/BtToSocketBase( 3217): Stop SendingThread
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
,I/BtToSocketBase( 3217): Close bt socket
I/BtToRequestSocket( 3217): Close server socket
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3271): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: A3-1,
,I/jxcore-log( 3217): 2015-12-01T22:09:11.830Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:11.831Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
,I/        ( 3217): Cleared service requests
,W/bt-btif ( 3271): invalid rfc slot id: 8
,I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8176
I/BtToSocketBase( 3217): Stop ReceivingThread
,I/BtToSocketBase( 3217): Stop SendingThread
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3217): Close bt out
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3217): Close bt socket
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8176
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
,I/BtToSocketBase( 3217): Close bt socket
I/jxcore-log( 3217): 2015-12-01T22:09:15.234Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3217): 
,I/        ( 3217): Started peer discovery
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,W/bt-rfcomm( 3271): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 3271): RFCOMM_DisconnectInd LCID:0x4d
,I/jxcore-log( 3217): 2015-12-01T22:09:16.836Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:16.837Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:16.837Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:09:16.838Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/BTConnectToThread( 3217): Starting to connect
W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3217): Connecting to A3-1, at 08:EC:A9:50:75:41
,D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 3271): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3271): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3271): invalid rfc slot id: 11
,I/BTConnectToThread( 3217): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3217): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3217): 2015-12-01T22:09:22.176Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:09:22.176Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:22.177Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3217): Found 11 peers.,
I/SS      ( 3217): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3217): Peer(2): S5-1 ee:1f:72:63:11:86,
I/SS      ( 3217): Peer(3): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3217): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3217): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3217): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3217): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3217): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3217): Peer(9): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3217): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3217): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3217): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3217): Added service request
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3217): Started service discovery
,W/bt-btif ( 3271): info:x10
D/        ( 3271): remote version info [34:fc:ef:11:ae:67]: 7, 1d, 7d3
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: Nexus 5
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3217): we got incoming connection
,I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
I/BTListenerThread( 3217): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/BTListenerThread( 3217): got MESSAGE_READ 77 bytes.,
I/BTListenerThread( 3217): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8176","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
I/HS      ( 3217): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT8176
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, LGE-Nexus 5_PT8176
I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3217): Creating BTConnectedThread
I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
,I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:09:25.726Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:26.272Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): ,
,I/        ( 3217): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/jxcore-log( 3217): 2015-12-01T22:09:26.357Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:26.379Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:26.383Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:26.391Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:27.178Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:27.179Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
,W/bt-btif ( 3271): info:x10,
D/        ( 3271): remote version info [b4:ce:f6:ab:a4:6a]: 7, f, 6109
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0540c rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3217): we got incoming connection
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3217): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0540c rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3217): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 3217): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
I/HS      ( 3217): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT5834
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT5834
I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3217): Creating BTConnectedThread
I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
,I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:09:29.517Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:29.934Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:29.940Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:29.959Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:29.971Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:30.017Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:30.024Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/        ( 3217): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6174, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6174, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3217): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3217): 2015-12-01T22:09:32.184Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:09:32.185Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:09:32.185Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:09:32.186Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3217): Connecting to A3-1, at 08:EC:A9:50:75:41
I/BTConnectToThread( 3217): Starting to connect
W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae,
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0,
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2990): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2990): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2990): 	at jdm.a(PG:82)
E/HttpOperation( 2990): 	at jcs.o(PG:406)
E/HttpOperation( 2990): 	at jcn.a(PG:1379)
E/HttpOperation( 2990): 	at jcs.i(PG:143)
E/HttpOperation( 2990): 	at blb.a(PG:3937)
E/HttpOperation( 2990): 	at czp.a(PG:18188)
E/HttpOperation( 2990): 	at czp.a(PG:9081)
E/HttpOperation( 2990): 	at czq.run(PG:1686)
E/HttpOperation( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2990): 	at jdj.a(PG:4091)
E/HttpOperation( 2990): 	at jdj.a(PG:1125)
E/HttpOperation( 2990): 	at jdm.a(PG:77)
E/HttpOperation( 2990): 	... 12 more
E/HttpOperation( 2990): Caused by: faj: BadAuthentication
E/HttpOperation( 2990): 	at fal.a(PG:38)
E/HttpOperation( 2990): 	at jdj.a(PG:4089)
E/HttpOperation( 2990): 	... 14 more
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=0,
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/HttpOperation( 2990): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2990): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2990): 	at jdm.a(PG:82)
E/HttpOperation( 2990): 	at jcs.o(PG:406)
E/HttpOperation( 2990): 	at jcn.a(PG:1379)
E/HttpOperation( 2990): 	at jcs.i(PG:143)
E/HttpOperation( 2990): 	at hec.a(PG:42)
E/HttpOperation( 2990): 	at hee.a(PG:102)
E/HttpOperation( 2990): 	at czr.a(PG:65)
E/HttpOperation( 2990): 	at kka.a(PG:108)
E/HttpOperation( 2990): 	at czp.a(PG:19176)
E/HttpOperation( 2990): 	at czp.a(PG:9081)
E/HttpOperation( 2990): 	at czq.run(PG:1686)
,E/HttpOperation( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2990): 	at jdj.a(PG:4091)
E/HttpOperation( 2990): 	at jdj.a(PG:1125)
E/HttpOperation( 2990): 	at jdm.a(PG:77)
E/HttpOperation( 2990): 	,... 15 more
E/HttpOperation( 2990): Caused by: faj: BadAuthentication
E/HttpOperation( 2990): 	at fal.a(PG:38)
E/HttpOperation( 2990): 	at jdj.a(PG:4089)
E/HttpOperation( 2990): 	... 17 more
E/ExperimentLoader( 2990): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2990): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2990): 	at jdm.a(PG:82)
E/ExperimentLoader( 2990): 	,at jcs.o(PG:406)
E/ExperimentLoader( 2990): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2990): 	at jcs.i(PG:143)
E/ExperimentLoader( 2990): 	at hec.a(PG:42)
E/ExperimentLoader( 2990): 	at hee.a(PG:102)
E/ExperimentLoader( 2990): 	at czr.a(PG:65)
E/ExperimentLoader( 2990): 	at kka.a(PG:108)
E/ExperimentLoader( 2990): 	at czp.a(PG:19176)
E/ExperimentLoader( 2990): ,	at czp.a(PG:9081)
E/ExperimentLoader( 2990): 	at czq.run(PG:1686)
E/ExperimentLoader( 2990): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2990): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2990): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2990): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2990): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2990): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2990): 	at jdm.a(PG:77)
E/ExperimentLoader( 2990): 	... 15 more
E/ExperimentLoader( 2990): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2990): 	at fal.a(PG:38)
E/ExperimentLoader( 2990): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2990): 	... 17 more
,W/bt-btif ( 3271): invalid rfc slot id: 10
I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8176
I/BtToSocketBase( 3217): Stop ReceivingThread,
I/BtToSocketBase( 3217): Stop SendingThread
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
I/BtToSocketBase( 3217): Close bt socket
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed,
I/jxcore-log( 3217): 2015-12-01T22:09:36.407Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3217): 
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 483273, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3271): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0,
W/bt-rfcomm( 3271): RFCOMM_DisconnectInd LCID:0x40
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0540c rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3271): invalid rfc slot id: 12,
I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT5834
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
,I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
I/BtToSocketBase( 3217): Close bt socket
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3217): 2015-12-01T22:09:40.384Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,W/bt-rfcomm( 3271): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0,
,W/bt-rfcomm( 3271): RFCOMM_DisconnectInd LCID:0x42
D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: Nexus 5
,I/        ( 3217): Cleared service requests
,I/        ( 3217): Started peer discovery
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3217): Found 12 peers.
I/SS      ( 3217): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3217): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3217): Peer(3): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3217): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3217): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3217): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3217): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3217): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3217): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3217): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3217): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3217): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3217): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3217): Added service request
,I/        ( 3217): Started service discovery
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3217): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: HTC Desire 820
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT4379, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT4379, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3217): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3477, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3477, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-btif ( 3271): info:x10
,D/        ( 3271): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3217): we got incoming connection
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
I/BTListenerThread( 3217): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/BTListenerThread( 3217): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3217): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8176","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
I/HS      ( 3217): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT8176
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, LGE-Nexus 5_PT8176
I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3217): Creating BTConnectedThread
I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
,I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:09:48.354Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:48.766Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:48.782Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:48.786Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:48.798Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:48.804Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3217): 
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3271): info:x10
,D/        ( 3271): remote version info [7c:f9:0e:34:8a:a0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=0
W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,D/btif_config( 3271): btif_get_device_type: Device [7c:f9:0e:34:8a:a0] type 1
,I/BluetoothBondStateMachine( 3271): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 3271): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3271): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3271): Entering PendingCommandState State
,W/bt-btif ( 3271): info:x10
,D/        ( 3271): remote version info [b4:ce:f6:ab:a4:6a]: 7, f, 6109
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: HTC Desire 820
,I/BluetoothBondStateMachine( 3271): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3271): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3271): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3271): StableState(): Entering Off State
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/        ( 3217): Cleared service requests,
W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3217): we got incoming connection
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
I/        ( 3217): Started peer discovery
I/BTListenerThread( 3217): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3217): Found 12 peers.
I/SS      ( 3217): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3217): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3217): Peer(3): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3217): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3217): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3217): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3217): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3217): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3217): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3217): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3217): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3217): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3217): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3217): Added service request
,I/BTListenerThread( 3217): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3217): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3217): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT3584
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, samsung-SM-G900F_PT3584
,I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3217): Creating BTConnectedThread
,I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:09:54.152Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0540c rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/        ( 3217): Started service discovery
,I/jxcore-log( 3217): 2015-12-01T22:09:55.196Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.251Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.256Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.259Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.290Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.412Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.420Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.465Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.505Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.539Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.543Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data,
I/jxcore-log( 3217): ,
,I/jxcore-log( 3217): 2015-12-01T22:09:55.551Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.601Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.607Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.614Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data,
,I/jxcore-log( 3217): 
,I/        ( 3217): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/        ( 3217): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
,I/BTListenerThread( 3217): we got incoming connection
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
I/BTListenerThread( 3217): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/jxcore-log( 3217): 2015-12-01T22:09:55.657Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.666Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.696Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.718Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.726Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.766Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3217): ,
,I/jxcore-log( 3217): 2015-12-01T22:09:55.774Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.780Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0540c rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3217): 2015-12-01T22:09:55.814Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.828Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.837Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.887Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.893Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.925Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.954Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.959Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:55.966Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.014Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.019Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.025Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.076Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.091Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3217): 
,W/bt-sdp  ( 3271): SDP - Rcvd conn cnf with error: 0x8  CID 0x43
,E/bt-btif ( 3271): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3271): invalid rfc slot id: 14
I/BTConnectToThread( 3217): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3217): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3217): 2015-12-01T22:09:56.196Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:09:56.197Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.210Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.210Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:09:56.215Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3217): 
I/jxcore-log( 3217): ---- round done--------
I/jxcore-log( 3217): 
I/jxcore-log( 3217): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3217): 
I/jxcore-log( 3217): do fake peer & start
I/jxcore-log( 3217): 
I/jxcore-log( 3217): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.221Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:09:56.222Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:09:56.222Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/BTConnectToThread( 3217): Starting to connect
,W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3217): Connecting to null, at 44:80:EB:7B:5A:05
,D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/jxcore-log( 3217): 2015-12-01T22:09:56.242Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3217): ,
,I/chromium( 3217): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3217): 2015-12-01T22:09:56.280Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.431Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.480Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.485Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.523Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.527Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.531Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:56.535Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0540c rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3217): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 3217): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
I/HS      ( 3217): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT5834
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT5834
I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3217): Creating BTConnectedThread
I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280,
,I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:09:56.949Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3217): 2015-12-01T22:09:57.446Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): 
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0,
,I/jxcore-log( 3217): 2015-12-01T22:09:58.350Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:58.593Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:58.746Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:58.961Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:09:58.973Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 3285): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,W/bt-btif ( 3271): info:x10
,D/        ( 3271): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3,
E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=0,
W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14),
,W/bt-btif ( 3271): invalid rfc slot id: 13
,I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8176
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread
I/BtToSocketBase( 3217): Close local in
,I/BtToSocketBase( 3217): Close LocalOutputStream
I/BtToSocketBase( 3217): Close localHostSocket
,I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3217): Close bt in
,I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3217): Close bt out
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8176
,I/BtToSocketBase( 3217): Close bt socket
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
,I/BtToSocketBase( 3217): Close bt socket
I/jxcore-log( 3217): 2015-12-01T22:10:00.177Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3271): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 3271): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f055d4 rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3271): process_service_search_attr_rsp
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f04eb4 rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,D/btif_config( 3271): btif_get_device_type: Device [44:80:eb:7b:5a:05] type 1
,I/BluetoothBondStateMachine( 3271): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,E/bt-btif ( 3271): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3271): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3271): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3271): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3271): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3271): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3271): StableState(): Entering Off State
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f055d4 rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/        ( 3217): Cleared service requests
,I/        ( 3217): Started peer discovery
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3217): Found 12 peers.
,I/SS      ( 3217): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3217): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3217): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3217): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3217): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3217): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3217): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3217): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3217): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3217): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3217): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3217): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3217): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3217): Added service request
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f055d4 rs_disc_pending=0
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0540c rs_disc_pending=0
W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/        ( 3217): Started service discovery
,I/        ( 3217): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT384, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT384, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,W/bt-btif ( 3271): info:x10,
D/        ( 3271): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3271): invalid rfc slot id: 15
I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT3584
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread
,I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3217): Close bt in
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3217): Close bt out
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT3584
,I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
I/BtToSocketBase( 3217): Close bt socket
I/BtToSocketBase( 3217): Close bt socket
,I/jxcore-log( 3217): 2015-12-01T22:10:06.915Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3217): 
,I/        ( 3217): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0540c rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3271): L2CAP - con rsp - bad ID. Exp: 9 Got: 8
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT4379, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT4379, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255,
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3217): we got incoming connection
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
I/BTListenerThread( 3217): waiting to accept incoming Connection
W/bt-btif ( 3271): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 3217): Starting to Handshake
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:1
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/BTConnectToThread( 3217): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,W/bt-btif ( 3271): invalid rfc slot id: 16
,I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT5834
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
,I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
I/BtToSocketBase( 3217): Close bt socket
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed,
I/jxcore-log( 3217): 2015-12-01T22:10:07.781Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3217): 
,W/bt-rfcomm( 3271): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3271): RFCOMM_DisconnectInd LCID:0x49
,I/        ( 3217): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3477, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3477, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3217): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6174, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6174, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/BTListenerThread( 3217): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3217): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
I/HS      ( 3217): Incoming connection Hand Shake finished for : motorola-XT1072_PT7532
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, motorola-XT1072_PT7532
I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3217): Creating BTConnectedThread
,I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3217): --DoOneRunRound started
I/BTConnectToThread( 3217): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3217): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3217): HandshakeOk : motorola-XT1072_PT7532
I/HS      ( 3217): Hand Shake finished outgoing for : motorola-XT1072_PT7532
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3217): Starting the connected thread incoming : false, motorola-XT1072_PT7532
,I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3217): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3217): mHTTPPort  set to : 50462
I/BtConnectorHelper( 3217): Request socket is using : 50462
I/BtToRequestSocket( 3217): Now accepting connections
I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:10:08.364Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,W/bt-rfcomm( 3271): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0,
W/bt-rfcomm( 3271): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0579c rs_disc_pending=1,
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 3217): Calling ConnectionStatusUpdate with port :50462
,I/jxcore-log( 3217): 2015-12-01T22:10:08.665Z SendDataConnector.js: CLIENT connected to 50462, error: null
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:08.666Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3217): 
,I/BtToRequestSocket( 3217): incoming data from: /127.0.0.1, port: 50462
,I/BtToRequestSocket( 3217): Set local streams
I/BtToRequestSocket( 3217): rin ended ---------------------------;
,I/jxcore-log( 3217): 2015-12-01T22:10:08.677Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f055d4 rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0579c rs_disc_pending=0,
,W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3217): 2015-12-01T22:10:09.278Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:09.374Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:09.424Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:09.525Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:09.565Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:09.572Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:09.663Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3217): 
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:,
I/        ( 3217): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3217): 2015-12-01T22:10:09.744Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data,
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:10:09.746Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3217): 
,D/        ( 3271): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
I/jxcore-log( 3217): 2015-12-01T22:10:09.827Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:09.835Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:09.838Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:09.885Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:09.964Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.019Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.091Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.140Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.178Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.180Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.407Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3217): 
,I/        ( 3217): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3217): 2015-12-01T22:10:10.591Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.639Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.711Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.717Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.754Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.757Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.764Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3217): 
,D/        ( 3271): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14088
,I/jxcore-log( 3217): 2015-12-01T22:10:10.771Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.775Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.777Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.882Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.928Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:10.940Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.034Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3217): 
,D/        ( 3271): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4188
,I/jxcore-log( 3217): 2015-12-01T22:10:11.046Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.050Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.167Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data,
,I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.246Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.299Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.307Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.314Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.363Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.375Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3217): 2015-12-01T22:10:11.482Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.523Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.617Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.709Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.767Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.774Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.815Z SendDataConnector.js: CLIENT is data received : 80000
,I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.823Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0579c rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3217): 2015-12-01T22:10:11.855Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.902Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.911Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.948Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:11.996Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3217): 
,I/        ( 3217): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8736, peerAddress: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3217): 2015-12-01T22:10:12.087Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3217): 
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8736, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3217): 2015-12-01T22:10:12.137Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:12.144Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:12.147Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:12.233Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: S5-1
,I/        ( 3217): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/btif_config( 3271): btif_get_device_type: Device [00:f4:6f:30:e0:6c] type 1,
,I/BluetoothBondStateMachine( 3271): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1,
E/bt-btif ( 3271): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3271): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3271): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3271): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 3271): Failed to remove device: 00:F4:6F:30:E0:6C,
,I/BluetoothBondStateMachine( 3271): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3271): StableState(): Entering Off State
,I/        ( 3217): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6355, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6355, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0579c rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3217): we got incoming connection
,I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
I/BTListenerThread( 3217): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0579c rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
,W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,I/        ( 3217): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT371, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT371, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3271): info:x10
D/        ( 3271): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: S5-1
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3217): we got incoming connection
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3217): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/BTListenerThread( 3217): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3217): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
I/HS      ( 3217): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT3584
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, samsung-SM-G900F_PT3584
I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3217): Creating BTConnectedThread
I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
,I/BtToRequestSocket( 3217): --DoOneRunRound ended,
,I/jxcore-log( 3217): 2015-12-01T22:10:19.561Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:20.129Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:20.137Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:20.159Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:20.163Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:20.177Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:20.184Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3217): 
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3217): 2015-12-01T22:10:22.233Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3217): ,
,I/jxcore-log( 3217): 2015-12-01T22:10:22.234Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:22.236Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:10:22.236Z SendDataConnector.js: tryAgain afer: 5000 ms.,
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:10:22.238Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3217): 
,I/BtToSocketBase( 3217): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3217): Disconnect outgoing peer: motorola-XT1072_PT7532
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread
,I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
,I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
,I/BtToSocketBase( 3217): Close bt socket
I/BtToRequestSocket( 3217): Close server socket
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 3271): invalid rfc slot id: 17
I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
W/bt-btif ( 3271): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT7532
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
,I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3217): Close bt in
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3217): Close bt out
,I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT7532
I/BtToSocketBase( 3217): Close bt socket
I/BtToSocketBase( 3217): Close bt in
,I/BtToSocketBase( 3217): Close bt out
I/BtToSocketBase( 3217): Close bt socket
,I/jxcore-log( 3217): 2015-12-01T22:10:22.409Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3217): 
,I/        ( 3217): Cleared service requests
,I/        ( 3217): Started peer discovery
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: XT1072
,I/jxcore-log( 3217): 2015-12-01T22:10:27.238Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:27.239Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3217): Found 12 peers.
I/SS      ( 3217): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3217): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3217): Peer(3): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3217): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3217): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3217): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3217): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3217): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3217): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3217): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3217): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 3217): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3217): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3217): Added service request
,I/        ( 3217): Started service discovery
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3285): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 3285): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,W/bt-btif ( 3271): invalid rfc slot id: 20
,I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT3584
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread,
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
,I/BtToSocketBase( 3217): Close bt out
I/BtToSocketBase( 3217): Close bt socket
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3217): 2015-12-01T22:10:30.369Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f05244 rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3271): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 3271): RFCOMM_DisconnectInd LCID:0x45
,I/        ( 3217): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3217): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3477, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3477, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3217): 2015-12-01T22:10:32.243Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:32.244Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:10:32.245Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:10:32.245Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: 44:80:EB:7B:5A:05, name: XT1072,
,I/        ( 3217): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3217): Starting to connect
,W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f05244 rs_disc_pending=1
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3271): onReceive,
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: S5-1,
,W/bt-btif ( 3271): No ag scb for peer addr
,W/bt-btif ( 3271): info:x10
D/        ( 3271): remote version info [44:80:eb:7b:5a:05]: 7, f, 610c
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f055d4 rs_disc_pending=1
W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3271): process_service_search_attr_rsp
,I/        ( 3217): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6174, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6174, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 3271): invalid rfc slot id: 19
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread disconnected: java.io.IOException: bt socket closed, read return: -1
I/BTListenerThread( 3217): HandShakeFailed: SOCKET_DISCONNECTED
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: S5mini-1
,I/        ( 3217): Cleared service requests
,I/        ( 3217): Started peer discovery
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3217): Found 10 peers.
I/SS      ( 3217): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3217): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3217): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3217): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3217): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3217): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3217): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3217): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3217): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3217): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3217): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3217): Added service request
,W/bt-btif ( 3271): info:x10
D/        ( 3271): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: S5mini-1
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3217): Started service discovery
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3217): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3217): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6174, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6174, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3217): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8736, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8736, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3217): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3217): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT371, peerAddress: B0:C5:59:3F:75:69,
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT371, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3217): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
I/        ( 3217): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3584, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3584, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3271): onReceive,
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: S5mini-1
,I/        ( 3217): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:,
I/        ( 3217): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3271): info:x10
D/        ( 3271): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: S5mini-1
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3217): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3217): we got incoming connection
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3217): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started,
,I/BTListenerThread( 3217): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3217): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3217): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT8573
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, samsung-SM-G800F_PT8573
I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3217): Creating BTConnectedThread
I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
,I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:10:58.339Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.355Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.398Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.401Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.464Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.515Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.519Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.568Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.605Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.609Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.616Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.620Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/jxcore-log( 3217): 2015-12-01T22:10:59.765Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.794Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
,I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.800Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3217): 2015-12-01T22:10:59.849Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:10:59.965Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.002Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.009Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.049Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.057Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.065Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.077Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.115Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.159Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.167Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.205Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.209Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.216Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.255Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.274Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.280Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.325Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3217): 
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3217): 2015-12-01T22:11:00.364Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.382Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.388Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.395Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.437Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.475Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:00.593Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3217): 2015-12-01T22:11:00.674Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data,
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3217): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,W/bt-rfcomm( 3271): PORT_StartCnf failed result:5
W/bt-btif ( 3271): btm_sec_disconnected - 
E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
I/BTConnectToThread( 3217): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3217): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/jxcore-log( 3217): 2015-12-01T22:11:06.301Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:06.302Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:11:06.303Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3217): 
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: XT1072
,W/bt-btif ( 3271): invalid rfc slot id: 21
,I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT8573
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
,I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
I/BtToSocketBase( 3217): Close bt socket
,I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3217): 2015-12-01T22:11:10.755Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3217): 
,I/        ( 3217): Cleared service requests
,I/        ( 3217): Started peer discovery
,I/jxcore-log( 3217): 2015-12-01T22:11:11.304Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:11.305Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
,W/bt-rfcomm( 3271): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3271): RFCOMM_DisconnectInd LCID:0x49
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3217): Found 11 peers.
I/SS      ( 3217): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3217): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3217): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3217): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3217): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3217): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3217): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3217): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3217): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3217): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3217): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3217): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3217): Added service request
,I/        ( 3217): Started service discovery
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3271): onReceive,
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3217): 2015-12-01T22:11:16.309Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:16.310Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:11:16.310Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:16.311Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/BTConnectToThread( 3217): Starting to connect
,W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3217): Connecting to XT1072, at 44:80:EB:7B:5A:05
,D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3217): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:,
I/        ( 3217): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-btif ( 3271): info:x10,
D/        ( 3271): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3217): we got incoming connection
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
I/BTListenerThread( 3217): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/BTListenerThread( 3217): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3217): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
I/HS      ( 3217): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT8573
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, samsung-SM-G800F_PT8573
I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket,
I/BtToRequestSocket( 3217): Creating BTConnectedThread
,I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
,I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:11:21.624Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT4379, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT4379, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3217): 2015-12-01T22:11:22.136Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:22.140Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:22.144Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:22.164Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:22.168Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:22.172Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3217): 
,I/        ( 3217): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3217): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}, typeCordovap2p._tcp.local.:,
I/        ( 3217): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3477, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3477, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3217): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:,
I/        ( 3217): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6174, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6174, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51,
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3217): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:,
I/        ( 3217): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3217): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT371, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT371, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3217): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3584, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3584, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3217): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 3271): info:x10,
,D/        ( 3271): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 3271): process_service_search_attr_rsp
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:1
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3217): Starting to Handshake
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
I/BTConnectToThread( 3217): MESSAGE_WRITE 82 bytes.
,I/BTConnectToThread( 3217): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3217): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3217): HandshakeOk : motorola-XT1072_PT7532
I/HS      ( 3217): Hand Shake finished outgoing for : motorola-XT1072_PT7532
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3217): Starting the connected thread incoming : false, motorola-XT1072_PT7532
I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3217): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3217): mHTTPPort  set to : 56299
,I/BtConnectorHelper( 3217): Request socket is using : 56299
I/BtToRequestSocket( 3217): Now accepting connections
,I/BtConnectorHelper( 3217): Calling ConnectionStatusUpdate with port :56299
,I/jxcore-log( 3217): 2015-12-01T22:11:24.817Z SendDataConnector.js: CLIENT connected to 56299, error: null
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:24.820Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3217): 
,I/BtToRequestSocket( 3217): incoming data from: /127.0.0.1, port: 56299
,I/BtToRequestSocket( 3217): Set local streams
,I/BtToRequestSocket( 3217): rin ended ---------------------------;
,I/jxcore-log( 3217): 2015-12-01T22:11:24.840Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3217): we got incoming connection
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3217): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/BTListenerThread( 3217): got MESSAGE_READ 81 bytes.,
I/BTListenerThread( 3217): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
I/HS      ( 3217): Incoming connection Hand Shake finished for : motorola-XT1072_PT7532
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, motorola-XT1072_PT7532
I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3217): Creating BTConnectedThread
I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
,I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:11:28.134Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:28.567Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data,
,I/jxcore-log( 3217): ,
,I/jxcore-log( 3217): 2015-12-01T22:11:28.574Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:28.578Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:28.586Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:28.596Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3217): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2504, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2504, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3271): invalid rfc slot id: 23
,I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT8573
I/BtToSocketBase( 3217): Stop ReceivingThread
,I/BtToSocketBase( 3217): Stop SendingThread
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
,I/BtToSocketBase( 3217): Close bt socket
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3217): 2015-12-01T22:11:32.194Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3217): 
,W/bt-rfcomm( 3271): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3271): RFCOMM_DisconnectInd LCID:0x41
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,W/bt-btif ( 3271): dm_pm_timer expires
,W/bt-btif ( 3271): dm_pm_timer expires 0
W/bt-btif ( 3271): proc dm_pm_timer expires
,I/jxcore-log( 3217): 2015-12-01T22:11:34.902Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:34.903Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:34.905Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:11:34.906Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:34.908Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3217): 
,I/BtToSocketBase( 3217): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3217): Disconnect outgoing peer: motorola-XT1072_PT7532
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread
I/BtToSocketBase( 3217): Close local in
,I/BtToSocketBase( 3217): Close LocalOutputStream
I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
,I/BtToSocketBase( 3217): Close bt socket
I/BtToRequestSocket( 3217): Close server socket
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 3271): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: S5mini-1
,I/        ( 3217): Cleared service requests
I/        ( 3217): Started peer discovery
,W/bt-btif ( 3271): invalid rfc slot id: 25
I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT7532
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread
,I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
,I/BtToSocketBase( 3217): Close localHostSocket
,I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
I/BtToSocketBase( 3217): Close bt socket
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3217): 2015-12-01T22:11:38.679Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:39.907Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:39.908Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3217): Found 12 peers.
,I/SS      ( 3217): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3217): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3217): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3217): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3217): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3217): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3217): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3217): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3217): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3217): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3217): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3217): Peer(12): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3217): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3217): Added service request
,I/        ( 3217): Started service discovery
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 3271): info:x10,
D/        ( 3271): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3217): we got incoming connection
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
I/BTListenerThread( 3217): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/BTListenerThread( 3217): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3217): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3217): MESSAGE_WRITE 82 bytes.
I/HS      ( 3217): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT8573
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3217): Starting the connected thread incoming : true, samsung-SM-G800F_PT8573
,I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3217): Creating BTConnectedThread
I/BtConnectorHelper( 3217): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3217): --DoOneRunRound started
,I/BtToRequestSocket( 3217): LocalHost address: localhost/127.0.0.1, port: 48280
,I/BtToRequestSocket( 3217): --DoOneRunRound ended
,I/jxcore-log( 3217): 2015-12-01T22:11:43.024Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:43.453Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:43.458Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:43.463Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:43.466Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:11:43.494Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3271): onReceive,
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 3959): Bluetooth Device Name: XT1072
,I/jxcore-log( 3217): 2015-12-01T22:11:44.914Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
,I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:11:44.915Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:11:44.915Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:11:44.916Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: 44:80:EB:7B:5A:05, name: XT1072,
,I/BTConnectToThread( 3217): Starting to connect
W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3217): Connecting to XT1072, at 44:80:EB:7B:5A:05
D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3217): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8176","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8176","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT8176, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT8176, WifiDirectName: , WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/        ( 3217): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2504, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2504, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3217): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2405, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2405, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3217): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8736, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8736, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3217): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT4379, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT4379, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3217): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f0579c rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3271): invalid rfc slot id: 26
,I/BtToSocketBase( 3217): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT8573
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
,I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3217): Close bt out
I/BtConnectorHelper( 3217): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3217): Close bt socket
I/BtConnectorHelper( 3217): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT8573
I/BtToSocketBase( 3217): Close bt in
I/BtToSocketBase( 3217): Close bt out
I/BtToSocketBase( 3217): Close bt socket
I/jxcore-log( 3217): 2015-12-01T22:11:53.969Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3217): 
,W/bt-rfcomm( 3271): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 3271): RFCOMM_DisconnectInd LCID:0x45
,I/        ( 3217): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3477, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3477, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3217): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6174, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6174, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3217): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3584, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3584, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: S5mini-1
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,I/        ( 3217): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 3285): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,V/GoogleAuthProtoRequest( 3288): [340] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3288): [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3288): [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3288): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3288): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3288): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3288): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3288): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3288): 	at com.a.a.k.run(SourceFile:110)
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3285): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3217): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3271): info:x10
D/        ( 3271): remote version info [44:80:eb:7b:5a:05]: 6, f, 410d,
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 3271): process_service_search_attr_rsp
,W/bt-btif ( 3271): new conn_srvc id:26, app_id:1
W/bt-btif ( 3271): bta_dm_pm_ssr conn_srvc id:26, app_id:1,
W/bt-btif ( 3271): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3217): Starting to Handshake
I/BTHandshakeSocketThread( 3217): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3217): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread started
,I/BTConnectToThread( 3217): got MESSAGE_READ 81 bytes.,
,I/BTConnectToThread( 3217): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3217): HandshakeOk : motorola-XT1072_PT7532
I/HS      ( 3217): Hand Shake finished outgoing for : motorola-XT1072_PT7532
,I/BTHandshakeSocketThread( 3217): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3217): Starting the connected thread incoming : false, motorola-XT1072_PT7532
I/BtToSocketBase( 3217): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3217): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3217): mHTTPPort  set to : 40427
,I/BtConnectorHelper( 3217): Request socket is using : 40427
,I/BtToRequestSocket( 3217): Now accepting connections
,I/BtConnectorHelper( 3217): Calling ConnectionStatusUpdate with port :40427,
I/jxcore-log( 3217): 2015-12-01T22:12:06.917Z SendDataConnector.js: CLIENT connected to 40427, error: null
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:12:06.918Z SendDataConnector.js: CLIENT starting client ,
I/jxcore-log( 3217): 
I/BtToRequestSocket( 3217): incoming data from: /127.0.0.1, port: 40427,
I/BtToRequestSocket( 3217): Set local streams
I/BtToRequestSocket( 3217): rin ended ---------------------------;
I/jxcore-log( 3217): 2015-12-01T22:12:06.930Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3217): 
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3271): tBTM_SEC_DEV:0xa2f055d4 rs_disc_pending=0
,W/bt-btif ( 3271): bta_dm_check_av:0
W/bt-btif ( 3271): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/KeepSync( 3315): Connecting to GoogleApiClient
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1775): Handling authorization failure
E/ClientConnectionOperation( 1775): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1775): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1775): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1775): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1775): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1775): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1775): 	... 7 more
,V/KeepSync( 3315): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3315): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 49863(2MB) AllocSpace objects, 7(489KB) LOS objects, 32% free, 33MB/49MB, paused 2.203ms total 97.636ms
,E/KeepSync( 3315): IOException
E/KeepSync( 3315): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3315): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3315): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3315): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3315): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3315): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3315): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3315): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3315): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3315): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3315): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3315): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3315): 	... 10 more
,W/KeepSync( 3315): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 661436, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-btif ( 3271): dm_pm_timer expires
,W/bt-btif ( 3271): dm_pm_timer expires 0
,W/bt-btif ( 3271): proc dm_pm_timer expires
,I/        ( 3217): Cleared service requests
,I/        ( 3217): Started peer discovery
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3217): Found 14 peers.
,I/SS      ( 3217): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3217): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3217): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3217): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3217): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3217): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3217): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3217): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3217): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
,I/SS      ( 3217): Peer(10): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3217): Peer(11): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3217): Peer(12): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3217): Peer(13): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3217): Peer(14): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3217): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 3217): Added service request
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3285): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3217): Started service discovery
,D/HeadsetStateMachine( 3271): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3285): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3217): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/jxcore-log( 3217): 2015-12-01T22:12:16.992Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:12:16.993Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:16.994Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:12:16.996Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:12:17.000Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3217): 
,I/BtToSocketBase( 3217): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3217): Disconnect outgoing peer: motorola-XT1072_PT7532
I/BtToSocketBase( 3217): Stop ReceivingThread
I/BtToSocketBase( 3217): Stop SendingThread,
I/BtToSocketBase( 3217): Close local in
I/BtToSocketBase( 3217): Close LocalOutputStream
I/BtToSocketBase( 3217): Close localHostSocket
I/BtToSocketBase( 3217): Close bt in
,I/BtToSocketBase( 3217): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3217): Close bt out
I/BtToSocketBase( 3217): Close bt socket
I/BtToRequestSocket( 3217): Close server socket
,W/bt-btif ( 3271): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,I/        ( 3217): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2504, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2504, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3217): 2015-12-01T22:12:22.000Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:22.001Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3271): onReceive
,I/BTConnectionReceiver( 3959): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3959): Bluetooth Device Name: XT1072,
,I/        ( 3217): Cleared service requests,
--------- beginning of crash
F/libc    ( 3285): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 3285 (wpa_supplicant)
I/libc    ( 3285): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,I/jxcore-log( 3217): 2015-12-01T22:12:27.006Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:12:27.006Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:12:27.007Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:27.007Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/BTConnectToThread( 3217): Starting to connect
,W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3217): Connecting to XT1072, at 44:80:EB:7B:5A:05
D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 3271): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3271): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3271): invalid rfc slot id: 29
I/BTConnectToThread( 3217): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3217): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3217): 2015-12-01T22:12:32.167Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:32.168Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:12:32.173Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:32.174Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:12:32.177Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3217): 
I/jxcore-log( 3217): ---- round done--------
I/jxcore-log( 3217): 
I/jxcore-log( 3217): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1,
I/jxcore-log( 3217): 
I/jxcore-log( 3217): do fake peer & start
I/jxcore-log( 3217): 
I/jxcore-log( 3217): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:32.180Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:12:32.180Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:12:32.181Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
I/        ( 3217): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3217): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3217): Starting to connect
W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3217): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 44:80:EB:7B:5A:05 done with result: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/WifiHW  (  823): 'P2P_FIND 120' command timed out.
,I/        ( 3217): Starting peer discovery failed, error code 0
,E/WifiStateMachine(  823): Connection lost, restart supplicant
,E/WifiMonitor(  823): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/Settings( 2627): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  823): failed to set BSSID: any
,E/native  (  823): do suspend true
W/Settings( 1747): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1534): Read error: ssl=0xaecf5600: I/O error during system call, Connection timed out
I/jxcore-log( 3217): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3217): 
I/jxcore-log( 3217): The Coordinator has disconnected!
I/jxcore-log( 3217): 
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,V/NativeCrypto( 1534): SSL shutdown failed: ssl=0xaecf5600: I/O error during system call, Broken pipe
,D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  823): Unexpected BatchedScanResults :null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/WifiScanningService(  823): SCAN_AVAILABLE : 1
D/RttService(  823): SCAN_AVAILABLE : 1
D/RttService(  823): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  823): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  823): DefaultState
,I/        ( 3217): Discovery state changed to Stopped.
I/WB      ( 3217): Wifi is DISABLED !!
I/        ( 3217): Stoping All
I/        ( 3217): Stopping services
I/        ( 3217): Stopping services
,I/        ( 3217): Stop Bluetooth
I/        ( 3217): Stop Bluetooth
I/BTListenerThread( 3217): Stopped
I/BTConnectToThread( 3217): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/SS      ( 3217): We got empty peers list
E/bt-btif ( 3271): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:30, channel:-1
I/        ( 3217): Starting peer discovery failed, error code 2
,I/CONNEC  ( 3217): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3217): 2015-12-01T22:12:36.582Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:36.582Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:36.583Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3217): 
I/        ( 3217): Clearing local services failed, error code 2
I/        ( 3217): Clearing service requests failed, error code 2
I/        ( 3217): Stopping peer discovery failed, error code 2
,D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Disconnected - quitting
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  823): MasterInitialState.processMessage what=3
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  823): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,I/NetworkMonitor( 3456): type=WIFI subType= reason=null isConnected=false
,E/GpsLocationProvider(  823): No APN found to select.
,D/Tethering(  823): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3456): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
,I/ActivityManager(  823): Start proc 4155:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/GpsLocationProvider(  823): No APN found to select.
,D/SprintDMReceiver( 4155): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4155): simOperator:  IMSI: null
D/SprintDMReceiver( 4155): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1775): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1775): onCreate
,D/SystemUpdateService( 1775): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1775): active receiver: enabled
,I/SystemUpdateService( 1775): showing system update notification
,I/iu.Environment( 1775): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1775): num queued entries: 0
I/iu.UploadsManager( 1775): num updated entries: 0
I/iu.SyncManager( 1775): NEXT; no task
D/ChimeraCfgMgr( 1775): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  823): skipping global notification,
,V/SystemUpdateService( 1775): retry (wakeup: false) in 3599976 ms
,I/Babel   ( 2627): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  823): Start proc 4175:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1775): onDestroy
,I/ActivityManager(  823): Killing 3733:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/GAv4    ( 4175): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4175):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4175):   adb logcat -s GAv4
,W/GAv4    ( 4175): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4175): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4175): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/bt-sdp  ( 3271): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3271): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3271): invalid rfc slot id: 30
,I/WebViewFactory( 4175): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4175): Time to load native libraries: 1 ms (timestamps 9017-9018)
I/LibraryLoader( 4175): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4175): Binding Chromium to main looper Looper (main, tid 1) {eaaebdc}
I/LibraryLoader( 4175): Expected native library version number "",actual native library version number "",
I/chromium( 4175): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 4175): Initializing chromium process, singleProcess=true
W/art     ( 4175): Attempt to remove local handle scope entry from IRT, ignoring,
E/SysUtils( 4175): ApplicationContext is null in ApplicationStatus,
,W/chromium( 4175): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4175): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 4175): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 4175): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 4175): Requires BLUETOOTH permission
,I/NSApplication( 4175): Starting up...
,I/ActivityManager(  823): Killing 3652:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
I/jxcore-log( 3217): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3217): 
,D/WifiService(  823): setWifiEnabled: false pid=3217, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  823): setWifiEnabled: true pid=3217, uid=10265,
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiController(  823): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 481ms
,I/jxcore-log( 3217): Wifi toggled for connection repairment
I/jxcore-log( 3217): 
,I/chromium( 3217): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  823): Start proc 4233:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,V/MusicLeanback( 3456): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  823): Killing 3669:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/WifiController(  823): DEFERRED_TOGGLE handled
,D/SoftapController(  354): Softap fwReload - Ok
,D/CommandListener(  354): Setting iface cfg
,D/CommandListener(  354): Trying to bring down wlan0
,D/SprintDMReceiver( 4155): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  823): InitialState.processMessage what=4
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/SprintDMHelper( 4155): simOperator:  IMSI: null
D/SprintDMReceiver( 4155): Not Sprint UICC, don't do anything.
D/Tethering(  823): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiMonitor(  823): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/WifiMonitor(  823): startMonitoring(wlan0) with mConnected = false
I/SystemUpdateService( 1775): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,E/WifiHW  (  823): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,D/SystemUpdateService( 1775): onCreate
,D/SystemUpdateService( 1775): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1775): active receiver: enabled
,I/SystemUpdateService( 1775): showing system update notification
,I/wpa_supplicant( 4250): Successfully initialized wpa_supplicant
,D/ChimeraCfgMgr( 1775): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1775): retry (wakeup: false) in 3599974 ms
,D/SystemUpdateService( 1775): onDestroy
,I/wpa_supplicant( 4250): rfkill: Cannot open RFKILL control device
,D/Tethering(  823): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4250): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 4250): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  823): Loading config and enabling all networks 
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3aa3f88f}
,E/WifiConfigStore(  823): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  823): Setting external_sim to 1
W/Settings( 2627): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  823): Setting OUI to 92-68-C3
I/WifiNative-HAL(  823): startHal
,D/wifi    (  823): setting scan oui 0xb4b6ecd0
D/WifiHAL (  823): Sending mac address OUI
,E/native  (  823): do suspend true
,W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
D/WifiScanningService(  823): SCAN_AVAILABLE : 3
,D/WifiScanningService(  823): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService(  823): SCAN_AVAILABLE : 3
I/WifiNative-HAL(  823): startHal
D/wifi    (  823): getting scan capabilities on interface[0] = 0xb4b6ecd0
D/WifiHAL (  823): Creating message to get scan capablities; iface = 5
D/WifiHAL (  823): In GetCapabilities::handleResponse
D/WifiHAL (  823): Id = 0, subcmd = 0, len = 28, expected len = 32,
D/WifiScanningService(  823): StartedState
D/CommandListener(  354): Setting iface cfg
,D/RttService(  823): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiP2pService(  823): Unable to change interface settings: java.lang.IllegalStateException: command '56 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 56 Failed to set address (No such device)'
D/WifiMonitor(  823): startMonitoring(p2p0) with mConnected = true
,I/WB      ( 3217): Wifi is now enabled !
I/        ( 3217): Stoping All
I/        ( 3217): Stopping services
I/        ( 3217): Stop Bluetooth
I/        ( 3217): Starting All
,I/        ( 3217): Stopping services
I/        ( 3217): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@189b43d3
I/        ( 3217): Stopping services
I/        ( 3217): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}
,D/WifiNative-HAL(  823): p2pGetDeviceAddress
D/WifiNative-HAL(  823): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
I/        ( 3217): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}, length : 82
,I/        ( 3217): peerDiscoveryTimer timeout value:5426
I/        ( 3217): Stop Bluetooth
I/        ( 3217): StartBluetooth listener
I/        ( 3217): StartBluetooth listener
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3217): Added local service
I/        ( 3217): Discovery state changed to Stopped.
I/        ( 3217): Cleared service requests,
I/BTListenerThread( 3217): starting to listen
I/BTListenerThread( 3217): waiting to accept incoming Connection
,I/wpa_supplicant( 4250): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/        ( 3217): Stopped peer discovery
,I/        ( 3217): Started peer discovery,
I/        ( 3217): Discovery state changed to Started.
I/        ( 3217): Started peer discovery
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3217): 
,I/chromium( 3217): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4250): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  823):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  823):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  823): will read network variables netId=0
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0,
E/WifiConfigStore(  823): will read network variables netId=0
,I/jxcore-log( 3217): 2015-12-01T22:12:41.584Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:41.585Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
,I/wpa_supplicant( 4250): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 4250): wlan0: Trying to associate with SSID 'NG7005g'
,I/SS      ( 3217): Found 1 peers.
,I/SS      ( 3217): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
D/WifiP2pManager( 3217): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3217): Added service request
,I/        ( 3217): Started service discovery
,I/wpa_supplicant( 4250): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4250): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4250): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 2
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
E/WifiStateMachine(  823):  my bss beacon rx: 0
E/WifiStateMachine(  823):  RSSI mgmt: -45
E/WifiStateMachine(  823):  BE :  rx=0 tx=2 lost=0 retries=0
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 0 tx_time=172 rx_time=433 scan_time=0
,E/native  (  823): do suspend false
,E/WifiStateMachine(  823): scanCount==0 - aborting
,I/wpa_supplicant( 4250): P2P-FIND-STOPPED 
,I/        ( 3217): Discovery state changed to Stopped.
,I/        ( 3217): Starting peer discovery failed, error code 2
,I/dhcpcd  ( 4267): version 5.5.6 starting
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3217): 
I/jxcore-log( 3217): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3217): 
,I/chromium( 3217): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63),
,I/dhcpcd  ( 4267): wlan0: rebinding lease of 192.168.1.110
,I/wpa_supplicant( 4250): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3217): Found 2 peers.,
I/SS      ( 3217): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3217): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3217): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3217): Added service request
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3aa3f88f}
,I/        ( 3217): Starting service discovery failed, error code 2
,I/        ( 3217): Cleared service requests
,I/dhcpcd  ( 4267): wlan0: acknowledged 192.168.1.110 from 192.168.1.1,
,I/dhcpcd  ( 4267): wlan0: leased 192.168.1.110 for 86400 seconds
,E/native  (  823): do suspend true,
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  823): Adding iface wlan0 to network 101
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  823): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/Tethering(  823): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3456): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,E/GpsLocationProvider(  823): No APN found to select.
,V/MusicLeanback( 3456): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 4155): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4155): simOperator:  IMSI: null
D/SprintDMReceiver( 4155): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1775): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1775): onCreate
,D/SystemUpdateService( 1775): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1775): active receiver: enabled
,I/SystemUpdateService( 1775): showing system update notification
,I/iu.Environment( 1775): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1775): num queued entries: 0
I/iu.UploadsManager( 1775): num updated entries: 0
I/iu.SyncManager( 1775): NEXT; no task
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1775): retry (wakeup: false) in 3599980 ms
,D/ChimeraCfgMgr( 1775): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1775): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1775): onDestroy
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1534): Explicit concurrent mark sweep GC freed 55221(2MB) AllocSpace objects, 13(1434KB) LOS objects, 36% free, 27MB/43MB, paused 1.963ms total 44.422ms
,W/Kids    ( 1775): [AccountUtils] Account not ready,
W/Kids    ( 1775): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1775): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1775): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1775): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1775): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1775): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1775): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1775): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1775): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1775): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1775): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1775): 	at java.lang.Thread.run(Thread.java:818)
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 01 Dec 2015 22:12:46 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449007966470], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449007966454]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  823): Validated
,D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,V/Herrevad( 1775): NQAS connected
,I/Babel   ( 2627): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3217): 2015-12-01T22:12:46.587Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:46.587Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:46.587Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:46.587Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3217): Starting to connect
W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3217): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/GCM     ( 1534): Connected
,D/GCM     ( 1534): Message class com.google.f.a.a.p
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3217): DBG, CoordinatorConnector connect called
I/jxcore-log( 3217): 
I/jxcore-log( 3217): Coordinator is now connected to the server!
I/jxcore-log( 3217): 
,I/chromium( 3217): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-sdp  ( 3271): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
,E/bt-btif ( 3271): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3271): invalid rfc slot id: 32
,I/BTConnectToThread( 3217): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/CONNEC  ( 3217): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3217): 2015-12-01T22:12:51.745Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:51.746Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed,
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:51.747Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3217): 
,I/wpa_supplicant( 4250): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3217): Found 2 peers.
I/SS      ( 3217): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3217): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3217): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 3217): Added service request
,I/wpa_supplicant( 4250): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4250): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3217): Started service discovery,
,I/wpa_supplicant( 4250): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3217): 2015-12-01T22:12:56.748Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:12:56.748Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:01.751Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:01.752Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:01.753Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:13:01.754Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3217): Connecting to null, at F8:95:C7:87:85:54,
I/BTConnectToThread( 3217): Starting to connect
,W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 3271): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3271): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3271): invalid rfc slot id: 33
I/BTConnectToThread( 3217): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3217): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3217): 2015-12-01T22:13:06.912Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed,
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:06.913Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
,I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:13:06.917Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:11.917Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:13:11.918Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
,I/        ( 3217): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}, typeCordovap2p._tcp.local.:
,I/        ( 3217): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT384, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT384, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/BooksSync( 3512): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3512): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  823): Explicit concurrent mark sweep GC freed 64499(3MB) AllocSpace objects, 5(174KB) LOS objects, 31% free, 34MB/50MB, paused 1.524ms total 60.775ms
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1534): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1534): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1534): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1534): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1534): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3512): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3512): Soft error
E/BooksSync( 3512): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3512): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3512): Sync error
E/BooksSync( 3512): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3512): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3512): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 700985, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3217): 2015-12-01T22:13:16.922Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:16.923Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:16.925Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:13:16.925Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): ,
,I/        ( 3217): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3217): Starting to connect
,W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3217): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3271): info:x10
D/        ( 3271): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3271): process_service_search_attr_rsp
,E/bt-btif ( 3271): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3271): invalid rfc slot id: 34
I/BTConnectToThread( 3217): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3217): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3217): 2015-12-01T22:13:18.902Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:18.903Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:13:18.904Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3217): 
,I/        ( 3217): Cleared service requests
,I/        ( 3217): Started peer discovery
,I/        ( 3217): Discovery state changed to Started.
,D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3217): 2015-12-01T22:13:23.906Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:23.907Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
,I/wpa_supplicant( 4250): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3217): Found 4 peers.
,I/SS      ( 3217): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3217): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3217): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3217): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
D/WifiP2pManager( 3217): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3217): Added service request
,I/        ( 3217): Started service discovery
,I/        ( 3217): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3584, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3584, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0,
,I/        ( 3217): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3217): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2504, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3217): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2504, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3217): 2015-12-01T22:13:28.910Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:28.911Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:13:28.912Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:13:28.913Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3217): Starting to connect
,I/        ( 3217): Connecting to null, at F8:95:C7:87:85:54
W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3271): info:x10
D/        ( 3271): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3271): process_service_search_attr_rsp
,E/bt-btif ( 3271): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3271): invalid rfc slot id: 35
I/BTConnectToThread( 3217): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3217): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3217): 2015-12-01T22:13:30.080Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:30.081Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:30.086Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:13:30.090Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3217): 
I/jxcore-log( 3217): ---- round done--------
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 3217): 
I/jxcore-log( 3217): do fake peer & start
I/jxcore-log( 3217): 
I/jxcore-log( 3217): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:30.093Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:30.094Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:13:30.095Z SendDataConnector.js: do connect now
I/jxcore-log( 3217): 
,I/        ( 3217): Selected device address: 08:EC:A9:50:76:27, name: null
,I/BTConnectToThread( 3217): Starting to connect
,W/BluetoothAdapter( 3217): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3217): Connecting to null, at 08:EC:A9:50:76:27
,I/chromium( 3217): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:85:54 done with result: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3271): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3271): info:x10
,D/        ( 3271): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3,
,E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3271): process_service_search_attr_rsp
,E/bt-btif ( 3271): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3271): invalid rfc slot id: 36
,I/BTConnectToThread( 3217): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3217): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3217): 2015-12-01T22:13:31.521Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3217): 
,I/jxcore-log( 3217): 2015-12-01T22:13:31.522Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:13:31.523Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3217): 
,E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
,I/        ( 3217): Cleared service requests
,I/        ( 3217): Started peer discovery
,TIME-OUT KILL (timeout was 600000ms),E/bt-btm  ( 3271): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3271): aclStateChangeCallback: Device is NULL
D/btif_config_util( 3271): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/jxcore-log( 3217): 2015-12-01T22:13:36.524Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3217): 
I/jxcore-log( 3217): 2015-12-01T22:13:36.526Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3217): 
I/        ( 3217): Cleared service requests
I/        ( 3217): Started peer discovery
D/AndroidRuntime( 4337): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4337): CheckJNI is OFF
D/AndroidRuntime( 4337): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  823): Killing 3217:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  823): Skipping PackageSetting{178872ed com.example.hello/10272} due to missing metadata
E/libprocessgroup(  823): failed to kill 1 processes for processgroup 3217
W/ActivityManager(  823): Force removing ActivityRecord{1a7509df u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
E/JavaBinder(  823): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  823): !!! FAILED BINDER TRANSACTION !!!
V/ActivityManager(  823): Display changed displayId=0
D/WifiService(  823): Client connection lost with reason: 4
W/DisplayManagerService(  823): Failed to notify process 3217 that displays changed, assuming it died.
W/DisplayManagerService(  823): android.os.DeadObjectException
W/DisplayManagerService(  823): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService(  823): 	at android.os.BinderProxy.transact(Binder.java:496)
W/DisplayManagerService(  823): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService(  823): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1094)
W/DisplayManagerService(  823): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:932)
W/DisplayManagerService(  823): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:112)
W/DisplayManagerService(  823): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1027)
W/DisplayManagerService(  823): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService(  823): 	at android.os.Looper.loop(Looper.java:135)
W/DisplayManagerService(  823): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService(  823): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
I/InputReader(  823): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1214): resetDictionaries() : en_US
D/TaskPersister(  823): removeObsoleteFile: deleting file=24_task.xml
D/BuaReceiver( 3082): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/art     ( 1064): Explicit concurrent mark sweep GC freed 63290(2MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 73MB/89MB, paused 986us total 59.713ms
I/Keyboard.Facilitator.DecoderInitializer( 1214): run()
I/Decoder ( 1214): createOrResetDecoder
W/InputMethodManagerService(  823): Got RemoteException sending setActive(false) notification to pid 3217 uid 10265
I/Keyboard.Facilitator( 1214): onFinishInput()
I/ActivityManager(  823): Start proc 4353:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/art     (  823): Explicit concurrent mark sweep GC freed 14633(1014KB) AllocSpace objects, 5(268KB) LOS objects, 32% free, 33MB/49MB, paused 1.575ms total 99.219ms
I/art     (  823): WaitForGcToComplete blocked for 46.897ms for cause Explicit
I/ConfigService( 1534): onCreate
I/art     ( 1320): Explicit concurrent mark sweep GC freed 5671(417KB) AllocSpace objects, 11(1298KB) LOS objects, 31% free, 35MB/51MB, paused 1.078ms total 27.883ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1214): run()
D/JobSchedulerService(  823): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  823): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/Keyboard.Facilitator.MainLanguageModelLoader( 1214): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1214): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1214): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1214): run()
I/StatsUtilsManager( 1214): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1214): shouldRecordStats() = Too Soon
D/Launcher.Workspace( 1320): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1320): 11683562 - stripEmptyScreens()
D/VoicemailCleanupService( 4353): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  823): Start proc 4393:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/art     (  823): Explicit concurrent mark sweep GC freed 6351(311KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.607ms total 156.732ms
I/VS.Container( 3959): create_recognizer
I/ActivityManager(  823): Start proc 4414:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/ActivityManager(  823): Killing 3691:com.android.providers.calendar/u0a3 (adj 15): empty #17
I/ContactLocale( 4353): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/HotwordRecognitionRnr( 3959): Starting hotword detection.
I/MicrophoneInputStream( 3959): mic_starting com.google.android.apps.gsa.speech.audio.u@2a9dd49c
I/AudioFlinger(  358): AudioFlinger's thread 0xb4cd0000 ready to run
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 3959): mic_started com.google.android.apps.gsa.speech.audio.u@2a9dd49c
I/art     ( 4337): System.exit called, status: 0
I/AndroidRuntime( 4337): VM exiting with result code 0.
D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
W/ContextImpl( 4414): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1534): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1534): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1775): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1775): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1775): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1775): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1775): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1775): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1775): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1775): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1775): disk I/O error (code 3850)
E/DriveAsyncService( 1775): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1775): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1775): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1775): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1775): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1775): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1775): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1775): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1775): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1775): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1775): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1775): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1775): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1775): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1775): 	at java.lang.Thread.run(Thread.java:818)
I/LocationSettingsChecker( 1775): Removing dialog suppression flag for package com.test.thalitest
E/AndroidRuntime( 1775): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1775): Process: com.google.android.gms, PID: 1775
E/AndroidRuntime( 1775): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1775): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1775): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1775): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1775): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1775): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1775): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1775): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1775): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1775): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1775): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1775): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1775): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1775): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1775): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1775): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1775): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1775): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1775): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 1775): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1775): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1775): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1775): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1775): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1775): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1775): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1775): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1775): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1775): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1775): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1775): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1775): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1775): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1775): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1775): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1775): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1775): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1775): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1775): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1775): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1775): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1775): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1775): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1775): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1775): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1775): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1775): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1775): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1775): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1775): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1775): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1775): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1775): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1775): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1775): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1775): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1775): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1775): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1775): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1775): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1775): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1775): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1775): Sending signal. PID: 1775 SIG: 9
E/DropBoxManagerService(  823): Can't write: system_app_crash
E/DropBoxManagerService(  823): java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  823): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  823): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  823): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  823): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  823): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  823): 	... 5 more
W/ResourcesManager(  823): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  823): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/OpenGLRenderer(  823): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  823): Validating map...
I/OpenGLRenderer(  823): Initialized EGL, version 1.4
I/HotwordWorker( 3959): onReady
D/OpenGLRenderer(  823): Enabling debug mode 0
E/Search.SharedPreferencesProto( 3959): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
E/JavaBinder( 3959): !!! FAILED BINDER TRANSACTION !!!
W/GmsClient( 3959): Remote exception occurred
W/GmsClient( 3959): android.os.TransactionTooLargeException
W/GmsClient( 3959): 	at android.os.BinderProxy.transactNative(Native Method)
W/GmsClient( 3959): 	at android.os.BinderProxy.transact(Binder.java:496)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.ao.a(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.r.a(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.api.ag.aYh(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.api.ag.aYe(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.api.ag.g(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.api.aj.b(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.z.aYZ(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.s.f(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.s.bC(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.u.aZb(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.t.handleMessage(Unknown Source)
W/GmsClient( 3959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/GmsClient( 3959): 	at android.os.Looper.loop(Looper.java:135)
W/GmsClient( 3959): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
W/GmsClient( 3959): 	at java.lang.reflect.Method.invoke(Native Method)
W/GmsClient( 3959): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/GmsClient( 3959): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
W/GmsClient( 3959): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/JavaBinder( 3959): !!! FAILED BINDER TRANSACTION !!!
W/GmsClient( 3959): Remote exception occurred
W/GmsClient( 3959): android.os.TransactionTooLargeException
W/GmsClient( 3959): 	at android.os.BinderProxy.transactNative(Native Method)
W/GmsClient( 3959): 	at android.os.BinderProxy.transact(Binder.java:496)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.ao.a(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.r.a(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.api.ag.aYh(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.api.ag.aYe(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.api.ag.g(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.api.aj.b(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.z.aYZ(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.s.f(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.s.bC(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.u.aZb(Unknown Source)
W/GmsClient( 3959): 	at com.google.android.gms.common.internal.t.handleMessage(Unknown Source)
W/GmsClient( 3959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/GmsClient( 3959): 	at android.os.Looper.loop(Looper.java:135)
W/GmsClient( 3959): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
W/GmsClient( 3959): 	at java.lang.reflect.Method.invoke(Native Method)
W/GmsClient( 3959): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/GmsClient( 3959): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
W/GmsClient( 3959): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/WifiService(  823): Client connection lost with reason: 4
E/Search.IcingConnection( 3959): Could not connect to Icing. Error code 8.
W/Launcher( 1320): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@31095d20 new=com.google.android.velvet.VelvetApplication@31095d20
E/SQLiteLog( 1320): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
I/ActivityManager(  823): Start proc 4457:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
I/ActivityManager(  823): Process com.google.android.gms (pid 1775) has died
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
W/ActivityManager(  823): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
E/SharedPreferencesImpl( 3959): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 3959): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 3959): Process: com.google.android.googlequicksearchbox:search, PID: 3959
E/AndroidRuntime( 3959): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 3959): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:108)
E/AndroidRuntime( 3959): 	at com.google.android.apps.gsa.shared.e.j.c(ExtraDexRegistry.java:214)
E/AndroidRuntime( 3959): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.bb(UpdateIcingCorporaService.java:232)
E/AndroidRuntime( 3959): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:205)
E/AndroidRuntime( 3959): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3959): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 3959): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 3959): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime( 3959): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime( 3959): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime( 3959): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:94)
E/AndroidRuntime( 3959): 	... 7 more
E/AndroidRuntime( 3959): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 3959): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime( 3959): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime( 3959): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 3959): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 3959): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 3959): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 3959): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3959): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3959): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 3959): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 3959): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 3959): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime( 3959): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime( 3959): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime( 3959): 	... 9 more
E/AndroidRuntime( 3959): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 3959): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime( 3959): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime( 3959): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime( 3959): 	... 11 more
I/art     (  370): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 209us total 16.737ms
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 9.181ms
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 195us total 9.084ms
I/ActivityManager(  823): Start proc 4476:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
E/DropBoxManagerService(  823): Can't write: system_app_crash
E/DropBoxManagerService(  823): java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  823): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  823): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  823): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  823): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  823): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  823): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  823): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  823): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  823): 	... 5 more
I/HotwordDetector( 3959): Closing mic
I/MicrophoneInputStream( 3959): mic_close com.google.android.apps.gsa.speech.audio.u@2a9dd49c
I/ActivityManager(  823): Start proc 4495:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
W/ResourcesManager( 4495): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4495): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/TRUiThreadExecutor( 3959): Task does not implement UiTask: com.google.common.g.a.p@2ddf0500
I/OpenGLRenderer(  823): Initialized EGL, version 1.4
W/InputMethodManagerService(  823): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@12a1789f attribute=null, token = android.os.BinderProxy@1e9018bf
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 3959): Hotword detection finished
I/HotwordRecognitionRnr( 3959): Stopping hotword detection.
I/MultiDex( 4495): VM with version 2.1.0 has multidex support
I/MultiDex( 4495): install
I/MultiDex( 4495): VM has multidex support, MultiDex support library is disabled.
E/Search.SharedPreferencesProto( 3959): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
W/LocationOracleImpl( 3959): Best location was null
E/Search.SharedPreferencesProto( 3959): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak

```
