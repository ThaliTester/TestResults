#### Test 51517283acd5ddf_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2702): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2702): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2702): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3188): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3188): CheckJNI is OFF
D/AndroidRuntime( 3188): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{19e8c67a token=Token{3da9f2a5 ActivityRecord{117ed89c u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
V/WindowManager(  821): Adding window Window{2ae3207 u0 Starting com.test.thalitest} at 3 of 8 (after Window{3e5bdd4a u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1511): Closing mic
I/MicrophoneInputStream( 1511): mic_close com.google.android.apps.gsa.speech.audio.u@2f1d29ca
D/AndroidRuntime( 3188): Shutting down VM
I/ActivityManager(  821): Start proc 3203:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1511): Stopping hotword detection.
I/HotwordRecognitionRnr( 1511): Hotword detection finished
W/GCoreFlp( 1752): No location to return for getLastLocation()
I/ActivityManager(  821): Killing 2661:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659147539
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  821): Killing 2792:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/WebViewFactory( 3203): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3203): Time to load native libraries: 3 ms (timestamps 2702-2705)
I/LibraryLoader( 3203): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3203): Binding Chromium to main looper Looper (main, tid 1) {105e20ea}
,I/LibraryLoader( 3203): Expected native library version number "",actual native library version number ""
,I/chromium( 3203): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3203): Initializing chromium process, singleProcess=true
W/art     ( 3203): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3203): ApplicationContext is null in ApplicationStatus
,W/chromium( 3203): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3203): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3203): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3203): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3203): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
,D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ce1aaf7:true
,D/BluetoothAdapter( 3203): 780418743: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3203): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3203): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3203): CordovaWebView is running on device made by: motorola
,W/art     ( 3203): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3203): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3203): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3203): Validating map...
,I/art     (  821): Explicit concurrent mark sweep GC freed 17561(815KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.927ms total 69.930ms
,V/WindowManager(  821): Adding window Window{241d3fe7 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{2ae3207 u0 Starting com.test.thalitest}),
,W/chromium( 3203): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3203): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3203): Enabling debug mode 0
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +905ms (total +1m50s250ms)
,I/Keyboard.Facilitator( 1212): onFinishInput()
,W/BindingManager( 3203): Cannot call determinedVisibility() - never saw a connection for the pid: 3203
,D/JsMessageQueue( 3203): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3203): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576313472
D/JX-Cordova( 3203): jxcore cordova android initializing
,I/kickstart(  870): STATUS: Received file 'm9kefs1'
I/kickstart(  870): STATUS: 950272 bytes transferred in 0.985250 seconds
I/kickstart(  870): STATUS: Successfully downloaded files from target 
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  870): STATUS: Sahara protocol completed
,W/jxcore-log( 3203): Initializing JXcore engine
W/jxcore-log( 3203): JXcore engine is ready
,W/jxcore-log( 3203): Starting JXcore engine
,W/.test.thalitest( 3203): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11676]" dev="sockfs" ino=11676 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3203): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 3203): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9842]" dev="sockfs" ino=9842 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3203): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20065]" dev="sockfs" ino=20065 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3203): Platform android
W/jxcore-log( 3203): 
W/jxcore-log( 3203): Process ARCH arm
W/jxcore-log( 3203): 
,I/jxcore-log( 3203): JXcore Cordova bridge is ready!
I/jxcore-log( 3203): 
W/jxcore-log( 3203): JXcore engine is started
,I/Choreographer( 3203): Skipped 130 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3203): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3203): Turning radios to true
I/jxcore-log( 3203): 
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  821): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  821): Message: 1
D/BluetoothManagerService(  821): MESSAGE_ENABLE: mBluetooth = null
I/jxcore-log( 3203): toggleBluetooth - 
I/jxcore-log( 3203): 
,D/WifiService(  821): setWifiEnabled: true pid=3203, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  821): New client listening to asynchronous messages
,I/jxcore-log( 3203): toggleWiFi
I/jxcore-log( 3203): 
D/SoftapController(  353): Softap fwReload - Ok
,D/CommandListener(  353): Setting iface cfg
D/CommandListener(  353): Trying to bring down wlan0
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  821): Start proc 3258:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,D/WifiMonitor(  821): startMonitoring(wlan0) with mConnected = false
E/WifiHW  (  821): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/ActivityManager(  821): Start proc 3277:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/wpa_supplicant( 3269): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3258): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3269): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  821): Start proc 3303:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  821): Killing 2824:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 209us total 9.646ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 204us total 8.983ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 195us total 8.336ms
,D/AdapterServiceConfig( 3258): Adding HeadsetService
,D/AdapterServiceConfig( 3258): Adding A2dpService
D/AdapterServiceConfig( 3258): Adding HidService
D/AdapterServiceConfig( 3258): Adding HealthService
D/AdapterServiceConfig( 3258): Adding PanService
D/AdapterServiceConfig( 3258): Adding GattService
,D/AdapterServiceConfig( 3258): Adding BluetoothMapService
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b70b818:true
D/BluetoothAdapterState( 3258): make
,I/bluedroid( 3258): init
,I/BluetoothAdapterState( 3258): Entering OffState
,I/bte_conf( 3258): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3258): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3258): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3258): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3258): get_profile_interface socket
I/bluedroid( 3258): get_profile_interface map_client
I/GKI_LINUX( 3258): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  821): Message: 40
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 3258): Address is:F8:CF:C5:D9:E5:61
I/bluedroid( 3258): config_hci_snoop_log
,D/BluetoothManagerService(  821): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  821): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6
,D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3258): Name is: Nexus 6
,D/BluetoothAdapterState( 3258): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3258): Setting state to 11
I/BluetoothAdapterState( 3258): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  821): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3258): make
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State
,I/BluetoothAdapterState( 3258): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3258): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5177fdb
,D/HeadsetService( 3258): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3258): classInitNative: succeeds
D/HeadsetStateMachine( 3258): make
,D/HeadsetStateMachine( 3258): max_hf_connections = 1
I/bluedroid( 3258): get_profile_interface handsfree
D/HeadsetStateMachine( 3258): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3258): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5177fdb
,D/BluetoothA2dp(  821): Proxy object connected
D/BluetoothA2dp( 1062): Proxy object connected
D/A2dpService( 3258): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3258): classInitNative: succeeds
,I/bluedroid( 3258): get_profile_interface avrcp
,E/RemoteController( 3258): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 3258): classInitNative: succeeds
D/A2dpStateMachine( 3258): make
,I/bluedroid( 3258): get_profile_interface a2dp
I/GKI_LINUX( 3258): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3258): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3258): classInitNative: succeeds
,D/BluetoothAdapterService( 3258): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5177fdb
,D/BluetoothInputDevice( 1062): Proxy object connected
D/HidService( 3258): Received start request. Starting profile...
I/bluedroid( 3258): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3258): classInitNative: succeeds
,D/BluetoothAdapterService( 3258): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5177fdb
,D/HealthService( 3258): Received start request. Starting profile...
I/bluedroid( 3258): get_profile_interface health
I/BluetoothPanServiceJni( 3258): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3258): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5177fdb
D/BluetoothPan( 1062): BluetoothPAN Proxy object connected
,D/PanService( 3258): Received start request. Starting profile...,
D/BluetoothPanServiceJni( 3258): initializeNative(L110): pan
I/bluedroid( 3258): get_profile_interface pan
,I/BtGatt.JNI( 3258): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3258): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5177fdb
D/BtGatt.DebugUtils( 3258): handleDebugAction() action=null
D/BtGatt.GattService( 3258): Received start request. Starting profile...,
D/BtGatt.GattService( 3258): start()
I/bluedroid( 3258): get_profile_interface gatt
D/BluetoothAdapterService( 3258): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5177fdb,
D/BtGatt.AdvertiseManager( 3258): advertise manager created
,D/BluetoothAdapterService( 3258): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5177fdb
,D/BluetoothMap( 1062): Proxy object connected
,D/BluetoothMapService( 3258): Received start request. Starting profile...
D/BluetoothMapService( 3258): start()
,D/BluetoothMapEmailSettingsLoader( 3258): Found 0 applications
D/BluetoothMapEmailAppObserver( 3258): createReceiver()
,D/BluetoothMapEmailAppObserver( 3258): initObservers()
D/BluetoothMapEmailAppObserver( 3258): getEnabledAccountItems()
D/HeadsetStateMachine( 3258): Proxy object connected
D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3258): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3258): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3258): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3258): enable
,I/bt_hci_bdroid( 3258): init
I/GKI_LINUX( 3258): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3258): btu_task pending for preload complete event
,I/bt_vendor( 3258): init
I/bt_vnd_conf( 3258): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3258): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3258): userial_init
,I/bt_userial_vendor( 3258): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3258): device fd = 53 open
D/bt_userial( 3258): Entering userial_read_thread()
,I/ActivityManager(  821): Start proc 3345:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  821): Killing 2760:com.google.android.gm/u0a78 (adj 15): empty #17
,I/bt_hwcfg( 3258): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3258): Chipset BCM4354A2
D/bt_hwcfg( 3258): Target name = [BCM4354A2]
I/bt_hwcfg( 3258): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,D/Tethering(  821): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  821): Killing 2359:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3362:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/wpa_supplicant( 3269): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant( 3269): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  821): Loading config and enabling all networks 
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@22aac890}
,I/bt_hwcfg( 3258): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3258): Settlement delay -- 100 ms
I/bt_hwcfg( 3258): Setting fw settlement delay to 100 
,E/WifiConfigStore(  821): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  821): Setting external_sim to 1
W/Settings( 2632): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  821): Setting OUI to 92-68-C3
I/WifiNative-HAL(  821): startHal
D/wifi    (  821): setting scan oui 0xaee03568
D/WifiHAL (  821): Sending mac address OUI
,E/WifiStateMachine(  821): cancelDelayedScan -> 1
,W/CommandListener(  353): Failed to retrieve HW addr for p2p0 (No such device)
,D/WifiScanningService(  821): SCAN_AVAILABLE : 3
D/RttService(  821): SCAN_AVAILABLE : 3
D/RttService(  821): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  821): startHal
D/CommandListener(  353): Setting iface cfg
D/wifi    (  821): getting scan capabilities on interface[0] = 0xaee03568
D/WifiHAL (  821): Creating message to get scan capablities; iface = 5
D/WifiHAL (  821): In GetCapabilities::handleResponse
D/WifiHAL (  821): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  821): StartedState
E/WifiP2pService(  821): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  821): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 3269): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  821): p2pGetDeviceAddress
,D/WifiNative-HAL(  821): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,E/native  (  821): do suspend false
,I/bt_hwcfg( 3258): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg( 3258): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3258): vendor lib fwcfg completed
,I/bt-btu  ( 3258): btu_task received preload complete event
,I/        ( 3258): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3258): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3258): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3258): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3258): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3258): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3258): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3258): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3258): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3258): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3258): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3258): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3258): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3258): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3258): BTE_InitTraceLevels -- TRC_BTIF
,D/StrictMode( 3362): StrictMode policy violation; ~duration=229 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3362): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3362): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3362): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3362): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3362): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3362): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3362): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3362): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3362): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3362): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3362): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3362): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3362): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3362): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3362): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3362): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3362): StrictMode policy violation; ~duration=229 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3362): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3362): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3362): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3362): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3362): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3362): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3362): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3362): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3362): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3362): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3362): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3362): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3362): StrictMode policy violation; ~duration=227 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3362): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3362): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3362): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3362): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3362): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3362): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3362): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3362): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3362): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3362): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3362): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3362): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3362): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3362): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3362): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3362): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3362): StrictMode policy violation; ~duration=221 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3362): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3362): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3362): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3362): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3362): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3362): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3362): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3362): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3362): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3362): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3362): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3362): StrictMode policy violation; ~duration=209 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3362): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3362): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3362): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3362): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3362): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3362): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3362): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3362): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3362): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3362): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3362): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3362): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3362): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3362): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3362): StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3362): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137),
D/StrictMode( 3362): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3362): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3362): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3362): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3362): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3362): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3362): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3362): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3362): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3362): # via Binder call with stack:
D/StrictMode( 3362): android.os.StrictMode$LogStackTrace
D/StrictMode( 3362): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3362): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3362): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3362): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3362): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3362): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3362): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3362): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3362): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3362): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3362): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3362): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3362): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3362): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3362): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3362): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3362): StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3362): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3362): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3362): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3362): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3362): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3362): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3362): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3362): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3362): 	at com.google.android.apps.g,mm.shared.c.h.a(PG:149)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3362): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3362): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3362): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3362): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3362): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3362): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3362): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3362): StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3362): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3362): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3362): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3362): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3362): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3362): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3362): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3362): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3362): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3362): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3362): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3362): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3362): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3362): StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3362): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3362): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3362): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3362): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3362): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3362): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3362): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3362): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3362): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3362): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3362): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3362): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3362): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3362): StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3362): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3362): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3362): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3362): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3362): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3362): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3362): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3362): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3362): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3362): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3362): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3362): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3362): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3362): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3362): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3362): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3362): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3362): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3362): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3362): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3362): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3362): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 3362): Application name is not set. Call Builder#setApplicationName.
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e2719a8:true
,I/ActivityManager(  821): Killing 2863:com.google.android.music:main/u0a66 (adj 15): empty #17
E/bt-btm  ( 3258): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e6a085 
E/bt-btm  ( 3258): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e6a085 
,D/BluetoothAdapterProperties( 3258): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3258): Calling BTA_HhEnable
E/bt-btif ( 3258): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3258): Address is:F8:CF:C5:D9:E5:61
,W/bt-btm  ( 3258): Stopping oneshot timer
,D/AuthorizationBluetoothService( 1485): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapterProperties( 3258): Name is: Nexus 6
,D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
,D/BluetoothAdapterProperties( 3258): Scan Mode:20
D/BluetoothAdapterProperties( 3258): Discoverable Timeout:120
,D/bte_conf( 3258): Device ID record 1 : primary
D/bte_conf( 3258):   vendorId            = 000f
D/bte_conf( 3258):   vendorIdSource      = 0001
D/bte_conf( 3258):   product             = 1200
D/bte_conf( 3258):   version             = 1436
D/bte_conf( 3258):   clientExecutableURL = 
D/bte_conf( 3258):   serviceDescription  = 
D/bte_conf( 3258):   documentationURL    = 
D/bte_conf( 3258): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3258): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3258): ScanMode =  20
D/BluetoothAdapterProperties( 3258): State =  11
D/BluetoothPanServiceJni( 3258): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 3258): Setting state to 12
I/BluetoothAdapterState( 3258): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  821): Broadcasting onBluetoothStateChange(true) to 13 receivers.
I/BluetoothAdapterState( 3258): Entering On State
D/BluetoothAdapterProperties( 3258): Scan Mode:21
D/BluetoothAdapterProperties( 3258): Discoverable Timeout:120
D/BluetoothHeadset( 1278): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  821): Creating new ProfileServiceConnections object for profile: 1
,D/BluetoothAvrcpController( 1062): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1062): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothPan( 1062): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothMap( 1062): onBluetoothStateChange: up=true
,D/BluetoothA2dpSink( 1062): onBluetoothStateChange: up=true
,E/BluetoothA2dpSink( 1062): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
,D/BluetoothHeadsetClient( 1062): onBluetoothStateChange: up=true
E/BluetoothHeadsetClient( 1062): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothInputDevice( 1062): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 1062): onBluetoothStateChange: up=true
D/BluetoothA2dp(  821): onBluetoothStateChange: up=true
D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1062): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  821): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  821): Message: 40
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3258): onReceive
D/BluetoothMapService( 3258): STATE_ON
D/BluetoothMapMasInstance( 3258): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 3258): MAS initSocket()
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3258): getBluetoothService() called with no BluetoothManagerCallback
,E/bt_h4   ( 3258): vendor lib postload completed
,D/BluetoothMapMasInstance( 3258): Accepting socket connection...
W/ContextImpl( 3345): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4d6e44a:true
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/AuthorizationBluetoothService( 1485): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/BluetoothAdapter( 3258): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3258): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3258): Accept thread started.
,D/LocalBluetoothProfileManager( 3345): Adding local A2DP profile
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3345): Adding local HEADSET profile
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3345): Adding local MAP profile
D/BluetoothMap( 3345): Create BluetoothMap proxy object
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3345): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3345): finishStartingService: stopping service
,D/BluetoothA2dp( 3345): Proxy object connected
,D/A2dpProfile( 3345): Bluetooth service connected
,D/BluetoothInputDevice( 3345): Proxy object connected
D/HidProfile( 3345): Bluetooth service connected
,D/BluetoothPan( 3345): BluetoothPAN Proxy object connected
,D/PanProfile( 3345): Bluetooth service connected
D/BluetoothMap( 3345): Proxy object connected
,D/MapProfile( 3345): Bluetooth service connected
D/BluetoothMap( 3345): getConnectedDevices()
,D/BluetoothPbap( 3345): Proxy object connected
D/PbapServerProfile( 3345): Bluetooth service connected
,D/BluetoothManagerService(  821): Message: 400,
D/BluetoothHeadset( 1278): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset(  821): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 1062): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 3345): Proxy object connected
D/HeadsetProfile( 3345): Bluetooth service connected
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3203): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): my name is : motorola-Nexus 6_PT7032
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): attempting to connect to test coordinator
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): check test folder
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found test : ./testFindPeers.js
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found test : ./testReConnect.js
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found test : ./testSendData.js
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Test app app.js loaded
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): LogCallback not set !!!!
I/jxcore-log( 3203): ,
I/Choreographer( 3203): Skipped 136 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3203): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3269): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  821):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  821):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  821): will read network variables netId=0
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,I/wpa_supplicant( 3269): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3269): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/wpa_supplicant( 3269): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3269): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  353): Setting iface cfg,
,E/WifiStateMachine(  821): Start Dhcp Watchdog 1
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
,E/WifiStateMachine(  821):  my bss beacon rx: 1
E/WifiStateMachine(  821):  RSSI mgmt: -46
E/WifiStateMachine(  821):  BE :  rx=0 tx=2 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 0 tx_time=59 rx_time=79 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 3407): version 5.5.6 starting
,I/dhcpcd  ( 3407): wlan0: rebinding lease of 192.168.1.110
,I/dhcpcd  ( 3407): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 3407): wlan0: leased 192.168.1.110 for 86400 seconds
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 100
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  821): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  821): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,V/BackupManagerService(  821): Scheduling immediate backup pass
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,I/ActivityManager(  821): Start proc 3445:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,V/BackupManagerService(  821): Running a backup pass
,V/BackupManagerService(  821): clearing pending backups
,V/PerformBackupTask(  821): Beginning backup of 14 targets
,D/PerformBackupTask(  821): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  821): doBackup() invoked
,I/PMBA    (  821): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/AlarmManagerService(  821): Setting time of day to sec=1448293141
W/AlarmManagerService(  821): Unable to set rtc to 1448293141: Invalid argument
,E/GpsLocationProvider(  821): No APN found to select.
,I/BackupRestoreController(  821): Getting widget state for user: 0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 23 Nov 2015 15:39:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448293142002], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448293141990]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
,W/GmsBackupTransport( 1752): Unknown package in backup request: @pm@
V/GmsBackupTransport( 1752): starting performBackup for @pm@
,V/GmsBackupTransport( 1752): performBackup done for @pm@
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicStore( 3445): Database version: 120
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GpsLocationProvider(  821): NTP server returned: 1448293141958 (Mon Nov 23 16:39:01 GMT+01:00 2015) reference: 151518 certainty: 9 system time offset: -121
,W/GLSActivity( 1485): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1485): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1485): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1485): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1485): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1485): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1485): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/BackupManagerService(  821): Now staging backup of com.google.android.talk
,D/BackupManagerService(  821): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  821): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  821): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  821): Now staging backup of com.google.android.gm
,D/BackupManagerService(  821): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  821): Now staging backup of com.android.nfc
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 10717(562KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 959us total 28.224ms
,D/BackupManagerService(  821): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  821): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  821): Now staging backup of com.google.android.inputmethod.latin
,I/art     (  821): Explicit concurrent mark sweep GC freed 48975(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 2.671ms total 95.251ms
,D/BackupManagerService(  821): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  821): Now staging backup of com.android.vending
,D/BackupManagerService(  821): Now staging backup of android
,D/BackupManagerService(  821): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1752): Next backup will happen in 43199895 millis.
,I/BackupManagerService(  821): Backup pass finished.
,W/DriveInitializer( 1781): Background init thread started
,W/ResourcesManager( 3445): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3445): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Auth.Api.Credentials( 1781): [CredentialSyncAdapter] Unknown sync event.
,W/DriveInitializer( 1781): Awaiting to be initialized
,V/JNIHelp ( 3445): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3445): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3445): GMSCore installation verified
,I/ConfigStore( 3445): Config Database version: 1
,W/DriveInitializer( 1781): Background init thread ended
,I/MediaRouter( 3445): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=true
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at blb.a(PG:3937)
E/HttpOperation( 2971): 	at czp.a(PG:18188)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 12 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 14 more
,I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=true
,V/KeepSync( 3303): Connecting to GoogleApiClient
,I/ActivityManager(  821): Start proc 3504:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GHttpClientFactory( 3445): Using our fixed implementation of GMSCore's GoogleHttpClient
E/HttpOperation( 2971): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at hec.a(PG:42)
E/HttpOperation( 2971): 	at hee.a(PG:102)
E/HttpOperation( 2971): 	at czr.a(PG:65)
E/HttpOperation( 2971): 	at kka.a(PG:108)
E/HttpOperation( 2971): 	at czp.a(PG:19176)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 15 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 17 more
,E/ExperimentLoader( 2971): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): 	at jdm.a(PG:82)
E/ExperimentLoader( 2971): 	at jcs.o(PG:406)
E/ExperimentLoader( 2971): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2971): 	at jcs.i(PG:143)
E/ExperimentLoader( 2971): 	at hec.a(PG:42)
E/ExperimentLoader( 2971): 	at hee.a(PG:102)
E/ExperimentLoader( 2971): 	at czr.a(PG:65)
E/ExperimentLoader( 2971): 	at kka.a(PG:108)
E/ExperimentLoader( 2971): 	at czp.a(PG:19176)
E/ExperimentLoader( 2971): 	at czp.a(PG:9081)
E/ExperimentLoader( 2971): 	at czq.run(PG:1686)
E/ExperimentLoader( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2971): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2971): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2971): 	at jdm.a(PG:77)
E/ExperimentLoader( 2971): 	... 15 more
E/ExperimentLoader( 2971): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2971): 	at fal.a(PG:38)
E/ExperimentLoader( 2971): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2971): 	... 17 more
,I/GoogleURLConnFactory( 3445): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 3504): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3504): simOperator:  IMSI: null
D/SprintDMReceiver( 3504): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1781): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1781): onCreate
,D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1781): active receiver: enabled
,I/SystemUpdateService( 1781): showing system update notification
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,I/ValidateNoPeople(  821): skipping global notification
I/iu.SyncManager( 1781): SYNC; picasa accounts
,V/SystemUpdateService( 1781): retry (wakeup: false) in 3599966 ms
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/NetworkLogImpl( 1781): Loaded NetworkSpeedPredictor
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1781): num queued entries: 0
,I/iu.UploadsManager( 1781): num updated entries: 0
,I/iu.SyncManager( 1781): NEXT; no task
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 36581, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,D/SystemUpdateService( 1781): onDestroy
,V/KeepSync( 3303): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,I/ActivityManager(  821): Start proc 3541:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/ActivityManager(  821): Start proc 3558:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 2632): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 1781): [AccountUtils] Account not ready
W/Kids    ( 1781): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1781): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1781): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1781): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1781): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1781): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1781): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1781): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1781): 	at java.lang.Thread.run(Thread.java:818)
,I/GAv4    ( 3541): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3541):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3541):   adb logcat -s GAv4
,W/GAv4    ( 3541): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 19221(1127KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 26MB/42MB, paused 1.237ms total 27.208ms
,W/GAv4    ( 3541): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3541): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,D/GCM     ( 1485): Connected
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1485): Message class com.google.f.a.a.p
,E/KeepSync( 3303): IOException
E/KeepSync( 3303): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3303): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3303): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3303): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3303): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3303): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3303): 	... 10 more
W/KeepSync( 3303): Sync result 2
,I/ActivityManager(  821): Killing 2208:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 36583, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/WebViewFactory( 3541): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3541): Time to load native libraries: 1 ms (timestamps 2573-2574)
,I/LibraryLoader( 3541): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3541): Binding Chromium to main looper Looper (main, tid 1) {25f63a7f}
,I/LibraryLoader( 3541): Expected native library version number "",actual native library version number ""
I/chromium( 3541): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3541): Initializing chromium process, singleProcess=true
,W/art     ( 3541): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3541): ApplicationContext is null in ApplicationStatus
,W/chromium( 3541): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3541): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3541): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3541): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3541): Requires BLUETOOTH permission
,I/art     (  821): Explicit concurrent mark sweep GC freed 29975(1393KB) AllocSpace objects, 6(137KB) LOS objects, 32% free, 33MB/49MB, paused 939us total 49.102ms
,I/NSApplication( 3541): Starting up...
,I/ActivityManager(  821): Killing 1396:android.process.acore/u0a5 (adj 15): empty #17
,W/GAV2    ( 3558): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3558): Created application version: 3.6.8 (30608)
,I/ActivityManager(  821): Start proc 3629:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/BooksSync( 3558): Starting books sync for 61035162, extras: ade
,I/jxcore-log( 3203): BLE supported!!
I/jxcore-log( 3203): 
,I/BooksConfig( 3558): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3558): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3558): Soft error
E/BooksSync( 3558): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3558): Sync error
E/BooksSync( 3558): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3558): Finished books sync
,I/ActivityManager(  821): Killing 3104:com.android.musicfx/u0a18 (adj 15): empty #17
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36584, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Killing 3083:com.google.android.partnersetup/u0a16 (adj 15): empty #18
,I/ActivityManager(  821): Start proc 3651:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
I/ActivityManager(  821): Killing 2912:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,E/SQLiteLog( 3651): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  821): Start proc 3671:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3671): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 3651): PlayLogger.onLoggerConnected
,I/ActivityManager(  821): Start proc 3692:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/CalendarProvider2( 3671): Created com.android.providers.calendar.CalendarAlarmManager@2eeb70d5(com.android.providers.calendar.CalendarProvider2@105e20ea)
,I/ActivityManager(  821): Killing 3132:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/TimeService( 3692): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448293144935
D/        ( 3692): TimeServiceNative: User Time to be set is 1448293144935
,D/QC-time-services( 3692): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3692): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3692): Lib:time_genoff_operation: pargs->ts_val = 1448293144935
D/QC-time-services(  372): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 3692): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  372): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448293144935
D/QC-time-services(  372): Daemon:genoff_opr: Base = 2, val = 1448293144935, operation = 0
D/QC-time-services(  372): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/10/70 11:52:7
D/QC-time-services(  372): Daemon:Value read from RTC seconds = 8596327000
D/QC-time-services(  372): Daemon:new time 1448293144935 
D/QC-time-services(  372): Daemon: delta 1439696817935 genoff 1439696817935 
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696817935 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  372): Updating the TOD offset
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696817935 to memory
,D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  372): Daemon:Update to modem bit set
D/QC-time-services(  372): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  372): Daemon: Base = 2, Value being sent to MODEM = 1132328344935
,E/QC-time-services( 3692): Receive Passed == base = 2, unit = 1, operation = 0, result = 0,
,E/QC-time-services(  372): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  372): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  821): Start proc 3712:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 346us total 16.884ms
,I/ActivityManager(  821): Killing 3041:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 355us total 15.957ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 333us total 14.192ms
,I/GAv4    ( 3712): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3712):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3712):   adb logcat -s GAv4
,W/GAv4    ( 3712): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,W/GAv4    ( 3712): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3712): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  821): Killing 2702:com.android.vending/u0a19 (adj 15): empty #17
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@22aac890}
,V/Herrevad( 1781): NQAS connected
,I/art     ( 1781): Explicit concurrent mark sweep GC freed 15382(1169KB) AllocSpace objects, 16(256KB) LOS objects, 35% free, 28MB/44MB, paused 1.073ms total 60.714ms
,D/WifiService(  821): New client listening to asynchronous messages
,I/CalendarProvider2( 3671): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3671): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 13769(604KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 1.946ms total 69.345ms
,E/Babel   ( 2632): UserRecoverableAuthException.,
E/Babel   ( 2632): eei: BadAuthentication
E/Babel   ( 2632): 	at eeg.a(Unknown Source)
E/Babel   ( 2632): 	at eeg.a(Unknown Source)
E/Babel   ( 2632): 	at eeg.a(Unknown Source)
E/Babel   ( 2632): 	at g.a(Unknown Source)
E/Babel   ( 2632): 	at cae.a(SourceFile:3089)
E/Babel   ( 2632): 	at cae.a(SourceFile:1131)
E/Babel   ( 2632): 	at cws.a(SourceFile:4333)
E/Babel   ( 2632): 	at cws.a(SourceFile:1419)
E/Babel   ( 2632): 	at crl.a(SourceFile:492)
E/Babel   ( 2632): 	at crl.a(SourceFile:1468)
E/Babel   ( 2632): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2632): 	at cas.b(SourceFile:106)
E/Babel   ( 2632): 	at cap.d(SourceFile:335)
E/Babel   ( 2632): 	at caq.run(SourceFile:81)
,E/Babel   ( 2632): Error getting auth token
E/Babel   ( 2632): dvm
E/Babel   ( 2632): 	at g.a(Unknown Source)
E/Babel   ( 2632): 	at cae.a(SourceFile:3089)
E/Babel   ( 2632): 	at cae.a(SourceFile:1131)
E/Babel   ( 2632): 	at cws.a(SourceFile:4333)
E/Babel   ( 2632): 	at cws.a(SourceFile:1419)
E/Babel   ( 2632): 	at crl.a(SourceFile:492)
E/Babel   ( 2632): 	at crl.a(SourceFile:1468)
E/Babel   ( 2632): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2632): 	at cas.b(SourceFile:106)
E/Babel   ( 2632): 	at cap.d(SourceFile:335)
E/Babel   ( 2632): 	at caq.run(SourceFile:81)
,E/Babel   ( 2632): Account registration failed 1-Redacted-21
,E/Babel   ( 2632): cyp: null -- null
E/Babel   ( 2632): 	at cae.a(SourceFile:3121)
E/Babel   ( 2632): 	at cae.a(SourceFile:1131)
E/Babel   ( 2632): 	at cws.a(SourceFile:4333)
E/Babel   ( 2632): 	at cws.a(SourceFile:1419)
E/Babel   ( 2632): 	at crl.a(SourceFile:492)
E/Babel   ( 2632): 	at crl.a(SourceFile:1468)
E/Babel   ( 2632): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2632): 	at cas.b(SourceFile:106)
E/Babel   ( 2632): 	at cap.d(SourceFile:335)
E/Babel   ( 2632): 	at caq.run(SourceFile:81)
,I/art     ( 2632): Note: end time exceeds epoch: 
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1485): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2632): Unexpected exception while authenticating.
,E/Babel   ( 2632): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2632): 	at eeg.b(Unknown Source)
E/Babel   ( 2632): 	at eeg.b(Unknown Source)
E/Babel   ( 2632): 	at g.a(Unknown Source)
E/Babel   ( 2632): 	at cae.b(SourceFile:1146)
E/Babel   ( 2632): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2632): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2632): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2632): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 3671): (284) automatic index on view_events(_id)
,I/MusicLeanback( 3445): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3445): Stop autocaching.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=21.25 rxSuccessRate=20.81 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,I/ActivityManager(  821): Start proc 3760:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=21.25 rxSuccessRate=20.81 targetRoamBSSID=any RSSI=-47
,E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,W/ResourcesManager( 3760): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3760): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3760): VM with version 2.1.0 has multidex support
I/MultiDex( 3760): install
I/MultiDex( 3760): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3760): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3760): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1485): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1485): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 1781): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3760): callingUid 10011, callindPid: 3760
,D/LocationInitializer( 1781): Restart initialization of location
,E/MDM     ( 1752): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3445): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3445): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 3558): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 3651): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  821): Start proc 3797:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 19957(1164KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.362ms total 57.641ms
,D/Finsky  ( 3797): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager(  821): Killing 3345:com.android.settings/1000 (adj 15): empty #17
,D/Finsky  ( 3797): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  821): Killing 3362:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3837:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3797): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3797): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 3837): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3837): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,D/Finsky  ( 3797): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/Finsky  ( 3797): [1] 2.run: Finished loading 1 libraries.
,I/MultiDex( 3837): VM with version 2.1.0 has multidex support
I/MultiDex( 3837): install
I/MultiDex( 3837): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 3797): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (181 us)
,D/Finsky  ( 3797): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 3837): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3837): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1485): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/Finsky  ( 3797): [395] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
D/AuthorizationBluetoothService( 1485): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1781): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 3760): callingUid 10011, callindPid: 3760
,E/MDM     ( 1752): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1781): Restart initialization of location
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3797): [395] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/Finsky  ( 3797): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3797): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3797): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3797): [1] 5.onFinished: Scheduling replication attempt 4.
,D/Finsky  ( 3797): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  821): Display changed displayId=0
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3797): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  821): Excessive delay in setPowerMode(): 268ms
,I/DreamManagerService(  821): Entering dreamland.
I/PowerManagerService(  821): Dozing...
I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
E/WifiStateMachine(  821): cancelDelayedScan -> 5
,E/native  (  821): do suspend false
,I/art     (  821): Explicit concurrent mark sweep GC freed 22619(1118KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.488ms total 110.176ms
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3894ef92}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=3.66 rxSuccessRate=4.48 targetRoamBSSID=any RSSI=-46
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/Keyboard.Facilitator( 1212): onFinishInput()
,W/Finsky  ( 3797): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/WifiStateMachine(  821): cancelDelayedScan -> 7
,E/native  (  821): do suspend true
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 3797): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3797): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3797): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3797): [1] DailyHygiene.reschedule: Scheduling new run in 770 minutes (failures=5)
,D/DeviceConnectionService( 1752): client connected with version: 7571000
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3894ef92}
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/ActivityManager(  821): Killing 3504:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3504
,I/ActivityManager(  821): Killing 3541:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.50 rxSuccessRate=1.00 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1485): Vacuum at: now=1448293163462 tag=VacuumService
,V/GoogleAuthProtoRequest( 3277): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3277): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3277): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1485): Using platform SSLCertificateSocketFactory
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 42268(2MB) AllocSpace objects, 11(1047KB) LOS objects, 38% free, 26MB/42MB, paused 2.077ms total 66.035ms
,E/Uploader( 1485): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1485): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1485): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1485): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1485): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1485): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1485): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1485): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1485): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1485): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1485): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1485): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485):  no longer exists, so no auth token.
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1485): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1485): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1485): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1485): 	,at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1485): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1485): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1485): No account for auth token provided
,W/Uploader( 1485): No account for auth token provided
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1485): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1485): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,E/Uploader( 1485): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1485): 	at com.google.android.gms.auth.p.b(SourceFile:477)
,E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1485): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1485): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1485): 	,at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1485): No account for auth token provided
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3797): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3797): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3797): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
,I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,V/GoogleAuthProtoRequest( 3277): [337] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3277): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3277): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 30164(1392KB) AllocSpace objects, 5(174KB) LOS objects, 31% free, 34MB/50MB, paused 2.392ms total 78.939ms
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3797): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3797): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3797): [1] 5.onFinished: Giving up after 6 failures.
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
,I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/BooksSync( 3558): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3558): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2971): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at blb.a(PG:3937)
E/HttpOperation( 2971): 	,at czp.a(PG:18188)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
,E/HttpOperation( 2971): 	... 12 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 14 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2971): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at hec.a(PG:42)
E/HttpOperation( 2971): 	at hee.a(PG:102)
E/HttpOperation( 2971): 	at czr.a(PG:65)
E/HttpOperation( 2971): 	at kka.a(PG:108)
E/HttpOperation( 2971): 	at czp.a(PG:19176)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
,E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 15 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 17 more
E/ExperimentLoader( 2971): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): 	at jdm.a(PG:82)
E/ExperimentLoader( 2971): 	at jcs.o(PG:406)
E/ExperimentLoader( 2971): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2971): 	at jcs.i(PG:143)
E/ExperimentLoader( 2971): 	at hec.a(PG:42)
E/ExperimentLoader( 2971): 	at hee.a(PG:102)
E/ExperimentLoader( 2971): 	at czr.a(PG:65)
E/ExperimentLoader( 2971): 	at kka.a(PG:108)
E/ExperimentLoader( 2971): 	at czp.a(PG:19176),
E/ExperimentLoader( 2971): 	at czp.a(PG:9081)
E/ExperimentLoader( 2971): 	at czq.run(PG:1686)
E/ExperimentLoader( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2971): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2971): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2971): 	at jdm.a(PG:77)
E/ExperimentLoader( 2971): 	... 15 more
E/ExperimentLoader( 2971): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2971): 	at fal.a(PG:38)
E/ExperimentLoader( 2971): 	at jdj.a(PG:4089)
,E/ExperimentLoader( 2971): 	... 17 more
,E/BooksAccountManager( 3558): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3558): Soft error
E/BooksSync( 3558): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3558): Sync error
E/BooksSync( 3558): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3558): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 183434, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 3303): Connecting to GoogleApiClient
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 182877, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3303): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3303): IOException
E/KeepSync( 3303): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3303): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3303): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3303): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3303): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3303): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3303): 	... 10 more
W/KeepSync( 3303): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 183731, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1212): run()
I/Keyboard.Facilitator( 1212): flushDynamicLanguageModels()
,I/ConfigService( 1485): onCreate
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
,I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ConfigService( 1485): onDestroy
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0,
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/BooksSync( 3558): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3558): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3558): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): Soft error
E/BooksSync( 3558): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3558): Sync error
E/BooksSync( 3558): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3558): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 272140, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): ,
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,V/GoogleAuthProtoRequest( 3277): [338] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3277): [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3277): [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
,I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 65818(3MB) AllocSpace objects, 2(56KB) LOS objects, 36% free, 28MB/44MB, paused 2.067ms total 63.395ms
,V/KeepSync( 3303): Connecting to GoogleApiClient
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 34745(1517KB) AllocSpace objects, 10(631KB) LOS objects, 32% free, 33MB/49MB, paused 1.379ms total 66.238ms
,E/HttpOperation( 2971): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at blb.a(PG:3937)
E/HttpOperation( 2971): 	at czp.a(PG:18188)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 12 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 14 more
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3303): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at hec.a(PG:42)
E/HttpOperation( 2971): 	at hee.a(PG:102)
E/HttpOperation( 2971): 	at czr.a(PG:65)
E/HttpOperation( 2971): 	at kka.a(PG:108)
E/HttpOperation( 2971): 	at czp.a(PG:19176)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 15 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 17 more
E/ExperimentLoader( 2971): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): 	at jdm.a(PG:82)
E/ExperimentLoader( 2971): 	at jcs.o(PG:406)
E/ExperimentLoader( 2971): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2971): 	at jcs.i(PG:143)
E/ExperimentLoader( 2971): 	at hec.a(PG:42)
E/ExperimentLoader( 2971): 	at hee.a(PG:102)
E/ExperimentLoader( 2971): 	at czr.a(PG:65)
E/ExperimentLoader( 2971): 	at kka.a(PG:108)
E/ExperimentLoader( 2971): 	at czp.a(PG:19176)
E/ExperimentLoader( 2971): 	at czp.a(PG:9081)
E/ExperimentLoader( 2971): 	at czq.run(PG:1686)
E/ExperimentLoader( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2971): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2971): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2971): 	at jdm.a(PG:77)
E/ExperimentLoader( 2971): 	... 15 more
E/ExperimentLoader( 2971): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2971): 	at fal.a(PG:38)
E/ExperimentLoader( 2971): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2971): 	... 17 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3303): IOException
E/KeepSync( 3303): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3303): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3303): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3303): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3303): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3303): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3303): 	... 10 more
W/KeepSync( 3303): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 274911, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 273442, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
,I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110,
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63),
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object],
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): found interfaceName: wlan0
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Coordinator is now connected to the server!
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): found interfaceName: wlan0
I/jxcore-log( 3203): 
I/jxcore-log( 3203): -iface: IPv4 is internal : false, has ip: 192.168.1.110
I/jxcore-log( 3203): 
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/BooksSync( 3558): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3558): GmsCore Version = 7.8.99 (2134222-430),
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3558): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 3558): Soft error
E/BooksSync( 3558): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3558): Sync error
E/BooksSync( 3558): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3558): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 393045, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3277): [339] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3277): [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3277): [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 3303): Connecting to GoogleApiClient
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3303): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at blb.a(PG:3937)
E/HttpOperation( 2971): 	at czp.a(PG:18188)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 12 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 14 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3303): IOException
E/KeepSync( 3303): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3303): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3303): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3303): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3303): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3303): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3303): 	... 10 more
W/KeepSync( 3303): Sync result 2
,E/HttpOperation( 2971): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at hec.a(PG:42)
E/HttpOperation( 2971): 	at hee.a(PG:102)
E/HttpOperation( 2971): 	at czr.a(PG:65)
E/HttpOperation( 2971): 	at kka.a(PG:108)
E/HttpOperation( 2971): 	at czp.a(PG:19176)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 15 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 17 more
E/ExperimentLoader( 2971): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): 	at jdm.a(PG:82)
E/ExperimentLoader( 2971): 	at jcs.o(PG:406)
E/ExperimentLoader( 2971): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2971): 	at jcs.i(PG:143)
E/ExperimentLoader( 2971): 	at hec.a(PG:42)
E/ExperimentLoader( 2971): 	at hee.a(PG:102)
E/ExperimentLoader( 2971): 	at czr.a(PG:65)
E/ExperimentLoader( 2971): 	at kka.a(PG:108)
E/ExperimentLoader( 2971): 	at czp.a(PG:19176)
E/ExperimentLoader( 2971): 	at czp.a(PG:9081)
E/ExperimentLoader( 2971): 	at czq.run(PG:1686)
E/ExperimentLoader( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2971): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2971): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2971): 	at jdm.a(PG:77)
E/ExperimentLoader( 2971): 	... 15 more
E/ExperimentLoader( 2971): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2971): 	at fal.a(PG:38)
E/ExperimentLoader( 2971): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2971): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 427974, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 425569, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1485): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1485): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1485): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1485): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1485): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1485): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1485): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3797): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3797): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3797): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3797): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3797): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3797): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3797): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3797): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/BooksSync( 3558): Starting books sync for 61035162, extras: ade
,I/art     (  821): Explicit concurrent mark sweep GC freed 38709(1707KB) AllocSpace objects, 9(426KB) LOS objects, 32% free, 33MB/49MB, paused 2.229ms total 72.641ms
,I/BooksConfig( 3558): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3558): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3558): Soft error
E/BooksSync( 3558): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3558): Sync error
E/BooksSync( 3558): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3558): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 634417, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/jxcore-log( 3203): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): DBG, CoordinatorConnector command called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"4000\",\"conReTryCount\":\"1\"}","devices":19,"addressList":[{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"
,I/jxcore-log( 3203): Start now : testSendData.js
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): stop tests now !
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"1"}, bt-address lenght : 19
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): check server,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): serverPort is 36926
I/jxcore-log( 3203): 
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/        ( 3203): Stoping All
,I/        ( 3203): Stopping services
I/        ( 3203): Stop Bluetooth
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3203): Start-My BT: F8:CF:C5:D9:E5:61,
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3203):  mInstanceString : {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7032","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3203): All stuff available and enabled
,I/        ( 3203): Stoping All
I/        ( 3203): Stopping services
,I/        ( 3203): Stop Bluetooth
I/        ( 3203): Starting All
I/        ( 3203): Stopping services
,I/        ( 3203): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7032","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@2691acdf
I/        ( 3203): Stopping services
I/        ( 3203): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7032","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3203): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7032","ra":"F8:CF:C5:D9:E5:61"}, length : 82
,I/        ( 3203): peerDiscoveryTimer timeout value:6655
I/        ( 3203): Stop Bluetooth
I/        ( 3203): StartBluetooth listener
I/        ( 3203): StartBluetooth listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3203): StartBroadcasting started ok
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3203): 
,I/BTListenerThread( 3203): starting to listen
I/BTListenerThread( 3203): waiting to accept incoming Connection
I/jxcore-log( 3203): TCP/IP server  is bound to : undefined
I/jxcore-log( 3203): 
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/WB      ( 3203): We already were running, thus doing nothing
,I/        ( 3203): Added local service
I/        ( 3203): Cleared service requests
,I/        ( 3203): Stopped peer discovery
I/        ( 3203): Started peer discovery
I/        ( 3203): Discovery state changed to Started.
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 1 peers.
,I/SS      ( 3203): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
,D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,I/wpa_supplicant( 3269): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3203): Started service discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3269): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3269): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3203): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT5540","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT5540","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT5540, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT5540, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3203): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2743, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2743, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3203): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2552, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2552, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3203): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9217, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9217, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3203): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/BTConnectToThread( 3203): Starting to connect
,I/        ( 3203): Connecting to null, at 34:FC:EF:9D:93:0B
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3258): info:x10
,D/        ( 3258): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL,
,W/bt-btif ( 3258): info:x10
D/        ( 3258): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,D/btif_config( 3258): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
,E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State
,I/ActivityManager(  821): Start proc 4022:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32747772:true
,I/ActivityManager(  821): Killing 1511:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0,
,D/BluetoothAdapterProperties( 3258): Failed to remove device: E0:DB:10:1F:C9:5E
,D/WifiService(  821): Client connection lost with reason: 4
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe207c rs_disc_pending=0
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe1eb4 rs_disc_pending=1
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:255,
W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3203): we got incoming connection
I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread
I/BTListenerThread( 3203): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started
,I/BTListenerThread( 3203): got MESSAGE_READ 82 bytes.,
I/BTListenerThread( 3203): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6254","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3203): MESSAGE_WRITE 82 bytes.
I/HS      ( 3203): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT6254
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3203): Starting the connected thread incoming : true, samsung-SM-N9005_PT6254
,I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket,
I/BtToRequestSocket( 3203): Creating BTConnectedThread
I/BtConnectorHelper( 3203): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3203): --DoOneRunRound started,
,I/BtToRequestSocket( 3203): LocalHost address: localhost/127.0.0.1, port: 36926
,I/jxcore-log( 3203): TCP/IP server connected
I/jxcore-log( 3203): 
I/BtToRequestSocket( 3203): --DoOneRunRound ended
,I/jxcore-log( 3203): TCP/IP server has received 1980 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 10172 bytes of data
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 36184 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3203): ,
,I/jxcore-log( 3203): TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe207c rs_disc_pending=1
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3203): TCP/IP server has received 48064 bytes of data
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3203): 
,W/bt-sdp  ( 3258): process_service_search_attr_rsp
,I/jxcore-log( 3203): TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3203): ,
,I/jxcore-log( 3203): TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3203): 
,W/bt-btif ( 3258): invalid rfc slot id: 4
,I/BtToSocketBase( 3203): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3203): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT6254
,I/BtToSocketBase( 3203): Stop ReceivingThread
I/BtToSocketBase( 3203): Stop SendingThread
,I/BtToSocketBase( 3203): Close local in
I/BtToSocketBase( 3203): Close LocalOutputStream
I/BtToSocketBase( 3203): Close localHostSocket
I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3203): TCP/IP server is ended
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server is close
I/jxcore-log( 3203): 
W/bt-rfcomm( 3258): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3258): RFCOMM_DisconnectInd LCID:0x42
,D/btif_config( 3258): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3258): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3203): Starting to Handshake
I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3203): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe207c rs_disc_pending=0
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3203): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3203): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3203): HandshakeOk : LGE-LG-D802_PT7492
I/HS      ( 3203): Hand Shake finished outgoing for : LGE-LG-D802_PT7492
,I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3203): Starting the connected thread incoming : false, LGE-LG-D802_PT7492
,I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket,
I/BtToRequestSocket( 3203): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3203): mHTTPPort  set to : 54479
,I/BtConnectorHelper( 3203): Request socket is using : 54479
I/BtToRequestSocket( 3203): Now accepting connections
,I/BtConnectorHelper( 3203): Calling ConnectionStatusUpdate with port :54479
,I/jxcore-log( 3203): CLIENT connected to 54479, error: null
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT starting client 
I/jxcore-log( 3203): 
,I/BtToRequestSocket( 3203): incoming data from: /127.0.0.1, port: 54479
I/BtToRequestSocket( 3203): Set local streams
I/BtToRequestSocket( 3203): rin ended ---------------------------;
,I/jxcore-log( 3203): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3203): 
,D/        ( 3258): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2247
,I/jxcore-log( 3203): CLIENT is data received : 10000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 20000
I/jxcore-log( 3203): 
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,I/jxcore-log( 3203): CLIENT is data received : 30000
I/jxcore-log( 3203): 
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3203): CLIENT is data received : 40000
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3258): onReceive,
,I/ActivityManager(  821): Start proc 4051:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f9fa840:true
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  821): Start proc 4077:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,I/BluetoothClassifier( 4051): Bluetooth Device Name: Note3-1
,I/ActivityManager(  821): Killing 3692:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3629:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/jxcore-log( 3203): CLIENT is data received : 50000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 60000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 70000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 80000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 90000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 100000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): got all data for this round
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT closeClientSocket
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3203): 
,I/BtToSocketBase( 3203): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3203): Disconnect outgoing peer: LGE-LG-D802_PT7492
,I/BtToSocketBase( 3203): Stop ReceivingThread
I/BtToSocketBase( 3203): Stop SendingThread
I/BtToSocketBase( 3203): Close local in
I/BtToSocketBase( 3203): Close LocalOutputStream
,I/BtToSocketBase( 3203): Close localHostSocket
I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
,I/BtToRequestSocket( 3203): Close server socket
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 11824 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): CLIENT is closed
I/jxcore-log( 3203): 
,W/bt-btif ( 3258): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/jxcore-log( 3203): Connect (retry count 0) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: F8:95:C7:87:3C:51, name: null
,I/BTConnectToThread( 3203): Starting to connect
W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3203): Connecting to null, at F8:95:C7:87:3C:51
D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3258): onReceive
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 4051): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 3258): info:x10
,D/        ( 3258): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 9 peers.
,I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3203): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3203): Peer(3): Note4-1 92:b6:86:43:73:1c,
I/SS      ( 3203): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3203): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3203): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3203): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3203): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3203): Added service request
,I/wpa_supplicant( 3269): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3203): Started service discovery
,I/        ( 3203): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7297, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7297, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3203): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9628, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9628, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,W/bt-btif ( 3258): info:x10
,D/        ( 3258): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe240c rs_disc_pending=1
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3258): process_service_search_attr_rsp
,D/btif_config( 3258): btif_get_device_type: Device [00:f4:6f:30:e0:6c] type 1
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
,E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 3258): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2244 rs_disc_pending=0
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/        ( 3203): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,V/GoogleAuthProtoRequest( 3277): [340] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 54126(2MB) AllocSpace objects, 19(2MB) LOS objects, 36% free, 27MB/43MB, paused 2.899ms total 74.628ms
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3277): [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3277): [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,D/btif_config( 3258): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:255
W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3203): we got incoming connection
,I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread
I/BTListenerThread( 3203): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 3258): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2244 rs_disc_pending=1
W/bt-btif ( 3258): bta_dm_check_av:0
,W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe240c rs_disc_pending=0
W/bt-btif ( 3258): bta_dm_check_av:0
,W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3203): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3203): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3203): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3203): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT9628
,I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3203): Starting the connected thread incoming : true, samsung-SM-G800F_PT9628
I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3203): Creating BTConnectedThread
,I/BtConnectorHelper( 3203): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3203): --DoOneRunRound started
,I/BtToRequestSocket( 3203): LocalHost address: localhost/127.0.0.1, port: 36926
,I/BtToRequestSocket( 3203): --DoOneRunRound ended
,I/jxcore-log( 3203): TCP/IP server connected
I/jxcore-log( 3203): 
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:1
W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:1,
W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3203): Starting to Handshake
I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3203): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started
,I/jxcore-log( 3203): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3203): 
,I/BTConnectToThread( 3203): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3203): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3203): HandshakeOk : LGE-LG-H815_PT1675
I/HS      ( 3203): Hand Shake finished outgoing for : LGE-LG-H815_PT1675
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3203): Starting the connected thread incoming : false, LGE-LG-H815_PT1675
,I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3203): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3203): mHTTPPort  set to : 43908
I/BtConnectorHelper( 3203): Request socket is using : 43908
I/BtToRequestSocket( 3203): Now accepting connections
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2244 rs_disc_pending=1,
W/bt-btif ( 3258): bta_dm_check_av:0
,W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 3203): Calling ConnectionStatusUpdate with port :43908,
I/jxcore-log( 3203): CLIENT connected to 43908, error: null
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT starting client 
I/jxcore-log( 3203): 
,I/BtToRequestSocket( 3203): incoming data from: /127.0.0.1, port: 43908
,I/BtToRequestSocket( 3203): Set local streams
I/BtToRequestSocket( 3203): rin ended ---------------------------;
,I/jxcore-log( 3203): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe240c rs_disc_pending=1
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3203): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 10000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 20000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 30000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 40000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 50000
I/jxcore-log( 3203): 
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at blb.a(PG:3937)
E/HttpOperation( 2971): 	at czp.a(PG:18188)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 12 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 14 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at hec.a(PG:42)
E/HttpOperation( 2971): 	at hee.a(PG:102)
E/HttpOperation( 2971): 	at czr.a(PG:65)
E/HttpOperation( 2971): 	at kka.a(PG:108)
E/HttpOperation( 2971): 	at czp.a(PG:19176)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 15 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 17 more
,E/ExperimentLoader( 2971): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 2971): 	at jdm.a(PG:82)
E/ExperimentLoader( 2971): 	at jcs.o(PG:406)
E/ExperimentLoader( 2971): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2971): 	at jcs.i(PG:143)
E/ExperimentLoader( 2971): 	at hec.a(PG:42)
E/ExperimentLoader( 2971): 	at hee.a(PG:102)
E/ExperimentLoader( 2971): 	at czr.a(PG:65)
E/ExperimentLoader( 2971): 	at kka.a(PG:108)
E/ExperimentLoader( 2971): 	at czp.a(PG:19176)
E/ExperimentLoader( 2971): 	at czp.a(PG:9081)
E/ExperimentLoader( 2971): 	at czq.run(PG:1686)
E/ExperimentLoader( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2971): ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2971): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2971): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2971): 	at jdm.a(PG:77)
E/ExperimentLoader( 2971): 	,... 15 more
E/ExperimentLoader( 2971): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2971): 	at fal.a(PG:38)
E/ExperimentLoader( 2971): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2971): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 699369, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3203): CLIENT is data received : 60000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 25740 bytes of data,
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe240c rs_disc_pending=0
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3203): CLIENT is data received : 70000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 80000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 90000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 100000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): got all data for this round
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT closeClientSocket
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3203): 
,I/BtToSocketBase( 3203): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3203): Disconnect outgoing peer: LGE-LG-H815_PT1675
I/BtToSocketBase( 3203): Stop ReceivingThread
I/BtToSocketBase( 3203): Stop SendingThread
I/BtToSocketBase( 3203): Close local in,
I/BtToSocketBase( 3203): Close LocalOutputStream
I/BtToSocketBase( 3203): Close localHostSocket
I/BtToSocketBase( 3203): Close bt in,
I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
I/BtToRequestSocket( 3203): Close server socket
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 22867 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 3203): CLIENT is closed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 41580 bytes of data
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 43560 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 45540 bytes of data,
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe240c rs_disc_pending=1,
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3203): TCP/IP server has received 47520 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3203): 
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 9 peers.
I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(2): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3203): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3203): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3203): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3203): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3203): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,I/jxcore-log( 3203): TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe240c rs_disc_pending=0
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3203): TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3203): 
,I/        ( 3203): Started service discovery
,W/bt-btif ( 3258): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/jxcore-log( 3203): TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Connect (retry count 0) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3203): Starting to connect
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3203): Connecting to null, at 58:2A:F7:ED:96:BE,
D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3203): TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe240c rs_disc_pending=1
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3203): TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 93060 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 95040 bytes of data,
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3258): onReceive
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: G4-1,
,I/jxcore-log( 3203): TCP/IP server has received 97020 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 99000 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3203): ,
,W/bt-btif ( 3258): invalid rfc slot id: 6
,I/BtToSocketBase( 3203): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3203): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT9628
I/BtToSocketBase( 3203): Stop ReceivingThread
,I/BtToSocketBase( 3203): Stop SendingThread
I/BtToSocketBase( 3203): Close local in
I/BtToSocketBase( 3203): Close LocalOutputStream
I/BtToSocketBase( 3203): Close localHostSocket
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3203): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT9628
,I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
I/BtToSocketBase( 3203): Close bt in,
I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
I/jxcore-log( 3203): TCP/IP server is ended
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): TCP/IP server is close
I/jxcore-log( 3203): 
,W/bt-rfcomm( 3258): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 3258): RFCOMM_DisconnectInd LCID:0x4a
,W/bt-btif ( 3258): info:x10,
D/        ( 3258): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe25d4 rs_disc_pending=1
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3258): process_service_search_attr_rsp
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3258): onReceive
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: S5mini-1
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3258): check_cod: remote_cod = 0x5a0
E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3258): Device not in IRK list,
E/bt-btif ( 3258): Do not find the bg connection mask for the remote device
,W/bt-btif ( 3258): invalid rfc slot id: 9
I/BluetoothBondStateMachine( 3258): No record of the device:null
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
E/BluetoothBondStateMachine( 3258): In stable state, received invalid newState: 10
I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3203): 
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 13925 ms, rnd: 1, ex: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): Connect (retry count 0) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: B4:CE:F6:AB:A4:6A, name: null,
,I/BTConnectToThread( 3203): Starting to connect
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3203): Connecting to null, at B4:CE:F6:AB:A4:6A
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3258): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
,E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3258): invalid rfc slot id: 10
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 9163 ms, rnd: 1, ex: Connection to B4:CE:F6:AB:A4:6A failed", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3258): info:x10
,D/        ( 3258): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,D/btif_config( 3258): btif_get_device_type: Device [58:3f:54:73:64:c0] type 1
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State,
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 3258): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:255
W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3203): we got incoming connection
I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3203): waiting to accept incoming Connection,
,I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started,
,I/BTListenerThread( 3203): got MESSAGE_READ 77 bytes.,
,I/BTListenerThread( 3203): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������,
,I/BTListenerThread( 3203): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3203): Incoming connection Hand Shake finished for : LGE-LG-D855_PT3303
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3203): Starting the connected thread incoming : true, LGE-LG-D855_PT3303
I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3203): Creating BTConnectedThread
I/BtConnectorHelper( 3203): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3203): --DoOneRunRound started
,I/BtToRequestSocket( 3203): LocalHost address: localhost/127.0.0.1, port: 36926
,I/BtToRequestSocket( 3203): --DoOneRunRound ended
,I/jxcore-log( 3203): TCP/IP server connected
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 3960 bytes of data
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 10172 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 12152 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3203): ,
,I/jxcore-log( 3203): TCP/IP server has received 28264 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 38164 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 46084 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 48064 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 63904 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3203): 
,W/bt-btif ( 3258): invalid rfc slot id: 8
,I/BtToSocketBase( 3203): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3203): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT3303,
I/BtToSocketBase( 3203): Stop ReceivingThread
,I/BtToSocketBase( 3203): Stop SendingThread
I/BtToSocketBase( 3203): Close local in
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed,
,I/BtConnectorHelper( 3203): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT3303
I/BtToSocketBase( 3203): Close LocalOutputStream
I/BtToSocketBase( 3203): Close localHostSocket
I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Close bt in
,I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
W/bt-rfcomm( 3258): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3258): RFCOMM_DisconnectInd LCID:0x41
,I/jxcore-log( 3203): TCP/IP server is ended
I/jxcore-log( 3203): 
I/jxcore-log( 3203): TCP/IP server is close
I/jxcore-log( 3203): 
,V/KeepSync( 3303): Connecting to GoogleApiClient
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3303): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3303): IOException
E/KeepSync( 3303): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3303): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3303): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3303): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3303): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3303): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3303): 	... 10 more
W/KeepSync( 3303): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 704111, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3203): Connect (retry count 0) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/BTConnectToThread( 3203): Starting to connect
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3203): Connecting to null, at 50:2E:6C:AC:21:50
D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe279c rs_disc_pending=1,
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe279c rs_disc_pending=0
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3258): onReceive
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: G3-1,
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3258): info:x10
D/        ( 3258): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3258): process_service_search_attr_rsp,
,D/btif_config( 3258): btif_get_device_type: Device [50:2e:6c:ac:21:50] type 1
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3258): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 3258): Failed to remove device: 50:2E:6C:AC:21:50,
I/BluetoothBondStateMachine( 3258): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:1
I/BTConnectToThread( 3203): Starting to Handshake
W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3203): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started
,I/BTConnectToThread( 3203): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 3203): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3699","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3203): HandshakeOk : HTC-HTC One_M8_PT3699
I/HS      ( 3203): Hand Shake finished outgoing for : HTC-HTC One_M8_PT3699
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3203): Starting the connected thread incoming : false, HTC-HTC One_M8_PT3699
I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3203): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3203): mHTTPPort  set to : 33793
,I/BtConnectorHelper( 3203): Request socket is using : 33793
I/BtToRequestSocket( 3203): Now accepting connections
,I/BtConnectorHelper( 3203): Calling ConnectionStatusUpdate with port :33793
,I/jxcore-log( 3203): CLIENT connected to 33793, error: null
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT starting client 
I/jxcore-log( 3203): 
,I/BtToRequestSocket( 3203): incoming data from: /127.0.0.1, port: 33793
,I/BtToRequestSocket( 3203): Set local streams
,I/jxcore-log( 3203): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3203): 
I/BtToRequestSocket( 3203): rin ended ---------------------------;
,D/        ( 3258): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24843
,D/        ( 3258): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14943
,I/jxcore-log( 3203): CLIENT is data received : 10000,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 20000,
I/jxcore-log( 3203): 
,D/        ( 3258): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12963,
I/jxcore-log( 3203): CLIENT is data received : 30000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 40000
I/jxcore-log( 3203): 
,D/        ( 3258): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6033
,I/jxcore-log( 3203): CLIENT is data received : 50000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 60000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 70000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 80000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 90000,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 100000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): got all data for this round
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT closeClientSocket
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3203): 
,I/BtToSocketBase( 3203): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3203): Disconnect outgoing peer: HTC-HTC One_M8_PT3699
I/BtToSocketBase( 3203): Stop ReceivingThread
I/BtToSocketBase( 3203): Stop SendingThread
I/BtToSocketBase( 3203): Close local in
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 15527 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3203): Close LocalOutputStream
I/BtToSocketBase( 3203): Close localHostSocket
I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
,I/BtToRequestSocket( 3203): Close server socket
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3203): CLIENT is closed
I/jxcore-log( 3203): 
,W/bt-btif ( 3258): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3258): onReceive
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: HTC One_M8
,I/jxcore-log( 3203): Connect (retry count 0) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3203): Starting to connect
W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3203): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3258): info:x10
D/        ( 3258): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac,
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,D/btif_config( 3258): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3258): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State
W/bt-btif ( 3258): info:x10
D/        ( 3258): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 3258): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2b2c rs_disc_pending=1
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:255
W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3203): we got incoming connection
I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread
I/BTListenerThread( 3203): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started
,I/BTListenerThread( 3203): got MESSAGE_READ 76 bytes.
I/BTListenerThread( 3203): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT566","ra":"34:FC:EF:11:AE:67"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3203): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3203): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT566
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3203): Starting the connected thread incoming : true, LGE-Nexus 5_PT566
,I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3203): Creating BTConnectedThread
I/BtConnectorHelper( 3203): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3203): --DoOneRunRound started
,I/BtToRequestSocket( 3203): LocalHost address: localhost/127.0.0.1, port: 36926
I/BtToRequestSocket( 3203): --DoOneRunRound ended
I/jxcore-log( 3203): TCP/IP server connected
I/jxcore-log( 3203): 
,W/bt-sdp  ( 3258): process_service_search_attr_rsp
,I/jxcore-log( 3203): TCP/IP server has received 1980 bytes of data
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 40688 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3203): 
,D/btif_config( 3258): btif_get_device_type: Device [e0:db:10:14:e2:c0] type 1
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State
,I/jxcore-log( 3203): TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3203): ,
,I/jxcore-log( 3203): TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3203): 
,W/bt-btif ( 3258): invalid rfc slot id: 11,
I/BtToSocketBase( 3203): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3203): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT566
I/BtToSocketBase( 3203): Stop ReceivingThread
I/BtToSocketBase( 3203): Stop SendingThread,
I/BtToSocketBase( 3203): Close local in
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3203): Close LocalOutputStream
I/BtToSocketBase( 3203): Close localHostSocket
I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3203): Close bt in
I/BtConnectorHelper( 3203): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT566
I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
I/BtToSocketBase( 3203): Close bt in
,I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
I/jxcore-log( 3203): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3203): 
W/bt-rfcomm( 3258): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 3258): RFCOMM_DisconnectInd LCID:0x43
,I/jxcore-log( 3203): TCP/IP server is ended,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): TCP/IP server is close
I/jxcore-log( 3203): 
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3258): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State,
,I/EventLogService( 1781): Opted in for usage reporting
,I/EventLogService( 1781): Aggregate from 1448291890289 (log), 1448291890289 (data)
,W/EventLogAggregator( 1781): Unknown tag: snet_gcore
W/EventLogAggregator( 1781): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1781): dumping service [account]
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:1
W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3203): Starting to Handshake
,I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread,
I/BTConnectToThread( 3203): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started
,I/BTConnectToThread( 3203): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3203): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3203): HandshakeOk : samsung-SM-N910C_PT1968
,I/HS      ( 3203): Hand Shake finished outgoing for : samsung-SM-N910C_PT1968
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3203): Starting the connected thread incoming : false, samsung-SM-N910C_PT1968,
I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3203): Creating BtConnectedRequestSocket,
I/BtToRequestSocket( 3203): mHTTPPort  set to : 59325
,I/BtConnectorHelper( 3203): Request socket is using : 59325
I/BtToRequestSocket( 3203): Now accepting connections
,I/BtConnectorHelper( 3203): Calling ConnectionStatusUpdate with port :59325
,I/jxcore-log( 3203): CLIENT connected to 59325, error: null
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT starting client 
I/jxcore-log( 3203): 
,I/BtToRequestSocket( 3203): incoming data from: /127.0.0.1, port: 59325,
I/BtToRequestSocket( 3203): Set local streams
I/BtToRequestSocket( 3203): rin ended ---------------------------;
I/jxcore-log( 3203): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3203): ,
,D/        ( 3258): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:2111
,I/jxcore-log( 3203): CLIENT is data received : 10000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 20000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 30000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 40000
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2b2c rs_disc_pending=0
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3203): CLIENT is data received : 50000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 60000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 70000,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 80000,
I/jxcore-log( 3203): 
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3203): CLIENT is data received : 90000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 100000
I/jxcore-log( 3203): 
I/jxcore-log( 3203): got all data for this round
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT closeClientSocket
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3203): 
,I/BtToSocketBase( 3203): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3203): Disconnect outgoing peer: samsung-SM-N910C_PT1968
I/BtToSocketBase( 3203): Stop ReceivingThread
I/BtToSocketBase( 3203): Stop SendingThread
I/BtToSocketBase( 3203): Close local in
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 11692 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/BtToSocketBase( 3203): Close LocalOutputStream
,I/BtToSocketBase( 3203): Close localHostSocket
I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
I/BtToRequestSocket( 3203): Close server socket
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3203): CLIENT is closed
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2b2c rs_disc_pending=1
W/bt-btif ( 3258): bta_dm_check_av:0
,W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3258): onReceive
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2b2c rs_disc_pending=0
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3258): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 3203): Connect (retry count 0) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3203): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3203): Starting to connect
W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3258): onReceive
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: Note4-1,
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3203): Found 4 peers.
I/SS      ( 3203): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3203): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
D/WifiP2pManager( 3203): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3203): Added service request
,W/bt-btm  ( 3258): btm_sec_clr_temp_auth_service() - no dev CB
,E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3258): invalid rfc slot id: 15
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 13456 ms, rnd: 1, ex: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63),
,I/wpa_supplicant( 3269): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3203): Started service discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3203): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:,
I/        ( 3203): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5629, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5629, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3203): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"}, typeCordovap2p._tcp.local.:,
I/        ( 3203): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9217, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9217, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3203): Connect (retry count 0) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do connect now,
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3203): Starting to connect
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3203): Connecting to null, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  821): Explicit concurrent mark sweep GC freed 36049(1673KB) AllocSpace objects, 11(553KB) LOS objects, 32% free, 33MB/49MB, paused 1.591ms total 89.114ms
,W/bt-btif ( 3258): info:x10
D/        ( 3258): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3258): process_service_search_attr_rsp,
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,W/bt-btif ( 3258): info:x10
,D/        ( 3258): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/SS      ( 3203): Found 3 peers.
,I/SS      ( 3203): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3203): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(3): Android_63cc 82:01:84:6b:e8:5d
D/WifiP2pManager( 3203): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,W/bt-rfcomm( 3258): PORT_StartCnf failed result:5
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3258): Device not in IRK list
E/bt-btif ( 3258): Do not find the bg connection mask for the remote device
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3258): invalid rfc slot id: 16
I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3258): No record of the device:null
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 9 Address: 34:FC:EF:11:B1:66 newState: 0
E/BluetoothBondStateMachine( 3258): In stable state, received invalid newState: 10
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 10754 ms, rnd: 1, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/btif_config( 3258): btif_get_device_type: Device [7c:f9:0e:34:8a:a0] type 1
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
D/BluetoothAdapterProperties( 3258): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:255
W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3203): we got incoming connection
I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3203): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started
,I/BTListenerThread( 3203): got MESSAGE_READ 82 bytes.,
I/BTListenerThread( 3203): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3203): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3203): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT2552
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3203): Starting the connected thread incoming : true, samsung-SM-G900F_PT2552
I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3203): Creating BTConnectedThread
,I/BtConnectorHelper( 3203): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3203): --DoOneRunRound started
,I/BtToRequestSocket( 3203): LocalHost address: localhost/127.0.0.1, port: 36926
,I/BtToRequestSocket( 3203): --DoOneRunRound ended
,I/jxcore-log( 3203): TCP/IP server connected
I/jxcore-log( 3203): 
,I/        ( 3203): Started service discovery
,I/jxcore-log( 3203): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 14132 bytes of data
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 18364 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 26284 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 30244 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 36184 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 38164 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 77764 bytes of data
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3203): ,
,I/jxcore-log( 3203): TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 99544 bytes of data
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3203): 
,I/        ( 3203): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5629, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5629, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 3203): Connect (retry count 0) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 80:01:84:8A:B3:68, name: null
,I/BTConnectToThread( 3203): Starting to connect
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3203): Connecting to null, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3203): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9217, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9217, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3203): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3303, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3303, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3258): info:x10
,D/        ( 3258): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2ebc rs_disc_pending=1
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3258): process_service_search_attr_rsp
,D/btif_config( 3258): btif_get_device_type: Device [80:01:84:8a:b3:68] type 1
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
,E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c,
I/BluetoothBondStateMachine( 3258): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0,
,D/BluetoothAdapterProperties( 3258): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:1
W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3203): Starting to Handshake
I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3203): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2ebc rs_disc_pending=1
W/bt-btif ( 3258): bta_dm_check_av:0
,W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3203): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3203): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3203): HandshakeOk : HTC-HTC Desire 820_PT9217
,I/HS      ( 3203): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9217
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3203): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9217
,I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3203): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3203): mHTTPPort  set to : 45504
,I/BtConnectorHelper( 3203): Request socket is using : 45504
I/BtToRequestSocket( 3203): Now accepting connections
,I/BtConnectorHelper( 3203): Calling ConnectionStatusUpdate with port :45504
,I/jxcore-log( 3203): CLIENT connected to 45504, error: null
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT starting client 
I/jxcore-log( 3203): 
,I/BtToRequestSocket( 3203): incoming data from: /127.0.0.1, port: 45504
,I/BtToRequestSocket( 3203): Set local streams
I/BtToRequestSocket( 3203): rin ended ---------------------------;
,I/jxcore-log( 3203): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 10000
I/jxcore-log( 3203): 
,D/        ( 3258): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:3237
,I/jxcore-log( 3203): CLIENT is data received : 20000
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 30000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 40000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 50000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 60000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 70000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 80000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 90000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 100000,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): got all data for this round
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT closeClientSocket
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 7743 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
I/BtToSocketBase( 3203): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3203): Disconnect outgoing peer: HTC-HTC Desire 820_PT9217
I/BtToSocketBase( 3203): Stop ReceivingThread
,I/BtToSocketBase( 3203): Stop SendingThread
I/BtToSocketBase( 3203): Close local in
I/BtToSocketBase( 3203): Close LocalOutputStream
,I/BtToSocketBase( 3203): Close localHostSocket
I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Close bt out
,I/BtToSocketBase( 3203): Close bt socket
I/BtToRequestSocket( 3203): Close server socket
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3203): CLIENT is closed
I/jxcore-log( 3203): 
,W/bt-btif ( 3258): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2ebc rs_disc_pending=0
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe3084 rs_disc_pending=0
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,I/jxcore-log( 3203): Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
I/        ( 3203): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/BTConnectToThread( 3203): Starting to connect,
W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3203): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3258): invalid rfc slot id: 14,
I/BtToSocketBase( 3203): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3203): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2552,
I/BtToSocketBase( 3203): Stop ReceivingThread
I/BtToSocketBase( 3203): Stop SendingThread
I/BtToSocketBase( 3203): Close local in
I/BtToSocketBase( 3203): Close LocalOutputStream
,I/BtToSocketBase( 3203): Close localHostSocket
I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3203): Close bt socket
I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3203): TCP/IP server is ended
I/jxcore-log( 3203): 
I/jxcore-log( 3203): TCP/IP server is close
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2ebc rs_disc_pending=1
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3258): onReceive
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe3084 rs_disc_pending=1
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3258): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 3258): RFCOMM_DisconnectInd LCID:0x4a
,W/bt-btif ( 3258): info:x10
D/        ( 3258): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe3084 rs_disc_pending=0
W/bt-btif ( 3258): bta_dm_check_av:0
,W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3258): info:x10
,D/        ( 3258): remote version info [34:fc:ef:9d:93:0b]: 0, 0, 0
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe207c rs_disc_pending=0
W/bt-btif ( 3258): bta_dm_check_av:0
,W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3258): info:x10
,D/        ( 3258): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL,
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2244 rs_disc_pending=0
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3258): onReceive,
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe207c rs_disc_pending=1
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/BluetoothClassifier( 4051): Bluetooth Device Name: S5-1
W/bt-sdp  ( 3258): process_service_search_attr_rsp
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe2244 rs_disc_pending=1
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,D/btif_config( 3258): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1,
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1,
E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3258): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 3258): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3203): we got incoming connection
,I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread
I/BTListenerThread( 3203): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started
,E/bt-btm  ( 3258): invalid rfc slot id: 19
W/bt-btif ( 3258): invalid rfc slot id: 19
,I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
D/BluetoothMapService( 3258): onReceive
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 9513 ms, rnd: 1, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe207c rs_disc_pending=0
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3203): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3203): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3203): MESSAGE_WRITE 82 bytes.
I/HS      ( 3203): Incoming connection Hand Shake finished for : LGE-LG-D802_PT7492
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3203): Starting the connected thread incoming : true, LGE-LG-D802_PT7492
I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3203): Creating BTConnectedThread
I/BtConnectorHelper( 3203): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3203): --DoOneRunRound started
,I/BtToRequestSocket( 3203): LocalHost address: localhost/127.0.0.1, port: 36926
,I/BtToRequestSocket( 3203): --DoOneRunRound ended
,I/jxcore-log( 3203): TCP/IP server connected,
I/jxcore-log( 3203): 
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3203): Found 3 peers.
,I/SS      ( 3203): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3203): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3203): Peer(3): Android_63cc 82:01:84:6b:e8:5d
D/WifiP2pManager( 3203): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3203): Added service request
,I/jxcore-log( 3203): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3203): 
,D/btif_config( 3258): btif_get_device_type: Device [b4:ce:f6:ab:a4:6a] type 1
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State
I/BluetoothBondStateMachine( 3258): sspRequestCallback: [B@2552be25 name: [B@fc86bfa cod: 5898764 pairingVariant 0 passkey: 182735
,I/jxcore-log( 3203): TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 73804 bytes of data
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 77764 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 79744 bytes of data,
I/jxcore-log( 3203): 
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/jxcore-log( 3203): TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3203): 
,I/        ( 3203): Started service discovery
,I/jxcore-log( 3203): TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3203): 
,W/bt-btif ( 3258): invalid rfc slot id: 17
I/BtToSocketBase( 3203): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3203): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT7492
I/BtToSocketBase( 3203): Stop ReceivingThread
I/BtToSocketBase( 3203): Stop SendingThread
,I/BtToSocketBase( 3203): Close local in
I/BtToSocketBase( 3203): Close LocalOutputStream
,I/BtToSocketBase( 3203): Close localHostSocket
I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3203): Close bt out
,I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3203): Close bt socket
I/BtConnectorHelper( 3203): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT7492
I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Close bt out
,I/BtToSocketBase( 3203): Close bt socket
I/jxcore-log( 3203): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server is ended
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server is close
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe207c rs_disc_pending=1
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3258): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 3258): RFCOMM_DisconnectInd LCID:0x43
,I/        ( 3203): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1820"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1820"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT1820, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT1820, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3203): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5629, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5629, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3203): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"}, typeCordovap2p._tcp.local.:,
I/        ( 3203): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9217, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9217, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3203): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3303, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3303, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,W/bt-btif ( 3258): info:x10,
D/        ( 3258): remote version info [80:01:84:8a:b3:68]: 6, f, 410d
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 4051): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3203): we got incoming connection
,I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread
I/BTListenerThread( 3203): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started
,I/BTListenerThread( 3203): got MESSAGE_READ 84 bytes.
,I/BTListenerThread( 3203): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3203): MESSAGE_WRITE 82 bytes.
I/HS      ( 3203): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT9217
,I/BtConnectorHelper( 3203): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT9217
,I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3203): Creating BTConnectedThread
I/BtConnectorHelper( 3203): Server socket is using : 0, and is now connected.
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3203): --DoOneRunRound started
,I/BtToRequestSocket( 3203): LocalHost address: localhost/127.0.0.1, port: 36926
,I/BtToRequestSocket( 3203): --DoOneRunRound ended
,I/jxcore-log( 3203): TCP/IP server connected
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 1980 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 9900 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 11880 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3203): ,
,I/jxcore-log( 3203): TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Connect (retry count 0) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 08:EC:A9:50:75:41, name: null
,I/BTConnectToThread( 3203): Starting to connect
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3203): Connecting to null, at 08:EC:A9:50:75:41
,I/jxcore-log( 3203): TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3203): 
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3203): TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3203): 
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3258): onReceive
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: Thali Test's G2
,I/jxcore-log( 3203): TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 61380 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 67320 bytes of data,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3203): ,
,I/jxcore-log( 3203): TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3203): 
,W/bt-btif ( 3258): info:x10
,D/        ( 3258): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3203): TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3203): 
,W/bt-btif ( 3258): invalid rfc slot id: 20
,I/BtToSocketBase( 3203): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3203): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9217
I/BtToSocketBase( 3203): Stop ReceivingThread
,I/BtToSocketBase( 3203): Stop SendingThread
,I/BtToSocketBase( 3203): Close local in
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3203): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed,
I/BtConnectorHelper( 3203): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9217
I/BtToSocketBase( 3203): Close LocalOutputStream
I/BtToSocketBase( 3203): Close localHostSocket
,I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Close bt out
,I/BtToSocketBase( 3203): Close bt socket
I/jxcore-log( 3203): TCP/IP server is ended
I/jxcore-log( 3203): 
I/jxcore-log( 3203): TCP/IP server is close
I/jxcore-log( 3203): 
,W/bt-rfcomm( 3258): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3258): RFCOMM_DisconnectInd LCID:0x49
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe324c rs_disc_pending=0,
W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3258): process_service_search_attr_rsp
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/        ( 3203): Cleared service requests,
,I/        ( 3203): Started peer discovery
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3258): onReceive
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: HTC Desire 820
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe324c rs_disc_pending=1
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 6 peers.
,I/SS      ( 3203): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3203): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3203): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3203): Peer(6): Android_63cc 82:01:84:6b:e8:5d
D/WifiP2pManager( 3203): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3258): btm_sec_disconnected - 
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 17134 ms, rnd: 1, ex: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3203): Started service discovery
,I/        ( 3203): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2552, peerAddress: 7C:F9:0E:34:8A:A0,
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2552, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3203): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT9468, peerAddress: F4:F1:E1:5C:3B:E2,
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT9468, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3203): Connect (retry count 0) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3203): Starting to connect
W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3203): Connecting to null, at 7C:F9:0E:37:96:AB,
D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3258): info:x10
D/        ( 3258): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe3414 rs_disc_pending=1
,W/bt-btif ( 3258): bta_dm_check_av:0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 8 peers.
,I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3203): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3203): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3203): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3203): Added service request
,I/wpa_supplicant( 3269): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3203): Started service discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe25d4 rs_disc_pending=0
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3258): Device not in IRK list
E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
,W/bt-btif ( 3258): bta_dm_check_av:0
E/bt-btif ( 3258): Do not find the bg connection mask for the remote device
I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 9 Address: B4:CE:F6:AB:A4:6A newState: 0
W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
D/BluetoothAdapterProperties( 3258): Failed to remove device: B4:CE:F6:AB:A4:6A,
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,D/BluetoothMapService( 3258): onReceive
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: HTC Desire 820
,E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,E/bt-btm  ( 3258): invalid rfc slot id: 23
W/bt-btif ( 3258): invalid rfc slot id: 23
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 15848 ms, rnd: 1, ex: Connection to 7C:F9:0E:37:96:AB failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): Connect (retry count 0) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/BTConnectToThread( 3203): Starting to connect
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3203): Connecting to null, at 44:80:EB:7B:5A:05
D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3258): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
,E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3258): invalid rfc slot id: 24
,I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 9154 ms, rnd: 1, ex: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2,
,I/jxcore-log( 3203): Connect (retry count 0) to peer 34:FC:EF:11:AE:67 with availability status: true,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 34:FC:EF:11:AE:67, name: Nexus 5,
,I/        ( 3203): Connecting to Nexus 5, at 34:FC:EF:11:AE:67,
,I/BTConnectToThread( 3203): Starting to connect
W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0,
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery,
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 7 peers.
I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3203): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3203): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 3203): Added service request
,I/        ( 3203): Started service discovery
,I/        ( 3203): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3203): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2743, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2743, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-sdp  ( 3258): SDP - Rcvd conn cnf with error: 0x8  CID 0x4f
,E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3258): invalid rfc slot id: 25
,I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- gotta redo : 34:FC:EF:11:AE:67, try count now: 1,
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start,
I/jxcore-log( 3203): ,
I/jxcore-log( 3203): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3203): 
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 56819 ms, rnd: 1, ex: Connection to 34:FC:EF:11:AE:67 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3203): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2552, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2552, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b,
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/jxcore-log( 3203): Connect (retry count 0) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 3203): Connecting to null, at F4:F1:E1:5C:3B:E2
I/BTConnectToThread( 3203): Starting to connect
W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,W/bt-sdp  ( 3258): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
,E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3258): invalid rfc slot id: 26
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 9159 ms, rnd: 1, ex: Connection to F4:F1:E1:5C:3B:E2 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): Connect (retry count 0) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/        ( 3203): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
I/BTConnectToThread( 3203): Starting to connect
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 4 peers.
,I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3203): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3203): Peer(4): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3203): Added service request
,I/wpa_supplicant( 3269): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3203): Started service discovery
,I/        ( 3203): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT5540","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT5540","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT5540, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT5540, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 5 peers.,
,I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3203): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3203): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,I/        ( 3203): Started service discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,W/bt-sdp  ( 3258): SDP - Rcvd conn cnf with error: 0x8  CID 0x4a,
E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3258): invalid rfc slot id: 27
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- gotta redo : 7C:F9:0E:34:8A:A0, try count now: 1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 55704 ms, rnd: 1, ex: Connection to 7C:F9:0E:34:8A:A0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): Connect (retry count 0) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/BTConnectToThread( 3203): Starting to connect
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3203): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3203): Found 3 peers.
I/SS      ( 3203): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(3): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3203): Started service discovery
,I/        ( 3203): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7492, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7492, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3203): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9217, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9217, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3203): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5861","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5861","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT5861, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT5861, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3203): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3303, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3303, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3203): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2552, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2552, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3203): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9628, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9628, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3203): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1820"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1820"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT1820, peerAddress: 34:FC:EF:11:B1:66
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT1820, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 5 peers.
I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3203): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3203): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3203): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,W/bt-sdp  ( 3258): SDP - Rcvd conn cnf with error: 0x8  CID 0x40
,E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3258): invalid rfc slot id: 28
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- round done--------,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : E0:DB:10:1F:C9:5E, try count now: 1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do fake peer & start,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 55887 ms, rnd: 1, ex: Connection to E0:DB:10:1F:C9:5E failed", source: file:///android_asset/www/js/thali_main.js (63),
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3203): Started service discovery,
,I/        ( 3203): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3203): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7492, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7492, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3203): Connect (retry count 0) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: F8:95:C7:87:85:54, name: null
,I/BTConnectToThread( 3203): Starting to connect
W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3203): Connecting to null, at F8:95:C7:87:85:54
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3258): info:x10
,D/        ( 3258): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3258): process_service_search_attr_rsp
,E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3258): invalid rfc slot id: 29
,I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3203): 
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 4902 ms, rnd: 1, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3203): Connect (retry count 0) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 58:3F:54:73:64:C0, name: G3-1
,I/BTConnectToThread( 3203): Starting to connect
,I/        ( 3203): Connecting to G3-1, at 58:3F:54:73:64:C0
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 7 peers.
,I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3203): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3203): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3203): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3203): Added service request
,I/        ( 3203): Started service discovery
,I/        ( 3203): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3203): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7492, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7492, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3203): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"}, typeCordovap2p._tcp.local.:,
,I/        ( 3203): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9217, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9217, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3203): Cleared service requests
I/        ( 3203): Started peer discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 8 peers.
,I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3203): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3203): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3203): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3203): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3203): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,I/        ( 3203): Started service discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3203): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT1968, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT1968, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 10 peers.
I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3203): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3203): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3203): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3203): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3203): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,I/        ( 3203): Started service discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3203): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2743, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2743, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-sdp  ( 3258): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3258): invalid rfc slot id: 30
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3203): 
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 36296 ms, rnd: 1, ex: Connection to 58:3F:54:73:64:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3203): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT1968, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT1968, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,D/GCM     ( 1485): Message class com.google.f.a.a.i
,I/jxcore-log( 3203): Connect (retry count 0) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 58:2A:F7:ED:96:BE, name: null,
,I/        ( 3203): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3203): Starting to connect
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3258): info:x10
D/        ( 3258): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3258): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3258): process_service_search_attr_rsp
,D/btif_config( 3258): btif_get_device_type: Device [58:2a:f7:ed:96:be] type 1
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 3258): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3258): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3258): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3258): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
D/BluetoothAdapterProperties( 3258): Failed to remove device: 58:2A:F7:ED:96:BE
I/BluetoothBondStateMachine( 3258): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3258): StableState(): Entering Off State,
,W/bt-btif ( 3258): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3258): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3258): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3203): Starting to Handshake
,I/BTHandshakeSocketThread( 3203): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3203): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread started
,I/BTConnectToThread( 3203): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3203): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9956","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3203): HandshakeOk : HUAWEI-ALE-L21_PT9956
I/HS      ( 3203): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT9956
I/BTHandshakeSocketThread( 3203): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3203): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT9956
I/BtToSocketBase( 3203): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3203): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3203): mHTTPPort  set to : 46672
,I/BtConnectorHelper( 3203): Request socket is using : 46672
I/BtToRequestSocket( 3203): Now accepting connections
,I/BtConnectorHelper( 3203): Calling ConnectionStatusUpdate with port :46672
I/jxcore-log( 3203): CLIENT connected to 46672, error: null
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT starting client 
I/jxcore-log( 3203): 
,I/BtToRequestSocket( 3203): incoming data from: /127.0.0.1, port: 46672,
,I/BtToRequestSocket( 3203): Set local streams
I/BtToRequestSocket( 3203): rin ended ---------------------------;
,I/jxcore-log( 3203): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3203): 
,D/        ( 3258): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:28939
,I/jxcore-log( 3203): CLIENT is data received : 10000
I/jxcore-log( 3203): 
,D/        ( 3258): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22009
,I/jxcore-log( 3203): CLIENT is data received : 20000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 30000
I/jxcore-log( 3203): 
,D/        ( 3258): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3203): CLIENT is data received : 40000
I/jxcore-log( 3203): 
,D/        ( 3258): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7159
,I/jxcore-log( 3203): CLIENT is data received : 50000
,I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 60000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 70000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 80000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 90000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT is data received : 100000
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): got all data for this round
I/jxcore-log( 3203): ,
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT closeClientSocket
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: B4:CE:F6:AB:A4:6A,
I/jxcore-log( 3203): 
,I/BtToSocketBase( 3203): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3203): Disconnect outgoing peer: HUAWEI-ALE-L21_PT9956
I/BtToSocketBase( 3203): Stop ReceivingThread
I/BtToSocketBase( 3203): Stop SendingThread
I/BtToSocketBase( 3203): Close local in
I/BtToSocketBase( 3203): Close LocalOutputStream
,I/BtToSocketBase( 3203): Close localHostSocket
I/BtToSocketBase( 3203): Close bt in
I/BtToSocketBase( 3203): Close bt out
I/BtToSocketBase( 3203): Close bt socket
I/BtToRequestSocket( 3203): Close server socket
I/BtToSocketBase( 3203): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 6777 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): CLIENT is closed
I/jxcore-log( 3203): 
,W/bt-btif ( 3258): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,I/jxcore-log( 3203): Connect (retry count 0) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/BTConnectToThread( 3203): Starting to connect
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3203): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3258): tBTM_SEC_DEV:0xa2fe396c rs_disc_pending=0
,E/bt-btm  ( 3258): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3258): bta_dm_check_av:0
,W/bt-btif ( 3258): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3258): onReceive
,I/BTConnectionReceiver( 4051): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4051): Bluetooth Device Name: ALE-L21
,D/btif_config_util( 3258): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 11 peers.
I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3203): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3203): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3203): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3203): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3203): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,I/        ( 3203): Started service discovery
,I/        ( 3203): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT9468, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT9468, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3203): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2743, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2743, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3203): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT1968, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT1968, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 8 peers.,
I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(2): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3203): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3203): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3203): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3203): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3203): Added service request
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/        ( 3203): Started service discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3203): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:,
I/        ( 3203): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3303, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3303, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0,
,I/        ( 3203): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT9468, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT9468, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3203): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2743, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2743, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3203): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:,
I/        ( 3203): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT1968, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT1968, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3203): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3203): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7492, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7492, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3203): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
I/        ( 3203): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2552, peerAddress: 7C:F9:0E:34:8A:A0,
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2552, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3203): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9628, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9628, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery,
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3203): Found 9 peers.
I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3203): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3203): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3203): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3203): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3203): Added service request
,I/        ( 3203): Started service discovery
,I/        ( 3203): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5629, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5629, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery,
,I/BooksSync( 3558): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3558): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3558): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3558): Soft error
E/BooksSync( 3558): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3558): Sync error
E/BooksSync( 3558): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3558): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3558): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1116531, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/SS      ( 3203): Found 9 peers.
,I/SS      ( 3203): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3203): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3203): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3203): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3203): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,W/bt-sdp  ( 3258): SDP - Rcvd conn cnf with error: 0x8  CID 0x47
,E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3258): invalid rfc slot id: 32
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 2
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 57525 ms, rnd: 1, ex: Connection to B4:CE:F6:AB:A4:6A failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0,
I/wpa_supplicant( 3269): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3203): Started service discovery
,I/        ( 3203): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7297, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7297, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3203): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5629, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5629, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 3203): Connect (retry count 0) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 08:EC:A9:50:76:27, name: null,
,I/BTConnectToThread( 3203): Starting to connect
W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3203): Connecting to null, at 08:EC:A9:50:76:27
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 10 peers.
I/SS      ( 3203): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3203): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3203): Peer(4): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3203): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(7): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3203): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3203): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,I/        ( 3203): Started service discovery
,I/        ( 3203): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7297, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7297, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3203): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5629, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5629, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 10 peers.,
I/SS      ( 3203): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3203): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3203): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3203): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
I/SS      ( 3203): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(7): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3203): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3203): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3203): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3203): Added service request
,I/wpa_supplicant( 3269): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3203): Started service discovery
,W/bt-sdp  ( 3258): SDP - Rcvd conn cnf with error: 0x8  CID 0x43
E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3258): invalid rfc slot id: 33
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 2
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 36062 ms, rnd: 1, ex: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): Connect (retry count 0) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3203): Connecting to null, at 34:FC:EF:11:B1:66
I/BTConnectToThread( 3203): Starting to connect
,W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3203): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:,
I/        ( 3203): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7297, peerAddress: 08:EC:A9:50:76:27,
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7297, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3203): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5629, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5629, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 3258): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
,E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3258): invalid rfc slot id: 34
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 2
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3203): 
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 9164 ms, rnd: 1, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3203): Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): 
,I/        ( 3203): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/BTConnectToThread( 3203): Starting to connect
W/BluetoothAdapter( 3203): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3203): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3258): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,V/GoogleAuthProtoRequest( 3277): [341] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3277): [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3277): [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): ,	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	,at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
,W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	,at com.a.a.k.run(SourceFile:110)
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 11 peers.
,I/SS      ( 3203): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3203): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3203): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3203): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(7): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(8): G4-1 a2:39:f7:6f:c9:5d,
I/SS      ( 3203): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3203): Peer(10): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3203): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3203): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3203): Added service request
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3203): Started service discovery
,I/        ( 3203): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3203): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3303, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3303, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3203): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6254","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6254","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6254, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6254, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3203): Cleared service requests
,I/        ( 3203): Started peer discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3203): Found 12 peers.
,I/SS      ( 3203): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3203): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3203): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3203): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3203): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(7): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3203): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3203): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3203): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3203): Peer(11): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3203): Peer(12): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3203): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3203): Added service request
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/        ( 3203): Started service discovery
,E/HttpOperation( 2971): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at blb.a(PG:3937)
E/HttpOperation( 2971): 	at czp.a(PG:18188)
E/HttpOperation( 2971): 	at czp.a(PG:9087)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 12 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 14 more
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 63550(3MB) AllocSpace objects, 13(1434KB) LOS objects, 37% free, 27MB/43MB, paused 1.903ms total 37.720ms
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at blb.a(PG:3937)
E/HttpOperation( 2971): 	at czp.a(PG:18188)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 12 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 14 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at hec.a(PG:42)
E/HttpOperation( 2971): 	at hee.a(PG:102)
E/HttpOperation( 2971): 	at czr.a(PG:65)
E/HttpOperation( 2971): 	at kka.a(PG:108)
E/HttpOperation( 2971): 	at czp.a(PG:19176)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 15 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 17 more
,E/ExperimentLoader( 2971): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): 	at jdm.a(PG:82)
E/ExperimentLoader( 2971): 	at jcs.o(PG:406)
E/ExperimentLoader( 2971): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2971): 	at jcs.i(PG:143)
E/ExperimentLoader( 2971): 	at hec.a(PG:42)
E/ExperimentLoader( 2971): 	at hee.a(PG:102)
E/ExperimentLoader( 2971): 	at czr.a(PG:65)
E/ExperimentLoader( 2971): 	at kka.a(PG:108)
E/ExperimentLoader( 2971): 	at czp.a(PG:19176)
E/ExperimentLoader( 2971): 	at czp.a(PG:9081)
E/ExperimentLoader( 2971): 	at czq.run(PG:1686)
E/ExperimentLoader( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2971): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2971): 	,at jdj.a(PG:1125)
E/ExperimentLoader( 2971): 	at jdm.a(PG:77)
E/ExperimentLoader( 2971): 	... 15 more
E/ExperimentLoader( 2971): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2971): 	at fal.a(PG:38)
E/ExperimentLoader( 2971): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2971): 	... 17 more
,I/        ( 3203): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3303, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3303, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 699828, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/        ( 3203): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6254","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6254","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6254, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6254, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/wpa_supplicant( 3269): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/        ( 3203): Cleared service requests,
I/        ( 3203): Started peer discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3203): Found 11 peers.
,I/SS      ( 3203): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3203): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3203): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3203): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3203): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3203): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3203): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3203): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3203): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3203): Peer(10): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3203): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3203): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3203): Added service request
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3203): Started service discovery
,I/wpa_supplicant( 3269): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3203): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7297, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7297, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3203): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2743, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2743, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3203): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3303, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3303, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3203): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6254","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3203): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6254","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6254, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3203): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6254, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,--------- beginning of crash
,F/libc    ( 3269): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 3269 (wpa_supplicant)
I/libc    ( 3269): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
I/        ( 3203): Cleared service requests
,W/bt-sdp  ( 3258): SDP - Rcvd conn cnf with error: 0x8  CID 0x49
,E/bt-btif ( 3258): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3258): invalid rfc slot id: 35
I/BTConnectToThread( 3203): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3203): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3203): CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3203): 
I/jxcore-log( 3203): CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): CLIENT Stop now,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): ---- round done--------
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 2
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): do fake peer & start
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3203): 
I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback round[0] time: 56641 ms, rnd: 1, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiHW  (  821): 'P2P_FIND 120' command timed out.
,I/        ( 3203): Starting peer discovery failed, error code 0
,E/WifiStateMachine(  821): Connection lost, restart supplicant
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
W/Settings( 2632): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,W/Settings( 1752): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): failed to set BSSID: any
E/native  (  821): do suspend true
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1485): Read error: ssl=0xaec58800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1485): SSL shutdown failed: ssl=0xaec58800: I/O error during system call, Broken pipe
I/jxcore-log( 3203): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3203): 
I/jxcore-log( 3203): The Coordinator has disconnected!
I/jxcore-log( 3203): 
,D/ConnectivityService(  821): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/WifiStateMachine(  821): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  821): Unexpected BatchedScanResults :null
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiScanningService(  821): SCAN_AVAILABLE : 1
,D/RttService(  821): SCAN_AVAILABLE : 1
D/WifiScanningService(  821): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  821): DefaultState
D/RttService(  821): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3203): Discovery state changed to Stopped.
,D/WifiNetworkAgent(  821): NetworkAgent: NetworkAgent channel lost
,I/WB      ( 3203): Wifi is DISABLED !!
I/        ( 3203): Stoping All
I/        ( 3203): Stopping services
I/        ( 3203): Stopping services
,D/ConnectivityService(  821): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  821): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524292
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  821): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=false
,I/art     (  821): Explicit concurrent mark sweep GC freed 66513(3MB) AllocSpace objects, 5(268KB) LOS objects, 32% free, 33MB/49MB, paused 1.491ms total 65.013ms
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/        ( 3203): Stop Bluetooth
I/        ( 3203): Stop Bluetooth
I/BTListenerThread( 3203): Stopped
,I/SS      ( 3203): We got empty peers list
I/        ( 3203): Starting peer discovery failed, error code 2
I/        ( 3203): Clearing local services failed, error code 2
,I/        ( 3203): Clearing service requests failed, error code 2
I/        ( 3203): Stopping peer discovery failed, error code 2
,D/Tethering(  821): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
,I/ActivityManager(  821): Start proc 4296:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/GpsLocationProvider(  821): No APN found to select.
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,E/GpsLocationProvider(  821): No APN found to select.
,D/SprintDMReceiver( 4296): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4296): simOperator:  IMSI: null
,D/SprintDMReceiver( 4296): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1781): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1781): onCreate,
,D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1781): active receiver: enabled
,I/SystemUpdateService( 1781): showing system update notification
,I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 1781): num queued entries: 0
,I/iu.UploadsManager( 1781): num updated entries: 0
I/iu.SyncManager( 1781): NEXT; no task
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1781): retry (wakeup: false) in 3599942 ms
,I/Babel   ( 2632): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  821): Start proc 4316:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1781): onDestroy
,I/ActivityManager(  821): Killing 3651:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/GAv4    ( 4316): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4316):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4316):   adb logcat -s GAv4
,W/GAv4    ( 4316): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4316): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4316): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 4316): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4316): Time to load native libraries: 2 ms (timestamps 4719-4721),
I/LibraryLoader( 4316): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4316): Binding Chromium to main looper Looper (main, tid 1) {1b8919d9}
,I/LibraryLoader( 4316): Expected native library version number "",actual native library version number ""
,I/chromium( 4316): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4316): Initializing chromium process, singleProcess=true,
W/art     ( 4316): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4316): ApplicationContext is null in ApplicationStatus
,W/chromium( 4316): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4316): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4316): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 4316): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,W/AudioManagerAndroid( 4316): Requires BLUETOOTH permission
,I/NSApplication( 4316): Starting up...
,I/ActivityManager(  821): Killing 3671:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/jxcore-log( 3203): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3203): 
I/jxcore-log( 3203): printNetworkInfo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): found interfaceName: lo
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3203): 
I/jxcore-log( 3203): Turning Wifi off
I/jxcore-log( 3203): 
D/WifiService(  821): setWifiEnabled: false pid=3203, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3203): Turning Wifi back on
I/jxcore-log( 3203): 
,D/WifiService(  821): setWifiEnabled: true pid=3203, uid=10265
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiController(  821): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 482ms
,I/jxcore-log( 3203): toggleWiFi finished
I/jxcore-log( 3203): 
,I/jxcore-log( 3203): ReconnectWifiAP finished
I/jxcore-log( 3203): 
,I/chromium( 3203): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  821): Start proc 4374:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  821): Killing 3837:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/SprintDMReceiver( 4296): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4296): simOperator:  IMSI: null
,D/SprintDMReceiver( 4296): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1781): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/WifiController(  821): DEFERRED_TOGGLE handled
,D/SoftapController(  353): Softap fwReload - Ok
,D/CommandListener(  353): Setting iface cfg
D/CommandListener(  353): Trying to bring down wlan0
D/SystemUpdateService( 1781): onCreate
,D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1781): active receiver: enabled
,I/SystemUpdateService( 1781): showing system update notification
,D/Tethering(  821): InitialState.processMessage what=4
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/Tethering(  821): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor(  821): startMonitoring(wlan0) with mConnected = false
,E/WifiHW  (  821): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1781): retry (wakeup: false) in 3599948 ms
,D/SystemUpdateService( 1781): onDestroy
,I/wpa_supplicant( 4392): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4392): rfkill: Cannot open RFKILL control device
,I/jxcore-log( 3203): Connect (retry count 0) to peer 08:EC:A9:50:75:41 with availability status: true,
I/jxcore-log( 3203): 
I/jxcore-log( 3203): do connect now
I/jxcore-log( 3203): ,
,D/AndroidRuntime( 3203): Shutting down VM
,I/BtConnection( 3203): Got uncaughtException: java.lang.RuntimeException: Connector class is not initialized properly
,D/Tethering(  821): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4392): rfkill: Cannot open RFKILL control device,
E/wpa_supplicant( 4392): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  821): Loading config and enabling all networks 
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@25f4ce10}
,E/WifiConfigStore(  821): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 2632): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  821): Setting external_sim to 1
D/WifiStateMachine(  821): Setting OUI to 92-68-C3
I/WifiNative-HAL(  821): startHal
D/wifi    (  821): setting scan oui 0xaee03568
,D/WifiHAL (  821): Sending mac address OUI
,E/native  (  821): do suspend true
,D/WifiScanningService(  821): SCAN_AVAILABLE : 3
,D/RttService(  821): SCAN_AVAILABLE : 3
,W/CommandListener(  353): Failed to retrieve HW addr for p2p0 (No such device)
D/WifiScanningService(  821): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  821): startHal
,D/wifi    (  821): getting scan capabilities on interface[0] = 0xaee03568
D/WifiHAL (  821): Creating message to get scan capablities; iface = 5
D/WifiHAL (  821): In GetCapabilities::handleResponse
,D/WifiHAL (  821): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  821): StartedState
D/RttService(  821): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  353): Setting iface cfg
E/WifiP2pService(  821): Unable to change interface settings: java.lang.IllegalStateException: command '56 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 56 Failed to set address (No such device)'
D/WifiMonitor(  821): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  821): p2pGetDeviceAddress
,D/WifiNative-HAL(  821): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 4392): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/wpa_supplicant( 4392): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  821):  rewrite network history for "NG700"WPA_PSK
,E/WifiConfigStore(  821):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3,
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0,
,E/WifiConfigStore(  821): will read network variables netId=0,
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,I/wpa_supplicant( 4392): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 4392): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4392): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4392): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
E/WifiStateMachine(  821): Start Dhcp Watchdog 2
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 0,
E/WifiStateMachine(  821):  RSSI mgmt: -46
E/WifiStateMachine(  821):  BE :  rx=0 tx=2 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 0 tx_time=57 rx_time=393 scan_time=0
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 4404): version 5.5.6 starting
,I/dhcpcd  ( 4404): wlan0: rebinding lease of 192.168.1.110
,I/dhcpcd  ( 4404): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 4404): wlan0: leased 192.168.1.110 for 86400 seconds,
,E/native  (  821): do suspend true
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 101
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  821): Setting Dns servers for network 101 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821):    accepting network in place of null,
D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1278): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,D/Tethering(  821): MasterInitialState.processMessage what=3,
,I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  821): No APN found to select.
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 4296): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4296): simOperator:  IMSI: null
D/SprintDMReceiver( 4296): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1781): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1781): onCreate
,D/SystemUpdateService( 1781): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1781): active receiver: enabled
,I/SystemUpdateService( 1781): showing system update notification
,I/iu.Environment( 1781): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1781): num queued entries: 0
I/iu.UploadsManager( 1781): num updated entries: 0
I/iu.SyncManager( 1781): NEXT; no task
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  821): skipping global notification
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1781): retry (wakeup: false) in 3599960 ms
,D/SystemUpdateService( 1781): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 23 Nov 2015 15:57:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448294221884], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448294221869]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1062): CM callback handler got msg 524290
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1781): NQAS connected
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/KeepSync( 3303): Connecting to GoogleApiClient
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1781): [AccountUtils] Account not ready
W/Kids    ( 1781): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1781): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1781): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1781): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1781): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1781): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1781): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1781): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1781): 	at java.lang.Thread.run(Thread.java:818)
,E/HttpOperation( 2971): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at blb.a(PG:3937)
E/HttpOperation( 2971): 	at czp.a(PG:18188)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 12 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 14 more
I/Babel   ( 2632): connection state changed from DISCONNECTED to CONNECTED
,I/art     ( 1752): Explicit concurrent mark sweep GC freed 18694(1092KB) AllocSpace objects, 10(160KB) LOS objects, 37% free, 26MB/42MB, paused 4.012ms total 61.391ms
,E/DataBuffer( 1752): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@6a71dc9)
,E/DataBuffer( 1752): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@12b11cce)
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at hec.a(PG:42)
E/HttpOperation( 2971): 	at hee.a(PG:102)
E/HttpOperation( 2971): 	at czr.a(PG:65)
E/HttpOperation( 2971): 	at kka.a(PG:108)
E/HttpOperation( 2971): 	at czp.a(PG:19176)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 15 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 17 more
,E/ExperimentLoader( 2971): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): 	at jdm.a(PG:82)
E/ExperimentLoader( 2971): 	at jcs.o(PG:406)
E/ExperimentLoader( 2971): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2971): 	at jcs.i(PG:143)
E/ExperimentLoader( 2971): 	at hec.a(PG:42)
E/ExperimentLoader( 2971): 	at hee.a(PG:102)
E/ExperimentLoader( 2971): 	at czr.a(PG:65)
E/ExperimentLoader( 2971): 	at kka.a(PG:108)
E/ExperimentLoader( 2971): 	at czp.a(PG:19176)
E/ExperimentLoader( 2971): 	at czp.a(PG:9081)
E/ExperimentLoader( 2971): 	at czq.run(PG:1686)
E/ExperimentLoader( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2971): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2971): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2971): 	at jdm.a(PG:77)
E/ExperimentLoader( 2971): 	... 15 more
E/ExperimentLoader( 2971): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2971): 	at fal.a(PG:38)
E/ExperimentLoader( 2971): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2971): 	... 17 more
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3303): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@25f4ce10}
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1222384, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  821): Explicit concurrent mark sweep GC freed 56058(2MB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 1.361ms total 62.250ms
,D/GCM     ( 1485): Connected
,D/GCM     ( 1485): Message class com.google.f.a.a.p
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3303): IOException
E/KeepSync( 3303): com.google.android.apiary.AuthenticationException: Could not get an auth token,
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3303): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3303): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3303): ,	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3303): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3303): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3303): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
,E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3303): 	... 10 more
W/KeepSync( 3303): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1231081, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  821): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,V/KeepSync( 3303): Connecting to GoogleApiClient
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3303): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at blb.a(PG:3937)
E/HttpOperation( 2971): 	at czp.a(PG:18188)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 12 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 14 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at hec.a(PG:42)
E/HttpOperation( 2971): 	at hee.a(PG:102)
E/HttpOperation( 2971): 	at czr.a(PG:65)
E/HttpOperation( 2971): 	at kka.a(PG:108)
E/HttpOperation( 2971): 	at czp.a(PG:19176)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 15 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 17 more
E/ExperimentLoader( 2971): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): 	at jdm.a(PG:82)
E/ExperimentLoader( 2971): 	at jcs.o(PG:406)
E/ExperimentLoader( 2971): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2971): 	at jcs.i(PG:143)
E/ExperimentLoader( 2971): 	at hec.a(PG:42)
E/ExperimentLoader( 2971): 	at hee.a(PG:102)
E/ExperimentLoader( 2971): 	at czr.a(PG:65)
E/ExperimentLoader( 2971): 	at kka.a(PG:108)
E/ExperimentLoader( 2971): 	at czp.a(PG:19176)
E/ExperimentLoader( 2971): 	at czp.a(PG:9081)
E/ExperimentLoader( 2971): 	at czq.run(PG:1686)
E/ExperimentLoader( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2971): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2971): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2971): 	at jdm.a(PG:77)
E/ExperimentLoader( 2971): 	... 15 more
E/ExperimentLoader( 2971): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2971): 	at fal.a(PG:38)
E/ExperimentLoader( 2971): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2971): 	... 17 more
,E/KeepSync( 3303): IOException
E/KeepSync( 3303): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3303): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3303): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3303): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3303): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3303): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3303): 	... 10 more
W/KeepSync( 3303): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1261792, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1264035, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,V/KeepSync( 3303): Connecting to GoogleApiClient
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1781): Handling authorization failure
,E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	,at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
,E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
,E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97),
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): ,	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more,
V/KeepSync( 3303): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3303): IOException
E/KeepSync( 3303): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3303): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3303): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3303): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3303): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3303): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3303): 	... 10 more
W/KeepSync( 3303): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1341902, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 58056(3MB) AllocSpace objects, 6(661KB) LOS objects, 36% free, 27MB/43MB, paused 2.271ms total 32.781ms
,E/HttpOperation( 2971): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at blb.a(PG:3937)
E/HttpOperation( 2971): 	at czp.a(PG:18188)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 12 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 14 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at hec.a(PG:42)
E/HttpOperation( 2971): 	at hee.a(PG:102)
E/HttpOperation( 2971): 	at czr.a(PG:65)
E/HttpOperation( 2971): 	at kka.a(PG:108)
E/HttpOperation( 2971): 	at czp.a(PG:19176)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 15 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 17 more
,E/ExperimentLoader( 2971): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 2971): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): 	at jdm.a(PG:82)
E/ExperimentLoader( 2971): 	at jcs.o(PG:406)
E/ExperimentLoader( 2971): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2971): 	at jcs.i(PG:143)
E/ExperimentLoader( 2971): 	at hec.a(PG:42)
E/ExperimentLoader( 2971): ,	at hee.a(PG:102)
E/ExperimentLoader( 2971): 	at czr.a(PG:65)
E/ExperimentLoader( 2971): 	at kka.a(PG:108)
E/ExperimentLoader( 2971): 	at czp.a(PG:19176)
E/ExperimentLoader( 2971): 	at czp.a(PG:9081)
,E/ExperimentLoader( 2971): 	at czq.run(PG:1686)
E/ExperimentLoader( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2971): ,	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2971): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2971): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2971): 	at jdm.a(PG:77)
E/ExperimentLoader( 2971): 	,... 15 more
E/ExperimentLoader( 2971): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2971): 	at fal.a(PG:38)
E/ExperimentLoader( 2971): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2971): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1346594, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,V/KeepSync( 3303): Connecting to GoogleApiClient
,I/art     ( 3303): Explicit concurrent mark sweep GC freed 25079(3MB) AllocSpace objects, 0(0B) LOS objects, 24% free, 23MB/31MB, paused 306us total 28.041ms
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3303): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,I/art     (  821): Explicit concurrent mark sweep GC freed 41752(1791KB) AllocSpace objects, 8(222KB) LOS objects, 31% free, 34MB/50MB, paused 1.335ms total 52.085ms
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3303): IOException
E/KeepSync( 3303): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3303): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3303): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3303): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3303): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3303): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3303): 	... 10 more
,W/KeepSync( 3303): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1462378, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at blb.a(PG:3937)
E/HttpOperation( 2971): 	at czp.a(PG:18188)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 12 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 14 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [getmobileexperiments] Unexpected exception,
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at hec.a(PG:42)
,E/HttpOperation( 2971): 	at hee.a(PG:102)
E/HttpOperation( 2971): 	at czr.a(PG:65)
E/HttpOperation( 2971): 	at kka.a(PG:108)
E/HttpOperation( 2971): 	at czp.a(PG:19176)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 15 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 17 more
E/ExperimentLoader( 2971): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): 	at jdm.a(PG:82)
E/ExperimentLoader( 2971): 	at jcs.o(PG:406)
E/ExperimentLoader( 2971): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2971): 	at jcs.i(PG:143)
E/ExperimentLoader( 2971): 	at hec.a(PG:42)
E/ExperimentLoader( 2971): 	at hee.a(PG:102)
E/ExperimentLoader( 2971): 	at czr.a(PG:65)
E/ExperimentLoader( 2971): 	at kka.a(PG:108)
E/ExperimentLoader( 2971): 	at czp.a(PG:19176)
E/ExperimentLoader( 2971): 	at czp.a(PG:9081)
E/ExperimentLoader( 2971): 	at czq.run(PG:1686)
E/ExperimentLoader( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2971): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2971): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2971): 	at jdm.a(PG:77)
E/ExperimentLoader( 2971): 	... 15 more
E/ExperimentLoader( 2971): Caused by: faj: BadAuthentication,
E/ExperimentLoader( 2971): 	at fal.a(PG:38)
E/ExperimentLoader( 2971): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2971): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1501694, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3258): Stopping oneshot timer
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,V/KeepSync( 3303): Connecting to GoogleApiClient
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1781): Handling authorization failure
E/ClientConnectionOperation( 1781): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1781): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1781): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1781): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1781): 	... 7 more
,V/KeepSync( 3303): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3303): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3303): IOException
E/KeepSync( 3303): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3303): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3303): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3303): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3303): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3303): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3303): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3303): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3303): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3303): 	... 10 more
,W/KeepSync( 3303): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1702946, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): 	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at blb.a(PG:3937)
E/HttpOperation( 2971): 	at czp.a(PG:18188)
E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 12 more
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 14 more
,I/GLSUser ( 1485): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1485): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1485): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1485): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1485): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2971): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2971): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2971): 	at jdm.a(PG:82)
E/HttpOperation( 2971): 	at jcs.o(PG:406)
E/HttpOperation( 2971): 	at jcn.a(PG:1379)
E/HttpOperation( 2971): ,	at jcs.i(PG:143)
E/HttpOperation( 2971): 	at hec.a(PG:42)
E/HttpOperation( 2971): 	at hee.a(PG:102)
E/HttpOperation( 2971): 	at czr.a(PG:65)
E/HttpOperation( 2971): 	at kka.a(PG:108)
E/HttpOperation( 2971): 	at czp.a(PG:19176)
,E/HttpOperation( 2971): 	at czp.a(PG:9081)
E/HttpOperation( 2971): 	at czq.run(PG:1686)
E/HttpOperation( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2971): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2971): 	at jdj.a(PG:4091)
E/HttpOperation( 2971): 	at jdj.a(PG:1125)
E/HttpOperation( 2971): 	at jdm.a(PG:77)
E/HttpOperation( 2971): 	... 15 more,
E/HttpOperation( 2971): Caused by: faj: BadAuthentication
E/HttpOperation( 2971): 	at fal.a(PG:38)
E/HttpOperation( 2971): 	at jdj.a(PG:4089)
E/HttpOperation( 2971): 	... 17 more
E/ExperimentLoader( 2971): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2971): 	at jdm.a(PG:82)
E/ExperimentLoader( 2971): 	,at jcs.o(PG:406)
E/ExperimentLoader( 2971): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2971): 	at jcs.i(PG:143)
E/ExperimentLoader( 2971): 	at hec.a(PG:42)
E/ExperimentLoader( 2971): 	at hee.a(PG:102)
,E/ExperimentLoader( 2971): 	at czr.a(PG:65)
E/ExperimentLoader( 2971): 	at kka.a(PG:108)
E/ExperimentLoader( 2971): 	at czp.a(PG:19176)
E/ExperimentLoader( 2971): 	at czp.a(PG:9081)
E/ExperimentLoader( 2971): 	at czq.run(PG:1686)
E/ExperimentLoader( 2971): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2971): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2971): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2971): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2971): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2971): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2971): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2971): 	at jdm.a(PG:77)
E/ExperimentLoader( 2971): 	... 15 more
,E/ExperimentLoader( 2971): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2971): 	at fal.a(PG:38)
E/ExperimentLoader( 2971): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2971): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 1781622, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  821): Prepared write state in 25ms
,I/ProcessStatsService(  821): Prepared write state in 8ms
,I/ProcessStatsService(  821): Prepared write state in 6ms
,I/ProcessStatsService(  821): Pruning old procstats: /data/system/procstats/state-2015-11-22-23-02-07.bin
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3258): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4621): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4621): CheckJNI is OFF
D/AndroidRuntime( 4621): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3203:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  821): Skipping PackageSetting{3ce9b486 com.example.hello/10272} due to missing metadata
I/WindowState(  821): WIN DEATH: Window{241d3fe7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  821): Client connection lost with reason: 4
E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3203
W/ActivityManager(  821): Force removing ActivityRecord{117ed89c u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
V/ActivityManager(  821): Display changed displayId=0
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
W/ActivityManager(  821): Spurious death for ProcessRecord{3641ce2e 3203:com.test.thalitest/u0a265}, curProc for 3203: null
D/TaskPersister(  821): removeObsoleteFile: deleting file=24_task.xml
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1212): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1212): run()
W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3203 uid 10265
D/BuaReceiver( 3066): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/art     ( 1062): Explicit concurrent mark sweep GC freed 81044(3MB) AllocSpace objects, 1(30MB) LOS objects, 17% free, 74MB/90MB, paused 1.954ms total 73.337ms
I/art     (  821): Explicit concurrent mark sweep GC freed 49335(2MB) AllocSpace objects, 13(568KB) LOS objects, 31% free, 34MB/50MB, paused 2.077ms total 80.878ms
I/Keyboard.Facilitator( 1212): onFinishInput()
I/Decoder ( 1212): createOrResetDecoder
I/art     (  821): WaitForGcToComplete blocked for 58.598ms for cause Explicit
I/art     ( 1321): Explicit concurrent mark sweep GC freed 5061(369KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 566us total 18.135ms
I/ActivityManager(  821): Start proc 4639:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/ConfigService( 1485): onCreate
D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/art     ( 1485): Explicit concurrent mark sweep GC freed 63942(3MB) AllocSpace objects, 10(1102KB) LOS objects, 37% free, 27MB/43MB, paused 910us total 28.738ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1212): run()
D/Launcher.Workspace( 1321): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1321): 11683562 - stripEmptyScreens()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1212): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1212): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1212): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1212): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1212): run()
I/StatsUtilsManager( 1212): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1212): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 4639): Cleaning up data for package: com.test.thalitest
I/art     (  821): Explicit concurrent mark sweep GC freed 7820(382KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 1.388ms total 179.061ms
I/ActivityManager(  821): Start proc 4676:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 194us total 10.180ms
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 195us total 8.732ms
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 212us total 8.561ms
I/ContactLocale( 4639): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  821): Start proc 4697:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/ActivityManager(  821): Killing 3760:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
I/art     ( 4621): System.exit called, status: 0
I/AndroidRuntime( 4621): VM exiting with result code 0.
W/ContextImpl( 4697): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1485): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1485): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1781): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 4639): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/PackageBroadcastService( 1781): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1781): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1781): Module APK com.google.android.play.games already loaded
E/AndroidRuntime( 4639): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4639): Process: android.process.acore, PID: 4639
E/AndroidRuntime( 4639): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4639): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4639): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
E/AndroidRuntime( 4639): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
E/AndroidRuntime( 4639): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1706)
E/AndroidRuntime( 4639): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4639): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4639): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4639): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteLog( 1781): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/art     ( 4051): Background sticky concurrent mark sweep GC freed 78479(6MB) AllocSpace objects, 12(192KB) LOS objects, 19% free, 25MB/32MB, paused 5.405ms total 63.983ms
E/AndroidRuntime( 1781): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1781): Process: com.google.android.gms, PID: 1781
E/AndroidRuntime( 1781): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1781): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1781): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1781): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1781): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1781): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1781): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1781): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1781): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1781): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1781): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1781): 	at java.lang.Thread.run(Thread.java:818)
D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  821): Validating map...
E/SQLiteLog( 1781): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1781): disk I/O error (code 3850)
E/DriveAsyncService( 1781): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1781): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1781): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1781): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1781): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1781): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1781): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1781): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1781): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1781): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1781): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1781): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1781): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1781): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1781): 	at java.lang.Thread.run(Thread.java:818)
I/LocationSettingsChecker( 1781): Removing dialog suppression flag for package com.test.thalitest
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
E/SQLiteDatabase( 1781): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1781): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1781): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1781): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1781): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1781): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1781): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1781): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1781): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1781): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1781): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1781): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1781): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1781): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1781): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1781): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1781): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1781): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1781): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1781): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1781): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1781): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1781): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1781): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1781): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1781): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1781): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1781): Sending signal. PID: 1781 SIG: 9
I/ActivityManager(  821): Start proc 4732:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
E/lowmemorykiller(  256): Error writing /proc/1781/oom_score_adj; errno=22
I/VS.Container( 4051): create_recognizer
W/ResourcesManager(  821): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  821): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 4732): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4732): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/OpenGLRenderer(  821): Initialized EGL, version 1.4
D/OpenGLRenderer(  821): Enabling debug mode 0
I/MultiDex( 4732): VM with version 2.1.0 has multidex support
I/MultiDex( 4732): install
I/MultiDex( 4732): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  821): Process com.google.android.gms (pid 1781) has died
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
W/ActivityManager(  821): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
D/WifiService(  821): Client connection lost with reason: 4
W/GmsClient( 4051): service died
W/GmsClient( 4051): service died
E/Search.IcingConnection( 4051): Could not connect to Icing. Error code 8.
W/Launcher( 1321): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@13a1e58d new=com.google.android.velvet.VelvetApplication@13a1e58d
E/SQLiteLog( 1321): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
I/HotwordRecognitionRnr( 4051): Starting hotword detection.
I/MicrophoneInputStream( 4051): mic_starting com.google.android.apps.gsa.speech.audio.u@3ab7cfbe
I/AudioFlinger(  357): AudioFlinger's thread 0xb4caa000 ready to run
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 4051): mic_started com.google.android.apps.gsa.speech.audio.u@3ab7cfbe
I/ActivityManager(  821): Start proc 4758:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
V/JNIHelp ( 4732): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
I/ActivityManager(  821): Start proc 4777:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
I/ProviderInstaller( 4732): Installed default security provider GmsCore_OpenSSL
E/SharedPreferencesImpl( 4051): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 4051): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 4051): Process: com.google.android.googlequicksearchbox:search, PID: 4051
E/AndroidRuntime( 4051): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 4051): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:108)
E/AndroidRuntime( 4051): 	at com.google.android.apps.gsa.shared.e.j.c(ExtraDexRegistry.java:214)
E/AndroidRuntime( 4051): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.bb(UpdateIcingCorporaService.java:232)
E/AndroidRuntime( 4051): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:205)
E/AndroidRuntime( 4051): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4051): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4051): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4051): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 4051): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime( 4051): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime( 4051): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime( 4051): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:94)
E/AndroidRuntime( 4051): 	... 7 more
E/AndroidRuntime( 4051): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 4051): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime( 4051): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime( 4051): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 4051): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 4051): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 4051): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4051): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4051): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4051): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4051): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 4051): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 4051): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime( 4051): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime( 4051): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime( 4051): 	... 9 more
E/AndroidRuntime( 4051): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 4051): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime( 4051): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime( 4051): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime( 4051): 	... 11 more
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
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
W/NativeLibraryUtils( 4732): Failed to open lock file
W/NativeLibraryUtils( 4732): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4732): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4732): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4732): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4732): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4732): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4732): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4732): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4732): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4732): 	... 3 more
I/HotwordWorker( 4051): onReady
I/ActivityManager(  821): Killing 3797:com.android.vending/u0a19 (adj 15): empty #17
I/ActivityManager(  821): Start proc 4800:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService

```
