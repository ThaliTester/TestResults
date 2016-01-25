#### Test 57132760f6ec045_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2725): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2725): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2725): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3159): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3159): CheckJNI is OFF
D/AndroidRuntime( 3159): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{9ea75b8 token=Token{200001b ActivityRecord{34137a2a u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
V/WindowManager(  821): Adding window Window{c5c63cd u0 Starting com.test.thalitest} at 2 of 7 (after Window{180183a2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3159): Shutting down VM
I/HotwordDetector( 1503): Closing mic
I/MicrophoneInputStream( 1503): mic_close com.google.android.apps.gsa.speech.audio.u@361a1782
I/ActivityManager(  821): Start proc 3173:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1503): Stopping hotword detection.
I/HotwordRecognitionRnr( 1503): Hotword detection finished
I/ActivityManager(  821): Killing 2816:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1720206611
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/kickstart(  875): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  875): STATUS: Wrote to /sys/power/wake_lock
,I/WebViewFactory( 3173): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3173): Time to load native libraries: 2 ms (timestamps 1606-1608)
,I/LibraryLoader( 3173): Expected native library version number "",actual native library version number ""
,E/kickstart(  875): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  875): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,V/WebViewChromiumFactoryProvider( 3173): Binding Chromium to main looper Looper (main, tid 1) {1adc5625}
I/LibraryLoader( 3173): Expected native library version number "",actual native library version number ""
,I/chromium( 3173): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3173): Initializing chromium process, singleProcess=true
W/art     ( 3173): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3173): ApplicationContext is null in ApplicationStatus
,W/chromium( 3173): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3173): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3173): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3173): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3173): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f1ada3d:true
,D/BluetoothAdapter( 3173): 831656116: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3173): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3173): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3173): CordovaWebView is running on device made by: motorola
,W/art     ( 3173): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3173): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3173): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3173): Validating map...
,V/WindowManager(  821): Adding window Window{145bccad u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{c5c63cd u0 Starting com.test.thalitest})
,W/chromium( 3173): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  821): Explicit concurrent mark sweep GC freed 24134(1062KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.903ms total 57.270ms
,I/OpenGLRenderer( 3173): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3173): Enabling debug mode 0
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +656ms
,I/Keyboard.Facilitator( 1215): onFinishInput()
,W/BindingManager( 3173): Cannot call determinedVisibility() - never saw a connection for the pid: 3173
,D/JsMessageQueue( 3173): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3173): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576257408
,I/chromium( 3173): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/kickstart(  875): STATUS: Received file 'm9kefs1'
I/kickstart(  875): STATUS: 950272 bytes transferred in 0.994217 seconds
I/kickstart(  875): STATUS: Successfully downloaded files from target 
I/kickstart(  875): STATUS: Wrote to /sys/power/wake_unlock
I/kickstart(  875): STATUS: Sahara protocol completed
,W/jxcore-log( 3173): Initializing JXcore engine
W/jxcore-log( 3173): JXcore engine is ready
,W/Thread-326( 3225): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11466]" dev="sockfs" ino=11466 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
,W/Thread-326( 3225): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-326( 3225): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9809]" dev="sockfs" ino=9809 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-326( 3225): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21740]" dev="sockfs" ino=21740 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3173): Starting JXcore engine
,W/jxcore-log( 3173): Platform android
W/jxcore-log( 3173): 
W/jxcore-log( 3173): Process ARCH arm
W/jxcore-log( 3173): 
,I/jxcore-log( 3173): JXcore Cordova bridge is ready!
I/jxcore-log( 3173): 
W/jxcore-log( 3173): JXcore engine is started
,I/jxcore-log( 3173): Toggling radios to true
I/jxcore-log( 3173): 
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,D/BluetoothManagerService(  821): enable():  mBluetooth =null mBinding = false,
,D/BluetoothManagerService(  821): Message: 1
D/BluetoothManagerService(  821): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  821): setWifiEnabled: true pid=3173, uid=10265,
,D/WifiService(  821): New client listening to asynchronous messages,
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled,
,D/SoftapController(  353): Softap fwReload - Ok
I/jxcore-log( 3173): Radios toggled
I/jxcore-log( 3173): 
,D/CommandListener(  353): Setting iface cfg
,D/CommandListener(  353): Trying to bring down wlan0
,I/jxcore-log( 3173): My device name is: motorola-Nexus 6
I/jxcore-log( 3173): 
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,I/ActivityManager(  821): Start proc 3232:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/WifiMonitor(  821): startMonitoring(wlan0) with mConnected = false
,E/WifiHW  (  821): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/wpa_supplicant( 3244): Successfully initialized wpa_supplicant
,I/ActivityManager(  821): Start proc 3250:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,W/ResourcesManager( 3232): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3244): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  821): Start proc 3276:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
I/ActivityManager(  821): Killing 2684:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,D/AdapterServiceConfig( 3232): Adding HeadsetService
D/AdapterServiceConfig( 3232): Adding A2dpService
D/AdapterServiceConfig( 3232): Adding HidService
D/AdapterServiceConfig( 3232): Adding HealthService
D/AdapterServiceConfig( 3232): Adding PanService
D/AdapterServiceConfig( 3232): Adding GattService
,D/AdapterServiceConfig( 3232): Adding BluetoothMapService
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14606b06:true
,D/BluetoothAdapterState( 3232): make
,I/bluedroid( 3232): init
,I/BluetoothAdapterState( 3232): Entering OffState
,I/bte_conf( 3232): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3232): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3232): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3232): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found,
,I/bluedroid( 3232): get_profile_interface socket
I/bluedroid( 3232): get_profile_interface map_client
,I/GKI_LINUX( 3232): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 3232): Address is:F8:CF:C5:D9:E5:61
D/BluetoothAdapterProperties( 3232): Name is: Nexus 6
,D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  821): Message: 40
D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6
,D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
,I/bluedroid( 3232): config_hci_snoop_log
D/BluetoothManagerService(  821): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  821): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3232): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3232): Setting state to 11
I/BluetoothAdapterState( 3232): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  821): Message: 60
,D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  821): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3232): make
I/BluetoothBondStateMachine( 3232): StableState(): Entering Off State
,I/BluetoothAdapterState( 3232): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3232): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ae23fa
D/HeadsetService( 3232): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3232): classInitNative: succeeds
D/HeadsetStateMachine( 3232): make
D/HeadsetStateMachine( 3232): max_hf_connections = 1
I/bluedroid( 3232): get_profile_interface handsfree
D/HeadsetStateMachine( 3232): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 3232): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ae23fa
D/BluetoothA2dp(  821): Proxy object connected
D/BluetoothA2dp( 1065): Proxy object connected
D/A2dpService( 3232): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3232): classInitNative: succeeds
I/bluedroid( 3232): get_profile_interface avrcp
E/RemoteController( 3232): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3232): classInitNative: succeeds
D/A2dpStateMachine( 3232): make
I/bluedroid( 3232): get_profile_interface a2dp
I/GKI_LINUX( 3232): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/A2dpStateMachine( 3232): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3232): classInitNative: succeeds
D/BluetoothAdapterService( 3232): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ae23fa
D/BluetoothInputDevice( 1065): Proxy object connected
D/HidService( 3232): Received start request. Starting profile...
I/bluedroid( 3232): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3232): classInitNative: succeeds
D/BluetoothAdapterService( 3232): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ae23fa
D/HealthService( 3232): Received start request. Starting profile...
I/bluedroid( 3232): get_profile_interface health
I/BluetoothPanServiceJni( 3232): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3232): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ae23fa
D/BluetoothPan( 1065): BluetoothPAN Proxy object connected
D/PanService( 3232): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 3232): initializeNative(L110): pan
I/bluedroid( 3232): get_profile_interface pan
I/BtGatt.JNI( 3232): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3232): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ae23fa
D/BtGatt.DebugUtils( 3232): handleDebugAction() action=null
D/BtGatt.GattService( 3232): Received start request. Starting profile...
D/BtGatt.GattService( 3232): start()
I/bluedroid( 3232): get_profile_interface gatt
D/BluetoothAdapterService( 3232): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ae23fa
D/BtGatt.AdvertiseManager( 3232): advertise manager created
,D/BluetoothAdapterService( 3232): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ae23fa
,D/BluetoothMap( 1065): Proxy object connected
D/BluetoothMapService( 3232): Received start request. Starting profile...
D/BluetoothMapService( 3232): start()
,D/BluetoothMapEmailSettingsLoader( 3232): Found 0 applications
D/BluetoothMapEmailAppObserver( 3232): createReceiver()
D/BluetoothMapEmailAppObserver( 3232): initObservers()
D/BluetoothMapEmailAppObserver( 3232): getEnabledAccountItems()
,D/HeadsetStateMachine( 3232): Proxy object connected
D/HeadsetStateMachine( 3232): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3232): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3232): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3232): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3232): enable
I/GKI_LINUX( 3232): gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3232): btu_task pending for preload complete event
I/bt_hci_bdroid( 3232): init
I/bt_vendor( 3232): init
I/bt_vnd_conf( 3232): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3232): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3232): userial_init
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 103841(6MB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 918us total 38.502ms
,I/bt_userial_vendor( 3232): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3232): device fd = 53 open
D/bt_userial( 3232): Entering userial_read_thread()
,I/bt_hwcfg( 3232): bt vendor lib: set UART baud 3000000
,I/ActivityManager(  821): Start proc 3318:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  821): Killing 2855:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/bt_hwcfg( 3232): Chipset BCM4354A2
D/bt_hwcfg( 3232): Target name = [BCM4354A2]
I/bt_hwcfg( 3232): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,D/Tethering(  821): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  821): Killing 2783:com.google.android.gm/u0a78 (adj 15): empty #17
,I/wpa_supplicant( 3244): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant( 3244): Could not read interface p2p-dev-wlan0 flags: No such device
,I/ActivityManager(  821): Start proc 3335:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/ActivityManager(  821): Killing 2346:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 323us total 17.998ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 224us total 13.863ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 224us total 11.266ms
,D/WifiConfigStore(  821): Loading config and enabling all networks 
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1d8f1a3e}
,E/WifiConfigStore(  821): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  821): Setting external_sim to 1
,W/Settings( 2639): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  821): Setting OUI to 92-68-C3
I/WifiNative-HAL(  821): startHal
D/wifi    (  821): setting scan oui 0xaec7b988
D/WifiHAL (  821): Sending mac address OUI
,E/WifiStateMachine(  821): cancelDelayedScan -> 1
,D/WifiScanningService(  821): SCAN_AVAILABLE : 3
D/RttService(  821): SCAN_AVAILABLE : 3
D/WifiScanningService(  821): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  821): startHal
D/RttService(  821): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
W/CommandListener(  353): Failed to retrieve HW addr for p2p0 (No such device)
D/wifi    (  821): getting scan capabilities on interface[0] = 0xaec7b988
D/WifiHAL (  821): Creating message to get scan capablities; iface = 5
D/WifiHAL (  821): In GetCapabilities::handleResponse
D/WifiHAL (  821): Id = 0, subcmd = 0, len = 28, expected len = 32
,D/CommandListener(  353): Setting iface cfg
D/WifiScanningService(  821): StartedState
,E/WifiP2pService(  821): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  821): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  821): p2pGetDeviceAddress
,D/WifiNative-HAL(  821): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 3244): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 3232): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3232): Settlement delay -- 100 ms
I/bt_hwcfg( 3232): Setting fw settlement delay to 100 
,E/native  (  821): do suspend false
,I/bt_hwcfg( 3232): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg( 3232): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3232): vendor lib fwcfg completed,
I/bt-btu  ( 3232): btu_task received preload complete event
,I/        ( 3232): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 3232): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3232): BTE_InitTraceLevels -- TRC_RFCOMM
,I/        ( 3232): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3232): BTE_InitTraceLevels -- TRC_AVRC
,I/        ( 3232): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3232): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3232): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 3232): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3232): BTE_InitTraceLevels -- TRC_PAN
,I/        ( 3232): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3232): BTE_InitTraceLevels -- TRC_GATT
,I/        ( 3232): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3232): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3232): BTE_InitTraceLevels -- TRC_BTIF,
,D/StrictMode( 3335): StrictMode policy violation; ~duration=219 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3335): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3335): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3335): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3335): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3335): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3335): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3335): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3335): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3335): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3335): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3335): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3335): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3335): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3335): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3335): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3335): StrictMode policy violation; ~duration=219 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3335): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3335): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3335): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3335): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3335): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3335): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3335): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3335): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3335): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3335): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3335): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3335): StrictMode policy violation; ~duration=216 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3335): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3335): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3335): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3335): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3335): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3335): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3335): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3335): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3335): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
,D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3335): 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3335): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3335): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151),
D/StrictMode( 3335): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,D/StrictMode( 3335): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3335): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3335): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3335): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3335): StrictMode policy violation; ~duration=212 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3335): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3335): ,	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3335): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3335): 	,at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540),
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3335): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3335): ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3335): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3335): 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3335): 	at android.os.Looper.loop(Looper.java:135),
D/StrictMode( 3335): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Native Method)
,D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
,D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3335): StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3335): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137),
D/StrictMode( 3335): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3335): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3335): ,	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3335): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3335): 	,at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3335): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42),
D/StrictMode( 3335): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
,D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3335): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3335): ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3335): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3335): 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3335): 	at android.os.Looper.loop(Looper.java:135),
D/StrictMode( 3335): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Native Method)
,D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3335): ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3335): StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2,
D/StrictMode( 3335): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3335): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3335): ,	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3335): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3335): 	,at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3335): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3335): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133),
D/StrictMode( 3335): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3335): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
,D/StrictMode( 3335): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3335): # via Binder call with stack:
D/StrictMode( 3335): android.os.StrictMode$LogStackTrace
D/StrictMode( 3335): ,	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3335): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3335): 	,at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3335): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3335): 	at android.content.ContentResolver.query(ContentResolver.java:478)
,D/StrictMode( 3335): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3335): 	at com.google.android.c.c.a(PG:87)
,D/StrictMode( 3335): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3335): ,	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3335): 	,at com.google.b.a.by.a(PG:125)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540),
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3335): 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3335): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3335): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3335): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3335): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3335): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3335): StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3335): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3335): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3335): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3335): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3335): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3335): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3335): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3335): ,	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3335): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3335): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3335): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3335): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3335): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3335): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3335): StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3335): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3335): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3335): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3335): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3335): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3335): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84),
D/StrictMode( 3335): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3335): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3335): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3335): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3335): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3335): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3335): StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3335): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3335): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3335): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3335): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3335): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3335): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176),
D/StrictMode( 3335): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3335): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3335): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3335): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3335): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,D/StrictMode( 3335): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3335): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3335): StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3335): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3335): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3335): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3335): 	,at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3335): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3335): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3335): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3335): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3335): ,	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3335): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3335): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3335): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3335): 	,at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3335): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3335): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3335): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3335): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3335): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3335): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3335): 	,at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3335): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3335): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 3335): Application name is not set. Call Builder#setApplicationName.
E/bt-btm  ( 3232): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e2f085 
E/bt-btm  ( 3232): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e2f085 
,D/BluetoothManagerService(  821): Message: 20
,D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@df23316:true
,I/ActivityManager(  821): Killing 2154:com.android.defcontainer/u0a7 (adj 15): empty #17,
,D/BluetoothAdapterProperties( 3232): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true,
E/bt-btif ( 3232): Calling BTA_HhEnable
,E/bt-btif ( 3232): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3232): Address is:F8:CF:C5:D9:E5:61
,W/bt-btm  ( 3232): Stopping oneshot timer
,D/AuthorizationBluetoothService( 1478): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapterProperties( 3232): Name is: Nexus 6
,D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3232): Scan Mode:20
D/BluetoothAdapterProperties( 3232): Discoverable Timeout:120
,D/bte_conf( 3232): Device ID record 1 : primary
D/bte_conf( 3232):   vendorId            = 000f
D/bte_conf( 3232):   vendorIdSource      = 0001
D/bte_conf( 3232):   product             = 1200
D/bte_conf( 3232):   version             = 1436
D/bte_conf( 3232):   clientExecutableURL = 
,D/bte_conf( 3232):   serviceDescription  = 
,D/bte_conf( 3232):   documentationURL    = 
D/bte_conf( 3232): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3232): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 3232): ScanMode =  20
D/BluetoothAdapterProperties( 3232): State =  11
D/BluetoothAdapterProperties( 3232): Setting state to 12
I/BluetoothAdapterState( 3232): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 3232): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  821): Broadcasting onBluetoothStateChange(true) to 13 receivers.
I/BluetoothAdapterState( 3232): Entering On State,
D/BluetoothA2dp( 1065): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3232): Scan Mode:21
D/BluetoothAdapterProperties( 3232): Discoverable Timeout:120
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
,E/bt_h4   ( 3232): vendor lib postload completed
D/BluetoothManagerService(  821): Creating new ProfileServiceConnections object for profile: 1
D/BluetoothMap( 1065): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 1065): onBluetoothStateChange: up=true,
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1274): onBluetoothStateChange: up=true
,D/BluetoothPan( 1065): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset( 1065): onBluetoothStateChange: up=true
D/BluetoothA2dpSink( 1065): onBluetoothStateChange: up=true
E/BluetoothA2dpSink( 1065): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothAvrcpController( 1065): onBluetoothStateChange: up=true
,E/BluetoothAvrcpController( 1065): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
,D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothA2dp(  821): onBluetoothStateChange: up=true
,D/BluetoothHeadsetClient( 1065): onBluetoothStateChange: up=true
E/BluetoothHeadsetClient( 1065): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
,D/BluetoothManagerService(  821): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  821): Message: 40
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3232): onReceive
D/BluetoothMapService( 3232): STATE_ON
,D/BluetoothMapMasInstance( 3232): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3232): MAS initSocket()
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/ContextImpl( 3318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
W/BluetoothAdapter( 3232): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3232): Accepting socket connection...
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13195ab:true
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3232): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3318): Adding local A2DP profile
,D/AuthorizationBluetoothService( 1478): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3318): Adding local HEADSET profile
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): Message: 30
W/BluetoothAdapter( 3232): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3232): Accept thread started.
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3318): Adding local MAP profile
D/BluetoothMap( 3318): Create BluetoothMap proxy object
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3318): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3318): finishStartingService: stopping service
,D/BluetoothA2dp( 3318): Proxy object connected
D/A2dpProfile( 3318): Bluetooth service connected
,D/BluetoothInputDevice( 3318): Proxy object connected
D/HidProfile( 3318): Bluetooth service connected
,D/BluetoothPan( 3318): BluetoothPAN Proxy object connected
D/PanProfile( 3318): Bluetooth service connected
D/BluetoothMap( 3318): Proxy object connected
D/MapProfile( 3318): Bluetooth service connected
D/BluetoothMap( 3318): getConnectedDevices()
,D/BluetoothPbap( 3318): Proxy object connected
D/PbapServerProfile( 3318): Bluetooth service connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset(  821): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset( 1274): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset( 1065): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset(  821): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 3318): Proxy object connected
,D/HeadsetProfile( 3318): Bluetooth service connected
,I/wpa_supplicant( 3244): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  821):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  821):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0,
,E/WifiConfigStore(  821): will read network variables netId=0
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,I/wpa_supplicant( 3244): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3244): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3244): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3244): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  353): Setting iface cfg,
,E/WifiStateMachine(  821): Start Dhcp Watchdog 1
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 1
E/WifiStateMachine(  821):  RSSI mgmt: -50
E/WifiStateMachine(  821):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 0 tx_time=59 rx_time=379 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 3379): version 5.5.6 starting
,I/dhcpcd  ( 3379): wlan0: broadcasting for a lease
,I/jxcore-log( 3173): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
,I/jxcore-log( 3173): 
,I/jxcore-log( 3173): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
,I/jxcore-log( 3173): 
,I/jxcore-log( 3173): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
,I/jxcore-log( 3173): 
,I/jxcore-log( 3173): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
,I/jxcore-log( 3173): 
,I/jxcore-log( 3173): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,I/jxcore-log( 3173): 
,I/dhcpcd  ( 3379): wlan0: offered 192.168.1.122 from 192.168.1.1,
,I/dhcpcd  ( 3379): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3379): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3173): Test app app.js loaded
I/jxcore-log( 3173): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3173): BLE advertisement is supported
I/jxcore-log( 3173): 
,I/chromium( 3173): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  821): Adding iface wlan0 to network 100
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  821): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821):    accepting network in place of null
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,V/BackupManagerService(  821): Scheduling immediate backup pass
,V/BackupManagerService(  821): Running a backup pass
,V/BackupManagerService(  821): clearing pending backups
,V/PerformBackupTask(  821): Beginning backup of 14 targets
,I/NetworkMonitor( 2892): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1503): Network connectivity changed, type is: 2
,D/PhoneInterfaceManager( 1274): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1274): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/PerformBackupTask(  821): invokeAgentForBackup on @pm@
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,V/MusicLeanback( 2892): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,V/BackupServiceBinder(  821): doBackup() invoked
,I/PMBA    (  821): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,E/GpsLocationProvider(  821): No APN found to select.
,D/DownloadManager( 1086): [82] Starting
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 25 Jan 2016 21:43:08 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453758187558], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453758187542]}
,W/ActivityThread( 1086): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  821): Start proc 3421:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
,I/BackupRestoreController(  821): Getting widget state for user: 0
,D/SprintDMReceiver( 3421): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3421): simOperator:  IMSI: null
D/SprintDMReceiver( 3421): Not Sprint UICC, don't do anything.
,I/art     (  821): Explicit concurrent mark sweep GC freed 58352(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 2.153ms total 74.985ms
,I/GoogleURLConnFactory( 1478): Using platform SSLCertificateSocketFactory
,W/GmsBackupTransport( 1704): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1704): starting performBackup for @pm@
,V/GmsBackupTransport( 1704): performBackup done for @pm@
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DriveInitializer( 1733): Background init thread started
,I/ConfigService( 1478): onCreate
I/ConfigFetchService( 1733): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1733): running network task: configservice_periodic
,E/WakeLock( 1733): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1733): launchTask
,I/SystemUpdateService( 1733): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,W/GLSActivity( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1478): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1478): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1478): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ConfigFetchService( 1733): service connected
D/SystemUpdateService( 1733): onCreate
,D/SystemUpdateService( 1733): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/GmsBackupTransport( 1704): Error sending final backup to server: 
W/GmsBackupTransport( 1704): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1704): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1704): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1704): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1704): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1704): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1704): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1704): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1704): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1704): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1704): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1704): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1704): 	... 1 more
,W/DriveInitializer( 1733): Awaiting to be initialized
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 18434(1001KB) AllocSpace objects, 3(71KB) LOS objects, 37% free, 26MB/42MB, paused 1.118ms total 27.061ms
,D/BackupManagerService(  821): Now staging backup of com.google.android.talk
,D/BackupManagerService(  821): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  821): Now staging backup of com.android.providers.settings
,I/SystemUpdateService( 1733): active receiver: enabled
,D/BackupManagerService(  821): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  821): Now staging backup of com.google.android.gm
,D/ConfigFetchService( 1733): ConfigApi connection successful.
,D/BackupManagerService(  821): Now staging backup of com.android.providers.userdictionary
,I/SystemUpdateService( 1733): showing system update notification
,D/BackupManagerService(  821): Now staging backup of com.android.nfc
,D/BackupManagerService(  821): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  821): Now staging backup of com.google.android.marvin.talkback
,I/CheckinService( 1733): Checking schedule, now: 1453758187969 next: 1452614914759
,I/CheckinService( 1733): active receiver: enabled
,I/iu.SyncManager( 1733): SYNC; picasa accounts
,D/NetworkLogImpl( 1733): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1733): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/BackupManagerService(  821): Now staging backup of com.google.android.inputmethod.latin
,W/DriveInitializer( 1733): Background init thread ended
,I/CheckinService( 1733): Preparing to send checkin request
I/EventLogService( 1733): Accumulating logs since 1453757405084
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.UploadsManager( 1733): num queued entries: 0
,I/iu.UploadsManager( 1733): num updated entries: 0
I/iu.SyncManager( 1733): NEXT; no task
,D/DownloadManager( 1086): [82] Finished with status SUCCESS
,D/BackupManagerService(  821): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  821): Now staging backup of com.android.vending
,I/ValidateNoPeople(  821): skipping global notification
,D/BackupManagerService(  821): Now staging backup of android
,V/SystemUpdateService( 1733): retry (wakeup: false) in 3599904 ms
,D/BackupManagerService(  821): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1704): Next backup will happen in 43199843 millis.
,I/GcmGroups( 1733): Failed to subscribe to group.
I/GcmGroups( 1733): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 1733): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 1733): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 1733): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 1733): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 1733): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 1733): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 1733): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 1733): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/BackupManagerService(  821): Backup pass finished.
,I/GcmGroups( 1733): Groups upload failed, retrying in 24000:00:00
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1733): onDestroy
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/EventLogService( 1733): Opted in for usage reporting
,V/KeepSync( 3276): Connecting to GoogleApiClient
,I/ActivityManager(  821): Start proc 3489:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 18215(1145KB) AllocSpace objects, 11(176KB) LOS objects, 35% free, 28MB/44MB, paused 1.101ms total 47.911ms
,I/ActivityManager(  821): Start proc 3509:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,I/Babel   ( 2639): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1478): Connected
,E/HttpOperation( 3081): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3081): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3081): 	at jdm.a(PG:82)
E/HttpOperation( 3081): 	at jcs.o(PG:406)
E/HttpOperation( 3081): 	at jcn.a(PG:1379)
E/HttpOperation( 3081): 	at jcs.i(PG:143)
E/HttpOperation( 3081): 	at blb.a(PG:3937)
E/HttpOperation( 3081): 	at czp.a(PG:18188)
E/HttpOperation( 3081): 	at czp.a(PG:9081)
E/HttpOperation( 3081): 	at czq.run(PG:1686)
E/HttpOperation( 3081): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3081): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3081): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3081): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3081): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3081): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3081): 	at jdj.a(PG:4091)
E/HttpOperation( 3081): 	at jdj.a(PG:1125)
E/HttpOperation( 3081): 	at jdm.a(PG:77)
E/HttpOperation( 3081): 	... 12 more
E/HttpOperation( 3081): Caused by: faj: BadAuthentication
E/HttpOperation( 3081): 	at fal.a(PG:38)
E/HttpOperation( 3081): 	at jdj.a(PG:4089)
E/HttpOperation( 3081): 	... 14 more
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,D/GCM     ( 1478): Message class com.google.f.a.a.p
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1733): [AccountUtils] Account not ready
W/Kids    ( 1733): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1733): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1733): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1733): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1733): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1733): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1733): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1733): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1733): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1733): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1733): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 3509): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3509): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ClientConnectionOperation( 1733): Handling authorization failure
E/ClientConnectionOperation( 1733): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1733): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1733): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1733): 	... 7 more
,V/KeepSync( 3276): GoogleApiClient failed to connect with error code: 4
,E/HttpOperation( 3081): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3081): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3081): 	at jdm.a(PG:82)
E/HttpOperation( 3081): 	at jcs.o(PG:406)
E/HttpOperation( 3081): 	at jcn.a(PG:1379)
E/HttpOperation( 3081): 	at jcs.i(PG:143)
E/HttpOperation( 3081): 	at hec.a(PG:42)
E/HttpOperation( 3081): 	at hee.a(PG:102)
E/HttpOperation( 3081): 	at czr.a(PG:65)
E/HttpOperation( 3081): 	at kka.a(PG:108)
E/HttpOperation( 3081): 	at czp.a(PG:19176)
E/HttpOperation( 3081): 	at czp.a(PG:9081)
E/HttpOperation( 3081): 	at czq.run(PG:1686)
E/HttpOperation( 3081): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3081): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3081): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3081): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3081): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3081): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3081): 	at jdj.a(PG:4091)
E/HttpOperation( 3081): 	at jdj.a(PG:1125)
E/HttpOperation( 3081): 	at jdm.a(PG:77)
E/HttpOperation( 3081): 	... 15 more
E/HttpOperation( 3081): Caused by: faj: BadAuthentication
E/HttpOperation( 3081): 	at fal.a(PG:38)
E/HttpOperation( 3081): 	at jdj.a(PG:4089)
E/HttpOperation( 3081): 	... 17 more
E/ExperimentLoader( 3081): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3081): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3081): 	at jdm.a(PG:82)
E/ExperimentLoader( 3081): 	at jcs.o(PG:406)
E/ExperimentLoader( 3081): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3081): 	at jcs.i(PG:143)
E/ExperimentLoader( 3081): 	at hec.a(PG:42)
E/ExperimentLoader( 3081): 	at hee.a(PG:102)
E/ExperimentLoader( 3081): 	at czr.a(PG:65)
E/ExperimentLoader( 3081): 	at kka.a(PG:108)
E/ExperimentLoader( 3081): 	at czp.a(PG:19176)
E/ExperimentLoader( 3081): 	at czp.a(PG:9081)
E/ExperimentLoader( 3081): 	at czq.run(PG:1686)
E/ExperimentLoader( 3081): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3081): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3081): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3081): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3081): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3081): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3081): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3081): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3081): 	at jdm.a(PG:77)
E/ExperimentLoader( 3081): 	... 15 more
E/ExperimentLoader( 3081): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3081): 	at fal.a(PG:38)
E/ExperimentLoader( 3081): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3081): 	... 17 more
,V/JNIHelp ( 3509): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SQLiteLog( 3276): (284) automatic index on blob_node(is_deleted)
,I/GAv4    ( 3489): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3489):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3489):   adb logcat -s GAv4
,E/SQLiteLog( 3276): (284) automatic index on blob_node(is_deleted)
,I/ProviderInstaller( 3509): Installed default security provider GmsCore_OpenSSL
E/SQLiteLog( 3276): (284) automatic index on blob_node(is_deleted)
,W/EventLogAggregator( 1733): Unknown tag: snet_gcore
W/EventLogAggregator( 1733): Unknown tag: snet_launch_service
,W/GAv4    ( 3489): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3489): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3489): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 37474, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/CheckinRequestBuilder( 1733): Checkin reason type: 12 attempt count: 1
,D/WifiService(  821): New client listening to asynchronous messages
E/ActivityThread( 1733): Failed to find provider info for com.google.android.wearable.settings
,E/YouTube MDX( 3509): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/ActivityManager(  821): Start proc 3559:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/dex2oat ( 3577): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-494565010.jar --oat-fd=30 --oat-location=/data/data/com.google.android.youtube/cache/ads-494565010.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/art     (  821): Explicit concurrent mark sweep GC freed 33559(1480KB) AllocSpace objects, 4(106KB) LOS objects, 32% free, 33MB/49MB, paused 1.622ms total 55.192ms
,W/InstanceID/Rpc( 3509): Found 10011
,I/WebViewFactory( 3489): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dex2oat ( 3577): dex2oat took 151.097ms (threads: 4) arena alloc=182KB java alloc=12KB native alloc=1099KB free=6MB
,I/LibraryLoader( 3489): Time to load native libraries: 1 ms (timestamps 1633-1634)
I/LibraryLoader( 3489): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3489): Binding Chromium to main looper Looper (main, tid 1) {1d89d1ae}
,I/LibraryLoader( 3489): Expected native library version number "",actual native library version number ""
,I/chromium( 3489): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 34947(1996KB) AllocSpace objects, 6(378KB) LOS objects, 37% free, 26MB/42MB, paused 1.252ms total 95.896ms
,I/BrowserStartupController( 3489): Initializing chromium process, singleProcess=true
,W/art     ( 3489): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3489): ApplicationContext is null in ApplicationStatus
,W/chromium( 3489): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3489): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3489): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3489): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AudioManagerAndroid( 3489): Requires BLUETOOTH permission
,I/NSApplication( 3489): Starting up...
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  821): Start proc 3659:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3276): IOException
E/KeepSync( 3276): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3276): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3276): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3276): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3276): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3276): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3276): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3276): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3276): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3276): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3276): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3276): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3276): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3276): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3276): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3276): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3276): 	... 10 more
W/KeepSync( 3276): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 37477, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,W/CheckinRequestBuilder( 1733): awaiting user notification for token
,I/ActivityManager(  821): Start proc 3681:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,W/ResourcesManager( 3681): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3681): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAV2    ( 3559): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3559): Created application version: 3.6.8 (30608)
,I/MultiDex( 3681): VM with version 2.1.0 has multidex support
,I/MultiDex( 3681): install
I/MultiDex( 3681): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3681): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3681): Installed default security provider GmsCore_OpenSSL
,E/LocSvc_ApiV02(  821): E/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1078]: failed status = eLOC_CLIENT_SUCCESS, inject_pos_ind.status = eQMI_LOC_GENERAL_FAILURE_V02, part num = 59, ind.partNum = 0
,I/ActivityManager(  821): Start proc 3705:com.google.android.gm/u0a78 for service com.google.android.gm/.provider.MailSyncAdapterService
,I/BooksSync( 3559): Starting books sync for 61035162, extras: ade
,D/ActivityThread( 3705): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
D/WVCdm   (  357): Instantiating CDM.
I/WVCdm   (  357): CdmEngine::OpenSession
I/WVCdm   (  357): Level3 Library Dec 11 2014 16:13:16
,I/Gmail   ( 3705): getAccountsCursor
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/WVCdm   (  357): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  357): Service_Initialize: starts!
D/QSEECOMAPI: (  357): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  357): App is not loaded in QSEE
,I/GoogleURLConnFactory( 3681): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  821): Start proc 3738:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,D/HeadsetStateMachine( 3232): Disconnected process message: 10, size: 0
,I/ActivityManager(  821): Start proc 3756:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  821): Killing 2988:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/BooksConfig( 3559): GmsCore Version = 7.8.99 (2134222-430)
,D/QSEECOMAPI: (  357): Loaded image: APP id = 3
,D/DrmWidevineDash(  357): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
E/DrmWidevineDash(  357): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
,D/DrmLibTime(  313): got the req here! ret=0
D/DrmLibTime(  313): command id, time_cmd_id = 770
D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
,D/DrmLibTime(  313): QSEE Time Listener: seconds: 1453758189
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 634289587
D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1453758189; nsec = 634289587
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: starts!
,I/ActivityManager(  821): Killing 3008:com.android.musicfx/u0a18 (adj 15): empty #17
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  357): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: starts! SID=0xbeb9a520
,D/DrmWidevineDash(  357): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_GetRandom: starts! randomData=0xb4c4edc8, dataLength=8
,D/DrmWidevineDash(  357): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb5b94000, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  357): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  357): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  357): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  357): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d1a840, idLength=0xb3f01710
,D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
,D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  357): PrepareKeyRequest: nonce=3899561351
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4d46600
D/DrmWidevineDash(  357): message_length=1599, signature=0xb4c3eb40, signature_length=3018856180
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  357): CdmEngine::CloseSession
D/DrmWidevineDash(  357): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  357): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  357): L3 Terminate.
D/DrmWidevineDash(  357): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  357): Service_Uninitialize: starts!
D/QSEECOMAPI: (  357): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  357): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  357): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_Terminate: ends! returns 0
,W/ActivityManager(  821): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/art     (  821): Explicit concurrent mark sweep GC freed 19799(776KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 1.849ms total 61.920ms
,I/Gmail   ( 3705): Observing account changes for notifications
,I/Exchange( 3738): EasService.onCreate
,W/GAV2    ( 3705): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Exchange( 3738): RestartPingTask
,I/Exchange( 3738): RestartPingsTask did not start any pings.
I/Exchange( 3738): PSS stopIfIdle
I/Exchange( 3738): PSS has no active accounts; stopping service.
I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Gmail   ( 3705): Sync started for account: account:61035162
,I/Gmail   ( 3705): getAccountsCursor
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 3705): (283) recovered 52 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/Exchange( 3738): onDestroy
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3559): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,I/ActivityManager(  821): Killing 3041:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,E/BooksSync( 3559): Soft error
E/BooksSync( 3559): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3559): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3559): Sync error
E/BooksSync( 3559): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3559): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3559): Finished books sync
,I/Gmail   ( 3705): notifyAccountChanged
,I/Gmail   ( 3705): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 3705): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3705): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3705): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  821): Killing 2426:android.process.acore/u0a5 (adj 15): empty #17
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37478, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/WVCdm   (  357): CdmEngine::OpenSession
I/WVCdm   (  357): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  357): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  357): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  357): Service_Initialize: starts!
D/QSEECOMAPI: (  357): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  357): App is not loaded in QSEE
,I/Gmail   ( 3705): notifyAccountChanged
,I/PeopleSync( 1733): onPerformSync() [5005f081]
,I/ActivityManager(  821): Killing 1769:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/QSEECOMAPI: (  357): Loaded image: APP id = 3
,D/DrmWidevineDash(  357): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
,E/DrmWidevineDash(  357): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
,D/DrmLibTime(  313): got the req here! ret=0
D/DrmLibTime(  313): command id, time_cmd_id = 770
D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
,D/DrmLibTime(  313): QSEE Time Listener: seconds: 1453758190
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 516471722
D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1453758190; nsec = 516471722
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  357): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: starts! SID=0xbeb9a520
D/DrmWidevineDash(  357): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_GetRandom: starts! randomData=0xb4da5118, dataLength=8
,D/DrmWidevineDash(  357): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb5b93a00, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  357): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  357): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  357): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  357): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d1a880, idLength=0xb3e03710
,D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: ends! returns 0,
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: wv_app_version = 21
,D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  357): PrepareKeyRequest: nonce=2624474330
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4031600
D/DrmWidevineDash(  357): message_length=1634, signature=0xb587ffc0, signature_length=3017815796
,I/PeopleDatabaseHelper( 1733): cleanUpNonGplusAccounts done.
,V/Herrevad( 1733): NQAS connected
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  357): CdmEngine::CloseSession
D/DrmWidevineDash(  357): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  357): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  357): L3 Terminate.
D/DrmWidevineDash(  357): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  357): Service_Uninitialize: starts!
D/QSEECOMAPI: (  357): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  357): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  357): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_Terminate: ends! returns 0
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1d8f1a3e}
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dex2oat ( 3809): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/Gmail   ( 3705): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4353, normalSync: true
,I/dex2oat ( 3809): dex2oat took 29.397ms (threads: 4) arena alloc=95KB java alloc=18KB native alloc=1243KB free=6MB
,I/DictionaryProvider:UpdateHandler( 1215): downloadFinished() : DownloadId = 82
I/Adreno  ( 3681): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 28877(1656KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 27MB/43MB, paused 905us total 30.078ms
,D/GCM     ( 1478): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/Adreno  ( 3681): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/AuthorizationBluetoothService( 1478): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1733): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/GCM     ( 1478): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  821): Start proc 3821:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,V/GoogleAuthProtoRequest( 3250): [326] a.<init>: mAccountName set to: thalitester@gmail.com
,D/LocationInitializer( 1733): Restart initialization of location
,W/ResourcesManager( 3821): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3821): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3821): VM with version 2.1.0 has multidex support
I/MultiDex( 3821): install
I/MultiDex( 3821): VM has multidex support, MultiDex support library is disabled.
,I/EventLogService( 1733): Opted in for usage reporting
,V/JNIHelp ( 3821): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProviderInstaller( 3821): Installed default security provider GmsCore_OpenSSL
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Gmail   ( 3705): getAccountsCursor
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 3821): callingUid 10011, callindPid: 3821
,E/MDM     ( 1704): [123] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/art     (  821): Explicit concurrent mark sweep GC freed 25279(1062KB) AllocSpace objects, 4(252KB) LOS objects, 32% free, 33MB/49MB, paused 1.195ms total 59.234ms
,E/Babel   ( 2639): UserRecoverableAuthException.
E/Babel   ( 2639): eei: BadAuthentication
E/Babel   ( 2639): 	at eeg.a(Unknown Source)
E/Babel   ( 2639): 	at eeg.a(Unknown Source)
E/Babel   ( 2639): 	at eeg.a(Unknown Source)
E/Babel   ( 2639): 	at g.a(Unknown Source)
E/Babel   ( 2639): 	at cae.a(SourceFile:3089)
E/Babel   ( 2639): 	at cae.a(SourceFile:1131)
E/Babel   ( 2639): 	at cws.a(SourceFile:4333)
E/Babel   ( 2639): 	at cws.a(SourceFile:1419)
E/Babel   ( 2639): 	at crl.a(SourceFile:492)
E/Babel   ( 2639): 	at crl.a(SourceFile:1468)
E/Babel   ( 2639): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2639): 	at cas.b(SourceFile:106)
E/Babel   ( 2639): 	at cap.d(SourceFile:335)
E/Babel   ( 2639): 	at caq.run(SourceFile:81)
E/Babel   ( 2639): Error getting auth token
E/Babel   ( 2639): dvm
E/Babel   ( 2639): 	at g.a(Unknown Source)
E/Babel   ( 2639): 	at cae.a(SourceFile:3089)
E/Babel   ( 2639): 	at cae.a(SourceFile:1131)
E/Babel   ( 2639): 	at cws.a(SourceFile:4333)
E/Babel   ( 2639): 	at cws.a(SourceFile:1419)
E/Babel   ( 2639): 	at crl.a(SourceFile:492)
E/Babel   ( 2639): 	at crl.a(SourceFile:1468)
E/Babel   ( 2639): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2639): 	at cas.b(SourceFile:106)
E/Babel   ( 2639): 	at cap.d(SourceFile:335)
E/Babel   ( 2639): 	at caq.run(SourceFile:81)
,E/Babel   ( 2639): Account registration failed 1-Redacted-21
E/Babel   ( 2639): cyp: null -- null
E/Babel   ( 2639): 	at cae.a(SourceFile:3121)
E/Babel   ( 2639): 	at cae.a(SourceFile:1131)
E/Babel   ( 2639): 	at cws.a(SourceFile:4333)
E/Babel   ( 2639): 	at cws.a(SourceFile:1419)
E/Babel   ( 2639): 	at crl.a(SourceFile:492)
E/Babel   ( 2639): 	at crl.a(SourceFile:1468)
E/Babel   ( 2639): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2639): 	at cas.b(SourceFile:106)
E/Babel   ( 2639): 	at cap.d(SourceFile:335)
E/Babel   ( 2639): 	at caq.run(SourceFile:81)
,I/Gmail   ( 3705): getAccountsCursor
,I/art     ( 2639): Note: end time exceeds epoch: 
,W/ResourcesManager( 3705): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3705): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleSync( 1733): Setting subscription: result=true [5005f081]
I/PeopleSync( 1733): Starting sync, feed=null [5005f081]
,W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2639): Unexpected exception while authenticating.
E/Babel   ( 2639): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2639): 	at eeg.b(Unknown Source)
E/Babel   ( 2639): 	at eeg.b(Unknown Source)
E/Babel   ( 2639): 	at g.a(Unknown Source)
E/Babel   ( 2639): 	at cae.b(SourceFile:1146)
E/Babel   ( 2639): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2639): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2639): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2639): 	at java.lang.Thread.run(Thread.java:818)
,V/JNIHelp ( 3705): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProviderInstaller( 3705): Installed default security provider GmsCore_OpenSSL
,W/ExperimentUpdateService( 3250): [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3250): [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3250): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3250): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3250): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3250): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3250): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3250): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3250): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3250): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3250): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3250): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 1733): Suspending all threads took: 13.132ms
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 20141(1290KB) AllocSpace objects, 11(176KB) LOS objects, 35% free, 29MB/45MB, paused 16.420ms total 105.195ms
,I/DictionaryProvider:UpdateHandler( 1215): downloadFinished() : Success = true
I/DictionaryProvider:UpdateHandler( 1215): downloadFinished() : Metadata Success
,I/Keyboard.Facilitator( 1215): resetDictionaries() : en_US
,D/GCM     ( 1478): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Keyboard.Facilitator.DecoderInitializer( 1215): run()
,D/AuthorizationBluetoothService( 1478): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/Decoder ( 1215): createOrResetDecoder
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GmsCoreStatsServiceLauncher( 1733): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1704): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/WVCdm   (  357): CdmEngine::OpenSession
I/WVCdm   (  357): Level3 Library Dec 11 2014 16:13:16
,I/GoogleURLConnFactory( 3681): Using platform SSLCertificateSocketFactory
,W/WVCdm   (  357): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  357): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  357): Service_Initialize: starts!
D/QSEECOMAPI: (  357): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  357): App is not loaded in QSEE
,D/LocationInitializer( 1733): Restart initialization of location
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1215): run()
,W/GLSActivity( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1478): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1478): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1478): 	at android.os.Binder.execTransact(Binder.java:446)
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 34866(2028KB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 26MB/42MB, paused 1.035ms total 27.058ms
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/GLSActivity( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1478): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1478): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1478): 	at android.os.Binder.execTransact(Binder.java:446)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1215): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Gmail   ( 3705): notifyAccountChanged
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,I/Gmail   ( 3705): getAccountsCursor
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = contacts
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1215): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1215): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1215): run()
I/StatsUtilsManager( 1215): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1215): shouldRecordStats() = Too Soon
,I/PeopleSync( 1733): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/QSEECOMAPI: (  357): Loaded image: APP id = 3
,D/DrmWidevineDash(  357): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
E/DrmWidevineDash(  357): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
,D/DrmLibTime(  313): got the req here! ret=0
D/DrmLibTime(  313): command id, time_cmd_id = 770
D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  313): QSEE Time Listener: seconds: 1453758191
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 717421618
D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1453758191; nsec = 717421618
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  357): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: starts! SID=0xaef01940
,D/DrmWidevineDash(  357): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_GetRandom: starts! randomData=0xb4c4edc8, dataLength=8
,D/DrmWidevineDash(  357): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4dbce00, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  357): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  357): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  357): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  357): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d1a860, idLength=0xb3e03710
,I/Gmail   ( 3705): notifyAccountChanged
,W/Gmail   ( 3705): Sync complete for account: account:61035162
,I/Gmail   ( 3705): getAccountsCursor
,D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: starts! SID=1
V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  357): PrepareKeyRequest: nonce=152076262
D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4031600
D/DrmWidevineDash(  357): message_length=1598, signature=0xb587ffc0, signature_length=3017815796
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 37509, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,I/ActivityManager(  821): Killing 2194:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/SyncManager(  821): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 165793, reason: Periodic
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  357): CdmEngine::CloseSession
D/DrmWidevineDash(  357): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  357): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  357): L3 Terminate.
D/DrmWidevineDash(  357): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  357): Service_Uninitialize: starts!
D/QSEECOMAPI: (  357): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  357): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  357): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_Terminate: ends! returns 0
,I/DictionaryProvider:UpdateHandler( 1215): downloadFinished() : Success = true
I/DictionaryProvider:UpdateHandler( 1215): downloadFinished() : Metadata Success
,I/Keyboard.Facilitator( 1215): resetDictionaries() : en_US
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.DecoderInitializer( 1215): run()
,I/Decoder ( 1215): createOrResetDecoder
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1215): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1215): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = contacts
,I/art     (  368): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 209us total 9.775ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1215): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1215): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1215): run()
I/StatsUtilsManager( 1215): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1215): shouldRecordStats() = Too Soon
,I/ActivityManager(  821): Start proc 3868:com.google.android.apps.docs.editors.sheets/u0a48 for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,I/art     (  368): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 795us total 12.558ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 9.778ms
,I/PeopleSync( 1733): Sync finished, successful=false, took 282ms
,I/PeopleSync( 1733): Cannot authenticate [5005f081]
I/PeopleSync( 1733): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 1733): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 1733): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 1733): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 1733): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 1733): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 1733): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 1733): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 1733): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 1733): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 1733): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 1733): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/PeopleSync( 1733): ***Sync finished***, duration: 1608 [5005f081]
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1733): Module APK com.google.android.play.games already loaded
,W/PlaySystemBroadcastReceiver( 1733): Processed handlePeopleChanged at 134914
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1733): Module APK com.google.android.play.games already loaded
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 37509, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  821): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 166010, reason: Periodic
,W/DataBroker( 1733): No player ID found and calling context is not the dest app
,E/SQLiteLog( 1733): (284) automatic index on invitations(external_inviter_id)
,I/ActivityManager(  821): Start proc 3894:com.google.android.calendar/u0a37 for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService
,I/CheckinTask( 1733): Sending checkin request (10482 bytes)
,E/SQLiteLog( 3894): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  821): Start proc 3914:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3914): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3914): Created com.android.providers.calendar.CalendarAlarmManager@3f369a1c(com.android.providers.calendar.CalendarProvider2@1adc5625)
,I/art     (  821): Explicit concurrent mark sweep GC freed 28376(1201KB) AllocSpace objects, 4(158KB) LOS objects, 31% free, 34MB/50MB, paused 1.166ms total 50.117ms
,I/AnalyticsLogBase( 3894): PlayLogger.onLoggerConnected
I/AnalyticsLogBase( 3894): PlayLogger.onLoggerConnected
,W/ResourcesManager( 3894): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3894): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3894): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3894): Installed default security provider GmsCore_OpenSSL
,W/AbstractGoogleClient( 3894): Application name is not set. Call Builder#setApplicationName.
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/CalendarSyncAdapter( 3894): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 3894): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 3894): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 3894): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 3894): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 3894): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 3894): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 3894): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 3894): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2382)
E/CalendarSyncAdapter( 3894): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1850)
E/CalendarSyncAdapter( 3894): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:1733)
E/CalendarSyncAdapter( 3894): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:503)
E/CalendarSyncAdapter( 3894): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:392)
E/CalendarSyncAdapter( 3894): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 3894): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 3894): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 3894): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 3894): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 3894): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 3894): 	... 12 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 37509, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  821): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 167986, reason: Periodic
,I/ActivityManager(  821): Killing 2725:com.android.vending/u0a19 (adj 15): empty #17
,I/CheckinResponseProcessor( 1733): From server: 12 gservices updates and 5 deletes
,I/GAv4    ( 3868): Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3868):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3868):   adb logcat -s GAv4
,W/GAv4    ( 3868): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3868): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 3868): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.332.11.30
,W/GAv4    ( 3868): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GHttpClientFactory( 2892): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2892): Using platform SSLCertificateSocketFactory
,I/MusicLifecycle( 2892): Sync started
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=64.66 rxSuccessRate=66.06 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=64.66 rxSuccessRate=66.06 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@985b220}
,I/ActivityManager(  821): Start proc 3966:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1478): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1478): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1478): 	at android.os.Binder.execTransact(Binder.java:446)
,I/MusicLifecycle( 2892): Sync ended
W/MusicSyncAdapter( 2892): Sync failed due to an authentication issue.
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 37509, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  821): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 166881, reason: Periodic
,I/MusicLeanback( 2892): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2892): Stop autocaching.
,I/ActivityManager(  821): Start proc 3993:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,W/ResourcesManager( 3868): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3868): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 3868): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3868): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ContactLocale( 3966): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/GmsUtils( 2892): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 2892): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/CertBlacklister(  821): Certificate blacklist changed, updating...
,I/CertBlacklister(  821): Certificate blacklist updated
,I/GservicesProvider( 1478): main difference update completed
,V/JNIHelp ( 3868): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  821): Start proc 4018:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,W/Telecom (  821): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 2639): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 2639): BAM#gBA: invalid account id: -1
W/Babel   ( 2639): BAM#gBA: invalid account id: -1
I/Babel_telephony( 2639): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,I/CheckinRequestBuilder( 1733): Checkin reason type: 12 attempt count: 1
,I/ActivityManager(  821): Start proc 4037:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,E/ActivityThread( 1733): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 3993): Sync request not initiated by GCP app. Dropping
,I/CalendarProvider2( 3914): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3914): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ProviderInstaller( 3868): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  821): Killing 3318:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3335:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,E/DefaultHttpIssuer( 3868): Attempt to close HttpIssuer when no request is executing.
,E/BaseSyncManager( 3868): ClientFlagSyncException
E/BaseSyncManager( 3868): com.google.android.apps.docs.flags.f$a: IO Exception opening: https://ssl.gstatic.com/docs/android/editors/sheets/client_flags?1453758193114= Socket is closed
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.flags.f.a(PG:1108)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.sync.syncadapter.n.a(PG:23060)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.sync.syncadapter.n.c(PG:612)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.sync.syncadapter.q.run(PG:3508)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.sync.syncadapter.o.run(PG:3031)
E/BaseSyncManager( 3868): Caused by: java.net.SocketException: Socket is closed
E/BaseSyncManager( 3868): 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.checkOpen(SourceFile:245)
E/BaseSyncManager( 3868): 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.access$000(SourceFile:56)
E/BaseSyncManager( 3868): 	at com.google.android.gms.org.conscrypt.s.write(SourceFile:749)
E/BaseSyncManager( 3868): 	at okio.q.a_(PG:78)
E/BaseSyncManager( 3868): 	,at okio.b.a_(PG:155)
E/BaseSyncManager( 3868): 	at okio.t.flush(PG:221)
E/BaseSyncManager( 3868): 	at com.squareup.okhttp.internal.spdy.e$d.b(PG:381)
E/BaseSyncManager( 3868): 	at com.squareup.okhttp.internal.spdy.q.a(PG:279)
E/BaseSyncManager( 3868): 	at com.squareup.okhttp.internal.http.u.a(PG:10245)
E/BaseSyncManager( 3868): 	at com.squareup.okhttp.internal.http.h$a.a(PG:890)
E/BaseSyncManager( 3868): 	at com.squareup.okhttp.e.a(PG:50089)
E/BaseSyncManager( 3868): 	at com.squareup.okhttp.e$a.a(PG:230)
E/BaseSyncManager( 3868): 	at com.squareup.okhttp.e.a(PG:3201)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.net.okhttp.c.a(PG:156)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.http.executors.b.a(PG:47)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.http.executors.a.a(PG:22)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.http.executors.c.a(PG:69)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.http.issuers.c.b(PG:96)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.http.issuers.c.a(PG:84)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.http.issuers.a.b(PG:6140)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.http.issuers.a.a(PG:2096)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.http.issuers.a.a(PG:1062)
E/BaseSyncManager( 3868): 	at com.google.android.apps.docs.flags.f.a(PG:1106)
E/BaseSyncManager( 3868): 	... 4 more
,I/ActivityManager(  821): Killing 3421:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3489:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 52749(2MB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 27MB/43MB, paused 1.499ms total 41.978ms
,I/ActivityManager(  821): Start proc 4072:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs.editors.sheets, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     (  821): Explicit concurrent mark sweep GC freed 30900(1276KB) AllocSpace objects, 6(378KB) LOS objects, 32% free, 33MB/49MB, paused 1.370ms total 51.892ms
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1478): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1478): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1478): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DefaultHttpIssuer( 3868): Attempt to consume entity of HttpIssuer when no request is executing.
,E/DefaultHttpIssuer( 3868): Attempt to close HttpIssuer when no request is executing.
,E/BaseSyncManager( 3868): AuthenticatorException
E/BaseSyncManager( 3868): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 3868): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/BaseSyncManager( 3868): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 3868): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/BaseSyncManager( 3868): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 3868): 	at android.os.Binder.execTransact(Binder.java:446)
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@985b220}
,E/Auth.Api.Credentials( 1733): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  821): Killing 1503:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,E/UpdateRequestReceiver( 4072): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/WifiService(  821): Client connection lost with reason: 4
,E/UpdateRequestReceiver( 4072): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/GAV2    ( 3559): Thread[GAThread,5,main]: No campaign data found.
,E/UpdateRequestReceiver( 4072): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4072): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  821): Killing 3659:com.android.chrome/u0a40 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3276:com.google.android.keep/u0a79 (adj 15): empty #17
,I/SystemUpdateService( 1733): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
,D/SystemUpdateService( 1733): onCreate
,D/SystemUpdateService( 1733): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/SystemEventReceiver( 1733): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1733): Updating ocr activity enabled=false
,I/GCoreUlr( 1704): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
D/GCM     ( 1478): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 1704): DispatchingService.onCreate()
,I/SystemUpdateService( 1733): active receiver: enabled
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 15757(873KB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 26MB/42MB, paused 1.471ms total 44.653ms
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 24141(3MB) AllocSpace objects, 11(174KB) LOS objects, 35% free, 29MB/45MB, paused 2.508ms total 40.750ms
,I/art     ( 1704): Explicit concurrent mark sweep GC freed 13081(703KB) AllocSpace objects, 4(64KB) LOS objects, 37% free, 26MB/42MB, paused 2.407ms total 47.856ms
,W/GLSActivity( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1478): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1478): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1478): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7108b51)
,W/SubscribedFeeds( 1733): Hard error
,I/SystemUpdateService( 1733): showing system update notification
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 37509, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  821): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 170037, reason: Periodic
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1733): retry (wakeup: false) in 3599806 ms
,I/[@@    ] SyncAdapterProxy( 1478): Delagator disabled, using the (deprecated) GData sync adapter
,I/GCoreUlr( 1704): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/CheckinRequestBuilder( 1733): awaiting user notification for token
,I/GCoreUlr( 1704): Uploading GCM registration ID for account#2#
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 10225(548KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 742us total 26.356ms
,W/BaseAppContext( 1704): Using Auth Proxy for data requests.
,W/GLSActivity( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1478): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1478): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1478): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 1478): innerSync failed
D/ContactsSyncAdapter( 1478): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1478): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1478): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1478): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1478): 	at com.google.android.syncadapters.contacts.delegation.SyncAdapterProxy.onPerformLoggedSync(SyncAdapterProxy.java:123)
D/ContactsSyncAdapter( 1478): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1478): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1478): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1478): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
D/ContactsSyncAdapter( 1478): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1478): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
D/ContactsSyncAdapter( 1478): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1478): 	at android.os.Binder.execTransact(Binder.java:446)
,I/GLSUser ( 1704): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1704): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GAV2    ( 3705): Thread[GAThread,5,main]: No campaign data found.
I/art     (  821): Explicit concurrent mark sweep GC freed 24455(1057KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 3.599ms total 63.624ms
I/art     (  821): WaitForGcToComplete blocked for 41.721ms for cause HeapTrim
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 37513, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SystemUpdateService( 1733): onDestroy
,D/SyncManager(  821): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 170694, reason: Periodic
,I/EventLogService( 1733): Opted in for usage reporting
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/CheckinTask( 1733): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1704): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/ActivityManager(  821): Start proc 4132:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver
,I/GCoreUlr( 1704): Unbound from all location providers
,E/GCoreUlr( 1704): 
E/GCoreUlr( 1704): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1704): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1704): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1704): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1704): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1704): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1704): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1704): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1704): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1704): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1704): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1704): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1704): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1704): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1704): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1704): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/CheckinService( 1733): Checking schedule, now: 1453758195044 next: 1453799337970
I/CheckinService( 1733): active receiver: disabled
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 37509, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  821): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 170038, reason: Periodic
,I/CheckinService( 1733): Checking schedule, now: 1453758195075 next: 1453799337970
I/CheckinService( 1733): active receiver: disabled
I/ReminderSync( 1733): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=242:priority=5:group=main]
,I/ActivityManager(  821): Start proc 4150:com.google.android.apps.docs.editors.docs/u0a47 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,I/GCoreUlr( 1704): DispatchingService.onDestroy()
,I/GCoreUlr( 1704): Unbound from all location providers
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 11598(663KB) AllocSpace objects, 5(80KB) LOS objects, 35% free, 29MB/45MB, paused 1.234ms total 39.272ms
,I/GservicesUpdateTask( 4132): Updating Gservices keys
,I/ActivityManager(  821): Start proc 4189:com.google.android.apps.docs/u0a46 for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 14465(829KB) AllocSpace objects, 5(551KB) LOS objects, 37% free, 26MB/42MB, paused 3.122ms total 31.625ms
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1478): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1733): [AccountUtils] Account not ready
W/Kids    ( 1733): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1733): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1733): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1733): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1733): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1733): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1733): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1733): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1733): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1733): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1733): 	at java.lang.Thread.run(Thread.java:818)
,I/GAv4    ( 4189): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4189):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4189):   adb logcat -s GAv4
,W/GAv4    ( 4189): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4189): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4189): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4189): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,W/ResourcesManager( 4189): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4189): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 4189): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4189): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4189): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4189): Installed default security provider GmsCore_OpenSSL
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@1194a2c7}
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4    ( 4150): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4150):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4150):   adb logcat -s GAv4
,W/GAv4    ( 4150): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4150): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4150): Analytics setup for ID UA-21125203-4, app name Docs, version 1.4.292.15.30
,W/GAv4    ( 4150): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 4150): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4150): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4150): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4150): Installed default security provider GmsCore_OpenSSL
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@b4a3cdb}
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  821): Killing 3081:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  821): Killing 3738:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  821): Killing 3559:com.google.android.apps.books/u0a34 (adj 15): empty #17
,W/GLSActivity( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1478): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1478): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1478): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DefaultHttpIssuer( 4189): Attempt to consume entity of HttpIssuer when no request is executing.
,E/DefaultHttpIssuer( 4189): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 4189): java.io.IOException
E/DefaultHttpIssuer( 4189): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 4189): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 4189): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 4189): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 4189): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 4189): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 4189): 	at dlr.run(PG:3031)
,E/BaseSyncManager( 4189): AuthenticatorException
E/BaseSyncManager( 4189): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 4189): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/BaseSyncManager( 4189): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 4189): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/BaseSyncManager( 4189): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 4189): 	at android.os.Binder.execTransact(Binder.java:446)
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@1194a2c7}
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs.editors.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  821): Killing 3509:com.google.android.youtube/u0a86 (adj 15): empty #17
,I/art     (  821): Explicit concurrent mark sweep GC freed 36920(1692KB) AllocSpace objects, 15(522KB) LOS objects, 32% free, 33MB/49MB, paused 1.313ms total 58.864ms
,I/ActivityManager(  821): Start proc 4278:com.google.android.apps.magazines/u0a67 for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService
,I/art     (  368): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 208us total 13.412ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 12.958ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 210us total 12.862ms
,W/GLSActivity( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1478): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1478): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1478): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DefaultHttpIssuer( 4150): Attempt to consume entity of HttpIssuer when no request is executing.
,E/DefaultHttpIssuer( 4150): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 4150): java.io.IOException
E/DefaultHttpIssuer( 4150): 	at fur.b(PG:162)
E/DefaultHttpIssuer( 4150): 	at fup.b(PG:6072)
E/DefaultHttpIssuer( 4150): 	at gtb.b(PG:213)
E/DefaultHttpIssuer( 4150): 	at gtb.a(PG:125)
E/DefaultHttpIssuer( 4150): 	at gyh.a(PG:224)
E/DefaultHttpIssuer( 4150): 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.b(PG:618)
E/DefaultHttpIssuer( 4150): 	at gtm.run(PG:2507)
E/DefaultHttpIssuer( 4150): 	at gtk.run(PG:3031)
,I/GAV2    ( 3894): Thread[GAThread,5,main]: No campaign data found.
,E/BaseSyncManager( 4150): AuthenticatorException
E/BaseSyncManager( 4150): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 4150): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/BaseSyncManager( 4150): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 4150): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/BaseSyncManager( 4150): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 4150): 	at android.os.Binder.execTransact(Binder.java:446)
D/WifiService(  821): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@b4a3cdb}
,I/GAv4    ( 4278): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4278):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4278):   adb logcat -s GAv4
,I/ActivityManager(  821): Killing 3250:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,W/GAv4    ( 4278): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4278): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4278): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,W/BaseAppContext( 1733): Using Auth Proxy for data requests.
,I/WebViewFactory( 4278): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4278): Time to load native libraries: 3 ms (timestamps 456-459)
,I/LibraryLoader( 4278): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4278): Binding Chromium to main looper Looper (main, tid 1) {1d89d1ae}
I/LibraryLoader( 4278): Expected native library version number "",actual native library version number ""
W/BaseAppContext( 1733): Using Auth Proxy for data requests.
I/chromium( 4278): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4278): Initializing chromium process, singleProcess=true
,W/art     ( 4278): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4278): ApplicationContext is null in ApplicationStatus
,W/chromium( 4278): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4278): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 4278): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 4278): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/ActivityManager(  821): Start proc 4328:com.android.chrome/u0a40 for service com.android.chrome/org.chromium.chrome.browser.sync.ChromeBrowserSyncAdapterService
,I/NSApplication( 4278): Starting up...
,W/AudioManagerAndroid( 4278): Requires BLUETOOTH permission
,I/SyncAdapterService( 4278): Ignoring sync request for non-current account
,D/DelayedSyncController( 4328): Delaying sync.
,I/ActivityManager(  821): Killing 2639:com.google.android.talk/u0a61 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3705:com.google.android.gm/u0a78 (adj 15): empty #17
,V/ConfigFetchTask( 1733): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Uh5S-9kQDTn8zH-bR-Bwant1SuQi0klDVdh02PgtJWCi9g7ojXPEtnSQkCfJl9dO7zh9gIA-GxudOra9Wkpr1zgpsmb55Ddm-Haw-UH0Auaj-rhHtNGxgYOtZBGcW2APZBswQz7rA5vNiPkYEO5ddOwAD-G6HLaZwjDNkL-ldGfyovj-9D-P71mLpHdgTrzaEoHc-8wSKVOtyzBSi8Pow8NSj1y-wOFti0hM41sRX1l95oPfc
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  821): Start proc 4368:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@31500d57}
,D/Finsky  ( 4368): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4368): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 39803(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 27MB/43MB, paused 1ms total 26.652ms
,E/ReminderSync( 1733): AuthError [T SyncAdapterThread-2:id=249:priority=5:group=main]
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  821): Start proc 4407:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 41904, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  821): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 171947, reason: Periodic
,W/Settings( 4368): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 4368): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ConfigFetchTask( 1733): updating config table for com.google.android.gms
W/GLSActivity( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1478): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1478): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1478): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 4407): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4407): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4368): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4368): [1] 2.run: Finished loading 1 libraries.
,E/DefaultHttpIssuer( 4189): Attempt to consume entity of HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 4189): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 4189): java.io.IOException
E/DefaultHttpIssuer( 4189): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 4189): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 4189): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 4189): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 4189): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 4189): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 4189): 	at dlr.run(PG:3031)
,E/BaseSyncManager( 4189): AuthenticatorException
E/BaseSyncManager( 4189): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 4189): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/BaseSyncManager( 4189): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 4189): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/BaseSyncManager( 4189): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 4189): 	at android.os.Binder.execTransact(Binder.java:446)
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@31500d57}
,I/MultiDex( 4407): VM with version 2.1.0 has multidex support
I/MultiDex( 4407): install
I/MultiDex( 4407): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  821): Start proc 4427:com.google.android.apps.genie.geniewidget/u0a80 for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService
,I/ConfigFetchService( 1733): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1733): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1733): GmsCore config value changed; rescheduling
,V/JNIHelp ( 4407): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ConfigFetchService( 1733): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1733): fetch service done; releasing wakelock
,I/ConfigFetchService( 1733): stopping self
,I/ProviderInstaller( 4407): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 4368): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  821): Start proc 4452:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,D/Finsky  ( 4368): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/AuthorizationBluetoothService( 1478): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1478): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/GoogleURLConnFactory( 1478): Using platform SSLCertificateSocketFactory
,V/GmsCoreStatsServiceLauncher( 1733): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/art     (  821): Explicit concurrent mark sweep GC freed 40023(1693KB) AllocSpace objects, 13(490KB) LOS objects, 32% free, 33MB/49MB, paused 1.586ms total 66.850ms
,D/WearableService( 3821): callingUid 10011, callindPid: 3821
,D/LocationInitializer( 1733): Restart initialization of location
,E/MDM     ( 1704): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Finsky  ( 4368): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 20125(1195KB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 26MB/42MB, paused 923us total 33.224ms
,E/Uploader( 1478): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1478): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GoogleAuthProtoRequest( 4452): [475] a.<init>: mAccountName set to: thalitester@gmail.com
,I/NewsWeather( 4427): Last usage 1447148544093, idle 6609654 seconds, sync interval 2592000 seconds
I/NewsWeather( 4427): setPeriodicSync in 2592000 seconds
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/NewsWeather( 4427): NewsAccounts 2, AllSystemAccounts 1
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4452): [475] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4452): [475] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4452): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4452): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4452): 	at com.a.a.k.run(SourceFile:110)
,W/ResourcesManager( 4427): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4427): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 4427): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/Ads     ( 1733): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,D/Finsky  ( 4368): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4368): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4368): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ActivityManager(  821): Killing 4037:com.google.android.apps.cloudprint/u0a41 (adj 15): empty #17
,I/ProviderInstaller( 4427): Installed default security provider GmsCore_OpenSSL
,I/GoogleURLConnFactory( 4427): binding HttpService
,W/Uploader( 1478): No account for auth token provided
,I/ActivityManager(  821): Killing 2892:com.google.android.music:main/u0a66 (adj 15): empty #18
,D/Finsky  ( 4368): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NewsWeather( 4427): ApiOperation url https://news.google.com/news/exec/fetchNewsEditions
,W/Finsky  ( 4368): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.genie.geniewidget, service: oauth2:https://www.googleapis.com/auth/newsreader
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/newsreader without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4368): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/NewsWeather( 4427): Exception reported
E/NewsWeather( 4427): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4427): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4427): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.pa(SourceFile:152)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:102)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.d.pb(SourceFile:82)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.l.au(SourceFile:153)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.l.as(SourceFile:92)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.l.onPerformSync(SourceFile:81)
E/NewsWeather( 4427): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/NewsWeather( 4427): Signed-in user with null auth token
E/NewsWeather( 4427): Failed to performDownSync for LookupEditions
E/NewsWeather( 4427): Down sync of lookup editions failed, error code: SYNC_IO_ERROR
,I/NewsWeather( 4427): Detected SyncErrorCodeCategory SOFT_ERROR
,I/NewsWeather( 4427): Abort on too many retries? false
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, currentRunTime 41945, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4368): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 4368): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4368): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4368): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2),
,D/Finsky  ( 4368): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/DeviceConnectionService( 1704): client connected with version: 7571000
,D/Finsky  ( 4368): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,I/ActivityManager(  821): Killing 3993:com.google.android.apps.cloudprint:sync/u0a41 (adj 15): empty #17
,W/Uploader( 1478): No account for auth token provided
,I/ActivityManager(  821): Killing 4072:com.google.android.configupdater/u0a42 (adj 15): empty #17
,W/Uploader( 1478): No account for auth token provided
,I/VacuumService( 1478): Vacuum at: now=1453758200786 tag=VacuumService
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,I/ConfigService( 1478): onDestroy
,W/Uploader( 1478): No account for auth token provided
,I/ActivityManager(  821): Killing 3966:android.process.acore/u0a5 (adj 15): empty #17
,W/PackageSettings(  821): Skipping PackageSetting{1ebd37b1 com.example.hello/10273} due to missing metadata
,I/ActivityManager(  821): Killing 4018:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  821): Start proc 4508:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  821): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  821): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager( 4508): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Uploader( 1478): No account for auth token provided
,I/Launcher( 1316): Deferring update until onResume
,I/art     (  821): Explicit concurrent mark sweep GC freed 54861(2MB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 1.458ms total 62.340ms
V/BackupManagerService(  821): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  821): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1234605f
,V/BackupManagerService(  821): Scheduling immediate backup pass
,V/BackupManagerService(  821): Running a backup pass
V/BackupManagerService(  821): clearing pending backups
,V/PerformBackupTask(  821): Beginning backup of 14 targets
,D/PerformBackupTask(  821): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  821): doBackup() invoked
,I/PMBA    (  821): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,V/GmsNetworkLocationProvi( 1704): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/GmsNetworkLocationProvi( 1704): DISABLE
,V/GmsNetworkLocationProvi( 1704): ENABLE
,V/GmsNetworkLocationProvi( 1704): SET-REQUEST
,V/GmsNetworkLocationProvi( 1704): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,I/BackupRestoreController(  821): Getting widget state for user: 0
,W/GmsBackupTransport( 1704): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1704): starting performBackup for @pm@
,V/GmsBackupTransport( 1704): performBackup done for @pm@
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1478): No account for auth token provided
,I/Babel_SMS( 4508): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4508): MmsConfig.loadMmsSettings
I/Babel_SMS( 4508): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 4508): MmsConfig.loadFromDatabase
,W/GLSActivity( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1478): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1478): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1478): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1478): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1704): Error sending final backup to server: 
W/GmsBackupTransport( 1704): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1704): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1704): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1704): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1704): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1704): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1704): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1704): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1704): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1704): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1704): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1704): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1704): 	... 1 more
,D/BackupManagerService(  821): Now staging backup of com.google.android.talk
,E/Babel_SMS( 4508): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4508): MmsConfig.loadFromResources
,D/BackupManagerService(  821): Now staging backup of com.google.android.dialer
,E/Babel_SMS( 4508): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4508): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,D/BackupManagerService(  821): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  821): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  821): Now staging backup of com.google.android.gm
,D/BackupManagerService(  821): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  821): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  821): Now staging backup of com.android.nfc
,W/Settings( 4508): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 4508): startup - clean
,D/BackupManagerService(  821): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  821): Now staging backup of com.android.vending
,I/Babel   ( 4508): deleted: false for 0
,D/BackupManagerService(  821): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  821): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  821): Now staging backup of android
,D/BackupManagerService(  821): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1704): Next backup will happen in 43199904 millis.
,I/Babel_telephony( 4508): TeleModule.launchCompleted
I/BackupManagerService(  821): Backup pass finished.
,W/Telecom (  821): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 4508): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 4508): BAM#gBA: invalid account id: -1
W/Babel   ( 4508): BAM#gBA: invalid account id: -1
I/Babel_telephony( 4508): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
W/Telecom (  821): TelecomServiceImpl: null is not visible for the calling user
,I/ActivityManager(  821): Start proc 4540:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,W/Uploader( 1478): No account for auth token provided
,W/VideoCapabilities( 4508): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 4508): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4508): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4508): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4508): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4508): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 1733): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 4132): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageBroadcastService( 1733): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1316): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@319210b4 new=com.google.android.velvet.VelvetApplication@319210b4
,I/Icing   ( 1733): updateResources: need to parse f{com.google.android.gms}
,I/vclib   ( 4508): onServiceConnected
W/Babel   ( 4508): Attempted to change video mute state without an active call.
,I/ContactLocale( 4540): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/ResourcesManager( 4508): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4508): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  821): Start proc 4567:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,W/Uploader( 1478): No account for auth token provided
,W/ResourcesManager( 4567): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4132): UpdateCorporaTask done [took 127 ms] updated apps [took 127 ms] 
,V/JNIHelp ( 4508): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4508): Installed default security provider GmsCore_OpenSSL
,W/Uploader( 1478): No account for auth token provided
,I/ActivityManager(  821): Killing 3756:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=75.90 rxSuccessRate=62.31 targetRoamBSSID=any RSSI=-50
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,I/ActivityManager(  821): Killing 3914:com.android.providers.calendar/u0a3 (adj 15): empty #17
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,I/ActivityManager(  821): Killing 3894:com.google.android.calendar/u0a37 (adj 15): empty #17
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided,
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,I/ActivityManager(  821): Start proc 4595:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,W/Uploader( 1478): No account for auth token provided
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4368): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4368): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4368): [1] 5.onFinished: Scheduling replication attempt 5.
,V/KeepSync( 4595): Connecting to GoogleApiClient
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (623 us)
,W/Uploader( 1478): No account for auth token provided
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1733): Handling authorization failure
E/ClientConnectionOperation( 1733): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1733): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1733): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1733): 	... 7 more
,V/KeepSync( 4595): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4595): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4595): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4595): (284) automatic index on blob_node(is_deleted)
,W/Uploader( 1478): No account for auth token provided
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4595): IOException
E/KeepSync( 4595): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4595): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4595): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4595): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4595): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4595): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4595): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4595): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4595): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4595): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4595): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4595): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4595): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4595): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4595): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4595): 	... 10 more
W/KeepSync( 4595): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 162372, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,W/Uploader( 1478): No account for auth token provided
,I/art     (  821): Explicit concurrent mark sweep GC freed 29161(1635KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 1.738ms total 64.455ms
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4567): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4567): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4567): 	at jdm.a(PG:82)
E/HttpOperation( 4567): 	at jcs.o(PG:406)
E/HttpOperation( 4567): 	at jcn.a(PG:1379)
E/HttpOperation( 4567): 	at jcs.i(PG:143)
E/HttpOperation( 4567): 	at blb.a(PG:3937)
E/HttpOperation( 4567): 	at czp.a(PG:18188)
E/HttpOperation( 4567): 	at czp.a(PG:9087)
E/HttpOperation( 4567): 	at czq.run(PG:1686)
E/HttpOperation( 4567): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4567): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4567): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4567): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4567): 	at jdj.a(PG:4091)
E/HttpOperation( 4567): 	at jdj.a(PG:1125)
E/HttpOperation( 4567): 	at jdm.a(PG:77)
E/HttpOperation( 4567): 	... 12 more
E/HttpOperation( 4567): Caused by: faj: BadAuthentication
E/HttpOperation( 4567): 	at fal.a(PG:38)
E/HttpOperation( 4567): 	at jdj.a(PG:4089)
E/HttpOperation( 4567): 	... 14 more
,W/Uploader( 1478): No account for auth token provided
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  821): Display changed displayId=0
,D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000
,D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4567): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4567): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4567): 	at jdm.a(PG:82)
E/HttpOperation( 4567): 	at jcs.o(PG:406)
E/HttpOperation( 4567): 	at jcn.a(PG:1379)
E/HttpOperation( 4567): 	at jcs.i(PG:143)
E/HttpOperation( 4567): 	at blb.a(PG:3937)
E/HttpOperation( 4567): 	at czp.a(PG:18188)
E/HttpOperation( 4567): 	at czp.a(PG:9081)
E/HttpOperation( 4567): 	at czq.run(PG:1686)
E/HttpOperation( 4567): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4567): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4567): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4567): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4567): 	at jdj.a(PG:4091)
E/HttpOperation( 4567): 	at jdj.a(PG:1125)
E/HttpOperation( 4567): 	at jdm.a(PG:77)
E/HttpOperation( 4567): 	... 12 more
E/HttpOperation( 4567): Caused by: faj: BadAuthentication
E/HttpOperation( 4567): 	at fal.a(PG:38)
E/HttpOperation( 4567): 	at jdj.a(PG:4089)
E/HttpOperation( 4567): 	... 14 more
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4567): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4567): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4567): 	at jdm.a(PG:82)
E/HttpOperation( 4567): 	at jcs.o(PG:406)
E/HttpOperation( 4567): 	at jcn.a(PG:1379)
E/HttpOperation( 4567): 	at jcs.i(PG:143)
E/HttpOperation( 4567): 	at hec.a(PG:42)
E/HttpOperation( 4567): 	at hee.a(PG:102)
E/HttpOperation( 4567): 	at czr.a(PG:65)
E/HttpOperation( 4567): 	at kka.a(PG:108)
E/HttpOperation( 4567): 	at czp.a(PG:19176)
E/HttpOperation( 4567): 	at czp.a(PG:9081)
E/HttpOperation( 4567): 	at czq.run(PG:1686)
E/HttpOperation( 4567): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4567): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4567): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4567): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4567): 	at jdj.a(PG:4091)
E/HttpOperation( 4567): 	at jdj.a(PG:1125)
E/HttpOperation( 4567): 	at jdm.a(PG:77)
E/HttpOperation( 4567): 	... 15 more
E/HttpOperation( 4567): Caused by: faj: BadAuthentication
E/HttpOperation( 4567): 	at fal.a(PG:38)
E/HttpOperation( 4567): 	at jdj.a(PG:4089)
E/HttpOperation( 4567): 	... 17 more
,E/ExperimentLoader( 4567): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4567): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4567): 	at jdm.a(PG:82)
E/ExperimentLoader( 4567): 	at jcs.o(PG:406)
E/ExperimentLoader( 4567): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4567): 	at jcs.i(PG:143)
E/ExperimentLoader( 4567): 	at hec.a(PG:42)
E/ExperimentLoader( 4567): 	at hee.a(PG:102)
E/ExperimentLoader( 4567): 	at czr.a(PG:65)
E/ExperimentLoader( 4567): 	at kka.a(PG:108)
E/ExperimentLoader( 4567): 	at czp.a(PG:19176)
E/ExperimentLoader( 4567): 	at czp.a(PG:9081)
E/ExperimentLoader( 4567): 	at czq.run(PG:1686)
E/ExperimentLoader( 4567): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4567): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4567): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4567): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4567): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4567): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4567): 	at jdm.a(PG:77)
E/ExperimentLoader( 4567): 	... 15 more
E/ExperimentLoader( 4567): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4567): 	at fal.a(PG:38)
E/ExperimentLoader( 4567): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4567): 	... 17 more
,W/Uploader( 1478): No account for auth token provided
,I/ActivityManager(  821): Killing 3681:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131327, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  821): Excessive delay in setPowerMode(): 269ms
,I/DreamManagerService(  821): Entering dreamland.
,I/PowerManagerService(  821): Dozing...
I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 6
,E/native  (  821): do suspend false
,W/Uploader( 1478): No account for auth token provided
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3f215b2e}
,I/Keyboard.Facilitator( 1215): onFinishInput()
,E/WifiStateMachine(  821): cancelDelayedScan -> 8
,E/native  (  821): do suspend true
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-50
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 144736(7MB) AllocSpace objects, 13(521KB) LOS objects, 36% free, 27MB/43MB, paused 2.310ms total 54.511ms
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,W/Uploader( 1478): No account for auth token provided
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.00 rxSuccessRate=1.00 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3f215b2e}
,I/art     ( 1704): Explicit concurrent mark sweep GC freed 19803(1189KB) AllocSpace objects, 9(167KB) LOS objects, 37% free, 27MB/43MB, paused 1.252ms total 51.163ms
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,E/DataBuffer( 1704): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3ef9b657)
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided,
,W/Uploader( 1478): No account for auth token provided
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=20.50 rxSuccessRate=21.50 targetRoamBSSID=any RSSI=-50
,E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 8 -> obsolete
,E/Uploader( 1478): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1478): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1478): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1478): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1478): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1478): No account for auth token provided
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1478): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1478): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided,
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided,
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1478): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1478): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478):  no longer exists, so no auth token.
,W/Uploader( 1478): No account for auth token provided
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1478): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1478): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1478): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1478): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1478): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1478): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1478): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1478): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1478): No account for auth token provided
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1478): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1478): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1478): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1478): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1478): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1478): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,I/GoogleURLConnFactory( 1478): Using platform SSLCertificateSocketFactory
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,W/Uploader( 1478): No account for auth token provided
,I/GoogleURLConnFactory( 1478): Using platform SSLCertificateSocketFactory
,I/art     (  821): Explicit concurrent mark sweep GC freed 35544(1716KB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 1.496ms total 98.921ms
,I/ActivityManager(  821): Start proc 4647:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,V/GoogleAuthProtoRequest( 4452): [476] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4452): [476] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4452): [476] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4452): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4452): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4452): 	at com.a.a.k.run(SourceFile:110)
,W/ResourcesManager( 4647): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4647): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4647): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GoogleAuthProtoRequest( 4452): [477] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ProviderInstaller( 4647): Installed default security provider GmsCore_OpenSSL
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4452): [477] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4452): [477] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4452): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4452): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4452): 	at com.a.a.k.run(SourceFile:110)
,E/YouTube MDX( 4647): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 4678): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-494565010.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads-494565010.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4678): dex2oat took 33.756ms (threads: 4) arena alloc=169KB java alloc=12KB native alloc=1218KB free=6MB
,W/InstanceID/Rpc( 4647): Found 10011
,I/ActivityManager(  821): Killing 4328:com.android.chrome/u0a40 (adj 15): empty #17
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4368): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4368): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4368): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 3232): Disconnected process message: 10, size: 0
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1733): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  821): Start proc 4739:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 225us total 11.123ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 10.015ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 379us total 9.896ms
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 1733): 0 accounts found with uca feature
,I/GamesSyncAdapter( 1733): Starting sync for 3a3529a
,I/GamesSyncAdapter( 1733): Sync duration for 3a3529a: 4
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.games from APK com.google.android.play.games,
,D/ChimeraModuleLdr( 1733): Module APK com.google.android.play.games already loaded
,I/PeopleSync( 1733): onPerformSync() [5005f081]
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4739): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4739): Created application version: 3.6.8 (30608)
,D/ChimeraCfgMgr( 1733): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1733): Module APK com.google.android.play.games already loaded
,I/PeopleSync( 1733): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1733): Starting sync, feed=null [5005f081]
,I/BooksSync( 4739): Starting books sync for 61035162, extras: ade
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 65705(4MB) AllocSpace objects, 50(5MB) LOS objects, 36% free, 27MB/43MB, paused 1.042ms total 42.337ms
,I/PeopleSync( 1733): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleSync( 1733): Sync finished, successful=false, took 35ms
,I/PeopleSync( 1733): Cannot authenticate [5005f081]
I/PeopleSync( 1733): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 1733): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 1733): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 1733): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 1733): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 1733): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 1733): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 1733): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 1733): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 1733): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 1733): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 1733): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/PeopleSync( 1733): ***Sync finished***, duration: 222 [5005f081]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 166010, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  821): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 255134, reason: Periodic
,I/BooksConfig( 4739): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  821): Explicit concurrent mark sweep GC freed 28374(1216KB) AllocSpace objects, 12(1040KB) LOS objects, 32% free, 33MB/49MB, paused 1.574ms total 50.280ms
,I/NewsWeather( 4427): Last usage 1447148544093, idle 6609706 seconds, sync interval 2592000 seconds
I/NewsWeather( 4427): setPeriodicSync in 2592000 seconds
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/NewsWeather( 4427): Skip sync for lookup editions,
,I/NewsWeather( 4427): syncNewsAppData traffic type BACKGROUND_POLL,
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4739): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4739): Soft error
E/BooksSync( 4739): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4739): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4739): Sync error
E/BooksSync( 4739): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4739): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4739): Finished books sync
,I/NewsWeather( 4427): onConnected null
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 165652, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/NewsWeather( 4427): Location onConnected: found location from FusedLocationApi
,I/NewsWeather( 4427): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.genie.geniewidget, service: oauth2:https://www.googleapis.com/auth/newsreader
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/newsreader without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/NewsWeather( 4427): Exception reported
E/NewsWeather( 4427): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4427): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4427): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.pa(SourceFile:152)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:102)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.d.a(SourceFile:284)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.l.au(SourceFile:164)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.l.as(SourceFile:92)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.l.onPerformSync(SourceFile:81)
E/NewsWeather( 4427): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,E/NewsWeather( 4427): Signed-in user with null auth token
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1720206611
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/NewsWeather( 4427): Transport error in DownSync
E/NewsWeather( 4427): Down sync of news app Failed, error code: SYNC_IO_ERROR
,I/NewsWeather( 4427): Detected SyncErrorCodeCategory SOFT_ERROR
,I/NewsWeather( 4427): Abort on too many retries? false
,I/ActivityManager(  821): Killing 4278:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, currentRunTime 172617, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GAV2    ( 4739): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 4368): [450] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4368): [450] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4567): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4567): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4567): 	at jdm.a(PG:82)
E/HttpOperation( 4567): 	at jcs.o(PG:406)
E/HttpOperation( 4567): 	at jcn.a(PG:1379)
E/HttpOperation( 4567): 	at jcs.i(PG:143)
E/HttpOperation( 4567): 	at blb.a(PG:3937)
E/HttpOperation( 4567): 	at czp.a(PG:18188)
E/HttpOperation( 4567): 	at czp.a(PG:9081)
E/HttpOperation( 4567): 	at czq.run(PG:1686)
E/HttpOperation( 4567): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4567): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4567): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4567): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4567): 	at jdj.a(PG:4091)
E/HttpOperation( 4567): 	at jdj.a(PG:1125)
E/HttpOperation( 4567): 	at jdm.a(PG:77)
E/HttpOperation( 4567): 	... 12 more
E/HttpOperation( 4567): Caused by: faj: BadAuthentication
E/HttpOperation( 4567): 	at fal.a(PG:38)
E/HttpOperation( 4567): 	at jdj.a(PG:4089)
E/HttpOperation( 4567): 	... 14 more
,D/AlarmManagerService(  821): Setting time of day to sec=1453758281
W/AlarmManagerService(  821): Unable to set rtc to 1453758281: Invalid argument
,V/GoogleAuthProtoRequest( 4452): [478] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ActivityManager(  821): Start proc 4793:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4567): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4567): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4567): 	at jdm.a(PG:82)
E/HttpOperation( 4567): 	at jcs.o(PG:406)
E/HttpOperation( 4567): 	at jcn.a(PG:1379)
E/HttpOperation( 4567): 	at jcs.i(PG:143)
E/HttpOperation( 4567): 	at hec.a(PG:42)
E/HttpOperation( 4567): 	at hee.a(PG:102)
E/HttpOperation( 4567): 	at czr.a(PG:65)
E/HttpOperation( 4567): 	at kka.a(PG:108)
E/HttpOperation( 4567): 	at czp.a(PG:19176)
E/HttpOperation( 4567): 	at czp.a(PG:9081)
E/HttpOperation( 4567): 	at czq.run(PG:1686)
E/HttpOperation( 4567): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4567): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4567): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4567): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4567): 	at jdj.a(PG:4091)
E/HttpOperation( 4567): 	at jdj.a(PG:1125)
E/HttpOperation( 4567): 	at jdm.a(PG:77)
E/HttpOperation( 4567): 	... 15 more
E/HttpOperation( 4567): Caused by: faj: BadAuthentication
E/HttpOperation( 4567): 	at fal.a(PG:38)
E/HttpOperation( 4567): 	at jdj.a(PG:4089)
E/HttpOperation( 4567): 	... 17 more
,E/ExperimentLoader( 4567): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4567): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4567): 	at jdm.a(PG:82)
E/ExperimentLoader( 4567): 	at jcs.o(PG:406)
E/ExperimentLoader( 4567): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4567): 	at jcs.i(PG:143)
E/ExperimentLoader( 4567): 	at hec.a(PG:42)
E/ExperimentLoader( 4567): 	at hee.a(PG:102)
E/ExperimentLoader( 4567): 	at czr.a(PG:65)
E/ExperimentLoader( 4567): 	at kka.a(PG:108)
E/ExperimentLoader( 4567): 	at czp.a(PG:19176)
E/ExperimentLoader( 4567): 	at czp.a(PG:9081)
E/ExperimentLoader( 4567): 	at czq.run(PG:1686)
E/ExperimentLoader( 4567): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4567): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4567): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4567): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4567): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4567): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4567): 	at jdm.a(PG:77)
E/ExperimentLoader( 4567): 	... 15 more
E/ExperimentLoader( 4567): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4567): 	at fal.a(PG:38)
E/ExperimentLoader( 4567): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4567): 	... 17 more
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4452): [478] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4452): [478] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4452): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4452): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4452): 	at com.a.a.k.run(SourceFile:110)
,E/SQLiteLog( 4793): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  821): Start proc 4814:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 193964, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/ResourcesManager( 4814): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 4793): PlayLogger.onLoggerConnected
,I/ActivityManager(  821): Start proc 4835:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/CalendarProvider2( 4814): Created com.android.providers.calendar.CalendarAlarmManager@3f369a1c(com.android.providers.calendar.CalendarProvider2@1adc5625)
,D/TimeService( 4835): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453758281594
,D/        ( 4835): TimeServiceNative: User Time to be set is 1453758281594
D/QC-time-services( 4835): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4835): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4835): Lib:time_genoff_operation: pargs->ts_val = 1453758281594
D/QC-time-services( 4835): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  372): Daemon: Connection accepted:time_genoff
D/QC-time-services(  372): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453758281594
D/QC-time-services(  372): Daemon:genoff_opr: Base = 2, val = 1453758281594, operation = 0
D/QC-time-services(  372): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/12/70 17:57:9
D/QC-time-services(  372): Daemon:Value read from RTC seconds = 14061429000
D/QC-time-services(  372): Daemon:new time 1453758281594 
D/QC-time-services(  372): Daemon: delta 1439696852594 genoff 1439696852594 
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696852594 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  372): Updating the TOD offset
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696852594 to memory
,D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services( 4835): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  372): Daemon:Update to modem bit set
D/QC-time-services(  372): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  372): Daemon: Base = 2, Value being sent to MODEM = 1137793481594
,I/ActivityManager(  821): Killing 4407:com.google.android.gms:car/u0a11 (adj 15): empty #17
,E/QC-time-services(  372): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  372): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/kickstart(  875): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  875): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  875): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  875): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/ActivityManager(  821): Start proc 4856:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/art     (  821): Explicit concurrent mark sweep GC freed 20239(943KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.672ms total 87.264ms
,I/GAv4    ( 4856): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4856):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4856):   adb logcat -s GAv4
,W/GAv4    ( 4856): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4856): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1215): run()
I/Keyboard.Facilitator( 1215): flushDynamicLanguageModels()
,W/GAv4    ( 4856): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ConfigService( 1478): onCreate
,I/ActivityManager(  821): Killing 3821:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/CalendarProvider2( 4814): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 4814): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/kickstart(  875): STATUS: Received file 'm9kefs2'
I/kickstart(  875): STATUS: 950272 bytes transferred in 0.984847 seconds
I/kickstart(  875): STATUS: Successfully downloaded files from target 
I/kickstart(  875): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  875): STATUS: Sahara protocol completed,
,I/ActivityManager(  821): Killing 4132:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,I/GAV2    ( 4793): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1478): onDestroy
,I/ActivityManager(  821): Killing 4508:com.google.android.talk/u0a61 (adj 15): empty #17
,D/HeadsetStateMachine( 3232): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3232): Disconnected process message: 10, size: 0
,V/KeepSync( 4595): Connecting to GoogleApiClient
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1733): Handling authorization failure
E/ClientConnectionOperation( 1733): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1733): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1733): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1733): 	... 7 more
,V/KeepSync( 4595): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4595): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4595): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 4595): (284) automatic index on blob_node(is_deleted),
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4595): IOException
E/KeepSync( 4595): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4595): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4595): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4595): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4595): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4595): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4595): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4595): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4595): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4595): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4595): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4595): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4595): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4595): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4595): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4595): 	... 10 more
W/KeepSync( 4595): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 223956, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 4452): [479] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 32338(2039KB) AllocSpace objects, 13(1433KB) LOS objects, 37% free, 27MB/43MB, paused 1.910ms total 52.696ms
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4452): [479] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4452): [479] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4452): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4452): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4452): 	at com.a.a.k.run(SourceFile:110)
,I/NewsWeather( 4427): Last usage 1447148544093, idle 6609797 seconds, sync interval 2592000 seconds
I/NewsWeather( 4427): setPeriodicSync in 2592000 seconds
,I/BooksSync( 4739): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4739): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/NewsWeather( 4427): Skip sync for lookup editions,
I/NewsWeather( 4427): syncNewsAppData traffic type BACKGROUND_POLL,
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NewsWeather( 4427): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.genie.geniewidget, service: oauth2:https://www.googleapis.com/auth/newsreader
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/newsreader without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4739): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4739): Soft error
E/BooksSync( 4739): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4739): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4739): Sync error
E/BooksSync( 4739): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4739): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4739): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 258326, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/NewsWeather( 4427): Exception reported
E/NewsWeather( 4427): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4427): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4427): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.pa(SourceFile:152)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:102)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.d.a(SourceFile:284)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.l.au(SourceFile:164)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.l.as(SourceFile:92)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.l.onPerformSync(SourceFile:81)
E/NewsWeather( 4427): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/NewsWeather( 4427): Signed-in user with null auth token
E/NewsWeather( 4427): Transport error in DownSync
E/NewsWeather( 4427): Down sync of news app Failed, error code: SYNC_IO_ERROR
,I/NewsWeather( 4427): Detected SyncErrorCodeCategory SOFT_ERROR
I/NewsWeather( 4427): Abort on too many retries? false
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, currentRunTime 253638, reason: Periodic, SyncResult: stats [ numIoExceptions: 1],
,V/GoogleAuthProtoRequest( 4452): [480] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4452): [480] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4452): [480] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4452): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4452): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4452): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3232): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3232): Disconnected process message: 10, size: 0
,I/art     (  821): Explicit concurrent mark sweep GC freed 26381(1137KB) AllocSpace objects, 7(300KB) LOS objects, 31% free, 34MB/50MB, paused 1.513ms total 91.862ms
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4567): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4567): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4567): 	at jdm.a(PG:82)
E/HttpOperation( 4567): 	at jcs.o(PG:406)
E/HttpOperation( 4567): 	at jcn.a(PG:1379)
E/HttpOperation( 4567): 	at jcs.i(PG:143)
E/HttpOperation( 4567): 	at blb.a(PG:3937)
E/HttpOperation( 4567): 	at czp.a(PG:18188)
E/HttpOperation( 4567): 	at czp.a(PG:9081)
E/HttpOperation( 4567): 	at czq.run(PG:1686)
E/HttpOperation( 4567): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4567): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4567): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4567): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4567): 	at jdj.a(PG:4091)
E/HttpOperation( 4567): 	at jdj.a(PG:1125)
E/HttpOperation( 4567): 	at jdm.a(PG:77)
E/HttpOperation( 4567): 	... 12 more
E/HttpOperation( 4567): Caused by: faj: BadAuthentication
E/HttpOperation( 4567): 	at fal.a(PG:38)
E/HttpOperation( 4567): 	at jdj.a(PG:4089)
E/HttpOperation( 4567): 	... 14 more
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4567): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4567): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4567): 	at jdm.a(PG:82)
E/HttpOperation( 4567): 	at jcs.o(PG:406)
E/HttpOperation( 4567): 	at jcn.a(PG:1379)
E/HttpOperation( 4567): 	at jcs.i(PG:143)
E/HttpOperation( 4567): 	at hec.a(PG:42)
E/HttpOperation( 4567): 	at hee.a(PG:102)
E/HttpOperation( 4567): 	at czr.a(PG:65)
E/HttpOperation( 4567): 	at kka.a(PG:108)
E/HttpOperation( 4567): 	at czp.a(PG:19176)
E/HttpOperation( 4567): 	at czp.a(PG:9081)
E/HttpOperation( 4567): 	at czq.run(PG:1686)
E/HttpOperation( 4567): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4567): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4567): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4567): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4567): 	at jdj.a(PG:4091)
E/HttpOperation( 4567): 	at jdj.a(PG:1125)
E/HttpOperation( 4567): 	at jdm.a(PG:77)
E/HttpOperation( 4567): 	... 15 more
E/HttpOperation( 4567): Caused by: faj: BadAuthentication
E/HttpOperation( 4567): 	at fal.a(PG:38)
E/HttpOperation( 4567): 	at jdj.a(PG:4089)
E/HttpOperation( 4567): 	... 17 more
E/ExperimentLoader( 4567): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4567): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4567): 	at jdm.a(PG:82)
E/ExperimentLoader( 4567): 	at jcs.o(PG:406)
E/ExperimentLoader( 4567): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4567): 	at jcs.i(PG:143)
E/ExperimentLoader( 4567): 	at hec.a(PG:42)
E/ExperimentLoader( 4567): 	at hee.a(PG:102)
E/ExperimentLoader( 4567): 	at czr.a(PG:65)
E/ExperimentLoader( 4567): 	at kka.a(PG:108)
E/ExperimentLoader( 4567): 	at czp.a(PG:19176)
E/ExperimentLoader( 4567): 	at czp.a(PG:9081)
E/ExperimentLoader( 4567): 	at czq.run(PG:1686)
E/ExperimentLoader( 4567): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4567): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4567): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4567): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4567): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4567): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4567): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4567): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4567): 	at jdm.a(PG:77)
E/ExperimentLoader( 4567): 	... 15 more
E/ExperimentLoader( 4567): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4567): 	at fal.a(PG:38)
E/ExperimentLoader( 4567): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4567): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 283995, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3232): Disconnected process message: 10, size: 0
,V/KeepSync( 4595): Connecting to GoogleApiClient
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1733): Handling authorization failure
E/ClientConnectionOperation( 1733): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1733): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1733): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1733): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1733): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1733): 	... 7 more
,V/KeepSync( 4595): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4595): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4595): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4595): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 4595): IOException
E/KeepSync( 4595): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4595): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4595): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4595): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4595): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4595): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4595): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4595): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4595): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4595): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4595): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4595): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4595): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4595): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4595): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4595): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4595): 	... 10 more
W/KeepSync( 4595): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 375144, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 4452): [481] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4452): [481] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4452): [481] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4452): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4452): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4452): 	at com.a.a.k.run(SourceFile:110)
,I/NewsWeather( 4427): Last usage 1447148544093, idle 6609919 seconds, sync interval 2592000 seconds
,I/NewsWeather( 4427): setPeriodicSync in 2592000 seconds
,I/NewsWeather( 4427): Skip sync for lookup editions
,I/NewsWeather( 4427): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4427): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.genie.geniewidget, service: oauth2:https://www.googleapis.com/auth/newsreader
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/newsreader without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/NewsWeather( 4427): Exception reported
E/NewsWeather( 4427): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4427): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4427): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.pa(SourceFile:152)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:102)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.d.a(SourceFile:284)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.l.au(SourceFile:164)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.l.as(SourceFile:92)
E/NewsWeather( 4427): 	at com.google.android.apps.genie.geniewidget.sync.l.onPerformSync(SourceFile:81)
E/NewsWeather( 4427): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/NewsWeather( 4427): Signed-in user with null auth token
E/NewsWeather( 4427): Transport error in DownSync
E/NewsWeather( 4427): Down sync of news app Failed, error code: SYNC_IO_ERROR
,I/NewsWeather( 4427): Detected SyncErrorCodeCategory SOFT_ERROR
,I/NewsWeather( 4427): Abort on too many retries? true
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, currentRunTime 403679, reason: Periodic, SyncResult: tooManyRetries: true stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 4452): [482] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1478): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1478): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1478): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1478): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1478): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4452): [482] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4452): [482] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4452): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4452): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4452): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4452): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4452): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3173): TAP version 13
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # multiplex can send data
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 1 String should be length:200
I/jxcore-log( 3173): 
I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # basic
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 2 sane
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # another
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 3 sane
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 4 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 5 null
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 6 (unnamed assert)
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 7 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 8 should not throw
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 9 (unnamed assert)
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 10 (unnamed assert)
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 11 should not throw
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 12 should be equal
I/jxcore-log( 3173): 
I/jxcore-log( 3173): ok 13 should be equal,
I/jxcore-log( 3173): ,
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 14 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # failed to get mobile documents path
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 15 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 16 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 17 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 18 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #init should register the networkChanged event
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 19 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #startBroadcasting should throw on null device name
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 20 should throw
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
,I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 21 should throw
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
,I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 22 should throw,
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 23 should throw
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #startBroadcasting should throw on negative port
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 24 should throw
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #startBroadcasting should throw on too large port
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 25 should throw
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 26 should be equal,
I/jxcore-log( 3173): 
I/jxcore-log( 3173): ok 27 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 28 should be equal,
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup,
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error,
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown,
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 29 should be equal,
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 30 should be equal,
I/jxcore-log( 3173): 
I/jxcore-log( 3173): ok 31 should be equal
I/jxcore-log( 3173): 
I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): ,
,I/jxcore-log( 3173): ok 32 should be equal
I/jxcore-log( 3173): ,
I/jxcore-log( 3173): ok 33 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup,
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 34 should be equal
I/jxcore-log( 3173): ,
,I/jxcore-log( 3173): ok 35 should be equal
,I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 36 should be equal,
I/jxcore-log( 3173): 
I/jxcore-log( 3173): ok 37 should be equal
I/jxcore-log( 3173): 
I/jxcore-log( 3173): ok 38 should be equal
I/jxcore-log( 3173): 
I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 39 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 40 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 41 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 42 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 43 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 44 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758478564.3173
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478564.3173","ra":"F8:CF:C5:D9:E5:61"},
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback,
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758478564.3173
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758478564.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3232): registerClient() - UUID=83b6ecd6-f124-4091-9efa-3afcc1e96c1c
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=83b6ecd6-f124-4091-9efa-3afcc1e96c1c, clientIf=5
,D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3232): message : 0
,D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): registerClient() - UUID=d8263bc9-e4bc-497f-a0be-c909b7b7db33
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=d8263bc9-e4bc-497f-a0be-c909b7b7db33, clientIf=6
D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3232): start scan with filters
,D/BtGatt.ScanManager( 3232): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothAdapterService( 3232): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17ae23fa
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478564.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478564.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478564.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758478564.3173
,I/io.jxcore.node.ConnectionHelper( 3173): start: OK
I/jxcore-log( 3173): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 3173): 
,I/io.jxcore.node.ConnectionHelper( 3173): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
,D/BtGatt.AdvertiseManager( 3232): message : 1
,D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
,D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): Client app is not null!
,D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.GattService( 3232): stopScan() - queue size =1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): onScanResult: Callback type: 1, Scan result: ScanResult{mDevice=FC:F3:1C:68:15:41, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 124, -7, 14, 52, -118, -96]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-78, mTimestampNanos=420328355411}
,D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services
,D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 3232): stop scan
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onPeerDiscovered: [7C:F9:E:34:8A:A0 <no peer name>]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): modifyListOfDiscoveredPeers: [7C:F9:E:34:8A:A0 <no peer name>], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): modifyListOfDiscoveredPeers: Adding a new peer: [7C:F9:E:34:8A:A0 <no peer name>]
,I/jxcore-log( 3173): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3173): onPeerDiscovered: [7C:F9:E:34:8A:A0 <no peer name>], Bluetooth address: 7C:F9:E:34:8A:A0, device name: , device address: 
D/io.jxcore.node.ConnectionHelper( 3173): notifyPeerAvailability: Peer [7C:F9:E:34:8A:A0 <no peer name>] is available
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758478748.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478748.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758478748.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758478748.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3232): registerClient() - UUID=68930dd6-f607-429c-98b9-c7c57b71c622
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=68930dd6-f607-429c-98b9-c7c57b71c622, clientIf=5
D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3232): message : 0
,D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): registerClient() - UUID=8c61c638-cfbe-4d40-b1a5-cef50942fd2a
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=8c61c638-cfbe-4d40-b1a5-cef50942fd2a, clientIf=6
,D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3232): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3232): handling starting scan
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478748.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478748.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478748.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/wpa_supplicant( 3244): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758478748.3173
I/io.jxcore.node.ConnectionHelper( 3173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
I/jxcore-log( 3173): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 3173): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3173): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 3232): message : 1
D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
,D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): Client app is not null!
,D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 3232): stopScan() - queue size =1
,D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): stop scan
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
I/jxcore-log( 3173): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758478851.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478851.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758478851.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758478851.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3232): registerClient() - UUID=7e31b792-76e2-483e-b783-8ad1e61a246d
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=7e31b792-76e2-483e-b783-8ad1e61a246d, clientIf=5
D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3232): message : 0
,D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): registerClient() - UUID=bece0e73-a879-4630-bb3f-e90ddb4324bd
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=bece0e73-a879-4630-bb3f-e90ddb4324bd, clientIf=6
D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3232): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3232): handling starting scan
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478851.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478851.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478851.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3173): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758478851.3173
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/wpa_supplicant( 3244): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED
I/jxcore-log( 3173): ok 49 Should be able to call startBroadcasting without error
,I/jxcore-log( 3173): 
I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3173): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 3232): message : 1
D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3232): Client app is not null!
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 3232): stopScan() - queue size =1
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
D/BtGatt.ScanManager( 3232): stop scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
,D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log( 3173): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758478921.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478921.3173","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758478921.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758478921.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3232): registerClient() - UUID=5656d0e1-8bff-46e2-a9be-28fc914a92de,
D/BtGatt.GattService( 3232): onClientRegistered() - UUID=5656d0e1-8bff-46e2-a9be-28fc914a92de, clientIf=5
D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3232): message : 0
,D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): registerClient() - UUID=f9f1c9c6-314a-4b5f-bcf7-4129105b96c8
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=f9f1c9c6-314a-4b5f-bcf7-4129105b96c8, clientIf=6
D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3232): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3232): handling starting scan
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478921.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478921.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758478921.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 3244): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758478921.3173
I/io.jxcore.node.ConnectionHelper( 3173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
I/jxcore-log( 3173): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 3173): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3173): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 3232): message : 1
,D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
,D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): Client app is not null!
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3232): stopScan() - queue size =1
,D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...
,D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
D/BtGatt.ScanManager( 3232): stop scan
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
,I/jxcore-log( 3173): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI,
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479003.3173
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479003.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479003.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758479003.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3232): registerClient() - UUID=016fbb87-d9a7-4193-9a8f-3984e71c3ace
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=016fbb87-d9a7-4193-9a8f-3984e71c3ace, clientIf=5
D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3232): message : 0
,D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0,
,D/BtGatt.GattService( 3232): registerClient() - UUID=ff969362-23cf-4b8a-be77-d2d9652944c1,
D/BtGatt.GattService( 3232): onClientRegistered() - UUID=ff969362-23cf-4b8a-be77-d2d9652944c1, clientIf=6
,D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3232): start scan with filters
,D/BtGatt.ScanManager( 3232): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479003.3173","ra":"F8:CF:C5:D9:E5:61"},
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479003.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479003.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479003.3173
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
I/wpa_supplicant( 3244): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED
I/jxcore-log( 3173): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 3173): 
I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3173): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 3232): message : 1
,D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3232): Client app is not null!
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 3232): stopScan() - queue size =1
,D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 3232): stop scan
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3173): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479095.3173
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479095.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479095.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758479095.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3232): registerClient() - UUID=57ffc14c-ba85-43c0-bf89-e84d0fb496e5
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=57ffc14c-ba85-43c0-bf89-e84d0fb496e5, clientIf=5
,D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3232): message : 0
,D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): registerClient() - UUID=55d41f14-36a4-461f-b641-f84a04917476
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=55d41f14-36a4-461f-b641-f84a04917476, clientIf=6
D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3232): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3232): handling starting scan
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479095.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479095.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479095.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479095.3173
I/wpa_supplicant( 3244): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
I/jxcore-log( 3173): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 3173): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3173): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 3232): message : 1
D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3232): Client app is not null!
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 3232): stopScan() - queue size =1
,D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): stop scan
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3173): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479166.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479166.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479166.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758479166.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3232): registerClient() - UUID=3c8e63d9-a629-4b64-bdcd-d4287450e899
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=3c8e63d9-a629-4b64-bdcd-d4287450e899, clientIf=5
D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3232): message : 0
,D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): registerClient() - UUID=d0b0d529-8abf-4012-aaad-63a4621d00f2
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=d0b0d529-8abf-4012-aaad-63a4621d00f2, clientIf=6
,D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3232): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3232): handling starting scan
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479166.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479166.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479166.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479166.3173
I/io.jxcore.node.ConnectionHelper( 3173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED
I/jxcore-log( 3173): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 3173): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3173): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped
,I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
D/BtGatt.AdvertiseManager( 3232): message : 1
D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
,D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3232): Client app is not null!
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 3232): stopScan() - queue size =1
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...
D/BtGatt.ScanManager( 3232): stop scan
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
,I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
I/jxcore-log( 3173): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479259.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479259.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479259.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758479259.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3232): registerClient() - UUID=dac8eaae-afc4-4b49-b266-0395084e272c
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=dac8eaae-afc4-4b49-b266-0395084e272c, clientIf=5
,D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3232): message : 0
,D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0,
,D/BtGatt.GattService( 3232): registerClient() - UUID=1786c575-5e94-48d2-a2b2-83d79914de7d,
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=1786c575-5e94-48d2-a2b2-83d79914de7d, clientIf=6
,D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3232): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3232): handling starting scan
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479259.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479259.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479259.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI,
I/io.jxcore.node.ConnectionHelper( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479259.3173
,I/wpa_supplicant( 3244): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED
I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 3173): ok 59 Should be able to call startBroadcasting without error,
I/jxcore-log( 3173): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 3173): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 3232): message : 1
D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
,D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3232): Client app is not null!
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 3232): stopScan() - queue size =1
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 3232): stop scan
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3173): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479342.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479342.3173","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479342.3173
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758479342.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3232): registerClient() - UUID=d1ae7d70-3cc2-4771-882d-c66d6937eb57
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=d1ae7d70-3cc2-4771-882d-c66d6937eb57, clientIf=5
D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3232): message : 0
,D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): registerClient() - UUID=43c96f0c-0191-484c-8c2e-ecad500f103a
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=43c96f0c-0191-484c-8c2e-ecad500f103a, clientIf=6
D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3232): start scan with filters
,D/BtGatt.ScanManager( 3232): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0,
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479342.3173","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479342.3173","ra":"F8:CF:C5:D9:E5:61"},
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479342.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/wpa_supplicant( 3244): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479342.3173
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
I/jxcore-log( 3173): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 3173): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3173): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/BtGatt.AdvertiseManager( 3232): message : 1
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3232): Client app is not null!
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3232): stopScan() - queue size =1
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): stop scan
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED
,D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
I/jxcore-log( 3173): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479425.3173
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479425.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479425.3173
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758479425.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3232): registerClient() - UUID=fda97c03-d0c3-4342-a555-b6dcaa01e160
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=fda97c03-d0c3-4342-a555-b6dcaa01e160, clientIf=5
D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3232): message : 0
,D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0,
,D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): registerClient() - UUID=70e70b08-39e5-485c-b324-c775eaa23d08
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=70e70b08-39e5-485c-b324-c775eaa23d08, clientIf=6
,D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3232): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK,
D/BtGatt.ScanManager( 3232): handling starting scan
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479425.3173","ra":"F8:CF:C5:D9:E5:61"},
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479425.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479425.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
,I/wpa_supplicant( 3244): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479425.3173
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
I/jxcore-log( 3173): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 3173): 
I/io.jxcore.node.ConnectionHelper( 3173): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
,D/BtGatt.AdvertiseManager( 3232): message : 1
D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
,D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0,
D/BtGatt.GattService( 3232): Client app is not null!
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3232): stopScan() - queue size =1,
,D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED
,D/BtGatt.ScanManager( 3232): stop scan,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1,
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
I/jxcore-log( 3173): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown,
I/jxcore-log( 3173): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479856.3173
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479856.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479856.3173
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758479856.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3232): registerClient() - UUID=8f13e9f1-7be1-46f2-bc91-51bc1c1f8132
D/BtGatt.GattService( 3232): onClientRegistered() - UUID=8f13e9f1-7be1-46f2-bc91-51bc1c1f8132, clientIf=5
,D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3232): message : 0
,D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0
D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): registerClient() - UUID=3ca6beab-218b-46ca-9c52-cb939852de7f
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=3ca6beab-218b-46ca-9c52-cb939852de7f, clientIf=6
,D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3232): start scan with filters,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3232): handling starting scan
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479856.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479856.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758479856.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758479856.3173
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
,I/jxcore-log( 3173): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 66 Cannot call startBroadcasting twice
I/jxcore-log( 3173): 
,I/io.jxcore.node.ConnectionHelper( 3173): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
,D/BtGatt.AdvertiseManager( 3232): message : 1
,D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
,D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3232): Client app is not null!
,D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3232): stopScan() - queue size =1
,D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): stop scan
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log( 3173): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # ThaliEmitter throws on connection to bad peer
,I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758480419.3173
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758480419.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758480419.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758480419.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3232): registerClient() - UUID=bfa1b5b7-80a6-418f-9682-ccc8f1766338,
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=bfa1b5b7-80a6-418f-9682-ccc8f1766338, clientIf=5
,D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3232): message : 0
,D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0,
,D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0,
,D/BtGatt.GattService( 3232): registerClient() - UUID=5ac4b110-6d8f-411a-82b6-9b9625716bce
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=5ac4b110-6d8f-411a-82b6-9b9625716bce, clientIf=6
D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3232): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK,
D/BtGatt.ScanManager( 3232): handling starting scan
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758480419.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758480419.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758480419.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758480419.3173
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
I/jxcore-log( 3173): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3173): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3173): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 3173): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,E/io.jxcore.node.ConnectionHelper( 3173): connect: Invalid Bluetooth address: foobar
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
I/jxcore-log( 3173): ok 69 Should not connect to a bad peer
I/jxcore-log( 3173): 
,I/io.jxcore.node.ConnectionHelper( 3173): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped
D/BtGatt.AdvertiseManager( 3232): message : 1
,D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3232): Client app is not null!
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3232): stopScan() - queue size =1
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): stop scan
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
I/jxcore-log( 3173): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758480872.3173
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758480872.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3173): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): start: OK
I/io.jxcore.node.ConnectionHelper( 3173): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758480872.3173
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): createAdvertiseData: From: 1453758480872.3173 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3173): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3173): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0,
,D/BtGatt.GattService( 3232): registerClient() - UUID=6196aa47-4bcb-4682-87d9-e19bef733e07
,D/BtGatt.GattService( 3232): onClientRegistered() - UUID=6196aa47-4bcb-4682-87d9-e19bef733e07, clientIf=5
D/BluetoothLeAdvertiser( 3173): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3232): message : 0
D/BtGatt.AdvertiseManager( 3232): starting multi advertising
,D/BtGatt.GattService( 3232): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3232): onAdvertiseDataSet() - clientIf=5, status=0,
,D/BtGatt.GattService( 3232): registerClient() - UUID=b8c2b293-d231-4d93-b738-acdda2e4ea18
D/BtGatt.GattService( 3232): onClientRegistered() - UUID=b8c2b293-d231-4d93-b738-acdda2e4ea18, clientIf=6
,D/BluetoothLeScanner( 3173): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3232): start scan with filters
,D/BtGatt.ScanManager( 3232): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3173): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758480872.3173","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453758480872.3173","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453758480872.3173","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3232): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453758480872.3173
I/io.jxcore.node.ConnectionHelper( 3173): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3173): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
I/wpa_supplicant( 3244): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: STARTED
I/wpa_supplicant( 3244): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3173): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 3173): 
,D/io.jxcore.node.ConnectionHelper( 3173): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
,E/io.jxcore.node.ConnectionHelper( 3173): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
,D/io.jxcore.node.ConnectionHelper( 3173): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 3173): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
I/jxcore-log( 3173): ok 72 Disconnect should fail to a non-existant peer 
,I/jxcore-log( 3173): 
I/io.jxcore.node.ConnectionHelper( 3173): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3173): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3173): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3173): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3173): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 3232): message : 1
,D/BtGatt.AdvertiseManager( 3232): stop advertise for client 5
D/BtGatt.GattService( 3232): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3232): Client app is not null!
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=5,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3232): stopScan() - queue size =1
D/BtGatt.GattService( 3232): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3173): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3173): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3173): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3173): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3173): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3173): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3173): Service requests cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3173): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3173): onDiscoveryManagerStateChanged: NOT_STARTED
D/BtGatt.GattService( 3232): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3232): callback done for clientIf - 6 status - 0
,D/BtGatt.ScanManager( 3232): stop scan
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3232): configureRegularScanParams() - queue emtpy, scan stopped
I/jxcore-log( 3173): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
,I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 74 should be equal
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # setup
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
,I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
,I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 75 should not be equal,
,I/jxcore-log( 3173): ,
,I/jxcore-log( 3173): # setup,
,I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # verify that Thali-specific messages are filtered correctly,
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): # teardown
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): ok 76 irrelevant messages should be ignored
I/jxcore-log( 3173): 
I/jxcore-log( 3173): ok 77 relevant messages should not be ignored
I/jxcore-log( 3173): 
I/jxcore-log( 3173): ok 78 messages from this device should be ignored
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): Tests Complete
I/jxcore-log( 3173): 
,I/jxcore-log( 3173): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 3173): 
,I/chromium( 3173): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3173): Toggling radios to false
I/jxcore-log( 3173): 
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@45614 mBinding = false
,I/chromium( 3173): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothManagerService(  821): Message: 2
,D/BluetoothManagerService(  821): Sending off request.
,D/BluetoothAdapterState( 3232): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3232): Setting state to 13
,I/BluetoothAdapterState( 3232): Bluetooth adapter state changed: 12-> 13
,D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  821): Bluetooth State Change Intent: 12 -> 13
D/BluetoothAdapterProperties( 3232): onBluetoothDisable()
I/BluetoothAdapterState( 3232): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiService(  821): setWifiEnabled: false pid=3173, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothMapService( 3232): onReceive
D/BluetoothMapService( 3232): STATE_TURNING_OFF
,D/BluetoothMapService( 3232): MAP Service closeService in
D/BluetoothMapMasInstance( 3232): MAP Service shutdown
V/BluetoothMapMasInstance( 3232): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3232): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3232): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3232): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
,V/BluetoothMapMasInstance( 3232): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3232): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3232): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3232): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,I/BtOppRfcommListener( 3232): stopping Accept Thread
E/BtOppRfcommListener( 3232): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 3232): BluetoothSocket listen thread finished
,I/jxcore-log( 3173): Radios toggled
I/jxcore-log( 3173): 
I/jxcore-log( 3173): ****TEST TOOK:  ms ****
I/jxcore-log( 3173): 
I/jxcore-log( 3173): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3173): 
E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  821): do suspend true
D/CommandListener(  353): Clearing all IP addresses on wlan0
I/ActivityManager(  821): Start proc 4969:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
V/NativeCrypto( 1478): Read error: ssl=0xaec59c00: I/O error during system call, Connection timed out
D/BluetoothAdapterProperties( 3232): Scan Mode:20
D/BluetoothAdapterState( 3232): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 3232): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3173): Toggling radios to false
I/jxcore-log( 3173): 
V/NativeCrypto( 1478): SSL shutdown failed: ssl=0xaec59c00: I/O error during system call, Broken pipe
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@45614 mBinding = false
D/BluetoothManagerService(  821): Message: 2
D/BluetoothManagerService(  821): Sending off request.
W/bt-btif ( 3232): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3232): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3232): L2CAP - PSM: 0x0017 not found for deregistration
D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/BluetoothAdapterState( 3232): CURRENT_STATE=PENDING, MESSAGE = USER_TURN_ON, isTurningOn=false, isTurningOff=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
I/BluetoothAdapterState( 3232): CURRENT_STATE=PENDING: Alreadying turning off bluetooth... Ignoring USER_TURN_OFF...
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/WifiService(  821): setWifiEnabled: false pid=3173, uid=10265
,E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3173): Radios toggled
I/jxcore-log( 3173): 
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  821): scanCount==0 - aborting
,D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
D/WifiScanningService(  821): SCAN_AVAILABLE : 1
D/RttService(  821): SCAN_AVAILABLE : 1
D/WifiScanningService(  821): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState
D/RttService(  821): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/native  (  821): do suspend true
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  821): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524292
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  821): MasterInitialState.processMessage what=3
,E/ConnectivityService(  821): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,W/ContextImpl( 4969): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19dabf80:true
,I/ActivityManager(  821): Start proc 4995:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/PhoneInterfaceManager( 1274): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1274): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,I/wpa_supplicant( 3244): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3244): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/GpsLocationProvider(  821): No APN found to select.
,D/LocalBluetoothProfileManager( 4969): Adding local MAP profile
,D/BluetoothMap( 4969): Create BluetoothMap proxy object
,D/BluetoothManagerService(  821): Message: 30
,I/art     (  821): Explicit concurrent mark sweep GC freed 43941(2MB) AllocSpace objects, 6(378KB) LOS objects, 31% free, 34MB/50MB, paused 1.568ms total 60.632ms
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 4969): LocalBluetoothProfileManager construction complete
,D/PhoneInterfaceManager( 1274): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1274): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,D/DockEventReceiver( 4969): finishStartingService: stopping service
,D/BluetoothInputDevice( 4969): Proxy object connected
D/HidProfile( 4969): Bluetooth service connected
,E/GpsLocationProvider(  821): No APN found to select.
D/BluetoothPan( 4969): BluetoothPAN Proxy object connected
D/PanProfile( 4969): Bluetooth service connected
D/BluetoothMap( 4969): Proxy object connected
D/MapProfile( 4969): Bluetooth service connected
D/BluetoothMap( 4969): getConnectedDevices()
D/BluetoothMap( 4969): Bluetooth is Not enabled
,I/ActivityManager(  821): Killing 4540:android.process.acore/u0a5 (adj 15): empty #17
,D/bt_userial( 3232): RX termination
W/bt_userial( 3232): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3232): Leaving userial_read_thread()
W/bt-btif ( 3232): ag scb idx 1 not allocated
E/bt-btif ( 3232): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3232): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3232): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3232): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3232): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3232): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3232): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3232): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3232): hw_epilog_process
,I/bt_userial_vendor( 3232): device fd = 53 close
,D/AndroidRuntime( 4993): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4993): CheckJNI is OFF
,I/GKI_LINUX( 3232): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3232): GKI_exit_task 0 done,
I/GKI_LINUX( 3232): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3232): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/AndroidRuntime( 4993): Calling main entry com.android.commands.pm.Pm
,W/PackageSettings(  821): Skipping PackageSetting{1ebd37b1 com.example.hello/10273} due to missing metadata
,I/wpa_supplicant( 3244): wlan0: CTRL-EVENT-TERMINATING 
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
D/Tethering(  821): InitialState.processMessage what=4
,I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
,I/ActivityManager(  821): Killing 3173:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,D/HeadsetService( 3232): Received stop request...Stopping profile...
,E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3173
,W/ActivityManager(  821): Force removing ActivityRecord{34137a2a u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
,D/WifiService(  821): Client connection lost with reason: 4
,W/WindowManager(  821): Failed looking up window
W/WindowManager(  821): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@89735c4 does not exist
W/WindowManager(  821): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8539)
W/WindowManager(  821): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8530)
W/WindowManager(  821): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1142)
W/WindowManager(  821): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,I/WindowState(  821): WIN DEATH: null
,V/ActivityManager(  821): Display changed displayId=0
,I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/Tethering(  821): sendTetherStateChangedBroadcast 0, 0, 0
,D/HeadsetStateMachine( 3232): Exit Disconnected: -1
D/BluetoothHeadset( 1274): Proxy object disconnected
,D/BluetoothHeadset(  821): Proxy object disconnected
D/BluetoothHeadset( 1065): Proxy object disconnected
D/BluetoothHeadset(  821): Proxy object disconnected
D/BluetoothHeadset(  821): Proxy object disconnected
,D/A2dpService( 3232): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3232): Exit Disconnected: -1
D/BluetoothA2dp(  821): Proxy object disconnected
D/HidService( 3232): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 3232): Stopping profile services that were post enabled
D/HeadsetStateMachine( 3232): Unbinding service...
,D/BluetoothInputDevice( 4969): Proxy object disconnected
D/HidProfile( 4969): Bluetooth service disconnected
,I/Keyboard.Facilitator( 1215): resetDictionaries() : en_US
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
,D/TaskPersister(  821): removeObsoleteFile: deleting file=28_task.xml
,I/Keyboard.Facilitator.DecoderInitializer( 1215): run()
,W/BluetoothHeadsetServiceJni( 3232): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3232): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 3232): Received stop request...Stopping profile...
W/Settings( 1704): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/GKI_LINUX( 3232): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3232): GKI_exit_task 2 done
I/GKI_LINUX( 3232): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/PanService( 3232): Received stop request...Stopping profile...
D/BtGatt.DebugUtils( 3232): handleDebugAction() action=null
D/BluetoothPan( 4969): BluetoothPAN Proxy object disconnected
D/PanProfile( 4969): Bluetooth service disconnected
,D/BtGatt.GattService( 3232): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3232): stop()
D/BtGatt.AdvertiseManager( 3232): advertise clients cleared
,I/Decoder ( 1215): createOrResetDecoder
,I/art     ( 1065): Explicit concurrent mark sweep GC freed 60189(2MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 73MB/89MB, paused 1.602ms total 64.276ms
D/BluetoothA2dp( 1065): Proxy object disconnected
D/BluetoothInputDevice( 1065): Proxy object disconnected
D/BluetoothPan( 1065): BluetoothPAN Proxy object disconnected
,W/BluetoothHidServiceJni( 3232): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3232): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3232): Cleaning up Bluetooth GID callback object
,D/BluetoothMapService( 3232): Received stop request...Stopping profile...
D/BluetoothMapService( 3232): stop()
,D/BluetoothMapEmailAppObserver( 3232): deinitObservers()
D/BluetoothMapEmailAppObserver( 3232): removeReceiver()
,W/BluetoothHealthServiceJni( 3232): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3232): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3232): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3232): Cleaning up Bluetooth PAN callback object
,D/BluetoothMap( 1065): Proxy object disconnected
,D/BluetoothMap( 4969): Proxy object disconnected
D/MapProfile( 4969): Bluetooth service disconnected
,D/BluetoothMapService( 3232): MAP Service closeService in
D/BluetoothAdapterState( 3232): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3232): Setting state to 10
D/BluetoothMapService( 3232): cleanup()
I/BluetoothAdapterState( 3232): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 3232): MAP Service closeService in
I/BluetoothAdapterState( 3232): Entering OffState
D/BluetoothManagerService(  821): Message: 60
,D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  821): Broadcasting onBluetoothStateChange(false) to 17 receivers.
,D/BluetoothA2dp( 1065): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  821): onBluetoothStateChange: up=false
,D/BluetoothMap( 1065): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 4969): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 1065): onBluetoothStateChange: up=false
D/BluetoothHeadset(  821): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1274): onBluetoothStateChange: up=false
,D/BluetoothMap( 4969): onBluetoothStateChange: up=false
,I/ConfigService( 1478): onCreate
,D/BluetoothHeadset( 1065): onBluetoothStateChange: up=false
D/BluetoothPbap( 4969): onBluetoothStateChange: up=false
,D/BluetoothA2dpSink( 1065): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1065): 
E/BluetoothA2dpSink( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@8979d31
E/BluetoothA2dpSink( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1065): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothAvrcpController( 1065): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1065): 
E/BluetoothAvrcpController( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@1f590c16
E/BluetoothAvrcpController( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1065): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset(  821): onBluetoothStateChange: up=false
D/BluetoothA2dp(  821): onBluetoothStateChange: up=false
,D/BluetoothHeadsetClient( 1065): onBluetoothStateChange: up=false,
E/BluetoothHeadsetClient( 1065): 
E/BluetoothHeadsetClient( 1065): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@299d0997
E/BluetoothHeadsetClient( 1065): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1065): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1065): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
,E/BluetoothHeadsetClient( 1065): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1065): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1065): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothManagerService(  821): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  821): Broadcasting onBluetoothServiceDown() to 7 receivers.
,D/BluetoothManagerService(  821): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@45614 mBinding = false
,D/BluetoothManagerService(  821): Sending unbind request.
,D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1215): run()
,I/ActivityManager(  821): Start proc 5037:com.google.android.googlequicksearchbox:search/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService
,D/BluetoothManagerService(  821): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1065): 821475756: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1065): 821475756: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1065): 821475756: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3232): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3232): GKI_exit_task 1 done
,I/GKI_LINUX( 3232): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3232): cleanupNative: return from cleanup
,I/art     ( 3232): System.exit called, status: 0
I/AndroidRuntime( 3232): VM exiting with result code 0, cleanup skipped.
,W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3173 uid 10265
I/Keyboard.Facilitator( 1215): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1215): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1215): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1215): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1215): run()
I/StatsUtilsManager( 1215): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1215): shouldRecordStats() = Too Soon
,I/art     (  821): Explicit concurrent mark sweep GC freed 14272(1017KB) AllocSpace objects, 4(252KB) LOS objects, 32% free, 33MB/49MB, paused 2.416ms total 200.356ms
,I/art     ( 1316): Explicit concurrent mark sweep GC freed 11830(665KB) AllocSpace objects, 10(1188KB) LOS objects, 31% free, 35MB/51MB, paused 704us total 29.822ms
,I/ActivityManager(  821): Process com.android.bluetooth (pid 3232) has died
D/StrictMode( 4995): StrictMode policy violation; ~duration=518 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4995): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4995): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4995): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4995): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4995): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4995): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4995): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 4995): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 4995): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4995): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4995): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4995): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4995): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4995): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4995): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4995): StrictMode policy violation; ~duration=517 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4995): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4995): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4995): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4995): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4995): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4995): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4995): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4995): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4995): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4995): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4995): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4995): StrictMode policy violation; ~duration=514 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4995): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4995): 	at libcore.io.BlockGua,rdOs.open(BlockGuardOs.java:182)
D/StrictMode( 4995): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4995): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4995): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4995): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4995): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4995): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 4995): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4995): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4995): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4995): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4995): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4995): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4995): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4995): StrictMode policy violation; ~duration=504 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4995): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4995): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4995): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 4995): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4995): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4995): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4995): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4995): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4995): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4995): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4995): StrictMode policy violation; ~duration=496 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4995): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4995): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4995): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4995): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4995): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4995): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4995): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4995): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4995): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4995): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4995): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4995): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4995): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4995): StrictMode policy violation; ~duration=215 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 4995): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4995): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 4995): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 4995): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 4995): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 4995): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 4995): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 4995): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 4995): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 4995): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 4995): # via Binder call with stack:
D/StrictMode( 4995): android.os.StrictMode$LogStackTrace
D/StrictMode( 4995): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 4995): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 4995): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 4995): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 4995): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 4995): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 4995): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 4995): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 4995): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4995): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4995): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4995): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4995): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4995): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4995): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4995): StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4995): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4995): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4995): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4995): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4995): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4995): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4995): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 4995): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4995): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4995): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4995): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4995): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4995): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4995): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4995): StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4995): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4995): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4995): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4995): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4995): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4995): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4995): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4995): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4995): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4995): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4995): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4995): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4995): StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4995): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4995): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4995): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4995): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4995): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4995): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4995): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4995): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4995): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4995): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4995): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4995): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4995): StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4995): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4995): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4995): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4995): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4995): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4995): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4995): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 4995): 	at com.google.p.j.a(PG:121)
D/StrictMode( 4995): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 4995): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 4995): 	at com.google.p.e.a(PG:170)
D/StrictMode( 4995): 	at com.google.p.e.b(PG:21)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4995): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4995): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4995): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4995): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4995): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4995): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4995): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4995): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 4995): Application name is not set. Call Builder#setApplicationName.
I/art     ( 4993): System.exit called, status: 0
I/AndroidRuntime( 4993): VM exiting with result code 0.
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d01f659:true
,I/ActivityManager(  821): Killing 4647:com.google.android.youtube/u0a86 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1478): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/Launcher.Workspace( 1316): 11683562 - stripEmptyScreens()
,D/Launcher.Workspace( 1316): 11683562 - stripEmptyScreens()
E/SQLiteLog( 1316): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,I/ActivityManager(  821): Start proc 5067:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,I/ActivityManager(  821): Start proc 5088:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,W/ResourcesManager( 5067): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AndroidRuntime( 5037): Shutting down VM
,I/ActivityManager(  821): Start proc 5116:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,E/SharedPreferencesImpl( 5037): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,--------- beginning of crash
E/AndroidRuntime( 5037): FATAL EXCEPTION: main
E/AndroidRuntime( 5037): Process: com.google.android.googlequicksearchbox:search, PID: 5037
E/AndroidRuntime( 5037): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 5037): 	at com.google.android.search.core.bh$2.onFailure(SearchController.java:381)
E/AndroidRuntime( 5037): 	at com.google.android.apps.gsa.shared.util.c.a.r$1.run(TaskRunnerImpl.java:329)
E/AndroidRuntime( 5037): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5037): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5037): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5037): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 5037): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5037): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5037): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 5037): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 5037): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 5037): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime( 5037): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime( 5037): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime( 5037): 	at com.google.android.apps.gsa.shared.util.c.d$1.call(LazyListenableFuture.java:46)
E/AndroidRuntime( 5037): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 5037): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 5037): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 5037): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 5037): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 5037): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 5037): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime( 5037): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime( 5037): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 5037): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 5037): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 5037): 	... 5 more
E/AndroidRuntime( 5037): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 5037): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime( 5037): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime( 5037): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime( 5037): 	... 9 more
E/AndroidRuntime( 5037): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 5037): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime( 5037): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime( 5037): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime( 5037): 	... 11 more
,E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
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
,D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  821): Validating map...
,I/OpenGLRenderer(  821): Initialized EGL, version 1.4
,D/OpenGLRenderer(  821): Enabling debug mode 0
,D/GFEEDBACK_SendErrorReportOperation( 1733): Error doing instant send: java.io.IOException: failed to create reports directory
,E/GFEEDBACK_SendErrorReportOperation( 1733): Error saving report: java.io.IOException: failed to create reports directory
,I/Babel_SMS( 5067): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5067): MmsConfig.loadMmsSettings
I/Babel_SMS( 5067): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 5067): MmsConfig.loadFromDatabase
,E/SQLiteDatabase( 5067): Failed to open database '/data/data/com.google.android.talk/databases/apn.db'.
E/SQLiteDatabase( 5067): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5067): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5067): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5067): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5067): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5067): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5067): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5067): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5067): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5067): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5067): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5067): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5067): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5067): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5067): 	at alg.<init>(SourceFile:161)
E/SQLiteDatabase( 5067): 	at alj.a(SourceFile:1015)
E/SQLiteDatabase( 5067): 	at gen_binder.root.RootModule$Generated.a(SourceFile:662)
E/SQLiteDatabase( 5067): 	at gvf.d(SourceFile:408)
E/SQLiteDatabase( 5067): 	at gvf.b(SourceFile:238)
E/SQLiteDatabase( 5067): 	at gvf.a(SourceFile:204)
E/SQLiteDatabase( 5067): 	at gvf.a(SourceFile:485)
E/SQLiteDatabase( 5067): 	at alg.a(SourceFile:167)
E/SQLiteDatabase( 5067): 	at dnm.c(SourceFile:606)
E/SQLiteDatabase( 5067): 	at dnm.b(SourceFile:570)
E/SQLiteDatabase( 5067): 	at dnn.run(SourceFile:221)
E/AndroidRuntime( 5067): FATAL EXCEPTION: Thread-541
E/AndroidRuntime( 5067): Process: com.google.android.talk, PID: 5067
E/AndroidRuntime( 5067): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5067): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5067): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5067): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5067): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5067): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5067): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5067): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 5067): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 5067): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5067): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 5067): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5067): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5067): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5067): 	at alg.<init>(SourceFile:161)
E/AndroidRuntime( 5067): 	at alj.a(SourceFile:1015)
E/AndroidRuntime( 5067): 	at gen_binder.root.RootModule$Generated.,a(SourceFile:662)
E/AndroidRuntime( 5067): 	at gvf.d(SourceFile:408)
E/AndroidRuntime( 5067): 	at gvf.b(SourceFile:238)
E/AndroidRuntime( 5067): 	at gvf.a(SourceFile:204)
E/AndroidRuntime( 5067): 	at gvf.a(SourceFile:485)
E/AndroidRuntime( 5067): 	at alg.a(SourceFile:167)
E/AndroidRuntime( 5067): 	at dnm.c(SourceFile:606)
E/AndroidRuntime( 5067): 	at dnm.b(SourceFile:570)
E/AndroidRuntime( 5067): 	at dnn.run(SourceFile:221)
,E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
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
,W/Settings( 5067): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5067): startup - clean
,I/Babel   ( 5067): deleted: false for 0
,I/Babel_telephony( 5067): TeleModule.launchCompleted
,W/Telecom (  821): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 5067): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 5067): BAM#gBA: invalid account id: -1
W/Babel   ( 5067): BAM#gBA: invalid account id: -1
I/Babel_telephony( 5067): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,W/Telecom (  821): TelecomServiceImpl: null is not visible for the calling user

```
