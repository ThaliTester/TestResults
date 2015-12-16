#### Test 50650278dbf8a2a_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2692): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2692): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2692): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3156): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3156): CheckJNI is OFF
D/AndroidRuntime( 3156): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{1472f95c token=Token{14377bcf ActivityRecord{f99842e u0 com.test.thalitest/.MainActivity t26}}} to stack=1 task=26 at 0
V/WindowManager(  822): Adding window Window{a0de1e1 u0 Starting com.test.thalitest} at 2 of 7 (after Window{39d9b048 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3156): Shutting down VM
I/MicrophoneInputStream( 1504): mic_close com.google.android.apps.gsa.speech.audio.u@1695fa94
I/HotwordDetector( 1504): Closing mic
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/ActivityManager(  822): Start proc 3170:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
I/HotwordRecognitionRnr( 1504): Hotword detection finished
I/HotwordRecognitionRnr( 1504): Stopping hotword detection.
I/ActivityManager(  822): Killing 2651:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1698157843
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  822): Killing 2784:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  874): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  874): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  874): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/WebViewFactory( 3170): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3170): Time to load native libraries: 2 ms (timestamps 6075-6077)
I/LibraryLoader( 3170): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3170): Binding Chromium to main looper Looper (main, tid 1) {3529927f}
,I/LibraryLoader( 3170): Expected native library version number "",actual native library version number ""
I/chromium( 3170): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3170): Initializing chromium process, singleProcess=true
,W/art     ( 3170): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3170): ApplicationContext is null in ApplicationStatus
,W/chromium( 3170): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3170): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3170): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3170): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3170): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18420551:true
,D/BluetoothAdapter( 3170): 547698488: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3170): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3170): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3170): CordovaWebView is running on device made by: motorola
,W/art     ( 3170): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3170): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  822): Explicit concurrent mark sweep GC freed 17803(852KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.506ms total 78.876ms
,D/OpenGLRenderer( 3170): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3170): Validating map...
,V/WindowManager(  822): Adding window Window{c3de4c1 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{a0de1e1 u0 Starting com.test.thalitest})
,W/chromium( 3170): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3170): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3170): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +943ms
,I/Keyboard.Facilitator( 1213): onFinishInput()
,W/BindingManager( 3170): Cannot call determinedVisibility() - never saw a connection for the pid: 3170
,D/JsMessageQueue( 3170): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3170): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576258688
,D/JX-Cordova( 3170): jxcore cordova android initializing
,I/kickstart(  874): STATUS: Received file 'm9kefs1'
I/kickstart(  874): STATUS: 950272 bytes transferred in 0.993807 seconds
I/kickstart(  874): STATUS: Successfully downloaded files from target 
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  874): STATUS: Sahara protocol completed
,W/jxcore-log( 3170): Initializing JXcore engine
W/jxcore-log( 3170): JXcore engine is ready
,W/jxcore-log( 3170): Starting JXcore engine
,W/.test.thalitest( 3170): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11442]" dev="sockfs" ino=11442 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3170): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3170): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13016]" dev="sockfs" ino=13016 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3170): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19433]" dev="sockfs" ino=19433 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3170): Platform android
W/jxcore-log( 3170): 
,W/jxcore-log( 3170): Process ARCH arm,
,W/jxcore-log( 3170): 
,I/jxcore-log( 3170): JXcore Cordova bridge is ready!
I/jxcore-log( 3170): 
,W/jxcore-log( 3170): JXcore engine is started
I/Choreographer( 3170): Skipped 133 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3170): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3170): Toggling radios to true
I/jxcore-log( 3170): 
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,D/BluetoothManagerService(  822): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  822): Message: 1
D/BluetoothManagerService(  822): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  822): setWifiEnabled: true pid=3170, uid=10265,
E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  822): New client listening to asynchronous messages
,I/jxcore-log( 3170): Radios toggled
I/jxcore-log( 3170): 
,D/SoftapController(  353): Softap fwReload - Ok
,D/CommandListener(  353): Setting iface cfg
D/CommandListener(  353): Trying to bring down wlan0
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,E/WifiMonitor(  822): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  822): Start proc 3229:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3170): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3170): 
I/jxcore-log( 3170): Perf Test app loaded loaded
I/jxcore-log( 3170): 
I/jxcore-log( 3170): check test folder
I/jxcore-log( 3170): 
I/jxcore-log( 3170): found test : ./testFindPeers.js
I/jxcore-log( 3170): 
,I/jxcore-log( 3170): found test : ./testSendData.js
I/jxcore-log( 3170): 
,W/ResourcesManager( 3229): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/WifiMonitor(  822): startMonitoring(wlan0) with mConnected = false
,I/Choreographer( 3170): Skipped 72 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3170): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  822): Start proc 3247:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/wpa_supplicant( 3246): Successfully initialized wpa_supplicant
,D/AdapterServiceConfig( 3229): Adding HeadsetService
D/AdapterServiceConfig( 3229): Adding A2dpService
D/AdapterServiceConfig( 3229): Adding HidService
D/AdapterServiceConfig( 3229): Adding HealthService
D/AdapterServiceConfig( 3229): Adding PanService
D/AdapterServiceConfig( 3229): Adding GattService
D/AdapterServiceConfig( 3229): Adding BluetoothMapService
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cc81c4a:true
,D/BluetoothAdapterState( 3229): make
I/BluetoothAdapterState( 3229): Entering OffState
,I/bluedroid( 3229): init
,I/bte_conf( 3229): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3229): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3229): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3229): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3229): get_profile_interface socket
I/bluedroid( 3229): get_profile_interface map_client
I/GKI_LINUX( 3229): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3229): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  822): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  822): Message: 40
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 3229): Name is: Nexus 6
D/BluetoothManagerService(  822): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  822): Stored Bluetooth name: Nexus 6
I/bluedroid( 3229): config_hci_snoop_log
,D/BluetoothManagerService(  822): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  822): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3229): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3229): Setting state to 11
I/BluetoothAdapterState( 3229): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  822): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3229): make
,I/BluetoothBondStateMachine( 3229): StableState(): Entering Off State
,I/BluetoothAdapterState( 3229): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a90424c
,D/HeadsetService( 3229): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3229): classInitNative: succeeds
,D/HeadsetStateMachine( 3229): make
,D/HeadsetStateMachine( 3229): max_hf_connections = 1
I/bluedroid( 3229): get_profile_interface handsfree
,D/HeadsetStateMachine( 3229): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a90424c
,D/BluetoothA2dp(  822): Proxy object connected
D/BluetoothA2dp( 1064): Proxy object connected
,D/A2dpService( 3229): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3229): classInitNative: succeeds
I/bluedroid( 3229): get_profile_interface avrcp
I/wpa_supplicant( 3246): rfkill: Cannot open RFKILL control device
,E/RemoteController( 3229): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3229): classInitNative: succeeds
D/A2dpStateMachine( 3229): make
,I/bluedroid( 3229): get_profile_interface a2dp
I/GKI_LINUX( 3229): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3229): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3229): classInitNative: succeeds
,D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a90424c
,D/BluetoothInputDevice( 1064): Proxy object connected
D/HidService( 3229): Received start request. Starting profile...
I/bluedroid( 3229): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3229): classInitNative: succeeds
,D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a90424c
,D/HealthService( 3229): Received start request. Starting profile...
,I/bluedroid( 3229): get_profile_interface health
,I/BluetoothPanServiceJni( 3229): classInitNative(L105): succeeds
,D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a90424c
,D/BluetoothPan( 1064): BluetoothPAN Proxy object connected
D/PanService( 3229): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3229): initializeNative(L110): pan
I/bluedroid( 3229): get_profile_interface pan
,I/BtGatt.JNI( 3229): classInitNative(L873): classInitNative: Success!
,D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a90424c
,D/BtGatt.DebugUtils( 3229): handleDebugAction() action=null
D/BtGatt.GattService( 3229): Received start request. Starting profile...
D/BtGatt.GattService( 3229): start()
I/bluedroid( 3229): get_profile_interface gatt
,D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a90424c
D/BtGatt.AdvertiseManager( 3229): advertise manager created
,I/ActivityManager(  822): Start proc 3288:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  822): Killing 2817:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a90424c
,D/BluetoothMapService( 3229): Received start request. Starting profile...
D/BluetoothMapService( 3229): start()
,D/BluetoothMap( 1064): Proxy object connected
,D/BluetoothMapEmailSettingsLoader( 3229): Found 0 applications
D/BluetoothMapEmailAppObserver( 3229): createReceiver()
D/BluetoothMapEmailAppObserver( 3229): initObservers()
D/BluetoothMapEmailAppObserver( 3229): getEnabledAccountItems()
,D/HeadsetStateMachine( 3229): Proxy object connected
D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3229): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3229): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3229): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3229): enable
I/GKI_LINUX( 3229): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3229): btu_task pending for preload complete event
I/bt_hci_bdroid( 3229): init
,I/bt_vendor( 3229): init
I/bt_vnd_conf( 3229): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3229): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3229): userial_init
,I/bt_userial_vendor( 3229): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3229): device fd = 53 open
,D/bt_userial( 3229): Entering userial_read_thread()
,I/bt_hwcfg( 3229): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3229): Chipset BCM4354A2
D/bt_hwcfg( 3229): Target name = [BCM4354A2]
I/bt_hwcfg( 3229): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/ActivityManager(  822): Start proc 3315:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  822): Killing 2750:com.google.android.gm/u0a78 (adj 15): empty #17
,D/Tethering(  822): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3246): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3246): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  822): Loading config and enabling all networks 
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3f016202}
,E/WifiConfigStore(  822): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  822): Setting external_sim to 1
,W/Settings( 2587): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  822): Setting OUI to 92-68-C3
I/WifiNative-HAL(  822): startHal
,D/wifi    (  822): setting scan oui 0xaeed6640
D/WifiHAL (  822): Sending mac address OUI
,E/WifiStateMachine(  822): cancelDelayedScan -> 1
,I/ActivityManager(  822): Killing 2309:com.google.android.calendar/u0a37 (adj 15): empty #17
W/CommandListener(  353): Failed to retrieve HW addr for p2p0 (No such device)
,D/CommandListener(  353): Setting iface cfg
,E/WifiP2pService(  822): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  822): startMonitoring(p2p0) with mConnected = true
,I/bt_hwcfg( 3229): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3229): Settlement delay -- 100 ms
I/bt_hwcfg( 3229): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3229): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg( 3229): Setting local bd addr to F8:CF:C5:D9:E5:61
,D/WifiScanningService(  822): SCAN_AVAILABLE : 3
D/RttService(  822): SCAN_AVAILABLE : 3
,D/RttService(  822): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  822): DefaultState got{ when=-3ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiNative-HAL(  822): startHal
,D/wifi    (  822): getting scan capabilities on interface[0] = 0xaeed6640,
D/WifiHAL (  822): Creating message to get scan capablities; iface = 5
D/WifiHAL (  822): In GetCapabilities::handleResponse
,D/WifiHAL (  822): Id = 0, subcmd = 0, len = 28, expected len = 32
,D/WifiScanningService(  822): StartedState
,I/bt_hwcfg( 3229): vendor lib fwcfg completed
,I/bt-btu  ( 3229): btu_task received preload complete event
,I/        ( 3229): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 3229): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3229): BTE_InitTraceLevels -- TRC_RFCOMM,
,I/        ( 3229): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3229): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3229): BTE_InitTraceLevels -- TRC_A2D
,I/        ( 3229): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3229): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3229): BTE_InitTraceLevels -- TRC_GAP
,I/        ( 3229): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3229): BTE_InitTraceLevels -- TRC_SDP
,I/        ( 3229): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3229): BTE_InitTraceLevels -- TRC_SMP
,I/        ( 3229): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3229): BTE_InitTraceLevels -- TRC_BTIF
,D/WifiNative-HAL(  822): p2pGetDeviceAddress
,I/wpa_supplicant( 3246): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  822): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62,
,I/ActivityManager(  822): Start proc 3334:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,E/native  (  822): do suspend false
,E/bt-btm  ( 3229): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2dc8085 
E/bt-btm  ( 3229): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2dc8085 
,D/BluetoothAdapterProperties( 3229): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3229): Calling BTA_HhEnable,
E/bt-btif ( 3229): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 3229): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothAdapterProperties( 3229): Name is: Nexus 6
D/BluetoothManagerService(  822): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  822): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3229): Scan Mode:20
D/BluetoothAdapterProperties( 3229): Discoverable Timeout:120,
W/bt-btm  ( 3229): Stopping oneshot timer
,D/bte_conf( 3229): Device ID record 1 : primary,
,D/bte_conf( 3229):   vendorId            = 000f
,D/bte_conf( 3229):   vendorIdSource      = 0001
D/bte_conf( 3229):   product             = 1200
D/bte_conf( 3229):   version             = 1436
,D/bte_conf( 3229):   clientExecutableURL = 
D/bte_conf( 3229):   serviceDescription  = 
D/bte_conf( 3229):   documentationURL    = 
,D/bte_conf( 3229): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 3229): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan,
D/BluetoothAdapterState( 3229): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false,
D/BluetoothAdapterProperties( 3229): ScanMode =  20
,D/BluetoothAdapterProperties( 3229): State =  11
D/BluetoothAdapterProperties( 3229): Scan Mode:21,
D/BluetoothAdapterProperties( 3229): Setting state to 12
,D/BluetoothAdapterProperties( 3229): Discoverable Timeout:120,
I/BluetoothAdapterState( 3229): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,I/BluetoothAdapterState( 3229): Entering On State,
D/BluetoothManagerService(  822): Broadcasting onBluetoothStateChange(true) to 13 receivers.
D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
D/BluetoothManagerService(  822): Creating new ProfileServiceConnections object for profile: 1
D/BluetoothAvrcpController( 1064): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1064): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothHeadsetClient( 1064): onBluetoothStateChange: up=true
,E/BluetoothHeadsetClient( 1064): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothPan( 1064): onBluetoothStateChange(on) call bindService
E/bt_h4   ( 3229): vendor lib postload completed
,D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
D/BluetoothMap( 1064): onBluetoothStateChange: up=true
,D/BluetoothA2dpSink( 1064): onBluetoothStateChange: up=true
,E/BluetoothA2dpSink( 1064): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothInputDevice( 1064): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 1064): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  822): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1064): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1258): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  822): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  822): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,W/bt-btm  ( 3229): Stopping oneshot timer
D/BluetoothMapService( 3229): onReceive
D/BluetoothMapService( 3229): STATE_ON
D/BluetoothMapMasInstance( 3229): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 3229): MAS initSocket()
W/bt-btm  ( 3229): Stopping oneshot timer
D/BluetoothManagerService(  822): Message: 40
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
W/bt-btm  ( 3229): Stopping oneshot timer
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/bt-btm  ( 3229): Stopping oneshot timer
,W/BluetoothAdapter( 3229): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3229): Accepting socket connection...
,D/BluetoothManagerService(  822): Message: 400
D/BluetoothHeadset(  822): Proxy object connected
,D/BluetoothManagerService(  822): Message: 400
D/BluetoothHeadset(  822): Proxy object connected
,D/BluetoothManagerService(  822): Message: 400,
D/BluetoothHeadset(  822): Proxy object connected
D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset( 1064): Proxy object connected,
,D/BluetoothManagerService(  822): Message: 400,
,D/BluetoothHeadset( 1258): Proxy object connected,
,D/StrictMode( 3334): StrictMode policy violation; ~duration=354 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
D/StrictMode( 3334): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3334): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3334): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3334): 	at java.io.File.exists(File.java:363)
,D/StrictMode( 3334): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3334): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3334): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
,D/StrictMode( 3334): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3334): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3334): ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3334): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3334): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3334): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3334): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3334): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3334): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3334): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3334): StrictMode policy violation; ~duration=353 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3334): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3334): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3334): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3334): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3334): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3334): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3334): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3334): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3334): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3334): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3334): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3334): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3334): StrictMode policy violation; ~duration=350 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3334): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3334): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3334): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3334): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3334): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3334): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3334): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3334): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3334): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3334): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3334): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3334): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3334): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3334): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3334): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3334): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3334): StrictMode policy violation; ~duration=344 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3334): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3334): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3334): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3334): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3334): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3334): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3334): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3334): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3334): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3334): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3334): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3334): StrictMode policy violation; ~duration=283 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3334): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3334): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3334): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3334): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3334): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3334): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3334): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3334): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3334): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3334): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3334): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3334): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3334): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3334): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3334): StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3334): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3334): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3334): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3334): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3334): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3334): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3334): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3334): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3334): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3334): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3334): # via Binder call with stack:
D/StrictMode( 3334): android.os.StrictMode$LogStackTrace
D/StrictMode( 3334): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3334): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3334): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3334): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3334): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3334): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3334): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3334): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3334): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3334): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3334): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3334): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3334): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3334): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3334): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3334): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3334): StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3334): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3334): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3334): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3334): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3334): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3334): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3334): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3334): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3334): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3334): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3334): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3334): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3334): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3334): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3334): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3334): StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3334): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3334): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3334): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3334): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3334): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3334): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3334): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3334): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3334): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3334): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3334): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3334): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3334): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3334): StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3334): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3334): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3334): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3334): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3334): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3334): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3334): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3334): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3334): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3334): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3334): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3334): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3334): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3334): StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3334): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3334): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3334): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3334): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3334): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3334): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3334): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3334): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3334): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3334): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3334): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3334): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3334): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3334): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3334): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3334): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3334): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3334): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3334): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3334): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Native Method),
D/StrictMode( 3334): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3334): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 3334): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10f38b9:true,
,I/ActivityManager(  822): Killing 2853:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1483): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  822): Message: 20
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13245f1:true
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3229): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1483): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LocalBluetoothProfileManager( 3315): Adding local A2DP profile
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3229): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3315): Adding local HEADSET profile
,I/BtOppRfcommListener( 3229): Accept thread started.
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/LocalBluetoothProfileManager( 3315): Adding local MAP profile
,D/BluetoothMap( 3315): Create BluetoothMap proxy object
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/LocalBluetoothProfileManager( 3315): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3315): finishStartingService: stopping service
,D/BluetoothA2dp( 3315): Proxy object connected
,D/A2dpProfile( 3315): Bluetooth service connected
,D/BluetoothInputDevice( 3315): Proxy object connected
,D/HidProfile( 3315): Bluetooth service connected
,D/BluetoothPan( 3315): BluetoothPAN Proxy object connected
,D/PanProfile( 3315): Bluetooth service connected
,D/BluetoothMap( 3315): Proxy object connected
D/MapProfile( 3315): Bluetooth service connected
,D/BluetoothMap( 3315): getConnectedDevices()
,D/BluetoothPbap( 3315): Proxy object connected
,D/PbapServerProfile( 3315): Bluetooth service connected
,I/PowerManagerService(  822): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  822): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset( 3315): Proxy object connected
,D/HeadsetProfile( 3315): Bluetooth service connected
,D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (235 us)
,I/wpa_supplicant( 3246): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  822): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  822):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  822):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiConfigStore(  822): writeKnownNetworkHistory write linked 1,
E/WifiStateMachine(  822): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  822): writeKnownNetworkHistory write linked 1
E/WifiStateMachine(  822): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,E/WifiStateMachine(  822): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  822): will read network variables netId=0
,I/wpa_supplicant( 3246): wlan0: Trying to associate with SSID 'NG7005g',
,I/DisplayManagerService(  822): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS},
D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0,
V/ActivityManager(  822): Display changed displayId=0
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  822): Excessive delay in setPowerMode(): 272ms
,I/DreamManagerService(  822): Entering dreamland.
,I/PowerManagerService(  822): Dozing...,
I/DreamController(  822): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  822): cancelDelayedScan -> 4
,E/native  (  822): do suspend false
,I/wpa_supplicant( 3246): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3246): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3246): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,I/Keyboard.Facilitator( 1213): onFinishInput()
,D/ConnectivityService(  822): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  822): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  822): Start Dhcp Watchdog 1
,E/WifiStateMachine(  822):  WifiLinkLayerStats: 
E/WifiStateMachine(  822):  my bss beacon rx: 1
E/WifiStateMachine(  822):  RSSI mgmt: -48
E/WifiStateMachine(  822):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  822):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  822):  on_time : 74 tx_time=59 rx_time=344 scan_time=0
,E/WifiStateMachine(  822): cancelDelayedScan -> 6
,D/ConnectivityService(  822): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off,
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/native  (  822): do suspend false
,E/WifiStateMachine(  822): scanCount==0 - aborting,
,I/dhcpcd  ( 3383): version 5.5.6 starting
,I/dhcpcd  ( 3383): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3383): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/jxcore-log( 3170): BLE advertisement not supported: Bluetooth LE advertising is not supported,
I/jxcore-log( 3170): ,
,I/dhcpcd  ( 3383): wlan0: leased 192.168.1.122 for 86400 seconds
,E/native  (  822): do suspend true
,D/ConnectivityService(  822): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  822): Adding iface wlan0 to network 100
,E/WifiStateMachine(  822): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  822): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  822): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  822): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100,
D/ConnectivityService(  822): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 6 -> obsolete
D/ConnectivityService(  822): Setting Dns servers for network 100 to [/192.168.1.1],
,D/ConnectivityService(  822): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  822): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100],
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  822):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  822): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  822): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  822): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  822): MasterInitialState.processMessage what=3
,V/BackupManagerService(  822): Scheduling immediate backup pass
,D/PhoneInterfaceManager( 1258): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1258): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  822): getDataEnabled: retVal=false
,D/AlarmManagerService(  822): Setting time of day to sec=1450226442
,W/AlarmManagerService(  822): Unable to set rtc to 1450226442: Invalid argument
I/ActivityManager(  822): Start proc 3421:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,V/BackupManagerService(  822): Running a backup pass
,V/BackupManagerService(  822): clearing pending backups
,D/NetworkChangeNotifierAutoDetect( 1504): Network connectivity changed, type is: 2
,V/PerformBackupTask(  822): Beginning backup of 14 targets
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 390us total 26.455ms
,D/PerformBackupTask(  822): invokeAgentForBackup on @pm@
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 340us total 20.369ms
,E/GpsLocationProvider(  822): No APN found to select.
,V/BackupServiceBinder(  822): doBackup() invoked
,I/PMBA    (  822): Previous metadata 1570415 mismatch vs 1743759 - rewriting
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 226us total 11.556ms
,I/BackupRestoreController(  822): Getting widget state for user: 0
,I/art     (  822): Explicit concurrent mark sweep GC freed 50607(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.464ms total 69.632ms
,I/GoogleURLConnFactory( 1483): Using platform SSLCertificateSocketFactory
,W/GmsBackupTransport( 1702): Unknown package in backup request: @pm@
V/GmsBackupTransport( 1702): starting performBackup for @pm@
,V/GmsBackupTransport( 1702): performBackup done for @pm@
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GpsLocationProvider(  822): NTP server returned: 1450226442004 (Wed Dec 16 01:40:42 GMT+01:00 2015) reference: 166164 certainty: 7 system time offset: -261
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicStore( 3421): Database version: 120
,W/GLSActivity( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1483): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1483): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1483): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1702): Error sending final backup to server: 
W/GmsBackupTransport( 1702): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1702): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1702): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1702): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1702): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1702): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1702): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1702): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1702): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1702): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1702): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1702): 	... 1 more
,D/BackupManagerService(  822): Now staging backup of com.google.android.talk
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 17586(1012KB) AllocSpace objects, 2(32KB) LOS objects, 37% free, 26MB/42MB, paused 2.179ms total 32.614ms
,D/BackupManagerService(  822): Now staging backup of com.google.android.dialer
,E/Auth.Api.Credentials( 1729): [CredentialSyncAdapter] Unknown sync event.
D/BackupManagerService(  822): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  822): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  822): Now staging backup of com.google.android.gm
,D/BackupManagerService(  822): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  822): Now staging backup of com.android.nfc
,D/BackupManagerService(  822): Now staging backup of com.google.android.apps.genie.geniewidget
,W/DriveInitializer( 1729): Background init thread started
,D/BackupManagerService(  822): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  822): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  822): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  822): Now staging backup of com.android.vending
,W/DriveInitializer( 1729): Awaiting to be initialized
,D/BackupManagerService(  822): Now staging backup of android
,W/ResourcesManager( 3421): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3421): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BackupManagerService(  822): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1702): Next backup will happen in 43199863 millis.
,I/BackupManagerService(  822): Backup pass finished.
,W/DriveInitializer( 1729): Background init thread ended
,V/JNIHelp ( 3421): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3421): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3421): GMSCore installation verified
,I/ConfigStore( 3421): Config Database version: 1
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  822): Start proc 3478:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,E/HttpOperation( 2941): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at blb.a(PG:3937)
E/HttpOperation( 2941): 	at czp.a(PG:18188)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 12 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 14 more
,V/GoogleAuthProtoRequest( 3247): [321] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2941): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at hec.a(PG:42)
E/HttpOperation( 2941): 	at hee.a(PG:102)
E/HttpOperation( 2941): 	at czr.a(PG:65)
E/HttpOperation( 2941): 	at kka.a(PG:108)
E/HttpOperation( 2941): 	at czp.a(PG:19176)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 15 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 17 more
E/ExperimentLoader( 2941): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): 	at jdm.a(PG:82)
E/ExperimentLoader( 2941): 	at jcs.o(PG:406)
E/ExperimentLoader( 2941): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2941): 	at jcs.i(PG:143)
E/ExperimentLoader( 2941): 	at hec.a(PG:42)
E/ExperimentLoader( 2941): 	at hee.a(PG:102)
E/ExperimentLoader( 2941): 	at czr.a(PG:65)
E/ExperimentLoader( 2941): 	at kka.a(PG:108)
E/ExperimentLoader( 2941): 	at czp.a(PG:19176)
E/ExperimentLoader( 2941): 	at czp.a(PG:9081)
E/ExperimentLoader( 2941): 	at czq.run(PG:1686)
E/ExperimentLoader( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2941): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2941): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2941): 	at jdm.a(PG:77)
E/ExperimentLoader( 2941): 	... 15 more
E/ExperimentLoader( 2941): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2941): 	at fal.a(PG:38)
E/ExperimentLoader( 2941): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2941): 	... 17 more
,I/MediaRouter( 3421): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3421): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3421): type=WIFI subType= reason=null isConnected=true
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3247): [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3247): [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3247): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3247): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3247): 	at com.a.a.k.run(SourceFile:110)
,I/NetworkMonitor( 3421): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  822): Start proc 3502:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/GHttpClientFactory( 3421): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3421): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 3502): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3502): simOperator:  IMSI: null
D/SprintDMReceiver( 3502): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1729): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 35903, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 2161:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/SystemUpdateService( 1729): onCreate
,I/CheckinService( 1729): Checking schedule, now: 1450226443045 next: 1450223863821
I/CheckinService( 1729): active receiver: enabled
,I/CheckinService( 1729): Preparing to send checkin request
I/EventLogService( 1729): Accumulating logs since 1450225212572
,D/SystemUpdateService( 1729): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1483): Vacuum at: now=1450226443082 tag=VacuumService
,I/SystemUpdateService( 1729): active receiver: enabled
,I/EventLogService( 1729): Opted in for usage reporting
,I/SystemUpdateService( 1729): showing system update notification
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1729): retry (wakeup: false) in 3599967 ms
,I/art     (  822): Explicit concurrent mark sweep GC freed 28358(1337KB) AllocSpace objects, 5(121KB) LOS objects, 32% free, 33MB/49MB, paused 1.384ms total 59.178ms
D/SystemUpdateService( 1729): onDestroy
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 23383(1286KB) AllocSpace objects, 3(165KB) LOS objects, 37% free, 26MB/42MB, paused 1.018ms total 24.841ms
,I/iu.SyncManager( 1729): SYNC; picasa accounts
,D/NetworkLogImpl( 1729): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1729): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1729): num queued entries: 0
,I/iu.UploadsManager( 1729): num updated entries: 0
I/iu.SyncManager( 1729): NEXT; no task
,W/GAV2    ( 3478): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ChimeraCfgMgr( 1729): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1729): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/BooksApp( 3478): Created application version: 3.6.8 (30608)
,V/KeepSync( 3288): Connecting to GoogleApiClient
W/EventLogAggregator( 1729): Unknown tag: snet_gcore
W/EventLogAggregator( 1729): Unknown tag: snet_launch_service
,I/ActivityManager(  822): Start proc 3542:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/CheckinRequestBuilder( 1729): Checkin reason type: 12 attempt count: 1
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiService(  822): New client listening to asynchronous messages
,E/ActivityThread( 1729): Failed to find provider info for com.google.android.wearable.settings
,I/Babel   ( 2587): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1729): [AccountUtils] Account not ready
W/Kids    ( 1729): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1729): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1729): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1729): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1729): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1729): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1729): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1729): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1729): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1729): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1729): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1729): 	at java.lang.Thread.run(Thread.java:818)
W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,W/BaseAppContext( 1729): Using Auth Proxy for data requests.
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1729): Handling authorization failure
E/ClientConnectionOperation( 1729): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1729): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1729): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1729): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1729): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1729): 	... 7 more
,V/KeepSync( 3288): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3288): (284) automatic index on blob_node(is_deleted)
,I/BooksSync( 3478): Starting books sync for 61035162, extras: ade
,E/SQLiteLog( 3288): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3288): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1729): Explicit concurrent mark sweep GC freed 15493(1222KB) AllocSpace objects, 16(256KB) LOS objects, 35% free, 29MB/45MB, paused 1.143ms total 37.052ms
,I/GAv4    ( 3542): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3542):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3542):   adb logcat -s GAv4
,I/ConfigFetchService( 1729): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,W/GAv4    ( 3542): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ConfigFetchService( 1729): running network task: configservice_periodic
E/WakeLock( 1729): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1729): launchTask
,D/GCM     ( 1483): Connected
,W/GAv4    ( 3542): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  822): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,I/ConfigService( 1483): onCreate
,I/GoogleURLConnFactory( 1483): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  822): reportInetCondition: type=1 ok, revalidate
,D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/GCM     ( 1483): Message class com.google.f.a.a.p
,D/ConnectivityService(  822): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  822): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,I/ConfigFetchService( 1729): service connected
W/Uploader( 1483): No account for auth token provided
,D/ConfigFetchService( 1729): ConfigApi connection successful.
,W/GAv4    ( 3542): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksConfig( 3478): GmsCore Version = 7.8.99 (2134222-430)
,W/CheckinRequestBuilder( 1729): awaiting user notification for token
,I/ActivityManager(  822): Start proc 3599:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,E/KeepSync( 3288): IOException
E/KeepSync( 3288): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3288): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3288): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3288): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3288): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3288): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3288): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3288): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3288): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3288): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3288): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3288): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3288): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3288): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3288): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3288): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3288): 	... 10 more
,W/KeepSync( 3288): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 35906, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/ResourcesManager( 3599): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3599): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/Uploader( 1483): No account for auth token provided
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MultiDex( 3599): VM with version 2.1.0 has multidex support
I/MultiDex( 3599): install
I/MultiDex( 3599): VM has multidex support, MultiDex support library is disabled.
,I/WebViewFactory( 3542): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,V/JNIHelp ( 3599): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/LibraryLoader( 3542): Time to load native libraries: 1 ms (timestamps 7813-7814)
,I/LibraryLoader( 3542): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3542): Binding Chromium to main looper Looper (main, tid 1) {2355d0e0}
,I/LibraryLoader( 3542): Expected native library version number "",actual native library version number ""
I/chromium( 3542): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BrowserStartupController( 3542): Initializing chromium process, singleProcess=true
W/art     ( 3542): Attempt to remove local handle scope entry from IRT, ignoring
E/BooksAccountManager( 3478): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/SysUtils( 3542): ApplicationContext is null in ApplicationStatus
E/BooksSync( 3478): Soft error
E/BooksSync( 3478): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3478): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3478): Sync error
E/BooksSync( 3478): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3478): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3478): Finished books sync
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ProviderInstaller( 3599): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 3542): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3542): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3542): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3542): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/art     (  822): Explicit concurrent mark sweep GC freed 20567(865KB) AllocSpace objects, 2(126KB) LOS objects, 31% free, 34MB/50MB, paused 1.453ms total 103.206ms
,W/AudioManagerAndroid( 3542): Requires BLUETOOTH permission
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 35906, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  822): Killing 1372:android.process.acore/u0a5 (adj 15): empty #17
,D/WVCdm   (  357): Instantiating CDM.
,I/WVCdm   (  357): CdmEngine::OpenSession
I/WVCdm   (  357): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  357): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  357): Service_Initialize: starts!
D/QSEECOMAPI: (  357): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  357): App is not loaded in QSEE
,I/NSApplication( 3542): Starting up...
,W/Uploader( 1483): No account for auth token provided
,I/ActivityManager(  822): Start proc 3643:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  822): Killing 3053:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/GoogleURLConnFactory( 3599): Using platform SSLCertificateSocketFactory
,W/Uploader( 1483): No account for auth token provided
,D/QSEECOMAPI: (  357): Loaded image: APP id = 3
,D/DrmWidevineDash(  357): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3c81000
E/DrmWidevineDash(  357): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3c81000
,D/DrmLibTime(  315): got the req here! ret=0
D/DrmLibTime(  315): command id, time_cmd_id = 770
D/DrmLibTime(  315): time_getutcsec starts!
D/DrmLibTime(  315): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  315): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  315): QSEE Time Listener: seconds: 1450226444
D/DrmLibTime(  315): QSEE Time Listener: nano seconds: 55640155
D/DrmLibTime(  315): time_getutcsec returns 0, sec = 1450226444; nsec = 55640155
D/DrmLibTime(  315): time_getutcsec finished! 
D/DrmLibTime(  315): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  315): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: starts!
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 41260(2MB) AllocSpace objects, 5(302KB) LOS objects, 36% free, 27MB/43MB, paused 1.566ms total 34.019ms
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  357): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  357): OEMCrypto_OpenSession: starts! SID=0xbef8d520
,D/DrmWidevineDash(  357): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_GetRandom: starts! randomData=0xb58762a0, dataLength=8
,D/DrmWidevineDash(  357): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb405e000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  357): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  357): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  357): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  357): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d0f440, idLength=0xb3580710
,D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: wv_app_version = 21
,D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: ends! returns 0x0,
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
,D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  357): PrepareKeyRequest: nonce=2340508302
D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb408c200
D/DrmWidevineDash(  357): message_length=1599, signature=0xb4079500, signature_length=3008890612
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
,E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	,at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
,E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  357): CdmEngine::CloseSession
,D/DrmWidevineDash(  357): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  357): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  357): L3 Terminate.
D/DrmWidevineDash(  357): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  357): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  357): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  357): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  357): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  357): OEMCrypto_Terminate: ends! returns 0
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  822): Start proc 3668:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  822): Killing 3073:com.android.musicfx/u0a18 (adj 15): empty #17
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  357): CdmEngine::OpenSession
I/WVCdm   (  357): Level3 Library Dec 11 2014 16:13:16
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/WVCdm   (  357): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  357): Service_Initialize: starts!
D/QSEECOMAPI: (  357): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  357): App is not loaded in QSEE
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1483): No account for auth token provided
,D/QSEECOMAPI: (  357): Loaded image: APP id = 3
,D/DrmWidevineDash(  357): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  357): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3c81000
E/DrmWidevineDash(  357): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3c81000
,D/DrmLibTime(  315): got the req here! ret=0,
D/DrmLibTime(  315): command id, time_cmd_id = 770
D/DrmLibTime(  315): time_getutcsec starts!
D/DrmLibTime(  315): QSEE Time Listener: time_getutcsec
,D/DrmLibTime(  315): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  315): QSEE Time Listener: seconds: 1450226444
,D/DrmLibTime(  315): QSEE Time Listener: nano seconds: 863578488
D/DrmLibTime(  315): time_getutcsec returns 0, sec = 1450226444; nsec = 863578488
D/DrmLibTime(  315): time_getutcsec finished! 
,D/DrmLibTime(  315): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  315): before calling ioctl to read the next time_cmd
D/DrmWidevineDash(  357): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: ends! returns 0,
D/WVCdm   (  357): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: starts! SID=0xbef8d520
,D/DrmWidevineDash(  357): OEMCrypto_OpenSession SID = 1,
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_GetRandom: starts! randomData=0xb4c4e7a8, dataLength=8
,D/DrmWidevineDash(  357): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb405da00, wrapped_rsa_key_length=1280
,W/Uploader( 1483):  no longer exists, so no auth token.,
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  357): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  357): BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
W/WVCdm   (  357): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  357): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d0f480, idLength=0xb3f01710
,D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  357): PrepareKeyRequest: nonce=810407814
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4d25600
,D/DrmWidevineDash(  357): message_length=1634, signature=0xb4c528c0, signature_length=3018856180
,W/Uploader( 1483): No account for auth token provided
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  357): CdmEngine::CloseSession
D/DrmWidevineDash(  357): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  357): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  357): L3 Terminate.
,D/DrmWidevineDash(  357): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  357): Service_Uninitialize: starts!
D/QSEECOMAPI: (  357): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  357): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  357): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_Terminate: ends! returns 0
,W/Uploader( 1483): No account for auth token provided
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dex2oat ( 3688): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/dex2oat ( 3688): dex2oat took 41.537ms (threads: 4) arena alloc=95KB java alloc=18KB native alloc=1118KB free=6MB
,I/Adreno  ( 3599): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/Uploader( 1483): No account for auth token provided
,I/Adreno  ( 3599): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/Uploader( 1483): No account for auth token provided
,I/ActivityManager(  822): Start proc 3695:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,I/ActivityManager(  822): Killing 1756:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,E/SQLiteLog( 3695): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  822): Start proc 3715:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/ResourcesManager( 3715): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/EventLogService( 1729): Opted in for usage reporting
,I/CalendarProvider2( 3715): Created com.android.providers.calendar.CalendarAlarmManager@f20079e(com.android.providers.calendar.CalendarProvider2@3529927f)
,I/ActivityManager(  822): Killing 3099:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,I/ActivityManager(  822): Start proc 3741:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3695): PlayLogger.onLoggerConnected
,D/TimeService( 3741): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450226446052
,D/        ( 3741): TimeServiceNative: User Time to be set is 1450226446052
D/QC-time-services( 3741): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3741): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3741): Lib:time_genoff_operation: pargs->ts_val = 1450226446052
D/QC-time-services( 3741): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  372): Daemon: Connection accepted:time_genoff
D/QC-time-services(  372): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450226446052
D/QC-time-services(  372): Daemon:genoff_opr: Base = 2, val = 1450226446052, operation = 0
D/QC-time-services(  372): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/2/70 20:53:35
D/QC-time-services(  372): Daemon:Value read from RTC seconds = 10529615000
D/QC-time-services(  372): Daemon:new time 1450226446052 
D/QC-time-services(  372): Daemon: delta 1439696831052 genoff 1439696831052 
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696831052 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  372): Updating the TOD offset
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696831052 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  372): Daemon:Update to modem bit set
D/QC-time-services(  372): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  372): Daemon: Base = 2, Value being sent to MODEM = 1134261646052
E/QC-time-services( 3741): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  822): Killing 3005:com.android.defcontainer/u0a7 (adj 15): empty #17
,E/QC-time-services(  372): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  372): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  822): Start proc 3762:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/GAv4    ( 3762): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3762):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3762):   adb logcat -s GAv4
,W/GAv4    ( 3762): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3762): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3762): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinTask( 1729): Sending checkin request (10029 bytes)
,I/ActivityManager(  822): Killing 2692:com.android.vending/u0a19 (adj 15): empty #17
,D/GCM     ( 1483): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1483): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1729): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  822): Start proc 3787:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,D/LocationInitializer( 1729): Restart initialization of location
,I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 472us total 25.138ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 335us total 18.641ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 328us total 17.598ms
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3f016202}
,W/ResourcesManager( 3787): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3787): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3787): VM with version 2.1.0 has multidex support
I/MultiDex( 3787): install
I/MultiDex( 3787): VM has multidex support, MultiDex support library is disabled.
,I/art     (  822): Explicit concurrent mark sweep GC freed 17559(802KB) AllocSpace objects, 5(457KB) LOS objects, 31% free, 34MB/50MB, paused 1.327ms total 56.061ms
,I/CheckinResponseProcessor( 1729): From server: 3 gservices updates and 0 deletes
,V/JNIHelp ( 3787): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2587): UserRecoverableAuthException.
E/Babel   ( 2587): eei: BadAuthentication
E/Babel   ( 2587): 	at eeg.a(Unknown Source)
E/Babel   ( 2587): 	at eeg.a(Unknown Source)
E/Babel   ( 2587): 	at eeg.a(Unknown Source)
E/Babel   ( 2587): 	at g.a(Unknown Source)
E/Babel   ( 2587): 	at cae.a(SourceFile:3089)
E/Babel   ( 2587): 	at cae.a(SourceFile:1131)
E/Babel   ( 2587): 	at cws.a(SourceFile:4333)
E/Babel   ( 2587): 	at cws.a(SourceFile:1419)
E/Babel   ( 2587): 	at crl.a(SourceFile:492)
E/Babel   ( 2587): 	at crl.a(SourceFile:1468)
E/Babel   ( 2587): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2587): 	at cas.b(SourceFile:106)
E/Babel   ( 2587): 	at cap.d(SourceFile:335)
E/Babel   ( 2587): 	at caq.run(SourceFile:81)
,E/Babel   ( 2587): Error getting auth token
E/Babel   ( 2587): dvm
E/Babel   ( 2587): 	at g.a(Unknown Source)
E/Babel   ( 2587): 	at cae.a(SourceFile:3089)
E/Babel   ( 2587): 	at cae.a(SourceFile:1131)
E/Babel   ( 2587): 	at cws.a(SourceFile:4333)
E/Babel   ( 2587): 	at cws.a(SourceFile:1419)
E/Babel   ( 2587): 	at crl.a(SourceFile:492)
E/Babel   ( 2587): 	at crl.a(SourceFile:1468)
E/Babel   ( 2587): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2587): 	at cas.b(SourceFile:106)
E/Babel   ( 2587): 	at cap.d(SourceFile:335)
E/Babel   ( 2587): 	at caq.run(SourceFile:81)
,E/Babel   ( 2587): Account registration failed 1-Redacted-21
,E/Babel   ( 2587): cyp: null -- null
E/Babel   ( 2587): 	at cae.a(SourceFile:3121)
E/Babel   ( 2587): 	at cae.a(SourceFile:1131)
E/Babel   ( 2587): 	at cws.a(SourceFile:4333)
E/Babel   ( 2587): 	at cws.a(SourceFile:1419)
E/Babel   ( 2587): 	at crl.a(SourceFile:492)
E/Babel   ( 2587): 	at crl.a(SourceFile:1468)
E/Babel   ( 2587): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2587): 	at cas.b(SourceFile:106)
E/Babel   ( 2587): 	at cap.d(SourceFile:335)
E/Babel   ( 2587): 	at caq.run(SourceFile:81)
,I/art     ( 2587): Note: end time exceeds epoch: 
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 00:40:46 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450226447007], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450226446986]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Validated
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): ValidatedState{ when=-3s566ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): DefaultState{ when=-3s566ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=-3s558ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=-3s557ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  822): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  822): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  822): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  822): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,I/ProviderInstaller( 3787): Installed default security provider GmsCore_OpenSSL
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 00:40:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450226447026], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450226447010]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  822): Validated
,D/ConnectivityService(  822): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  822): Validated NetworkAgentInfo [WIFI () - 100]
,D/GCM     ( 1483): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1483): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/Herrevad( 1729): NQAS connected
,D/WearableService( 3787): callingUid 10011, callindPid: 3787
,V/GmsCoreStatsServiceLauncher( 1729): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 3715): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3715): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,E/MDM     ( 1702): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1729): Restart initialization of location
,E/MDM     ( 1702): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ResourcesManager( 1483): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2587): Unexpected exception while authenticating.
,E/Babel   ( 2587): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2587): 	at eeg.b(Unknown Source)
E/Babel   ( 2587): 	at eeg.b(Unknown Source)
E/Babel   ( 2587): 	at g.a(Unknown Source)
E/Babel   ( 2587): 	at cae.b(SourceFile:1146)
E/Babel   ( 2587): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2587): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2587): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2587): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 3715): (284) automatic index on view_events(_id)
,I/CertBlacklister(  822): Certificate blacklist changed, updating...
,I/CertBlacklister(  822): Certificate blacklist updated
,I/GservicesProvider( 1483): main difference update completed
,I/ActivityManager(  822): Start proc 3828:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,I/CheckinRequestBuilder( 1729): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1729): Failed to find provider info for com.google.android.wearable.settings
,W/Telecom (  822): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 2587): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 2587): BAM#gBA: invalid account id: -1
W/Babel   ( 2587): BAM#gBA: invalid account id: -1
I/Babel_telephony( 2587): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 50139(2MB) AllocSpace objects, 14(1472KB) LOS objects, 36% free, 27MB/43MB, paused 1.441ms total 47.565ms
,I/ActivityManager(  822): Start proc 3860:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,E/UpdateRequestReceiver( 3860): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3860): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3860): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3860): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 6 -> obsolete
,I/ActivityManager(  822): Killing 3315:com.android.settings/1000 (adj 15): empty #17
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 9010(399KB) AllocSpace objects, 14(1543KB) LOS objects, 37% free, 26MB/42MB, paused 1.821ms total 29.855ms
,I/art     ( 1729): Explicit concurrent mark sweep GC freed 32205(2MB) AllocSpace objects, 10(159KB) LOS objects, 35% free, 29MB/45MB, paused 1.100ms total 33.309ms
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  822): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 6 -> obsolete
,I/SystemUpdateService( 1729): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1729): onCreate
,D/SystemUpdateService( 1729): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/SystemEventReceiver( 1729): Received GSERVICES_CHANGED broadcast
D/GCM     ( 1483): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/OcrUtils( 1729): Updating ocr activity enabled=false
,I/GCoreUlr( 1702): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1702): DispatchingService.onCreate()
,I/SystemUpdateService( 1729): active receiver: enabled
,I/SystemUpdateService( 1729): showing system update notification
,I/art     ( 1702): Explicit concurrent mark sweep GC freed 12905(726KB) AllocSpace objects, 4(64KB) LOS objects, 37% free, 26MB/42MB, paused 1.044ms total 26.025ms
,E/DataBuffer( 1702): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ec58eea)
,I/ValidateNoPeople(  822): skipping global notification
,V/SystemUpdateService( 1729): retry (wakeup: false) in 3599891 ms
,I/GCoreUlr( 1702): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 19493(976KB) AllocSpace objects, 6(661KB) LOS objects, 32% free, 33MB/49MB, paused 1.640ms total 61.252ms
,W/CheckinRequestBuilder( 1729): awaiting user notification for token
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 6529(311KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 934us total 30.095ms
,I/art     ( 1729): Explicit concurrent mark sweep GC freed 8139(470KB) AllocSpace objects, 4(64KB) LOS objects, 35% free, 29MB/45MB, paused 1.195ms total 33.343ms
,I/GCoreUlr( 1702): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/SystemUpdateService( 1729): onDestroy
,I/EventLogService( 1729): Opted in for usage reporting
,I/GCoreUlr( 1702): Unbound from all location providers
,I/GservicesUpdateTask( 1504): Updating Gservices keys
,I/GCoreUlr( 1702): DispatchingService.onDestroy()
,I/GCoreUlr( 1702): Unbound from all location providers
,I/CheckinTask( 1729): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1729): Checking schedule, now: 1450226448069 next: 1450267591052
I/CheckinService( 1729): active receiver: disabled
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 1729): Checking schedule, now: 1450226448110 next: 1450267591052
I/CheckinService( 1729): active receiver: disabled
,I/MusicLeanback( 3421): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3421): Stop autocaching.
,D/ChimeraCfgMgr( 1729): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1483): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 1729): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/GmsUtils( 3421): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3421): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 6672(316KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 26MB/42MB, paused 804us total 20.008ms
,I/GAV2    ( 3478): Thread[GAThread,5,main]: No campaign data found.
,W/Kids    ( 1729): [AccountUtils] Account not ready
W/Kids    ( 1729): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1729): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1729): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1729): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1729): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1729): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1729): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1729): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1729): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1729): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1729): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1729): 	at java.lang.Thread.run(Thread.java:818)
,E/WifiStateMachine(  822): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
,I/ActivityManager(  822): Start proc 3926:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/Finsky  ( 3926): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3926): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  822): Start proc 3963:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,I/ActivityManager(  822): Killing 3334:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,W/Settings( 3926): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3926): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/GAV2    ( 3695): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 3926): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3926): [1] 2.run: Finished loading 1 libraries.
,W/ResourcesManager( 3963): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3963): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 3926): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3926): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 3963): VM with version 2.1.0 has multidex support
I/MultiDex( 3963): install
I/MultiDex( 3963): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3963): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3963): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1483): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1483): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1729): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1702): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1729): Restart initialization of location
,V/Finsky  ( 3926): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3926): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3926): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3926): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ActivityManager(  822): Killing 3542:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3502:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #18
,D/Finsky  ( 3926): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 19018(978KB) AllocSpace objects, 9(238KB) LOS objects, 32% free, 33MB/49MB, paused 1.467ms total 69.939ms
,E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,W/Finsky  ( 3926): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3926): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 3926): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 3926): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3926): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3926): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,I/ActivityManager(  822): Killing 3643:com.android.chrome/u0a40 (adj 15): empty #17
,D/DeviceConnectionService( 1702): client connected with version: 7571000
,I/ActivityManager(  822): Killing 3478:com.google.android.apps.books/u0a34 (adj 15): empty #18
,V/ConfigFetchTask( 1729): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UKQNiK_8z-KXIQWrjqMm6uY_62drjjJY1ix4AVtVonaXACb1fuxg85RuFRAKGcweiCzHDLrqjEZoi5k5YYE1_eLLAC42-zvCJQN5hW86uAt_BkoV-QwGdzxm7_iqOc4ACIMfqNhEQ7COWMyeAan3bpr3sFIf28xJVz2ZOWR08vn7rWi6zgBWY30kuk4wnA4_THlCjwapE2UZiyZWrnIy7kMLjLV6eKhHJSpjR3Jal1P7BROFo
,I/GoogleURLConnFactory( 1729): Using platform SSLCertificateSocketFactory
,I/ConfigFetchTask( 1729): updating config table for com.google.android.gms
,I/ConfigFetchService( 1729): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1729): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1729): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1729): fetch service done; releasing wakelock
,I/ConfigFetchService( 1729): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1729): stopping self
,I/ActivityManager(  822): Killing 2941:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3288:com.google.android.keep/u0a79 (adj 15): empty #17
,W/PackageSettings(  822): Skipping PackageSetting{2e7f812b com.example.hello/10273} due to missing metadata
,I/InputReader(  822): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  822): Start proc 4006:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,V/GmsNetworkLocationProvi( 1702): DISABLE
,D/BackupManagerService(  822): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  822): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  822): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/GmsNetworkLocationProvi( 1702): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/BackupManagerService(  822): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  822): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@5cbe99a
,V/GmsNetworkLocationProvi( 1702): ENABLE
,V/GmsNetworkLocationProvi( 1702): SET-REQUEST
,V/GmsNetworkLocationProvi( 1702): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/BackupManagerService(  822): Scheduling immediate backup pass
,V/BackupManagerService(  822): Running a backup pass
,V/BackupManagerService(  822): clearing pending backups
V/PerformBackupTask(  822): Beginning backup of 14 targets
,D/PerformBackupTask(  822): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  822): doBackup() invoked
,I/PMBA    (  822): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/PackageBroadcastService( 1729): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 1504): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Launcher( 1277): Deferring update until onResume
W/Launcher( 1277): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3c476c76 new=com.google.android.velvet.VelvetApplication@3c476c76
,I/PackageBroadcastService( 1729): Null package name or gms related package.  Ignoreing.
,I/BackupRestoreController(  822): Getting widget state for user: 0
I/Icing   ( 1729): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 1504): UpdateCorporaTask done [took 34 ms] updated apps [took 34 ms] 
,I/ContactLocale( 4006): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  822): Start proc 4032:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,W/ResourcesManager( 4032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 19898(1056KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.219ms total 21.812ms
,W/GmsBackupTransport( 1702): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1702): starting performBackup for @pm@
,V/GmsBackupTransport( 1702): performBackup done for @pm@
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1483): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1483): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1483): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1702): Error sending final backup to server: 
W/GmsBackupTransport( 1702): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1702): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1702): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1702): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1702): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1702): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1702): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1702): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1702): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1702): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1702): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1702): 	... 1 more
,D/BackupManagerService(  822): Now staging backup of com.google.android.talk
,D/BackupManagerService(  822): Now staging backup of com.google.android.dialer
D/BackupManagerService(  822): Now staging backup of com.android.providers.settings
D/BackupManagerService(  822): Now staging backup of com.android.sharedstoragebackup
D/BackupManagerService(  822): Now staging backup of com.google.android.gm
,D/BackupManagerService(  822): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  822): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  822): Now staging backup of com.android.nfc
D/BackupManagerService(  822): Now staging backup of com.google.android.marvin.talkback
D/BackupManagerService(  822): Now staging backup of com.android.vending
D/BackupManagerService(  822): Now staging backup of com.google.android.calendar
D/BackupManagerService(  822): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  822): Now staging backup of android
,D/BackupManagerService(  822): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1702): Next backup will happen in 43199970 millis.
,I/BackupManagerService(  822): Backup pass finished.
,I/ConfigService( 1483): onDestroy
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/ActivityManager(  822): Killing 3741:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3762:com.google.android.deskclock/u0a44 (adj 15): empty #17
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  822): Explicit concurrent mark sweep GC freed 29142(1724KB) AllocSpace objects, 4(252KB) LOS objects, 32% free, 33MB/49MB, paused 2.109ms total 83.916ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3926): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3926): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3926): [1] 5.onFinished: Scheduling replication attempt 5.
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3247): [322] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3247): [322] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3247): [322] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3247): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3247): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3247): 	,at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3926): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3926): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3926): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1213): run()
,I/Keyboard.Facilitator( 1213): flushDynamicLanguageModels()
,I/ConfigService( 1483): onCreate
,I/ActivityManager(  822): Start proc 4065:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/ActivityManager(  822): Start proc 4082:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,W/GAV2    ( 4065): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4065): Created application version: 3.6.8 (30608)
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 14766(791KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.156ms total 37.315ms
,I/BooksSync( 4065): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4082): Connecting to GoogleApiClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksConfig( 4065): GmsCore Version = 7.8.99 (2134222-430)
,E/ClientConnectionOperation( 1729): Handling authorization failure
E/ClientConnectionOperation( 1729): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1729): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1729): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1729): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1729): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1729): 	... 7 more
,V/KeepSync( 4082): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4065): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4065): Soft error
E/BooksSync( 4065): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4065): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4065): Sync error
E/BooksSync( 4065): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4065): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4065): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 198326, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 4082): IOException
E/KeepSync( 4082): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4082): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4082): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4082): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4082): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4082): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4082): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4082): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4082): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4082): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4082): 	... 10 more
,W/KeepSync( 4082): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 198580, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at blb.a(PG:3937)
E/HttpOperation( 4032): 	at czp.a(PG:18188)
E/HttpOperation( 4032): 	at czp.a(PG:9087)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 12 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): 	... 14 more
,I/ActivityManager(  822): Killing 3715:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/ActivityManager(  822): Killing 3695:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at blb.a(PG:3937)
E/HttpOperation( 4032): 	at czp.a(PG:18188)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 12 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): 	... 14 more
,I/art     (  822): Explicit concurrent mark sweep GC freed 28642(1269KB) AllocSpace objects, 4(158KB) LOS objects, 32% free, 33MB/49MB, paused 1.879ms total 93.669ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at hec.a(PG:42)
E/HttpOperation( 4032): 	at hee.a(PG:102)
E/HttpOperation( 4032): 	at czr.a(PG:65)
E/HttpOperation( 4032): 	at kka.a(PG:108)
E/HttpOperation( 4032): 	at czp.a(PG:19176)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 15 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): 	... 17 more
,E/ExperimentLoader( 4032): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4032): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4032): 	at jdm.a(PG:82)
E/ExperimentLoader( 4032): 	at jcs.o(PG:406)
E/ExperimentLoader( 4032): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4032): 	at jcs.i(PG:143)
E/ExperimentLoader( 4032): 	at hec.a(PG:42)
E/ExperimentLoader( 4032): 	at hee.a(PG:102)
E/ExperimentLoader( 4032): 	at czr.a(PG:65)
E/ExperimentLoader( 4032): 	at kka.a(PG:108)
E/ExperimentLoader( 4032): 	at czp.a(PG:19176)
E/ExperimentLoader( 4032): 	at czp.a(PG:9081)
E/ExperimentLoader( 4032): 	at czq.run(PG:1686)
E/ExperimentLoader( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4032): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4032): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4032): 	at jdm.a(PG:77)
E/ExperimentLoader( 4032): 	... 15 more
E/ExperimentLoader( 4032): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4032): 	at fal.a(PG:38)
E/ExperimentLoader( 4032): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4032): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 166992, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1483): onDestroy
,I/GAV2    ( 4065): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 3926): [400] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3926): [400] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 4032): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
,E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143),
E/HttpOperation( 4032): 	at blb.a(PG:3937)
E/HttpOperation( 4032): 	at czp.a(PG:18188)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	,at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77),
E/HttpOperation( 4032): 	... 12 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): ,	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at hec.a(PG:42)
E/HttpOperation( 4032): 	at hee.a(PG:102)
E/HttpOperation( 4032): 	at czr.a(PG:65)
E/HttpOperation( 4032): 	at kka.a(PG:108)
E/HttpOperation( 4032): 	at czp.a(PG:19176)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 15 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): 	... 17 more
E/ExperimentLoader( 4032): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4032): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4032): 	at jdm.a(PG:82)
E/ExperimentLoader( 4032): 	at jcs.o(PG:406)
E/ExperimentLoader( 4032): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4032): 	at jcs.i(PG:143)
E/ExperimentLoader( 4032): 	at hec.a(PG:42)
E/ExperimentLoader( 4032): 	at hee.a(PG:102)
E/ExperimentLoader( 4032): 	at czr.a(PG:65)
E/ExperimentLoader( 4032): 	at kka.a(PG:108)
E/ExperimentLoader( 4032): 	at czp.a(PG:19176)
E/ExperimentLoader( 4032): 	at czp.a(PG:9081)
E/ExperimentLoader( 4032): 	at czq.run(PG:1686)
E/ExperimentLoader( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4032): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4032): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4032): 	at jdm.a(PG:77)
E/ExperimentLoader( 4032): 	... 15 more
E/ExperimentLoader( 4032): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4032): 	at fal.a(PG:38)
E/ExperimentLoader( 4032): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4032): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 261350, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3247): [323] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3247): [323] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3247): [323] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3247): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3247): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3247): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/BooksSync( 4065): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4065): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 4082): Connecting to GoogleApiClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1729): Handling authorization failure
E/ClientConnectionOperation( 1729): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1729): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1729): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1729): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1729): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1729): 	... 7 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
V/KeepSync( 4082): GoogleApiClient failed to connect with error code: 4
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4065): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4065): Soft error
E/BooksSync( 4065): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4065): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4065): Sync error
E/BooksSync( 4065): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4065): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4065): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 287840, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 40028(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 27MB/43MB, paused 1.345ms total 40.773ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4082): IOException
E/KeepSync( 4082): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4082): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4082): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4082): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4082): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4082): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4082): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4082): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4082): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4082): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4082): 	... 10 more
W/KeepSync( 4082): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 288737, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at blb.a(PG:3937)
E/HttpOperation( 4032): 	at czp.a(PG:18188)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4032): ,	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 12 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): 	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 4032): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at hec.a(PG:42)
E/HttpOperation( 4032): 	at hee.a(PG:102)
E/HttpOperation( 4032): 	at czr.a(PG:65)
E/HttpOperation( 4032): 	at kka.a(PG:108)
E/HttpOperation( 4032): 	at czp.a(PG:19176)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 15 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): 	... 17 more
,E/ExperimentLoader( 4032): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 4032): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4032): ,	at jdm.a(PG:82),
E/ExperimentLoader( 4032): 	at jcs.o(PG:406)
E/ExperimentLoader( 4032): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4032): 	at jcs.i(PG:143)
E/ExperimentLoader( 4032): 	at hec.a(PG:42)
E/ExperimentLoader( 4032): 	at hee.a(PG:102)
E/ExperimentLoader( 4032): 	at czr.a(PG:65),
E/ExperimentLoader( 4032): 	at kka.a(PG:108)
E/ExperimentLoader( 4032): 	at czp.a(PG:19176)
E/ExperimentLoader( 4032): 	at czp.a(PG:9081)
E/ExperimentLoader( 4032): 	at czq.run(PG:1686)
E/ExperimentLoader( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4032): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4032): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4032): ,	at jdj.a(PG:1125)
E/ExperimentLoader( 4032): 	at jdm.a(PG:77)
E/ExperimentLoader( 4032): 	... 15 more
E/ExperimentLoader( 4032): Caused by: faj: BadAuthentication
,E/ExperimentLoader( 4032): 	at fal.a(PG:38)
E/ExperimentLoader( 4032): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4032): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 353118, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/jxcore-log( 3170): Connected to the server!
I/jxcore-log( 3170): 
,I/chromium( 3170): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/art     (  822): Explicit concurrent mark sweep GC freed 36089(1562KB) AllocSpace objects, 8(316KB) LOS objects, 32% free, 33MB/49MB, paused 1.502ms total 76.263ms
,V/GoogleAuthProtoRequest( 3247): [324] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3247): [324] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3247): [324] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3247): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3247): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3247): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/ActivityManager(  822): Start proc 4197:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/BooksSync( 4065): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4065): GmsCore Version = 7.8.99 (2134222-430)
,I/GAv4    ( 4197): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4197):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4197):   adb logcat -s GAv4
,W/GAv4    ( 4197): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GAv4    ( 4197): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 4197): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4065): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 4065): Soft error
E/BooksSync( 4065): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4065): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4065): Sync error
E/BooksSync( 4065): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4065): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4065): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 438521, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  822): Killing 3828:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,V/KeepSync( 4082): Connecting to GoogleApiClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1729): Handling authorization failure
E/ClientConnectionOperation( 1729): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1729): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1729): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1729): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1729): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1729): 	... 7 more
,V/KeepSync( 4082): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4082): IOException
E/KeepSync( 4082): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4082): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4082): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4082): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4082): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4082): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4082): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4082): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4082): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4082): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4082): 	... 10 more
,W/KeepSync( 4082): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 440422, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1483): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1483): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1483): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3926): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3926): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 3926): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3926): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3926): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
,E/PlayEventLogger( 3926): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3926): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3926): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at blb.a(PG:3937)
E/HttpOperation( 4032): 	,at czp.a(PG:18188)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 12 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): 	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at hec.a(PG:42)
E/HttpOperation( 4032): 	at hee.a(PG:102)
E/HttpOperation( 4032): 	at czr.a(PG:65)
E/HttpOperation( 4032): 	at kka.a(PG:108)
E/HttpOperation( 4032): 	at czp.a(PG:19176)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 15 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): 	... 17 more
,E/ExperimentLoader( 4032): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4032): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4032): 	at jdm.a(PG:82)
E/ExperimentLoader( 4032): 	at jcs.o(PG:406)
E/ExperimentLoader( 4032): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4032): 	at jcs.i(PG:143)
E/ExperimentLoader( 4032): 	at hec.a(PG:42)
E/ExperimentLoader( 4032): 	at hee.a(PG:102)
E/ExperimentLoader( 4032): 	at czr.a(PG:65)
E/ExperimentLoader( 4032): 	at kka.a(PG:108)
E/ExperimentLoader( 4032): 	at czp.a(PG:19176)
E/ExperimentLoader( 4032): 	at czp.a(PG:9081)
E/ExperimentLoader( 4032): 	at czq.run(PG:1686)
E/ExperimentLoader( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4032): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4032): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4032): 	at jdm.a(PG:77)
E/ExperimentLoader( 4032): 	... 15 more
E/ExperimentLoader( 4032): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4032): 	at fal.a(PG:38)
E/ExperimentLoader( 4032): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4032): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 509147, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3247): [325] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 53400(2MB) AllocSpace objects, 8(882KB) LOS objects, 36% free, 27MB/43MB, paused 1.725ms total 50.933ms
,W/ExperimentUpdateService( 3247): [325] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3247): [325] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3247): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3247): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3247): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/BooksSync( 4065): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4065): GmsCore Version = 7.8.99 (2134222-430)
,I/art     (  822): Explicit concurrent mark sweep GC freed 36566(1629KB) AllocSpace objects, 6(284KB) LOS objects, 32% free, 33MB/49MB, paused 2.475ms total 83.382ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4065): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4065): Soft error
E/BooksSync( 4065): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4065): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4065): Sync error
E/BooksSync( 4065): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4065): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4065): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 682061, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/EventLogService( 1729): Opted in for usage reporting
,I/EventLogService( 1729): Aggregate from 1450226443247 (log), 1450225212572 (data)
,W/EventLogAggregator( 1729): Unknown tag: snet_gcore
,W/EventLogAggregator( 1729): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1729): dumping service [account]
,V/KeepSync( 4082): Connecting to GoogleApiClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1729): Handling authorization failure
E/ClientConnectionOperation( 1729): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1729): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1729): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1729): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1729): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1729): 	... 7 more
,V/KeepSync( 4082): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4082): IOException
E/KeepSync( 4082): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4082): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4082): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4082): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4082): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4082): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4082): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4082): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4082): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4082): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4082): 	... 10 more
W/KeepSync( 4082): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 715675, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at blb.a(PG:3937)
E/HttpOperation( 4032): 	at czp.a(PG:18188)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 12 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): 	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at hec.a(PG:42)
E/HttpOperation( 4032): 	at hee.a(PG:102)
E/HttpOperation( 4032): 	at czr.a(PG:65)
E/HttpOperation( 4032): 	at kka.a(PG:108)
E/HttpOperation( 4032): 	at czp.a(PG:19176)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 15 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): 	... 17 more
,E/ExperimentLoader( 4032): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4032): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4032): 	at jdm.a(PG:82)
E/ExperimentLoader( 4032): 	at jcs.o(PG:406)
E/ExperimentLoader( 4032): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4032): ,	at jcs.i(PG:143)
E/ExperimentLoader( 4032): 	at hec.a(PG:42)
E/ExperimentLoader( 4032): 	at hee.a(PG:102)
E/ExperimentLoader( 4032): 	at czr.a(PG:65)
E/ExperimentLoader( 4032): 	at kka.a(PG:108)
E/ExperimentLoader( 4032): 	at czp.a(PG:19176)
E/ExperimentLoader( 4032): 	at czp.a(PG:9081)
E/ExperimentLoader( 4032): 	at czq.run(PG:1686)
E/ExperimentLoader( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
,E/ExperimentLoader( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4032): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4032): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4032): 	at jdm.a(PG:77)
E/ExperimentLoader( 4032): 	... 15 more
E/ExperimentLoader( 4032): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4032): 	at fal.a(PG:38)
E/ExperimentLoader( 4032): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4032): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 793248, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3229): Stopping oneshot timer
,D/GCM     ( 1483): Message class com.google.f.a.a.i
,V/GoogleAuthProtoRequest( 3247): [326] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3247): [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3247): [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3247): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3247): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3247): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/BooksSync( 4065): Starting books sync for 61035162, extras: ade
,I/art     (  822): Explicit concurrent mark sweep GC freed 39626(1863KB) AllocSpace objects, 8(410KB) LOS objects, 32% free, 33MB/49MB, paused 2.899ms total 77.926ms
,I/BooksConfig( 4065): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4065): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4065): Soft error
E/BooksSync( 4065): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4065): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4065): Sync error
E/BooksSync( 4065): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4065): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4065): Finished books sync
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1168711, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,V/KeepSync( 4082): Connecting to GoogleApiClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 65424(3MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 1.744ms total 59.241ms
,E/ClientConnectionOperation( 1729): Handling authorization failure
E/ClientConnectionOperation( 1729): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1729): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1729): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1729): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1729): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1729): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1729): 	... 7 more
,V/KeepSync( 4082): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4082): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4082): IOException
E/KeepSync( 4082): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4082): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4082): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4082): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4082): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4082): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4082): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4082): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4082): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4082): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4082): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4082): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4082): 	... 10 more
W/KeepSync( 4082): Sync result 2
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1235768, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at blb.a(PG:3937)
E/HttpOperation( 4032): 	at czp.a(PG:18188)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 12 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): 	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at hec.a(PG:42)
E/HttpOperation( 4032): 	at hee.a(PG:102)
E/HttpOperation( 4032): 	at czr.a(PG:65)
E/HttpOperation( 4032): 	at kka.a(PG:108)
E/HttpOperation( 4032): 	at czp.a(PG:19176)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 15 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): 	... 17 more
,E/ExperimentLoader( 4032): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4032): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4032): 	at jdm.a(PG:82)
E/ExperimentLoader( 4032): 	at jcs.o(PG:406)
E/ExperimentLoader( 4032): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4032): 	at jcs.i(PG:143)
E/ExperimentLoader( 4032): 	at hec.a(PG:42)
E/ExperimentLoader( 4032): 	at hee.a(PG:102)
E/ExperimentLoader( 4032): 	at czr.a(PG:65)
E/ExperimentLoader( 4032): 	at kka.a(PG:108)
E/ExperimentLoader( 4032): 	at czp.a(PG:19176)
E/ExperimentLoader( 4032): 	at czp.a(PG:9081)
E/ExperimentLoader( 4032): 	at czq.run(PG:1686)
E/ExperimentLoader( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4032): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4032): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4032): 	at jdm.a(PG:77)
E/ExperimentLoader( 4032): 	... 15 more
E/ExperimentLoader( 4032): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4032): 	at fal.a(PG:38)
E/ExperimentLoader( 4032): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4032): 	... 17 more
,D/SyncManager(  822): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1330740, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  822): Prepared write state in 10ms
,I/ProcessStatsService(  822): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-18-22.bin
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3229): Stopping oneshot timer
,TIME-OUT KILL (timeout was 1800000ms)
```
