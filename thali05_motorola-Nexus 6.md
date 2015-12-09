#### Test 50650278d0426ce_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2697): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2697): [1] 5.onFinished: Scheduling replication attempt 2.
D/AndroidRuntime( 3158): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3158): CheckJNI is OFF
D/AndroidRuntime( 3158): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{31d32880 token=Token{3f742103 ActivityRecord{4c16db2 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
V/WindowManager(  821): Adding window Window{8df3d75 u0 Starting com.test.thalitest} at 3 of 8 (after Window{b9986df u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
D/AndroidRuntime( 3158): Shutting down VM
I/MicrophoneInputStream( 1511): mic_close com.google.android.apps.gsa.speech.audio.u@123a47f3
I/HotwordDetector( 1511): Closing mic
I/ActivityManager(  821): Start proc 3172:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1511): Stopping hotword detection.
I/HotwordRecognitionRnr( 1511): Hotword detection finished
W/GCoreFlp( 1747): No location to return for getLastLocation()
I/ActivityManager(  821): Killing 2656:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1699644691
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/ActivityManager(  821): Killing 2788:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  876): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  876): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  876): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3172): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3172): Time to load native libraries: 2 ms (timestamps 5386-5388)
,I/LibraryLoader( 3172): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3172): Binding Chromium to main looper Looper (main, tid 1) {258c6b2a}
,I/LibraryLoader( 3172): Expected native library version number "",actual native library version number ""
I/chromium( 3172): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3172): Initializing chromium process, singleProcess=true
,W/art     ( 3172): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3172): ApplicationContext is null in ApplicationStatus
,W/chromium( 3172): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3172): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3172): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3172): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
I/Adreno  ( 3172): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6fb6de5:true
,D/BluetoothAdapter( 3172): 517740749: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3172): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3172): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3172): CordovaWebView is running on device made by: motorola
,W/art     ( 3172): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3172): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3172): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3172): Validating map...
,V/WindowManager(  821): Adding window Window{1f7c9a55 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{8df3d75 u0 Starting com.test.thalitest})
,W/chromium( 3172): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3172): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3172): Enabling debug mode 0
,I/Keyboard.Facilitator( 1228): onFinishInput()
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +855ms (total +1m41s346ms)
,W/BindingManager( 3172): Cannot call determinedVisibility() - never saw a connection for the pid: 3172
,D/JsMessageQueue( 3172): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3172): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576197888
D/JX-Cordova( 3172): jxcore cordova android initializing
,I/kickstart(  876): STATUS: Received file 'm9kefs2'
I/kickstart(  876): STATUS: 950272 bytes transferred in 0.989364 seconds
,I/kickstart(  876): STATUS: Successfully downloaded files from target 
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  876): STATUS: Sahara protocol completed
,W/jxcore-log( 3172): Initializing JXcore engine
W/jxcore-log( 3172): JXcore engine is ready
,W/jxcore-log( 3172): Starting JXcore engine
,W/.test.thalitest( 3172): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9806]" dev="sockfs" ino=9806 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3172): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3172): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11634]" dev="sockfs" ino=11634 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3172): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19175]" dev="sockfs" ino=19175 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3172): Platform android
W/jxcore-log( 3172): 
W/jxcore-log( 3172): Process ARCH arm
W/jxcore-log( 3172): 
,I/jxcore-log( 3172): JXcore Cordova bridge is ready!
I/jxcore-log( 3172): 
,W/jxcore-log( 3172): JXcore engine is started
I/Choreographer( 3172): Skipped 134 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3172): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3172): Toggling radios to true
I/jxcore-log( 3172): 
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  821): Message: 1
D/BluetoothManagerService(  821): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  821): New client listening to asynchronous messages
D/WifiService(  821): setWifiEnabled: true pid=3172, uid=10265
,E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  354): Softap fwReload - Ok
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
D/CommandListener(  354): Clearing all IP addresses on wlan0
I/jxcore-log( 3172): Radios toggled
I/jxcore-log( 3172): 
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  821): Start proc 3229:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,W/ResourcesManager( 3229): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3234): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3234): rfkill: Cannot open RFKILL control device
,D/WifiMonitor(  821): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  821): Start proc 3247:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,D/AdapterServiceConfig( 3229): Adding HeadsetService
D/AdapterServiceConfig( 3229): Adding A2dpService
D/AdapterServiceConfig( 3229): Adding HidService
D/AdapterServiceConfig( 3229): Adding HealthService
D/AdapterServiceConfig( 3229): Adding PanService
D/AdapterServiceConfig( 3229): Adding GattService
D/AdapterServiceConfig( 3229): Adding BluetoothMapService
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3246c50e:true
,D/BluetoothAdapterState( 3229): make
I/bluedroid( 3229): init
I/BluetoothAdapterState( 3229): Entering OffState
,I/bte_conf( 3229): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3229): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3229): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3229): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3229): get_profile_interface socket
I/bluedroid( 3229): get_profile_interface map_client
I/GKI_LINUX( 3229): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3229): Address is:F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3229): Name is: Nexus 6
,D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  821): Message: 40
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 3229): config_hci_snoop_log
D/BluetoothManagerService(  821): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  821): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3229): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3229): Setting state to 11
I/BluetoothAdapterState( 3229): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  821): Message: 60
,D/BluetoothBondStateMachine( 3229): make
,D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  821): Bluetooth State Change Intent: 10 -> 11
,I/art     (  821): Explicit concurrent mark sweep GC freed 18560(907KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 6.931ms total 68.598ms
,I/BluetoothBondStateMachine( 3229): StableState(): Entering Off State
,I/BluetoothAdapterState( 3229): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11ec9d1b
,D/HeadsetService( 3229): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3229): classInitNative: succeeds
D/HeadsetStateMachine( 3229): make
,D/HeadsetStateMachine( 3229): max_hf_connections = 1
I/bluedroid( 3229): get_profile_interface handsfree
,D/HeadsetStateMachine( 3229): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11ec9d1b
,D/BluetoothA2dp(  821): Proxy object connected
D/BluetoothA2dp( 1062): Proxy object connected
D/A2dpService( 3229): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3229): classInitNative: succeeds
I/bluedroid( 3229): get_profile_interface avrcp
,E/RemoteController( 3229): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3229): classInitNative: succeeds
D/A2dpStateMachine( 3229): make
I/bluedroid( 3229): get_profile_interface a2dp
I/GKI_LINUX( 3229): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/A2dpStateMachine( 3229): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3229): classInitNative: succeeds
D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11ec9d1b
D/BluetoothInputDevice( 1062): Proxy object connected
D/HidService( 3229): Received start request. Starting profile...
I/bluedroid( 3229): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3229): classInitNative: succeeds
D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11ec9d1b
D/HealthService( 3229): Received start request. Starting profile...
I/bluedroid( 3229): get_profile_interface health
,I/BluetoothPanServiceJni( 3229): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11ec9d1b
D/BluetoothPan( 1062): BluetoothPAN Proxy object connected
,D/PanService( 3229): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3229): initializeNative(L110): pan
I/bluedroid( 3229): get_profile_interface pan
I/BtGatt.JNI( 3229): classInitNative(L873): classInitNative: Success!
,D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11ec9d1b
D/BtGatt.DebugUtils( 3229): handleDebugAction() action=null
,D/BtGatt.GattService( 3229): Received start request. Starting profile...
D/BtGatt.GattService( 3229): start()
I/bluedroid( 3229): get_profile_interface gatt
D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11ec9d1b
D/BtGatt.AdvertiseManager( 3229): advertise manager created
,D/BluetoothAdapterService( 3229): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11ec9d1b
,D/BluetoothMap( 1062): Proxy object connected
D/BluetoothMapService( 3229): Received start request. Starting profile...
D/BluetoothMapService( 3229): start()
,D/BluetoothMapEmailSettingsLoader( 3229): Found 0 applications
D/BluetoothMapEmailAppObserver( 3229): createReceiver()
,D/BluetoothMapEmailAppObserver( 3229): initObservers()
D/BluetoothMapEmailAppObserver( 3229): getEnabledAccountItems()
,D/HeadsetStateMachine( 3229): Proxy object connected
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3229): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 3229): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3229): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3229): enable
I/bt_hci_bdroid( 3229): init
I/GKI_LINUX( 3229): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3229): btu_task pending for preload complete event
,I/bt_vendor( 3229): init
,I/bt_vnd_conf( 3229): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3229): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3229): userial_init
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 24650(1295KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.046ms total 31.617ms
,I/ActivityManager(  821): Start proc 3291:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  821): Killing 2822:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/bt_userial_vendor( 3229): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3229): device fd = 53 open
,D/bt_userial( 3229): Entering userial_read_thread()
,I/bt_hwcfg( 3229): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3229): Chipset BCM4354A2
D/bt_hwcfg( 3229): Target name = [BCM4354A2]
I/bt_hwcfg( 3229): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,D/Tethering(  821): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3234): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3234): Could not read interface p2p-dev-wlan0 flags: No such device
,I/ActivityManager(  821): Start proc 3314:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/WifiConfigStore(  821): Loading config and enabling all networks 
,E/WifiConfigStore(  821): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
W/Settings( 2625): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 349us total 37.340ms
D/WifiNative-HAL(  821): Setting external_sim to 1
D/WifiStateMachine(  821): Setting OUI to 92-68-C3
I/WifiNative-HAL(  821): startHal
,D/wifi    (  821): setting scan oui 0xaec7d328
D/WifiHAL (  821): Sending mac address OUI
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1bcbd146}
,E/WifiStateMachine(  821): cancelDelayedScan -> 1
I/ActivityManager(  821): Killing 2755:com.google.android.gm/u0a78 (adj 15): empty #17
,W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
,D/CommandListener(  354): Setting iface cfg
,E/WifiP2pService(  821): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  821): startMonitoring(p2p0) with mConnected = true
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 318us total 24.300ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 233us total 11.763ms
,I/bt_hwcfg( 3229): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3229): Settlement delay -- 100 ms
I/bt_hwcfg( 3229): Setting fw settlement delay to 100 
,D/WifiScanningService(  821): SCAN_AVAILABLE : 3
D/RttService(  821): SCAN_AVAILABLE : 3
D/RttService(  821): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState got{ when=-4ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  821): startHal
,D/wifi    (  821): getting scan capabilities on interface[0] = 0xaec7d328
,D/WifiHAL (  821): Creating message to get scan capablities; iface = 5
D/WifiHAL (  821): In GetCapabilities::handleResponse
D/WifiHAL (  821): Id = 0, subcmd = 0, len = 28, expected len = 32,
,D/WifiScanningService(  821): StartedState
D/WifiNative-HAL(  821): p2pGetDeviceAddress,
D/WifiNative-HAL(  821): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 3234): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/native  (  821): do suspend false
,I/bt_hwcfg( 3229): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3229): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3229): vendor lib fwcfg completed
I/bt-btu  ( 3229): btu_task received preload complete event
,I/        ( 3229): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3229): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3229): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3229): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3229): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3229): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3229): BTE_InitTraceLevels -- TRC_BNEP
,I/        ( 3229): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3229): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3229): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3229): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3229): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3229): BTE_InitTraceLevels -- TRC_SMP
,I/        ( 3229): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3229): BTE_InitTraceLevels -- TRC_BTIF
,I/ActivityManager(  821): Killing 2346:com.google.android.calendar/u0a37 (adj 15): empty #17
,E/bt-btm  ( 3229): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e4a085 
E/bt-btm  ( 3229): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e4a085 
,D/BluetoothAdapterProperties( 3229): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3229): Calling BTA_HhEnable,
E/bt-btif ( 3229): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3229): Address is:F8:CF:C5:D9:E5:61
,W/bt-btm  ( 3229): Stopping oneshot timer,
D/BluetoothAdapterProperties( 3229): Name is: Nexus 6
,D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
,I/ActivityManager(  821): Start proc 3333:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
D/BluetoothAdapterProperties( 3229): Scan Mode:20
D/BluetoothAdapterProperties( 3229): Discoverable Timeout:120
,D/bte_conf( 3229): Device ID record 1 : primary,
,D/bte_conf( 3229):   vendorId            = 000f
D/bte_conf( 3229):   vendorIdSource      = 0001
D/bte_conf( 3229):   product             = 1200
,D/bte_conf( 3229):   version             = 1436,
D/bte_conf( 3229):   clientExecutableURL = 
D/bte_conf( 3229):   serviceDescription  = 
D/bte_conf( 3229):   documentationURL    = ,
D/bte_conf( 3229): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3229): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 3229): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 3229): ScanMode =  20
D/BluetoothAdapterProperties( 3229): State =  11
D/BluetoothAdapterProperties( 3229): Scan Mode:21
D/BluetoothAdapterProperties( 3229): Discoverable Timeout:120
D/BluetoothAdapterProperties( 3229): Setting state to 12
,I/BluetoothAdapterState( 3229): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterState( 3229): Entering On State
D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  821): Broadcasting onBluetoothStateChange(true) to 13 receivers.
D/BluetoothHeadset( 1062): onBluetoothStateChange: up=true
D/BluetoothManagerService(  821): Creating new ProfileServiceConnections object for profile: 1
,D/BluetoothA2dp(  821): onBluetoothStateChange: up=true
D/BluetoothPan( 1062): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadsetClient( 1062): onBluetoothStateChange: up=true
,E/BluetoothHeadsetClient( 1062): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
,D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
E/bt_h4   ( 3229): vendor lib postload completed
D/BluetoothInputDevice( 1062): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 1062): onBluetoothStateChange: up=true
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothAvrcpController( 1062): onBluetoothStateChange: up=true
,E/BluetoothAvrcpController( 1062): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothA2dpSink( 1062): onBluetoothStateChange: up=true
E/BluetoothA2dpSink( 1062): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
,D/BluetoothHeadset( 1273): onBluetoothStateChange: up=true
D/BluetoothMap( 1062): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  821): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  821): Message: 40
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 3229): onReceive
D/BluetoothMapService( 3229): STATE_ON
D/BluetoothMapMasInstance( 3229): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3229): MAS initSocket()
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3229): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothMapMasInstance( 3229): Accepting socket connection...
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 1062): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset(  821): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 1273): Proxy object connected
,D/StrictMode( 3333): StrictMode policy violation; ~duration=246 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3333): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3333): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3333): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3333): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3333): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3333): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3333): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3333): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3333): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3333): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3333): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3333): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3333): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3333): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3333): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3333): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3333): StrictMode policy violation; ~duration=246 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3333): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3333): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3333): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3333): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3333): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3333): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3333): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3333): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3333): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3333): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3333): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3333): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3333): StrictMode policy violation; ~duration=244 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3333): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3333): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3333): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3333): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3333): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3333): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3333): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3333): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3333): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3333): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3333): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3333): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3333): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3333): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3333): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3333): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3333): StrictMode policy violation; ~duration=240 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
D/StrictMode( 3333): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3333): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3333): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3333): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540),
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3333): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3333): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3333): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151),
D/StrictMode( 3333): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3333): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3333): ,	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3333): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698),
D/StrictMode( 3333): StrictMode policy violation; ~duration=197 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3333): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3333): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3333): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3333): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
,D/StrictMode( 3333): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3333): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3333): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3333): 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3333): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3333): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3333): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3333): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3333): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3333): 	at android.os.Looper.loop(Looper.java:135)
,D/StrictMode( 3333): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3333): StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3333): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3333): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3333): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3333): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3333): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3333): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3333): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3333): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3333): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3333): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3333): # via Binder call with stack:
D/StrictMode( 3333): android.os.StrictMode$LogStackTrace
D/StrictMode( 3333): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717),
D/StrictMode( 3333): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3333): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3333): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3333): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3333): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3333): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3333): 	at com.google.android.c.c.a(PG:107),
D/StrictMode( 3333): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3333): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
,D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3333): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3333): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3333): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3333): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3333): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,D/StrictMode( 3333): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3333): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3333): StrictMode policy violation; ~duration=42 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3333): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3333): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3333): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3333): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3333): ,	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3333): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3333): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3333): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587),
D/StrictMode( 3333): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3333): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3333): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3333): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3333): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3333): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3333): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3333): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3333): StrictMode policy violation; ~duration=42 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3333): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3333): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3333): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3333): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3333): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3333): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3333): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3333): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3333): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3333): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3333): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3333): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3333): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3333): StrictMode policy violation; ~duration=41 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3333): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3333): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3333): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3333): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3333): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3333): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3333): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3333): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3333): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3333): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3333): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3333): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3333): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3333): StrictMode policy violation; ~duration=40 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3333): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3333): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3333): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3333): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3333): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3333): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3333): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3333): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3333): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3333): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3333): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3333): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3333): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3333): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3333): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3333): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3333): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3333): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3333): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3333): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3333): 	at java.lang.reflect.Method.invoke(Native Method)
D/Stric,tMode( 3333): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3333): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 3333): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  821): Message: 20,
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3090c0cd:true
,I/ActivityManager(  821): Killing 2859:com.google.android.music:main/u0a66 (adj 15): empty #17,
,D/AuthorizationBluetoothService( 1482): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29749dfc:true
,D/LocalBluetoothProfileManager( 3314): Adding local A2DP profile
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3314): Adding local HEADSET profile,
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30,
,D/BluetoothManagerService(  821): Message: 30,
,D/LocalBluetoothProfileManager( 3314): Adding local MAP profile
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothMap( 3314): Create BluetoothMap proxy object
,D/AuthorizationBluetoothService( 1482): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  821): Message: 30
,W/BluetoothAdapter( 3229): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3229): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3229): Accept thread started.
,D/LocalBluetoothProfileManager( 3314): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3314): finishStartingService: stopping service
,D/BluetoothA2dp( 3314): Proxy object connected
D/A2dpProfile( 3314): Bluetooth service connected
,D/BluetoothInputDevice( 3314): Proxy object connected
,D/HidProfile( 3314): Bluetooth service connected
,D/BluetoothPan( 3314): BluetoothPAN Proxy object connected
D/PanProfile( 3314): Bluetooth service connected
D/BluetoothMap( 3314): Proxy object connected
D/MapProfile( 3314): Bluetooth service connected
D/BluetoothMap( 3314): getConnectedDevices()
,D/BluetoothPbap( 3314): Proxy object connected
,D/PbapServerProfile( 3314): Bluetooth service connected
,D/BluetoothManagerService(  821): Message: 400,
D/BluetoothHeadset( 3314): Proxy object connected
D/HeadsetProfile( 3314): Bluetooth service connected
,I/wpa_supplicant( 3234): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  821):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  821):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,I/wpa_supplicant( 3234): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3234): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3234): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3234): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 1
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 1
E/WifiStateMachine(  821):  RSSI mgmt: -53
E/WifiStateMachine(  821):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 0 tx_time=59 rx_time=66 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 3374): version 5.5.6 starting
,I/dhcpcd  ( 3374): wlan0: rebinding lease of 192.168.1.122
,I/dhcpcd  ( 3374): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3374): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 100
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  821): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821):    accepting network in place of null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  821): MasterInitialState.processMessage what=3
,V/BackupManagerService(  821): Scheduling immediate backup pass
,D/PhoneInterfaceManager( 1273): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1273): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,I/ActivityManager(  821): Start proc 3412:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,V/BackupManagerService(  821): Running a backup pass
V/BackupManagerService(  821): clearing pending backups
,V/PerformBackupTask(  821): Beginning backup of 14 targets
,D/PerformBackupTask(  821): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  821): doBackup() invoked
,E/GpsLocationProvider(  821): No APN found to select.
I/PMBA    (  821): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/AlarmManagerService(  821): Setting time of day to sec=1449681230
W/AlarmManagerService(  821): Unable to set rtc to 1449681230: Invalid argument
,I/BackupRestoreController(  821): Getting widget state for user: 0
,D/GpsLocationProvider(  821): NTP server returned: 1449681230092 (Wed Dec 09 18:13:50 GMT+01:00 2015) reference: 144027 certainty: 12 system time offset: -29
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:13:50 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449681230133], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449681230114]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
,W/GmsBackupTransport( 1747): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1747): starting performBackup for @pm@
,V/GmsBackupTransport( 1747): performBackup done for @pm@
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/MusicStore( 3412): Database version: 120
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
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
,E/Auth.Api.Credentials( 1775): [CredentialSyncAdapter] Unknown sync event.
,W/GmsBackupTransport( 1747): Error sending final backup to server: 
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
,D/BackupManagerService(  821): Now staging backup of com.google.android.talk
,D/BackupManagerService(  821): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  821): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  821): Now staging backup of com.android.sharedstoragebackup
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 8784(449KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.105ms total 21.014ms
,D/BackupManagerService(  821): Now staging backup of com.google.android.gm
,D/BackupManagerService(  821): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  821): Now staging backup of com.android.nfc
,D/BackupManagerService(  821): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  821): Now staging backup of com.google.android.marvin.talkback
,W/DriveInitializer( 1775): Background init thread started
,D/BackupManagerService(  821): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  821): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  821): Now staging backup of com.android.vending
,D/BackupManagerService(  821): Now staging backup of android
,D/BackupManagerService(  821): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1747): Next backup will happen in 43199880 millis.
,I/BackupManagerService(  821): Backup pass finished.
,W/ResourcesManager( 3412): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3412): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  821): Explicit concurrent mark sweep GC freed 50076(2MB) AllocSpace objects, 5(121KB) LOS objects, 32% free, 33MB/49MB, paused 1.750ms total 106.082ms
,W/DriveInitializer( 1775): Awaiting to be initialized
,W/DriveInitializer( 1775): Background init thread ended
,V/JNIHelp ( 3412): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2944): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2944): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2944): 	at jdm.a(PG:82)
E/HttpOperation( 2944): 	at jcs.o(PG:406)
E/HttpOperation( 2944): 	at jcn.a(PG:1379)
E/HttpOperation( 2944): 	at jcs.i(PG:143)
E/HttpOperation( 2944): 	at blb.a(PG:3937)
E/HttpOperation( 2944): 	at czp.a(PG:18188)
E/HttpOperation( 2944): 	at czp.a(PG:9081)
E/HttpOperation( 2944): 	at czq.run(PG:1686)
E/HttpOperation( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2944): 	at jdj.a(PG:4091)
E/HttpOperation( 2944): 	at jdj.a(PG:1125)
E/HttpOperation( 2944): 	at jdm.a(PG:77)
E/HttpOperation( 2944): 	... 12 more
E/HttpOperation( 2944): Caused by: faj: BadAuthentication
E/HttpOperation( 2944): 	at fal.a(PG:38)
E/HttpOperation( 2944): 	at jdj.a(PG:4089)
E/HttpOperation( 2944): 	... 14 more
,I/ProviderInstaller( 3412): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3412): GMSCore installation verified
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ConfigStore( 3412): Config Database version: 1
,E/HttpOperation( 2944): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2944): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2944): 	at jdm.a(PG:82)
E/HttpOperation( 2944): 	at jcs.o(PG:406)
E/HttpOperation( 2944): 	at jcn.a(PG:1379)
E/HttpOperation( 2944): 	at jcs.i(PG:143)
E/HttpOperation( 2944): 	at hec.a(PG:42)
E/HttpOperation( 2944): 	at hee.a(PG:102)
E/HttpOperation( 2944): 	at czr.a(PG:65)
E/HttpOperation( 2944): 	at kka.a(PG:108)
E/HttpOperation( 2944): 	at czp.a(PG:19176)
E/HttpOperation( 2944): 	at czp.a(PG:9081)
E/HttpOperation( 2944): 	at czq.run(PG:1686)
E/HttpOperation( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2944): 	at jdj.a(PG:4091)
E/HttpOperation( 2944): 	at jdj.a(PG:1125)
E/HttpOperation( 2944): 	at jdm.a(PG:77)
E/HttpOperation( 2944): 	... 15 more
E/HttpOperation( 2944): Caused by: faj: BadAuthentication
E/HttpOperation( 2944): 	at fal.a(PG:38)
E/HttpOperation( 2944): 	at jdj.a(PG:4089)
E/HttpOperation( 2944): 	... 17 more
E/ExperimentLoader( 2944): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2944): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2944): 	at jdm.a(PG:82)
E/ExperimentLoader( 2944): 	at jcs.o(PG:406)
E/ExperimentLoader( 2944): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2944): 	at jcs.i(PG:143)
E/ExperimentLoader( 2944): 	at hec.a(PG:42)
E/ExperimentLoader( 2944): 	at hee.a(PG:102)
E/ExperimentLoader( 2944): 	at czr.a(PG:65)
E/ExperimentLoader( 2944): 	at kka.a(PG:108)
E/ExperimentLoader( 2944): 	at czp.a(PG:19176)
E/ExperimentLoader( 2944): 	at czp.a(PG:9081)
E/ExperimentLoader( 2944): 	at czq.run(PG:1686)
E/ExperimentLoader( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2944): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2944): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2944): 	at jdm.a(PG:77)
E/ExperimentLoader( 2944): 	... 15 more
E/ExperimentLoader( 2944): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2944): 	at fal.a(PG:38)
E/ExperimentLoader( 2944): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2944): 	... 17 more
,I/MediaRouter( 3412): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3412): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3412): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  821): Start proc 3469:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/NetworkMonitor( 3412): type=WIFI subType= reason=null isConnected=true
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 38282, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Start proc 3487:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/GHttpClientFactory( 3412): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3412): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 3487): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3487): simOperator:  IMSI: null
D/SprintDMReceiver( 3487): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1775): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1775): onCreate
,D/SystemUpdateService( 1775): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1775): active receiver: enabled
,I/SystemUpdateService( 1775): showing system update notification
,V/KeepSync( 3291): Connecting to GoogleApiClient
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1775): retry (wakeup: false) in 3599967 ms
,I/iu.SyncManager( 1775): SYNC; picasa accounts
,D/NetworkLogImpl( 1775): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1775): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1775): num queued entries: 0
,I/iu.UploadsManager( 1775): num updated entries: 0
I/iu.SyncManager( 1775): NEXT; no task
,D/SystemUpdateService( 1775): onDestroy
,D/ChimeraCfgMgr( 1775): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1775): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  821): Start proc 3521:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,W/BaseAppContext( 1775): Using Auth Proxy for data requests.
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1775): Using Auth Proxy for data requests.
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
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 2625): connection state changed from DISCONNECTED to CONNECTED
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
,V/KeepSync( 3291): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
,D/GCM     ( 1482): Connected
,D/GCM     ( 1482): Message class com.google.f.a.a.p
,W/GAV2    ( 3469): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3469): Created application version: 3.6.8 (30608)
,I/GAv4    ( 3521): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3521):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3521):   adb logcat -s GAv4
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 14373(867KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 26MB/42MB, paused 909us total 22.480ms
,W/GAv4    ( 3521): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3521): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3521): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/BooksSync( 3469): Starting books sync for 61035162, extras: ade
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/ActivityManager(  821): Killing 2199:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 38284, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3172): Test app app.js loaded
I/jxcore-log( 3172): 
,I/Choreographer( 3172): Skipped 415 frames!  The application may be doing too much work on its main thread.
,I/art     (  821): Explicit concurrent mark sweep GC freed 25136(1142KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.249ms total 45.579ms
,I/chromium( 3172): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/BooksConfig( 3469): GmsCore Version = 7.8.99 (2134222-430)
I/WebViewFactory( 3521): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3521): Time to load native libraries: 2 ms (timestamps 5417-5419)
I/LibraryLoader( 3521): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3521): Binding Chromium to main looper Looper (main, tid 1) {de343bf}
I/LibraryLoader( 3521): Expected native library version number "",actual native library version number ""
,I/chromium( 3521): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3521): Initializing chromium process, singleProcess=true
,W/art     ( 3521): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3521): ApplicationContext is null in ApplicationStatus
,W/chromium( 3521): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3521): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3521): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3521): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
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
,E/BooksAccountManager( 3469): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3469): Soft error
E/BooksSync( 3469): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3469): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3469): Sync error
E/BooksSync( 3469): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3469): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3469): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38284, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
I/ActivityManager(  821): Killing 1387:android.process.acore/u0a5 (adj 15): empty #17
,W/AudioManagerAndroid( 3521): Requires BLUETOOTH permission
,I/NSApplication( 3521): Starting up...
,I/ActivityManager(  821): Killing 3076:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3055:com.google.android.partnersetup/u0a16 (adj 15): empty #18
,I/ActivityManager(  821): Start proc 3602:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  821): Start proc 3619:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
I/ActivityManager(  821): Killing 1805:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,E/SQLiteLog( 3619): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  821): Start proc 3639:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3639): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3639): Created com.android.providers.calendar.CalendarAlarmManager@30977c15(com.android.providers.calendar.CalendarProvider2@258c6b2a)
,I/ActivityManager(  821): Start proc 3661:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3619): PlayLogger.onLoggerConnected
,I/ActivityManager(  821): Killing 3104:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/TimeService( 3661): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449681233916
D/        ( 3661): TimeServiceNative: User Time to be set is 1449681233916
,D/QC-time-services( 3661): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3661): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3661): Lib:time_genoff_operation: pargs->ts_val = 1449681233916
D/QC-time-services( 3661): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  373): Daemon: Connection accepted:time_genoff
D/QC-time-services(  373): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449681233916
D/QC-time-services(  373): Daemon:genoff_opr: Base = 2, val = 1449681233916, operation = 0
D/QC-time-services(  373): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/26/70 13:26:47
D/QC-time-services(  373): Daemon:Value read from RTC seconds = 9984407000
D/QC-time-services(  373): Daemon:new time 1449681233916 
D/QC-time-services(  373): Daemon: delta 1439696826916 genoff 1439696826916 
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696826916 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  373): Updating the TOD offset,
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696826916 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  373): Daemon:Update to modem bit set
D/QC-time-services(  373): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  373): Daemon: Base = 2, Value being sent to MODEM = 1133716433916
E/QC-time-services( 3661): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  373): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  373): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  821): Start proc 3680:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  821): Killing 3006:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/GAv4    ( 3680): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3680):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3680):   adb logcat -s GAv4
,W/GAv4    ( 3680): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3680): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3680): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  821): Killing 2697:com.android.vending/u0a19 (adj 15): empty #17
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1bcbd146}
V/Herrevad( 1775): NQAS connected
,I/art     ( 1775): Explicit concurrent mark sweep GC freed 14973(1155KB) AllocSpace objects, 16(256KB) LOS objects, 35% free, 28MB/44MB, paused 1.387ms total 46.461ms
,I/CalendarProvider2( 3639): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3639): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/WifiService(  821): New client listening to asynchronous messages
,I/art     (  821): Explicit concurrent mark sweep GC freed 16939(697KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 1.362ms total 48.009ms
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2625): UserRecoverableAuthException.
,E/Babel   ( 2625): eei: BadAuthentication
E/Babel   ( 2625): 	at eeg.a(Unknown Source)
E/Babel   ( 2625): 	at eeg.a(Unknown Source)
E/Babel   ( 2625): 	at eeg.a(Unknown Source)
E/Babel   ( 2625): 	at g.a(Unknown Source)
E/Babel   ( 2625): 	at cae.a(SourceFile:3089)
E/Babel   ( 2625): 	at cae.a(SourceFile:1131)
E/Babel   ( 2625): 	at cws.a(SourceFile:4333)
E/Babel   ( 2625): 	at cws.a(SourceFile:1419)
E/Babel   ( 2625): 	at crl.a(SourceFile:492)
E/Babel   ( 2625): 	at crl.a(SourceFile:1468)
E/Babel   ( 2625): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2625): 	at cas.b(SourceFile:106)
E/Babel   ( 2625): 	at cap.d(SourceFile:335)
E/Babel   ( 2625): 	at caq.run(SourceFile:81)
E/Babel   ( 2625): Error getting auth token
E/Babel   ( 2625): dvm
E/Babel   ( 2625): 	at g.a(Unknown Source)
,E/Babel   ( 2625): 	at cae.a(SourceFile:3089)
E/Babel   ( 2625): 	at cae.a(SourceFile:1131)
E/Babel   ( 2625): 	at cws.a(SourceFile:4333)
E/Babel   ( 2625): 	at cws.a(SourceFile:1419)
E/Babel   ( 2625): 	at crl.a(SourceFile:492)
E/Babel   ( 2625): 	at crl.a(SourceFile:1468)
E/Babel   ( 2625): 	,at cqu.a(SourceFile:4416)
E/Babel   ( 2625): 	at cas.b(SourceFile:106)
E/Babel   ( 2625): 	at cap.d(SourceFile:335)
E/Babel   ( 2625): 	at caq.run(SourceFile:81)
,E/Babel   ( 2625): Account registration failed 1-Redacted-21
E/Babel   ( 2625): cyp: null -- null
E/Babel   ( 2625): 	at cae.a(SourceFile:3121)
E/Babel   ( 2625): 	at cae.a(SourceFile:1131)
E/Babel   ( 2625): 	at cws.a(SourceFile:4333)
E/Babel   ( 2625): 	at cws.a(SourceFile:1419)
E/Babel   ( 2625): 	at crl.a(SourceFile:492)
E/Babel   ( 2625): 	at crl.a(SourceFile:1468)
E/Babel   ( 2625): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2625): 	at cas.b(SourceFile:106)
E/Babel   ( 2625): 	at cap.d(SourceFile:335)
E/Babel   ( 2625): 	at caq.run(SourceFile:81)
,I/art     ( 2625): Note: end time exceeds epoch: 
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1482): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2625): Unexpected exception while authenticating.
,E/Babel   ( 2625): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2625): 	at eeg.b(Unknown Source)
E/Babel   ( 2625): 	at eeg.b(Unknown Source)
E/Babel   ( 2625): 	at g.a(Unknown Source)
E/Babel   ( 2625): 	at cae.b(SourceFile:1146)
E/Babel   ( 2625): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2625): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2625): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2625): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 3639): (284) automatic index on view_events(_id)
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=23.41 rxSuccessRate=23.56 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=23.41 rxSuccessRate=23.56 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,I/MusicLeanback( 3412): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3412): Stop autocaching.
,I/ActivityManager(  821): Start proc 3725:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 479us total 10.446ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 235us total 10.471ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 9.605ms
,W/ResourcesManager( 3725): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3725): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3725): VM with version 2.1.0 has multidex support,
I/MultiDex( 3725): install
,I/MultiDex( 3725): VM has multidex support, MultiDex support library is disabled.,
,V/JNIHelp ( 3725): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3725): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1482): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1482): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1775): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3725): callingUid 10011, callindPid: 3725
,D/LocationInitializer( 1775): Restart initialization of location
,E/MDM     ( 1747): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3412): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3412): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAV2    ( 3469): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 3619): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  821): Start proc 3763:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/Finsky  ( 3763): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3763): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  821): Start proc 3799:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3763): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3763): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 3799): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3799): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 3763): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3763): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 3763): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 3799): VM with version 2.1.0 has multidex support
I/MultiDex( 3799): install
I/MultiDex( 3799): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 3763): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 3799): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3799): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1482): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1482): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1775): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1747): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1775): Restart initialization of location
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 20599(1193KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.374ms total 24.252ms
,V/Finsky  ( 3763): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3763): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3763): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3763): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ActivityManager(  821): Killing 3333:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3314:com.android.settings/1000 (adj 15): empty #18
,D/Finsky  ( 3763): [390] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books,
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3763): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/Finsky  ( 3763): [390] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3763): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  821): Explicit concurrent mark sweep GC freed 19501(937KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.613ms total 88.071ms
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3763): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3763): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3763): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,D/Finsky  ( 3763): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3763): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/DeviceConnectionService( 1747): client connected with version: 7571000
,I/ActivityManager(  821): Killing 3487:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3521:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (415 us)
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  821): Display changed displayId=0
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.29 rxSuccessRate=3.42 targetRoamBSSID=any RSSI=-53
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  821): Excessive delay in setPowerMode(): 281ms
,I/DreamManagerService(  821): Entering dreamland.
I/PowerManagerService(  821): Dozing...
,I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 6
,E/native  (  821): do suspend false
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@29bfd5a5}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.32 rxSuccessRate=1.61 targetRoamBSSID=any RSSI=-52
,I/Keyboard.Facilitator( 1228): onFinishInput()
,E/WifiStateMachine(  821): cancelDelayedScan -> 8
,E/native  (  821): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@29bfd5a5}
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3247): [331] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3247): [331] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3247): [331] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.a(SourceFile:117),
W/ExperimentUpdateService( 3247): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3247): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3247): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3247): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3247): ,	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3247): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3247): 	at com.a.a.k.run(SourceFile:110)
,I/VacuumService( 1482): Vacuum at: now=1449681260137 tag=VacuumService
,I/GoogleURLConnFactory( 1482): Using platform SSLCertificateSocketFactory
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
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482): No account for auth token provided
,W/Uploader( 1482):  no longer exists, so no auth token.
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
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 66152(3MB) AllocSpace objects, 12(1089KB) LOS objects, 37% free, 27MB/43MB, paused 1.900ms total 58.417ms
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3763): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3763): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3763): [1] 5.onFinished: Scheduling replication attempt 4.
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
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.50 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 8 -> obsolete
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/art     (  821): Explicit concurrent mark sweep GC freed 34493(1638KB) AllocSpace objects, 6(190KB) LOS objects, 31% free, 34MB/50MB, paused 2.328ms total 99.608ms
,V/KeepSync( 3291): Connecting to GoogleApiClient
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2944): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2944): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2944): 	at jdm.a(PG:82)
E/HttpOperation( 2944): 	at jcs.o(PG:406)
E/HttpOperation( 2944): 	at jcn.a(PG:1379)
E/HttpOperation( 2944): 	at jcs.i(PG:143)
E/HttpOperation( 2944): 	at blb.a(PG:3937)
E/HttpOperation( 2944): 	at czp.a(PG:18188)
E/HttpOperation( 2944): 	at czp.a(PG:9087)
E/HttpOperation( 2944): 	at czq.run(PG:1686)
E/HttpOperation( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2944): 	at jdj.a(PG:4091)
E/HttpOperation( 2944): 	at jdj.a(PG:1125)
E/HttpOperation( 2944): 	at jdm.a(PG:77)
E/HttpOperation( 2944): 	... 12 more
E/HttpOperation( 2944): Caused by: faj: BadAuthentication
E/HttpOperation( 2944): 	at fal.a(PG:38)
E/HttpOperation( 2944): 	at jdj.a(PG:4089)
E/HttpOperation( 2944): 	... 14 more
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
,V/KeepSync( 3291): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3291): IOException,
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
,E/HttpOperation( 2944): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2944): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2944): 	at jdm.a(PG:82)
E/HttpOperation( 2944): 	at jcs.o(PG:406)
E/HttpOperation( 2944): 	at jcn.a(PG:1379)
E/HttpOperation( 2944): 	at jcs.i(PG:143)
E/HttpOperation( 2944): 	at blb.a(PG:3937)
E/HttpOperation( 2944): 	at czp.a(PG:18188)
E/HttpOperation( 2944): 	at czp.a(PG:9081)
E/HttpOperation( 2944): 	at czq.run(PG:1686)
E/HttpOperation( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2944): 	at jdj.a(PG:4091)
E/HttpOperation( 2944): 	at jdj.a(PG:1125)
E/HttpOperation( 2944): 	at jdm.a(PG:77)
E/HttpOperation( 2944): 	... 12 more
E/HttpOperation( 2944): Caused by: faj: BadAuthentication
E/HttpOperation( 2944): 	at fal.a(PG:38)
E/HttpOperation( 2944): 	at jdj.a(PG:4089)
E/HttpOperation( 2944): 	... 14 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 175670, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksSync( 3469): Starting books sync for 61035162, extras: ade
,E/HttpOperation( 2944): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2944): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2944): 	at jdm.a(PG:82)
E/HttpOperation( 2944): 	at jcs.o(PG:406)
E/HttpOperation( 2944): 	at jcn.a(PG:1379)
E/HttpOperation( 2944): 	at jcs.i(PG:143)
E/HttpOperation( 2944): 	at hec.a(PG:42)
E/HttpOperation( 2944): 	at hee.a(PG:102)
E/HttpOperation( 2944): 	at czr.a(PG:65)
E/HttpOperation( 2944): 	at kka.a(PG:108)
E/HttpOperation( 2944): 	at czp.a(PG:19176)
E/HttpOperation( 2944): 	at czp.a(PG:9081)
E/HttpOperation( 2944): 	at czq.run(PG:1686)
E/HttpOperation( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2944): 	at jdj.a(PG:4091)
E/HttpOperation( 2944): 	at jdj.a(PG:1125)
E/HttpOperation( 2944): 	at jdm.a(PG:77)
E/HttpOperation( 2944): 	... 15 more
E/HttpOperation( 2944): Caused by: faj: BadAuthentication
E/HttpOperation( 2944): 	at fal.a(PG:38)
E/HttpOperation( 2944): 	at jdj.a(PG:4089)
E/HttpOperation( 2944): 	... 17 more
E/ExperimentLoader( 2944): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2944): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2944): 	at jdm.a(PG:82)
E/ExperimentLoader( 2944): 	at jcs.o(PG:406)
E/ExperimentLoader( 2944): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2944): 	at jcs.i(PG:143)
E/ExperimentLoader( 2944): 	at hec.a(PG:42)
E/ExperimentLoader( 2944): 	at hee.a(PG:102)
E/ExperimentLoader( 2944): 	at czr.a(PG:65)
E/ExperimentLoader( 2944): 	at kka.a(PG:108)
E/ExperimentLoader( 2944): 	at czp.a(PG:19176)
E/ExperimentLoader( 2944): 	at czp.a(PG:9081)
E/ExperimentLoader( 2944): 	at czq.run(PG:1686)
E/ExperimentLoader( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2944): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2944): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2944): 	at jdm.a(PG:77)
E/ExperimentLoader( 2944): 	... 15 more
E/ExperimentLoader( 2944): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2944): 	at fal.a(PG:38)
E/ExperimentLoader( 2944): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2944): 	... 17 more
,I/BooksConfig( 3469): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 144648, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3469): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3469): Soft error
E/BooksSync( 3469): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3469): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3469): Sync error
E/BooksSync( 3469): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3469): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3469): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 177460, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3247): [333] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3247): [333] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3247): [333] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
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
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3763): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3763): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3763): [1] 5.onFinished: Scheduling replication attempt 5.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1228): run()
I/Keyboard.Facilitator( 1228): flushDynamicLanguageModels()
,I/ConfigService( 1482): onCreate
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3763): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3763): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3763): [1] 5.onFinished: Giving up after 6 failures.
,I/ConfigService( 1482): onDestroy
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2944): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2944): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2944): 	at jdm.a(PG:82)
E/HttpOperation( 2944): 	at jcs.o(PG:406)
E/HttpOperation( 2944): 	at jcn.a(PG:1379)
E/HttpOperation( 2944): 	at jcs.i(PG:143)
E/HttpOperation( 2944): 	at blb.a(PG:3937)
E/HttpOperation( 2944): 	at czp.a(PG:18188)
E/HttpOperation( 2944): 	at czp.a(PG:9081)
E/HttpOperation( 2944): 	at czq.run(PG:1686)
E/HttpOperation( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2944): 	at jdj.a(PG:4091)
E/HttpOperation( 2944): 	at jdj.a(PG:1125)
E/HttpOperation( 2944): 	at jdm.a(PG:77)
E/HttpOperation( 2944): 	... 12 more
E/HttpOperation( 2944): Caused by: faj: BadAuthentication
E/HttpOperation( 2944): 	at fal.a(PG:38)
E/HttpOperation( 2944): 	at jdj.a(PG:4089)
E/HttpOperation( 2944): 	... 14 more
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2944): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2944): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2944): 	at jdm.a(PG:82)
E/HttpOperation( 2944): 	at jcs.o(PG:406)
E/HttpOperation( 2944): 	at jcn.a(PG:1379)
E/HttpOperation( 2944): 	at jcs.i(PG:143)
E/HttpOperation( 2944): 	at hec.a(PG:42)
E/HttpOperation( 2944): 	at hee.a(PG:102)
E/HttpOperation( 2944): 	at czr.a(PG:65)
E/HttpOperation( 2944): 	at kka.a(PG:108)
E/HttpOperation( 2944): 	at czp.a(PG:19176)
E/HttpOperation( 2944): 	at czp.a(PG:9081)
E/HttpOperation( 2944): 	at czq.run(PG:1686)
E/HttpOperation( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2944): 	at jdj.a(PG:4091)
E/HttpOperation( 2944): 	at jdj.a(PG:1125)
E/HttpOperation( 2944): 	at jdm.a(PG:77)
E/HttpOperation( 2944): 	... 15 more
E/HttpOperation( 2944): Caused by: faj: BadAuthentication
E/HttpOperation( 2944): 	at fal.a(PG:38)
E/HttpOperation( 2944): 	at jdj.a(PG:4089)
E/HttpOperation( 2944): 	... 17 more
,E/ExperimentLoader( 2944): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2944): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2944): 	at jdm.a(PG:82)
E/ExperimentLoader( 2944): 	at jcs.o(PG:406)
E/ExperimentLoader( 2944): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2944): 	at jcs.i(PG:143)
E/ExperimentLoader( 2944): 	at hec.a(PG:42)
E/ExperimentLoader( 2944): 	at hee.a(PG:102),
E/ExperimentLoader( 2944): 	at czr.a(PG:65)
E/ExperimentLoader( 2944): 	at kka.a(PG:108)
E/ExperimentLoader( 2944): 	at czp.a(PG:19176)
E/ExperimentLoader( 2944): 	at czp.a(PG:9081)
E/ExperimentLoader( 2944): 	at czq.run(PG:1686)
E/ExperimentLoader( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2944): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2944): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2944): 	at jdm.a(PG:77)
E/ExperimentLoader( 2944): 	... 15 more
E/ExperimentLoader( 2944): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2944): 	at fal.a(PG:38)
E/ExperimentLoader( 2944): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2944): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 235231, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3247): [334] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  821): Explicit concurrent mark sweep GC freed 33290(1452KB) AllocSpace objects, 9(615KB) LOS objects, 32% free, 33MB/49MB, paused 2.955ms total 72.092ms
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3247): [334] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3247): [334] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
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
,I/BooksSync( 3469): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3469): GmsCore Version = 7.8.99 (2134222-430)
,V/KeepSync( 3291): Connecting to GoogleApiClient
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 48580(2MB) AllocSpace objects, 10(1015KB) LOS objects, 37% free, 27MB/43MB, paused 1.268ms total 38.454ms
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3291): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3469): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3469): Soft error
E/BooksSync( 3469): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3469): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3469): Sync error
E/BooksSync( 3469): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3469): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3469): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 268693, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,W/KeepSync( 3291): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 265438, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2944): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2944): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2944): 	at jdm.a(PG:82)
E/HttpOperation( 2944): 	at jcs.o(PG:406)
E/HttpOperation( 2944): 	at jcn.a(PG:1379)
E/HttpOperation( 2944): 	at jcs.i(PG:143)
E/HttpOperation( 2944): 	at blb.a(PG:3937)
E/HttpOperation( 2944): 	at czp.a(PG:18188)
E/HttpOperation( 2944): 	at czp.a(PG:9081)
E/HttpOperation( 2944): 	at czq.run(PG:1686)
E/HttpOperation( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2944): 	at jdj.a(PG:4091)
E/HttpOperation( 2944): 	at jdj.a(PG:1125)
E/HttpOperation( 2944): 	at jdm.a(PG:77)
E/HttpOperation( 2944): 	... 12 more
E/HttpOperation( 2944): Caused by: faj: BadAuthentication
E/HttpOperation( 2944): 	at fal.a(PG:38)
E/HttpOperation( 2944): 	at jdj.a(PG:4089)
E/HttpOperation( 2944): 	... 14 more
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2944): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2944): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2944): 	at jdm.a(PG:82)
E/HttpOperation( 2944): 	at jcs.o(PG:406)
E/HttpOperation( 2944): 	at jcn.a(PG:1379)
E/HttpOperation( 2944): 	at jcs.i(PG:143)
E/HttpOperation( 2944): 	at hec.a(PG:42)
E/HttpOperation( 2944): 	at hee.a(PG:102)
E/HttpOperation( 2944): 	at czr.a(PG:65)
E/HttpOperation( 2944): 	at kka.a(PG:108)
E/HttpOperation( 2944): 	at czp.a(PG:19176)
E/HttpOperation( 2944): 	at czp.a(PG:9081)
E/HttpOperation( 2944): 	at czq.run(PG:1686)
E/HttpOperation( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2944): 	at jdj.a(PG:4091)
E/HttpOperation( 2944): 	at jdj.a(PG:1125)
E/HttpOperation( 2944): 	at jdm.a(PG:77)
E/HttpOperation( 2944): 	... 15 more
E/HttpOperation( 2944): Caused by: faj: BadAuthentication
E/HttpOperation( 2944): 	at fal.a(PG:38)
E/HttpOperation( 2944): 	at jdj.a(PG:4089)
E/HttpOperation( 2944): 	... 17 more
,E/ExperimentLoader( 2944): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2944): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2944): 	at jdm.a(PG:82)
,E/ExperimentLoader( 2944): 	at jcs.o(PG:406)
E/ExperimentLoader( 2944): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2944): 	at jcs.i(PG:143)
E/ExperimentLoader( 2944): 	at hec.a(PG:42)
E/ExperimentLoader( 2944): 	at hee.a(PG:102)
E/ExperimentLoader( 2944): ,	at czr.a(PG:65)
E/ExperimentLoader( 2944): 	at kka.a(PG:108)
E/ExperimentLoader( 2944): 	at czp.a(PG:19176)
E/ExperimentLoader( 2944): 	at czp.a(PG:9081)
E/ExperimentLoader( 2944): 	at czq.run(PG:1686),
E/ExperimentLoader( 2944): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2944): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2944): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2944): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ExperimentLoader( 2944): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2944): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2944): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2944): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2944): 	at jdm.a(PG:77)
,E/ExperimentLoader( 2944): 	... 15 more
E/ExperimentLoader( 2944): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2944): 	at fal.a(PG:38)
E/ExperimentLoader( 2944): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2944): 	... 17 more,
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 325789, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3247): [335] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3247): [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3247): [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
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
,V/KeepSync( 3291): Connecting to GoogleApiClient
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3291): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3291): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,E/KeepSync( 3291): 	... 10 more
W/KeepSync( 3291): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 416204, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3229): Disconnected process message: 10, size: 0
,I/jxcore-log( 3172): Toggling radios to false
I/jxcore-log( 3172): 
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@310a5751 mBinding = false
,D/BluetoothManagerService(  821): Message: 2
,D/WifiService(  821): setWifiEnabled: false pid=3172, uid=10265
,E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService(  821): Sending off request.
D/BluetoothAdapterState( 3229): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3229): Setting state to 13
,I/BluetoothAdapterState( 3229): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3229): onBluetoothDisable()
I/BluetoothAdapterState( 3229): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  821): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3229): onReceive
,D/BluetoothMapService( 3229): STATE_TURNING_OFF
D/BluetoothMapService( 3229): MAP Service closeService in
D/BluetoothMapMasInstance( 3229): MAP Service shutdown
,V/BluetoothMapMasInstance( 3229): Accept exception: (expected at shutdown),
V/BluetoothMapMasInstance( 3229): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3229): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3229): 	,at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489),
V/BluetoothMapMasInstance( 3229): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3229): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3229): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
,V/BluetoothMapMasInstance( 3229): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
I/BtOppRfcommListener( 3229): stopping Accept Thread
E/BtOppRfcommListener( 3229): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 3229): BluetoothSocket listen thread finished
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3172): Radios toggled
I/jxcore-log( 3172): 
E/native  (  821): do suspend true
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1482): Read error: ssl=0xaec39000: I/O error during system call, Connection timed out
,V/NativeCrypto( 1482): SSL shutdown failed: ssl=0xaec39000: I/O error during system call, Broken pipe
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
I/ActivityManager(  821): Start proc 3951:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/BluetoothAdapterProperties( 3229): Scan Mode:20
D/BluetoothAdapterState( 3229): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
W/bt-btif ( 3229): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3229): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3229): L2CAP - PSM: 0x0017 not found for deregistration
D/btif_config_util( 3229): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  821): scanCount==0 - aborting
,D/WifiScanningService(  821): SCAN_AVAILABLE : 1
D/RttService(  821): SCAN_AVAILABLE : 1
D/WifiScanningService(  821): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  821): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState
,D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
E/native  (  821): do suspend true
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  821): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524292
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  821): MasterInitialState.processMessage what=3
,D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@134c178d:true
,D/PhoneInterfaceManager( 1273): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1273): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,I/wpa_supplicant( 3234): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  821): Start proc 3975:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
I/wpa_supplicant( 3234): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/art     (  821): Explicit concurrent mark sweep GC freed 41428(1836KB) AllocSpace objects, 7(300KB) LOS objects, 32% free, 33MB/49MB, paused 1.662ms total 52.894ms
,E/GpsLocationProvider(  821): No APN found to select.
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3951): Adding local MAP profile
,D/BluetoothMap( 3951): Create BluetoothMap proxy object
D/BluetoothManagerService(  821): Message: 30
,D/PhoneInterfaceManager( 1273): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1273): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3951): LocalBluetoothProfileManager construction complete
,E/GpsLocationProvider(  821): No APN found to select.
,D/DockEventReceiver( 3951): finishStartingService: stopping service
,D/BluetoothInputDevice( 3951): Proxy object connected
D/HidProfile( 3951): Bluetooth service connected
,D/BluetoothPan( 3951): BluetoothPAN Proxy object connected
D/PanProfile( 3951): Bluetooth service connected
D/BluetoothMap( 3951): Proxy object connected
D/MapProfile( 3951): Bluetooth service connected
,D/BluetoothMap( 3951): getConnectedDevices(),
D/BluetoothMap( 3951): Bluetooth is Not enabled
,I/ActivityManager(  821): Killing 1511:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/bt_userial( 3229): RX termination
W/bt_userial( 3229): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3229): Leaving userial_read_thread()
,W/bt-btif ( 3229): ag scb idx 1 not allocated
E/bt-btif ( 3229): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3229): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3229): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3229): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3229): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3229): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3229): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3229): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3229): hw_epilog_process
,I/bt_userial_vendor( 3229): device fd = 53 close
,D/WifiService(  821): Client connection lost with reason: 4
,I/wpa_supplicant( 3234): wlan0: CTRL-EVENT-TERMINATING 
,I/GKI_LINUX( 3229): gki_task task_id=0 [BTU] terminating
D/Tethering(  821): InitialState.processMessage what=4
E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/GKI_LINUX( 3229): GKI_exit_task 0 done,
I/GKI_LINUX( 3229): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3229): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3229): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 3229): Exit Disconnected: -1,
D/BluetoothHeadset(  821): Proxy object disconnected
,D/BluetoothHeadset(  821): Proxy object disconnected
D/BluetoothHeadset( 1273): Proxy object disconnected
D/A2dpService( 3229): Received stop request...Stopping profile...
D/A2dpStateMachine( 3229): Exit Disconnected: -1
D/BluetoothHeadset( 1062): Proxy object disconnected
D/Tethering(  821): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothHeadset(  821): Proxy object disconnected
D/BluetoothAdapterState( 3229): Stopping profile services that were post enabled
,D/BluetoothA2dp( 1062): Proxy object disconnected
D/BluetoothA2dp(  821): Proxy object disconnected
D/HidService( 3229): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 1062): Proxy object disconnected
,D/BluetoothInputDevice( 3951): Proxy object disconnected
D/HidProfile( 3951): Bluetooth service disconnected
,D/HealthService( 3229): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 3229): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3229): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3229): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 3229): Received stop request...Stopping profile...
,D/BluetoothPan( 1062): BluetoothPAN Proxy object disconnected
,D/BtGatt.DebugUtils( 3229): handleDebugAction() action=null
D/BluetoothPan( 3951): BluetoothPAN Proxy object disconnected
,D/BtGatt.GattService( 3229): Received stop request...Stopping profile...
D/BtGatt.GattService( 3229): stop()
,D/BtGatt.AdvertiseManager( 3229): advertise clients cleared
D/PanProfile( 3951): Bluetooth service disconnected
,I/GKI_LINUX( 3229): gki_task task_id=2 [A2DP-MEDIA] terminating,
I/GKI_LINUX( 3229): GKI_exit_task 2 done,
I/GKI_LINUX( 3229): GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothMapService( 3229): Received stop request...Stopping profile...
D/BluetoothMapService( 3229): stop(),
D/BluetoothMapEmailAppObserver( 3229): deinitObservers()
D/BluetoothMapEmailAppObserver( 3229): removeReceiver()
,D/BluetoothMap( 1062): Proxy object disconnected
W/BluetoothHidServiceJni( 3229): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3229): cleanup: HH disabling or disabled already, status = 0,
W/BluetoothHidServiceJni( 3229): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3229): Cleaning up Bluetooth Health Interface...
,D/BluetoothMap( 3951): Proxy object disconnected
D/MapProfile( 3951): Bluetooth service disconnected
W/BluetoothHealthServiceJni( 3229): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 3229): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3229): Cleaning up Bluetooth PAN callback object
,D/BluetoothMapService( 3229): MAP Service closeService in
D/BluetoothAdapterState( 3229): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 3229): Setting state to 10
I/BluetoothAdapterState( 3229): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 3229): cleanup(),
D/BluetoothMapService( 3229): MAP Service closeService in
D/BluetoothManagerService(  821): Message: 60
,D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
I/BluetoothAdapterState( 3229): Entering OffState
D/BluetoothManagerService(  821): Broadcasting onBluetoothStateChange(false) to 17 receivers.
,D/BluetoothInputDevice( 3951): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1062): onBluetoothStateChange: up=false
D/BluetoothA2dp(  821): onBluetoothStateChange: up=false,
D/BluetoothHeadsetClient( 1062): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1062): 
E/BluetoothHeadsetClient( 1062): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@399a4934,
E/BluetoothHeadsetClient( 1062): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1062): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1062): 	,at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1062): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1062): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
,E/BluetoothHeadsetClient( 1062): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset(  821): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 1062): onBluetoothStateChange: up=false,
D/BluetoothA2dp( 1062): onBluetoothStateChange: up=false
D/BluetoothHeadset(  821): onBluetoothStateChange: up=false
,D/BluetoothAvrcpController( 1062): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1062): 
E/BluetoothAvrcpController( 1062): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@1b37335d
E/BluetoothAvrcpController( 1062): ,	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1062): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1062): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551),
E/BluetoothAvrcpController( 1062): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1062): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1062): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothMap( 3951): onBluetoothStateChange: up=false
D/BluetoothHeadset(  821): onBluetoothStateChange: up=false
D/BluetoothA2dpSink( 1062): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1062): 
E/BluetoothA2dpSink( 1062): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@3f1564d2
E/BluetoothA2dpSink( 1062): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1062): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1062): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1062): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1062): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1062): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothPbap( 3951): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1273): onBluetoothStateChange: up=false
D/BluetoothMap( 1062): onBluetoothStateChange: up=false
D/BluetoothManagerService(  821): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  821): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService(  821): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@310a5751 mBinding = false
D/BluetoothManagerService(  821): Sending unbind request.
D/BluetoothManagerService(  821): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1062): 150053355: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1062): 150053355: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1062): 150053355: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3229): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3229): GKI_exit_task 1 done
I/GKI_LINUX( 3229): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 3229): cleanupNative: return from cleanup
,I/art     ( 3229): System.exit called, status: 0
I/AndroidRuntime( 3229): VM exiting with result code 0, cleanup skipped.
,W/Settings( 2625): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1747): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  821): Process com.android.bluetooth (pid 3229) has died
,D/StrictMode( 3975): StrictMode policy violation; ~duration=355 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3975): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3975): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3975): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3975): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3975): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3975): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3975): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3975): StrictMode policy violation; ~duration=355 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3975): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3975): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3975): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3975): StrictMode policy violation; ~duration=333 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3975): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3975): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3975): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3975): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3975): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3975): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3975): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3975): StrictMode policy violation; ~duration=284 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3975): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3975): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3975): StrictMode policy violation; ~duration=276 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3975): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3975): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3975): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3975): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3975): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3975): StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3975): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3975): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3975): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3975): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3975): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3975): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3975): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3975): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3975): # via Binder call with stack:
D/StrictMode( 3975): android.os.StrictMode$LogStackTrace
D/StrictMode( 3975): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3975): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3975): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3975): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3975): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3975): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3975): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3975): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3975): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3975): StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3975): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3975): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3975): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3975): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3975): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3975): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3975): StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3975): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3975): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3975): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3975): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3975): StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3975): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3975): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3975): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3975): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3975): StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3975): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3975): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3975): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3975): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3975): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3975): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3975): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3975): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3975): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3975): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3975): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3975): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3975): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3975): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3975): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3975): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3975): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3975): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3975): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3975): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,W/com.google.a.a.a.b.a( 3975): Application name is not set. Call Builder#setApplicationName.
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38e4efb5:true
,I/ActivityManager(  821): Killing 3661:com.qualcomm.timeservice/1000 (adj 15): empty #17,
,D/AuthorizationBluetoothService( 1482): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,V/MusicLeanback( 3412): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  821): Start proc 4004:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/SprintDMReceiver( 4004): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4004): simOperator:  IMSI: null,
D/SprintDMReceiver( 4004): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1775): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1775): onCreate
,D/SystemUpdateService( 1775): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1775): active receiver: enabled
,I/SystemUpdateService( 1775): showing system update notification
,I/iu.Environment( 1775): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*,
,I/iu.UploadsManager( 1775): num queued entries: 0
I/iu.UploadsManager( 1775): num updated entries: 0
,I/iu.SyncManager( 1775): NEXT; no task
,D/ChimeraCfgMgr( 1775): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1775): retry (wakeup: false) in 3599944 ms
,D/SystemUpdateService( 1775): onDestroy
,I/Babel   ( 2625): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  821): Start proc 4024:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/ActivityManager(  821): Killing 3602:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/GAv4    ( 4024): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4024):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4024):   adb logcat -s GAv4
,W/GAv4    ( 4024): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4024): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4024): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 4024): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4024): Time to load native libraries: 4 ms (timestamps 4642-4646)
,I/LibraryLoader( 4024): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4024): Binding Chromium to main looper Looper (main, tid 1) {10d83119}
,I/LibraryLoader( 4024): Expected native library version number "",actual native library version number ""
,I/chromium( 4024): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4024): Initializing chromium process, singleProcess=true
,W/art     ( 4024): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4024): ApplicationContext is null in ApplicationStatus
,W/chromium( 4024): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4024): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4024): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 4024): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/NSApplication( 4024): Starting up...
W/AudioManagerAndroid( 4024): Requires BLUETOOTH permission
,I/ActivityManager(  821): Killing 3619:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 4080:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,V/MusicLeanback( 3412): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  821): Killing 3639:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/SprintDMReceiver( 4004): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4004): simOperator:  IMSI: null
D/SprintDMReceiver( 4004): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1775): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1775): onCreate
,D/SystemUpdateService( 1775): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1775): active receiver: enabled
,I/SystemUpdateService( 1775): showing system update notification
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1775): retry (wakeup: false) in 3599966 ms
,D/ChimeraCfgMgr( 1775): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1775): onDestroy
,W/ContextImpl( 3951): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  821): Start proc 4101:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,D/DockEventReceiver( 3951): finishStartingService: stopping service
,W/ResourcesManager( 4101): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 4101): Adding HeadsetService
,D/AdapterServiceConfig( 4101): Adding A2dpService
,D/AdapterServiceConfig( 4101): Adding HidService
D/AdapterServiceConfig( 4101): Adding HealthService
D/AdapterServiceConfig( 4101): Adding PanService
D/AdapterServiceConfig( 4101): Adding GattService
D/AdapterServiceConfig( 4101): Adding BluetoothMapService
,I/ActivityManager(  821): Killing 3799:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1482): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
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
,E/PlayEventLogger( 3763): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3763): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3763): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3763): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3763): Ignoring header User-Agent because its value was null.
,D/ConnectivityService(  821): Failed to find a new network - expiring NetTransition Wakelock
,V/GoogleAuthProtoRequest( 3247): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3247): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3247): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
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
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 25501(1252KB) AllocSpace objects, 3(330KB) LOS objects, 32% free, 33MB/49MB, paused 2.866ms total 79.955ms
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 61535(3MB) AllocSpace objects, 9(992KB) LOS objects, 36% free, 27MB/43MB, paused 1.087ms total 34.271ms
,W/GLSActivity( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1482): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1482): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 3763): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3763): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3763): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3763): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 3763): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
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
,E/PlayEventLogger( 3763): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3763): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3763): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3763): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3763): Ignoring header User-Agent because its value was null.
,V/GoogleAuthProtoRequest( 3247): [337] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3247): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3247): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
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
,I/EventLogService( 1775): Opted in for usage reporting
I/EventLogService( 1775): Aggregate from 1449680503196 (log), 1449680503196 (data)
,W/EventLogAggregator( 1775): Unknown tag: snet_gcore
W/EventLogAggregator( 1775): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1775): dumping service [account]
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1482): ,	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1482): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1482): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 3763): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3763): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3763): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3763): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 3763): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1482): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1482): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1482): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1482): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1482): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1482): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1482): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1482): 	,at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1482): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3763): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3763): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3763): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3763): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3763): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3763): Ignoring header User-Agent because its value was null.
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 85982(3MB) AllocSpace objects, 11(1213KB) LOS objects, 36% free, 27MB/43MB, paused 1.500ms total 59.734ms
,I/ProcessStatsService(  821): Prepared write state in 10ms
,I/ProcessStatsService(  821): Prepared write state in 4ms
,I/ProcessStatsService(  821): Prepared write state in 7ms
,I/ProcessStatsService(  821): Pruning old procstats: /data/system/procstats/state-2015-12-09-03-34-43.bin
,TIME-OUT KILL (timeout was 1800000ms)
```
