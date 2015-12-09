#### Test 506502789252e15_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2711): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2711): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2711): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3195): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3195): CheckJNI is OFF
D/AndroidRuntime( 3195): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  825): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  825): addAppToken: AppWindowToken{212b8c59 token=Token{36ccb8a0 ActivityRecord{34575da3 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3195): Shutting down VM
V/WindowManager(  825): Adding window Window{2b7d102a u0 Starting com.test.thalitest} at 3 of 8 (after Window{1c7f396d u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/MicrophoneInputStream( 1524): mic_close com.google.android.apps.gsa.speech.audio.u@3d21677a
I/HotwordDetector( 1524): Closing mic
I/ActivityManager(  825): Start proc 3209:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1524): Stopping hotword detection.
I/HotwordRecognitionRnr( 1524): Hotword detection finished
I/ActivityManager(  825): Killing 2670:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
I/ActivityManager(  825): Killing 2802:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,W/GCoreFlp( 1760): No location to return for getLastLocation()
,I/WebViewFactory( 3209): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3209): Time to load native libraries: 2 ms (timestamps 5383-5385)
I/LibraryLoader( 3209): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3209): Binding Chromium to main looper Looper (main, tid 1) {19d46b8d}
,I/LibraryLoader( 3209): Expected native library version number "",actual native library version number ""
I/chromium( 3209): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/LocSvc_IzatApiV02(  825): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658971411
E/LocSvc_IzatApiV02(  825): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching ,
I/BrowserStartupController( 3209): Initializing chromium process, singleProcess=true,
W/art     ( 3209): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 3209): ApplicationContext is null in ApplicationStatus
,W/chromium( 3209): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3209): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3209): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 3209): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3209): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/kickstart(  873): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  873): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,I/kickstart(  873): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,D/BluetoothManagerService(  825): Message: 20
D/BluetoothManagerService(  825): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b11d7da:true
D/BluetoothAdapter( 3209): 913613743: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 1486): Explicit concurrent mark sweep GC freed 27101(1436KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 681us total 34.837ms
,W/art     ( 3209): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3209): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3209): CordovaWebView is running on device made by: motorola
,W/art     ( 3209): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3209): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  825): Explicit concurrent mark sweep GC freed 20208(970KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.593ms total 58.211ms
,D/OpenGLRenderer( 3209): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3209): Validating map...
,V/WindowManager(  825): Adding window Window{8ffeb8a u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{2b7d102a u0 Starting com.test.thalitest})
,W/chromium( 3209): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3209): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3209): Enabling debug mode 0
,I/ActivityManager(  825): Displayed com.test.thalitest/.MainActivity: +939ms (total +2m2s702ms)
,W/BindingManager( 3209): Cannot call determinedVisibility() - never saw a connection for the pid: 3209
,I/Keyboard.Facilitator( 1240): onFinishInput()
,D/JsMessageQueue( 3209): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3209): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576193152
D/JX-Cordova( 3209): jxcore cordova android initializing
,I/kickstart(  873): STATUS: Received file 'm9kefs2'
,I/kickstart(  873): STATUS: 950272 bytes transferred in 0.987795 seconds
I/kickstart(  873): STATUS: Successfully downloaded files from target 
I/kickstart(  873): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  873): STATUS: Sahara protocol completed
,W/jxcore-log( 3209): Initializing JXcore engine
,W/jxcore-log( 3209): JXcore engine is ready
,W/jxcore-log( 3209): Starting JXcore engine
,W/.test.thalitest( 3209): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11548]" dev="sockfs" ino=11548 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3209): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3209): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11733]" dev="sockfs" ino=11733 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3209): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20814]" dev="sockfs" ino=20814 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3209): Platform android
W/jxcore-log( 3209): 
,W/jxcore-log( 3209): Process ARCH arm
W/jxcore-log( 3209): 
,I/jxcore-log( 3209): JXcore Cordova bridge is ready!,
I/jxcore-log( 3209): ,
,W/jxcore-log( 3209): JXcore engine is started
I/Choreographer( 3209): Skipped 131 frames!  The application may be doing too much work on its main thread.
I/chromium( 3209): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3209): Toggling radios to true
I/jxcore-log( 3209): 
,D/BluetoothManagerService(  825): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  825): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  825): Message: 1
D/BluetoothManagerService(  825): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  825): New client listening to asynchronous messages
D/WifiService(  825): setWifiEnabled: true pid=3209, uid=10265
E/WifiService(  825): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3209): Radios toggled
I/jxcore-log( 3209): 
D/SoftapController(  354): Softap fwReload - Ok
,D/CommandListener(  354): Setting iface cfg,
D/CommandListener(  354): Trying to bring down wlan0
D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiMonitor(  825): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  825): Start proc 3269:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,W/ResourcesManager( 3269): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3286): Successfully initialized wpa_supplicant
,D/AdapterServiceConfig( 3269): Adding HeadsetService
D/AdapterServiceConfig( 3269): Adding A2dpService
D/AdapterServiceConfig( 3269): Adding HidService
D/AdapterServiceConfig( 3269): Adding HealthService
D/AdapterServiceConfig( 3269): Adding PanService
D/AdapterServiceConfig( 3269): Adding GattService
D/AdapterServiceConfig( 3269): Adding BluetoothMapService
,D/WifiMonitor(  825): startMonitoring(wlan0) with mConnected = false
,D/BluetoothManagerService(  825): Message: 20
D/BluetoothManagerService(  825): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27ad79cf:true
D/BluetoothAdapterState( 3269): make
I/bluedroid( 3269): init
,I/BluetoothAdapterState( 3269): Entering OffState,
,I/bte_conf( 3269): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 3269): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3269): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3269): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3269): get_profile_interface socket
I/bluedroid( 3269): get_profile_interface map_client
I/GKI_LINUX( 3269): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 3269): Address is:F8:CF:C5:D9:E5:61
,I/ActivityManager(  825): Start proc 3289:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,D/BluetoothManagerService(  825): Bluetooth Adapter name changed to Nexus 6
D/BluetoothAdapterProperties( 3269): Name is: Nexus 6
D/BluetoothManagerService(  825): Stored Bluetooth name: Nexus 6
,D/BluetoothManagerService(  825): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  825): Message: 40
D/BluetoothManagerService(  825): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3269): config_hci_snoop_log
,D/BluetoothManagerService(  825): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  825): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3269): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3269): Setting state to 11
I/BluetoothAdapterState( 3269): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  825): Message: 60
D/BluetoothManagerService(  825): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  825): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3269): make
,I/BluetoothBondStateMachine( 3269): StableState(): Entering Off State
,D/BluetoothAdapterService( 3269): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3444f142
D/HeadsetService( 3269): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3269): classInitNative: succeeds
D/HeadsetStateMachine( 3269): make
,I/BluetoothAdapterState( 3269): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3269): max_hf_connections = 1
I/bluedroid( 3269): get_profile_interface handsfree
,D/HeadsetStateMachine( 3269): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3269): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3444f142
,D/BluetoothA2dp( 1075): Proxy object connected
,D/BluetoothA2dp(  825): Proxy object connected
D/A2dpService( 3269): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3269): classInitNative: succeeds
I/bluedroid( 3269): get_profile_interface avrcp
,I/wpa_supplicant( 3286): rfkill: Cannot open RFKILL control device
,E/RemoteController( 3269): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3269): classInitNative: succeeds
D/A2dpStateMachine( 3269): make
,I/bluedroid( 3269): get_profile_interface a2dp
I/GKI_LINUX( 3269): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3269): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3269): classInitNative: succeeds
,D/BluetoothAdapterService( 3269): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3444f142
,D/BluetoothInputDevice( 1075): Proxy object connected
D/HidService( 3269): Received start request. Starting profile...
I/bluedroid( 3269): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3269): classInitNative: succeeds
D/BluetoothAdapterService( 3269): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3444f142
,D/HealthService( 3269): Received start request. Starting profile...
I/bluedroid( 3269): get_profile_interface health
,I/BluetoothPanServiceJni( 3269): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3269): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3444f142
D/BluetoothPan( 1075): BluetoothPAN Proxy object connected
D/PanService( 3269): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 3269): initializeNative(L110): pan
I/bluedroid( 3269): get_profile_interface pan
I/BtGatt.JNI( 3269): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3269): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3444f142
,D/BtGatt.DebugUtils( 3269): handleDebugAction() action=null
,D/BtGatt.GattService( 3269): Received start request. Starting profile...
,D/BtGatt.GattService( 3269): start()
I/bluedroid( 3269): get_profile_interface gatt
D/BluetoothAdapterService( 3269): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3444f142
D/BtGatt.AdvertiseManager( 3269): advertise manager created
,D/BluetoothAdapterService( 3269): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3444f142
D/BluetoothMap( 1075): Proxy object connected
D/BluetoothMapService( 3269): Received start request. Starting profile...
D/BluetoothMapService( 3269): start()
,D/BluetoothMapEmailSettingsLoader( 3269): Found 0 applications
D/BluetoothMapEmailAppObserver( 3269): createReceiver()
,D/BluetoothMapEmailAppObserver( 3269): initObservers()
,D/BluetoothMapEmailAppObserver( 3269): getEnabledAccountItems()
,D/HeadsetStateMachine( 3269): Proxy object connected
D/HeadsetStateMachine( 3269): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3269): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 3269): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3269): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3269): enable
I/GKI_LINUX( 3269): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3269): btu_task pending for preload complete event
I/bt_hci_bdroid( 3269): init
,I/bt_vendor( 3269): init
I/bt_vnd_conf( 3269): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3269): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3269): userial_init
,I/ActivityManager(  825): Start proc 3331:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
I/ActivityManager(  825): Killing 2834:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 197us total 9.874ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 8.963ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 8.505ms
,I/bt_userial_vendor( 3269): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3269): device fd = 53 open
,D/bt_userial( 3269): Entering userial_read_thread()
,I/bt_hwcfg( 3269): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3269): Chipset BCM4354A2
D/bt_hwcfg( 3269): Target name = [BCM4354A2]
I/bt_hwcfg( 3269): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/ActivityManager(  825): Start proc 3354:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  825): Killing 2769:com.google.android.gm/u0a78 (adj 15): empty #17
,D/Tethering(  825): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  825): Killing 2361:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/bt_hwcfg( 3269): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3269): Settlement delay -- 100 ms
I/bt_hwcfg( 3269): Setting fw settlement delay to 100 
,I/wpa_supplicant( 3286): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3286): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  825): Loading config and enabling all networks 
,E/WifiConfigStore(  825): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  825): Start proc 3373:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,I/bt_hwcfg( 3269): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg( 3269): Setting local bd addr to F8:CF:C5:D9:E5:61
W/Settings( 2638): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  825): Setting external_sim to 1
D/WifiStateMachine(  825): Setting OUI to 92-68-C3
I/WifiNative-HAL(  825): startHal
D/wifi    (  825): setting scan oui 0xa0eeee38
D/WifiHAL (  825): Sending mac address OUI
,D/WifiService(  825): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@242bc1a7}
,E/WifiStateMachine(  825): cancelDelayedScan -> 1
,D/WifiScanningService(  825): SCAN_AVAILABLE : 3
W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
D/RttService(  825): SCAN_AVAILABLE : 3
D/WifiScanningService(  825): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  825): startHal
,D/wifi    (  825): getting scan capabilities on interface[0] = 0xa0eeee38
D/WifiHAL (  825): Creating message to get scan capablities; iface = 5
D/WifiHAL (  825): In GetCapabilities::handleResponse
D/WifiHAL (  825): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  825): StartedState
D/RttService(  825): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  354): Setting iface cfg
,E/WifiP2pService(  825): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  825): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  825): p2pGetDeviceAddress,
D/WifiNative-HAL(  825): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/bt_hwcfg( 3269): vendor lib fwcfg completed
I/bt-btu  ( 3269): btu_task received preload complete event
,I/        ( 3269): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3269): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3269): BTE_InitTraceLevels -- TRC_RFCOMM
,I/        ( 3269): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3269): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3269): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3269): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3269): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 3269): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3269): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3269): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3269): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3269): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3269): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3269): BTE_InitTraceLevels -- TRC_BTIF
,I/wpa_supplicant( 3286): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/native  (  825): do suspend false
,E/bt-btm  ( 3269): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e23085 
E/bt-btm  ( 3269): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e23085 
,D/BluetoothAdapterProperties( 3269): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3269): Calling BTA_HhEnable
E/bt-btif ( 3269): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3269): Address is:F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  825): Bluetooth Adapter name changed to Nexus 6
D/BluetoothAdapterProperties( 3269): Name is: Nexus 6
D/BluetoothAdapterProperties( 3269): Scan Mode:20
D/BluetoothAdapterProperties( 3269): Discoverable Timeout:120
D/BluetoothManagerService(  825): Stored Bluetooth name: Nexus 6
,D/bte_conf( 3269): Device ID record 1 : primary
D/bte_conf( 3269):   vendorId            = 000f
D/bte_conf( 3269):   vendorIdSource      = 0001
D/bte_conf( 3269):   product             = 1200
D/bte_conf( 3269):   version             = 1436
D/bte_conf( 3269):   clientExecutableURL = 
D/bte_conf( 3269):   serviceDescription  = 
D/bte_conf( 3269):   documentationURL    = 
D/bte_conf( 3269): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3269): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3269): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 3269): ScanMode =  20
D/BluetoothAdapterProperties( 3269): State =  11
D/BluetoothAdapterProperties( 3269): Setting state to 12
I/BluetoothAdapterState( 3269): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties( 3269): Scan Mode:21
D/BluetoothAdapterProperties( 3269): Discoverable Timeout:120
D/BluetoothManagerService(  825): Message: 60
D/BluetoothManagerService(  825): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  825): Broadcasting onBluetoothStateChange(true) to 13 receivers.
,I/BluetoothAdapterState( 3269): Entering On State
D/BluetoothHeadset( 1286): onBluetoothStateChange: up=true
D/BluetoothManagerService(  825): Creating new ProfileServiceConnections object for profile: 1
D/BluetoothMap( 1075): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  825): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  825): onBluetoothStateChange: up=true
D/BluetoothPan( 1075): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1075): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 1075): onBluetoothStateChange: up=true
,D/BluetoothHeadsetClient( 1075): onBluetoothStateChange: up=true
E/BluetoothHeadsetClient( 1075): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
,D/BluetoothA2dp(  825): onBluetoothStateChange: up=true
E/bt_h4   ( 3269): vendor lib postload completed
,D/BluetoothA2dpSink( 1075): onBluetoothStateChange: up=true
W/bt-btm  ( 3269): Stopping oneshot timer
,E/BluetoothA2dpSink( 1075): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
,D/BluetoothA2dp( 1075): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  825): onBluetoothStateChange: up=true
D/BluetoothAvrcpController( 1075): onBluetoothStateChange: up=true
,E/BluetoothAvrcpController( 1075): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
,D/BluetoothManagerService(  825): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  825): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 3269): onReceive
D/BluetoothMapService( 3269): STATE_ON
D/BluetoothMapMasInstance( 3269): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3269): MAS initSocket()
D/BluetoothManagerService(  825): Message: 40
D/BluetoothManagerService(  825): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothManagerService(  825): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3269): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3269): Accepting socket connection...
,W/bt-btm  ( 3269): Stopping oneshot timer
,W/bt-btm  ( 3269): Stopping oneshot timer
,W/bt-btm  ( 3269): Stopping oneshot timer
,W/bt-btm  ( 3269): Stopping oneshot timer
,W/bt-btm  ( 3269): Stopping oneshot timer
,W/bt-btm  ( 3269): Stopping oneshot timer
,D/StrictMode( 3373): StrictMode policy violation; ~duration=275 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3373): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3373): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3373): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3373): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3373): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3373): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3373): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3373): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3373): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3373): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3373): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3373): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3373): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3373): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3373): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3373): StrictMode policy violation; ~duration=275 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3373): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3373): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3373): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3373): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3373): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3373): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3373): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3373): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3373): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3373): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3373): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3373): StrictMode policy violation; ~duration=273 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3373): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3373): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3373): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3373): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3373): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3373): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3373): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3373): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3373): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3373): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3373): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3373): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3373): 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3373): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3373): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3373): StrictMode policy violation; ~duration=270 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3373): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3373): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3373): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3373): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
,D/StrictMode( 3373): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
,D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3373): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3373): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3373): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3373): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3373): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3373): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3373): StrictMode policy violation; ~duration=221 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3373): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3373): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3373): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3373): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3373): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3373): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3373): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
,D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3373): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3373): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3373): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3373): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3373): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3373): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3373): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3373): StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3373): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3373): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3373): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3373): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3373): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3373): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3373): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3373): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3373): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3373): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3373): # via Binder call with stack:
D/StrictMode( 3373): android.os.StrictMode$LogStackTrace
D/StrictMode( 3373): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3373): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3373): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3373): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3373): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3373): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3373): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3373): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/S,trictMode( 3373): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3373): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3373): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3373): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3373): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3373): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3373): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3373): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3373): 	,at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3373): StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3373): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3373): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3373): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3373): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3373): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3373): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3373): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3373): 	,at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3373): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3373): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3373): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3373): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3373): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3373): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.ru,n(ZygoteInit.java:903)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3373): StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3373): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3373): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3373): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3373): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3373): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3373): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3373): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3373): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3373): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3373): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3373): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3373): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3373): StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3373): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3373): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3373): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3373): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3373): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3373): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3373): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3373): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3373): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3373): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3373): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3373): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3373): StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3373): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3373): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3373): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3373): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3373): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3373): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3373): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3373): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3373): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3373): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3373): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3373): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3373): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3373): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3373): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3373): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3373): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3373): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3373): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Native Metho,d)
D/StrictMode( 3373): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 3373): Application name is not set. Call Builder#setApplicationName.
D/BluetoothManagerService(  825): Message: 400
D/BluetoothHeadset( 1286): Proxy object connected
D/BluetoothManagerService(  825): Message: 400
D/BluetoothHeadset(  825): Proxy object connected
D/BluetoothManagerService(  825): Message: 400
D/BluetoothHeadset(  825): Proxy object connected
D/BluetoothManagerService(  825): Message: 400
D/BluetoothHeadset( 1075): Proxy object connected
D/BluetoothManagerService(  825): Message: 20
D/BluetoothManagerService(  825): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28482c84:true
,D/BluetoothManagerService(  825): Message: 400
,D/BluetoothHeadset(  825): Proxy object connected
,I/ActivityManager(  825): Killing 2872:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1486): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3354): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  825): Message: 20
D/BluetoothManagerService(  825): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a42c1fa:true
,D/BluetoothManagerService(  825): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3269): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1486): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LocalBluetoothProfileManager( 3354): Adding local A2DP profile
,D/BluetoothManagerService(  825): Message: 30
,D/LocalBluetoothProfileManager( 3354): Adding local HEADSET profile
,D/BluetoothManagerService(  825): Message: 30
,D/BluetoothManagerService(  825): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3269): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  825): Message: 30
,I/BtOppRfcommListener( 3269): Accept thread started.
,D/BluetoothManagerService(  825): Message: 30
,D/LocalBluetoothProfileManager( 3354): Adding local MAP profile
D/BluetoothMap( 3354): Create BluetoothMap proxy object
D/BluetoothManagerService(  825): Message: 30
,D/BluetoothManagerService(  825): Message: 30,
,D/LocalBluetoothProfileManager( 3354): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3354): finishStartingService: stopping service
,D/BluetoothA2dp( 3354): Proxy object connected
D/A2dpProfile( 3354): Bluetooth service connected
,D/BluetoothInputDevice( 3354): Proxy object connected
D/HidProfile( 3354): Bluetooth service connected
,D/BluetoothPan( 3354): BluetoothPAN Proxy object connected
,D/PanProfile( 3354): Bluetooth service connected
D/BluetoothMap( 3354): Proxy object connected
,D/MapProfile( 3354): Bluetooth service connected
D/BluetoothMap( 3354): getConnectedDevices()
,D/BluetoothPbap( 3354): Proxy object connected
,D/PbapServerProfile( 3354): Bluetooth service connected
,D/BluetoothManagerService(  825): Message: 400
,D/BluetoothHeadset( 3354): Proxy object connected
D/HeadsetProfile( 3354): Bluetooth service connected
,I/wpa_supplicant( 3286): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  825): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  825):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  825):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  825): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3,
E/WifiConfigStore(  825): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  825): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  825): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  825): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  825): will read network variables netId=0
,E/WifiStateMachine(  825): CMD_AUTO_CONNECT did save config ->  nid=0,
E/WifiConfigStore(  825): will read network variables netId=0
,I/wpa_supplicant( 3286): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3286): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3286): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3286): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  825): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  825): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  825): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  825): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  825): Start Dhcp Watchdog 1
,E/WifiStateMachine(  825):  WifiLinkLayerStats: 
E/WifiStateMachine(  825):  my bss beacon rx: 1
E/WifiStateMachine(  825):  RSSI mgmt: -53
E/WifiStateMachine(  825):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  825):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  825):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  825):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  825):  on_time : 0 tx_time=60 rx_time=58 scan_time=0
,D/ConnectivityService(  825): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  825): do suspend false
,E/WifiStateMachine(  825): scanCount==0 - aborting
,I/dhcpcd  ( 3414): version 5.5.6 starting
,I/dhcpcd  ( 3414): wlan0: rebinding lease of 192.168.1.122
,I/PowerManagerService(  825): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  825): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (211 us)
,I/DisplayManagerService(  825): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  825): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  825): Excessive delay in setPowerMode(): 253ms,
,I/DreamManagerService(  825): Entering dreamland.,
,I/PowerManagerService(  825): Dozing...
,I/DreamController(  825): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
E/WifiStateMachine(  825): cancelDelayedScan -> 4
,E/native  (  825): do suspend false
,E/WifiStateMachine(  825): cancelDelayedScan -> 5
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,I/dhcpcd  ( 3414): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3414): wlan0: leased 192.168.1.122 for 86400 seconds
,I/jxcore-log( 3209): Test app app.js loaded
I/jxcore-log( 3209): 
,I/Choreographer( 3209): Skipped 394 frames!  The application may be doing too much work on its main thread.
,I/Keyboard.Facilitator( 1240): onFinishInput()
,I/chromium( 3209): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/native  (  825): do suspend true
,D/ConnectivityService(  825): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  825): Adding iface wlan0 to network 100,
,E/WifiStateMachine(  825): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  825): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  825): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  825): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  825): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,E/WifiStateMachine(  825): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-53
,D/ConnectivityService(  825): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  825): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  825): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  825): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  825):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  825): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  825): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  825): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  825): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1075): CM callback handler got msg 524290
D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  825): MasterInitialState.processMessage what=3
,V/BackupManagerService(  825): Scheduling immediate backup pass
,I/ActivityManager(  825): Start proc 3458:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
V/BackupManagerService(  825): Running a backup pass
,V/BackupManagerService(  825): clearing pending backups
,V/PerformBackupTask(  825): Beginning backup of 14 targets
,D/PerformBackupTask(  825): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  825): doBackup() invoked
,I/PMBA    (  825): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  825): Getting widget state for user: 0
,I/art     (  825): Explicit concurrent mark sweep GC freed 51885(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 3.012ms total 82.539ms
,D/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  825): getDataEnabled: retVal=false
,E/GpsLocationProvider(  825): No APN found to select.
,W/GmsBackupTransport( 1760): Unknown package in backup request: @pm@
V/GmsBackupTransport( 1760): starting performBackup for @pm@
,V/GmsBackupTransport( 1760): performBackup done for @pm@
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1486): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1486): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1486): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1486): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1486): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1486): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1486): 	at android.os.Binder.execTransact(Binder.java:446)
,I/MusicStore( 3458): Database version: 120
,W/GmsBackupTransport( 1760): Error sending final backup to server: 
W/GmsBackupTransport( 1760): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1760): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1760): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1760): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1760): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1760): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1760): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1760): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1760): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1760): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1760): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1760): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1760): 	... 1 more
,D/BackupManagerService(  825): Now staging backup of com.google.android.talk
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:55:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449683702283], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449683702262]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): Validated
D/ConnectivityService(  825): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  825): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  825): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  825): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  825): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1075): CM callback handler got msg 524290
,D/BackupManagerService(  825): Now staging backup of com.google.android.dialer
,D/GpsLocationProvider(  825): NTP server returned: 1449683702807 (Wed Dec 09 18:55:02 GMT+01:00 2015) reference: 165666 certainty: 14 system time offset: 511
,D/AlarmManagerService(  825): Setting time of day to sec=1449683702
W/AlarmManagerService(  825): Unable to set rtc to 1449683702: Invalid argument
,D/BackupManagerService(  825): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  825): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  825): Now staging backup of com.google.android.gm
,I/art     ( 1486): Explicit concurrent mark sweep GC freed 8746(450KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.149ms total 34.302ms
,D/BackupManagerService(  825): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  825): Now staging backup of com.android.nfc
,E/Auth.Api.Credentials( 1787): [CredentialSyncAdapter] Unknown sync event.
,D/BackupManagerService(  825): Now staging backup of com.google.android.apps.genie.geniewidget
,W/DriveInitializer( 1787): Background init thread started
,D/BackupManagerService(  825): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  825): Now staging backup of com.google.android.inputmethod.latin
,W/DriveInitializer( 1787): Awaiting to be initialized
,D/BackupManagerService(  825): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  825): Now staging backup of com.android.vending
,D/BackupManagerService(  825): Now staging backup of android
,D/BackupManagerService(  825): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1760): Next backup will happen in 43199363 millis.
,I/BackupManagerService(  825): Backup pass finished.
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 3458): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3458): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/DriveInitializer( 1787): Background init thread ended
,E/HttpOperation( 2979): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2979): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2979): 	at jdm.a(PG:82)
E/HttpOperation( 2979): 	at jcs.o(PG:406)
E/HttpOperation( 2979): 	at jcn.a(PG:1379)
E/HttpOperation( 2979): 	at jcs.i(PG:143)
E/HttpOperation( 2979): 	at blb.a(PG:3937)
E/HttpOperation( 2979): 	at czp.a(PG:18188)
E/HttpOperation( 2979): 	at czp.a(PG:9081)
E/HttpOperation( 2979): 	at czq.run(PG:1686)
E/HttpOperation( 2979): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2979): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2979): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2979): 	at jdj.a(PG:4091)
E/HttpOperation( 2979): 	at jdj.a(PG:1125)
E/HttpOperation( 2979): 	at jdm.a(PG:77)
E/HttpOperation( 2979): 	... 12 more
E/HttpOperation( 2979): Caused by: faj: BadAuthentication
E/HttpOperation( 2979): 	at fal.a(PG:38)
E/HttpOperation( 2979): 	at jdj.a(PG:4089)
E/HttpOperation( 2979): 	... 14 more
,V/JNIHelp ( 3458): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2979): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2979): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2979): 	at jdm.a(PG:82)
E/HttpOperation( 2979): 	at jcs.o(PG:406)
E/HttpOperation( 2979): 	at jcn.a(PG:1379)
E/HttpOperation( 2979): 	at jcs.i(PG:143)
E/HttpOperation( 2979): 	at hec.a(PG:42)
E/HttpOperation( 2979): 	at hee.a(PG:102)
E/HttpOperation( 2979): 	at czr.a(PG:65)
E/HttpOperation( 2979): 	at kka.a(PG:108)
E/HttpOperation( 2979): 	at czp.a(PG:19176)
E/HttpOperation( 2979): 	at czp.a(PG:9081)
E/HttpOperation( 2979): 	at czq.run(PG:1686)
E/HttpOperation( 2979): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2979): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2979): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2979): 	at jdj.a(PG:4091)
E/HttpOperation( 2979): 	at jdj.a(PG:1125)
E/HttpOperation( 2979): 	at jdm.a(PG:77)
E/HttpOperation( 2979): 	... 15 more
E/HttpOperation( 2979): Caused by: faj: BadAuthentication
E/HttpOperation( 2979): 	at fal.a(PG:38)
E/HttpOperation( 2979): 	at jdj.a(PG:4089)
E/HttpOperation( 2979): 	... 17 more
E/ExperimentLoader( 2979): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2979): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2979): 	at jdm.a(PG:82)
E/ExperimentLoader( 2979): 	at jcs.o(PG:406)
E/ExperimentLoader( 2979): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2979): 	at jcs.i(PG:143)
E/ExperimentLoader( 2979): 	at hec.a(PG:42)
E/ExperimentLoader( 2979): 	at hee.a(PG:102)
E/ExperimentLoader( 2979): 	at czr.a(PG:65)
E/ExperimentLoader( 2979): 	at kka.a(PG:108)
E/ExperimentLoader( 2979): 	at czp.a(PG:19176)
E/ExperimentLoader( 2979): 	at czp.a(PG:9081)
E/ExperimentLoader( 2979): 	at czq.run(PG:1686)
E/ExperimentLoader( 2979): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2979): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2979): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2979): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2979): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2979): 	at jdm.a(PG:77)
E/ExperimentLoader( 2979): 	... 15 more
E/ExperimentLoader( 2979): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2979): 	at fal.a(PG:38)
E/ExperimentLoader( 2979): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2979): 	... 17 more
,I/ProviderInstaller( 3458): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3458): GMSCore installation verified
,I/ConfigStore( 3458): Config Database version: 1
,I/MediaRouter( 3458): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3458): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3458): type=WIFI subType= reason=null isConnected=true
,V/KeepSync( 3331): Connecting to GoogleApiClient
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 36729, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  825): Start proc 3518:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/NetworkMonitor( 3458): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  825): Start proc 3538:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/GHttpClientFactory( 3458): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3458): Using platform SSLCertificateSocketFactory
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,D/SprintDMReceiver( 3538): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,D/SprintDMHelper( 3538): simOperator:  IMSI: null
D/SprintDMReceiver( 3538): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1787): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1787): onCreate
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SystemUpdateService( 1787): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1787): active receiver: enabled
,I/SystemUpdateService( 1787): showing system update notification
,E/ClientConnectionOperation( 1787): Handling authorization failure
E/ClientConnectionOperation( 1787): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1787): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1787): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1787): 	... 7 more
,V/KeepSync( 3331): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3331): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3331): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3331): (284) automatic index on blob_node(is_deleted)
,I/iu.SyncManager( 1787): SYNC; picasa accounts
,I/ValidateNoPeople(  825): skipping global notification
,D/NetworkLogImpl( 1787): Loaded NetworkSpeedPredictor
V/SystemUpdateService( 1787): retry (wakeup: false) in 3599962 ms
,I/iu.Environment( 1787): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1787): num queued entries: 0
I/iu.UploadsManager( 1787): num updated entries: 0
I/iu.SyncManager( 1787): NEXT; no task
,D/SystemUpdateService( 1787): onDestroy
,D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  825): Start proc 3570:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/art     (  825): Explicit concurrent mark sweep GC freed 26882(1288KB) AllocSpace objects, 5(121KB) LOS objects, 32% free, 33MB/49MB, paused 1.480ms total 56.532ms
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1787): [AccountUtils] Account not ready
W/Kids    ( 1787): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1787): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1787): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1787): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1787): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1787): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1787): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1787): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1787): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1787): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1787): 	at java.lang.Thread.run(Thread.java:818)
,I/GAv4    ( 3570): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3570):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3570):   adb logcat -s GAv4
,W/GAv4    ( 3570): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/KeepSync( 3331): IOException
E/KeepSync( 3331): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3331): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3331): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3331): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3331): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3331): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3331): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3331): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3331): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3331): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3331): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3331): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3331): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3331): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3331): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3331): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3331): 	... 10 more
W/KeepSync( 3331): Sync result 2
,W/GAv4    ( 3570): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 36731, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,W/GAv4    ( 3570): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1486): Explicit concurrent mark sweep GC freed 16104(1020KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 764us total 20.364ms
,W/GAV2    ( 3518): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3518): Created application version: 3.6.8 (30608)
,I/WebViewFactory( 3570): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/BooksSync( 3518): Starting books sync for 61035162, extras: ade
,I/LibraryLoader( 3570): Time to load native libraries: 1 ms (timestamps 6558-6559)
I/LibraryLoader( 3570): Expected native library version number "",actual native library version number ""
,I/Babel   ( 2638): connection state changed from DISCONNECTED to CONNECTED
,I/ActivityManager(  825): Killing 2212:com.android.providers.calendar/u0a3 (adj 15): empty #17
,V/WebViewChromiumFactoryProvider( 3570): Binding Chromium to main looper Looper (main, tid 1) {24fee276}
,I/LibraryLoader( 3570): Expected native library version number "",actual native library version number ""
,I/chromium( 3570): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3570): Initializing chromium process, singleProcess=true
W/art     ( 3570): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3570): ApplicationContext is null in ApplicationStatus
,W/chromium( 3570): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3570): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3570): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3570): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3570): Requires BLUETOOTH permission
,I/NSApplication( 3570): Starting up...
,I/ActivityManager(  825): Killing 1404:android.process.acore/u0a5 (adj 15): empty #17
,D/GCM     ( 1486): Connected
,I/BooksConfig( 3518): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/GCM     ( 1486): Message class com.google.f.a.a.p
,I/ActivityManager(  825): Start proc 3646:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3518): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3518): Soft error
E/BooksSync( 3518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3518): Sync error
E/BooksSync( 3518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3518): Finished books sync
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36732, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  825): Killing 3112:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  825): Killing 3089:com.google.android.partnersetup/u0a16 (adj 15): empty #18
,D/WifiService(  825): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@242bc1a7}
,E/LocSvc_IzatApiV02(  825): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/ActivityManager(  825): Start proc 3663:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,I/ActivityManager(  825): Killing 2922:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,V/Herrevad( 1787): NQAS connected
,E/SQLiteLog( 3663): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/art     ( 1787): Explicit concurrent mark sweep GC freed 13957(1103KB) AllocSpace objects, 16(256KB) LOS objects, 35% free, 28MB/44MB, paused 1.148ms total 51.896ms
,D/WifiService(  825): New client listening to asynchronous messages
,I/ActivityManager(  825): Start proc 3685:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3685): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3685): Created com.android.providers.calendar.CalendarAlarmManager@3ae58424(com.android.providers.calendar.CalendarProvider2@19d46b8d)
,I/art     (  825): Explicit concurrent mark sweep GC freed 18613(859KB) AllocSpace objects, 6(96KB) LOS objects, 32% free, 33MB/49MB, paused 1.236ms total 53.692ms
,I/ActivityManager(  825): Start proc 3708:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3663): PlayLogger.onLoggerConnected
,D/TimeService( 3708): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449683705590
,D/        ( 3708): TimeServiceNative: User Time to be set is 1449683705590
D/QC-time-services( 3708): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3708): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3708): Lib:time_genoff_operation: pargs->ts_val = 1449683705590
D/QC-time-services(  373): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3708): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  373): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449683705590
D/QC-time-services(  373): Daemon:genoff_opr: Base = 2, val = 1449683705590, operation = 0
,D/QC-time-services(  373): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/26/70 14:7:58
D/QC-time-services(  373): Daemon:Value read from RTC seconds = 9986878000
D/QC-time-services(  373): Daemon:new time 1449683705590 
D/QC-time-services(  373): Daemon: delta 1439696827590 genoff 1439696827590 
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696827590 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  373): Updating the TOD offset
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696827590 to memory
,D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  373): Daemon:Update to modem bit set
D/QC-time-services(  373): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  373): Daemon: Base = 2, Value being sent to MODEM = 1133718905590
E/QC-time-services( 3708): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  825): Killing 3138:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,E/QC-time-services(  373): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  373): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  825): Start proc 3728:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 412us total 17.843ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 338us total 15.927ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 227us total 14.667ms
,I/GAv4    ( 3728): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3728):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3728):   adb logcat -s GAv4
,W/GAv4    ( 3728): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3728): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3728): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2638): UserRecoverableAuthException.
E/Babel   ( 2638): eei: BadAuthentication
E/Babel   ( 2638): 	at eeg.a(Unknown Source)
E/Babel   ( 2638): 	at eeg.a(Unknown Source)
E/Babel   ( 2638): 	at eeg.a(Unknown Source)
E/Babel   ( 2638): 	at g.a(Unknown Source)
E/Babel   ( 2638): 	at cae.a(SourceFile:3089)
E/Babel   ( 2638): 	at cae.a(SourceFile:1131)
E/Babel   ( 2638): 	at cws.a(SourceFile:4333)
E/Babel   ( 2638): 	at cws.a(SourceFile:1419)
E/Babel   ( 2638): 	at crl.a(SourceFile:492)
E/Babel   ( 2638): 	at crl.a(SourceFile:1468)
E/Babel   ( 2638): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2638): 	at cas.b(SourceFile:106)
E/Babel   ( 2638): 	at cap.d(SourceFile:335)
E/Babel   ( 2638): 	at caq.run(SourceFile:81)
,E/Babel   ( 2638): Error getting auth token
E/Babel   ( 2638): dvm
E/Babel   ( 2638): 	at g.a(Unknown Source)
E/Babel   ( 2638): 	at cae.a(SourceFile:3089)
E/Babel   ( 2638): 	at cae.a(SourceFile:1131)
E/Babel   ( 2638): 	at cws.a(SourceFile:4333)
E/Babel   ( 2638): 	at cws.a(SourceFile:1419)
E/Babel   ( 2638): 	at crl.a(SourceFile:492)
E/Babel   ( 2638): 	at crl.a(SourceFile:1468)
E/Babel   ( 2638): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2638): 	at cas.b(SourceFile:106)
E/Babel   ( 2638): 	at cap.d(SourceFile:335)
E/Babel   ( 2638): 	at caq.run(SourceFile:81)
,E/Babel   ( 2638): Account registration failed 1-Redacted-21
E/Babel   ( 2638): cyp: null -- null
E/Babel   ( 2638): 	at cae.a(SourceFile:3121)
E/Babel   ( 2638): 	at cae.a(SourceFile:1131)
E/Babel   ( 2638): 	at cws.a(SourceFile:4333)
E/Babel   ( 2638): 	at cws.a(SourceFile:1419)
E/Babel   ( 2638): 	at crl.a(SourceFile:492)
E/Babel   ( 2638): 	at crl.a(SourceFile:1468)
E/Babel   ( 2638): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2638): 	at cas.b(SourceFile:106)
E/Babel   ( 2638): 	at cap.d(SourceFile:335)
E/Babel   ( 2638): 	at caq.run(SourceFile:81)
,I/art     ( 2638): Note: end time exceeds epoch: 
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1486): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3685): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
E/Babel   ( 2638): Unexpected exception while authenticating.
W/ContentResolver( 3685): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
E/Babel   ( 2638): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2638): 	at eeg.b(Unknown Source)
E/Babel   ( 2638): 	at eeg.b(Unknown Source)
E/Babel   ( 2638): 	at g.a(Unknown Source)
E/Babel   ( 2638): 	at cae.b(SourceFile:1146)
E/Babel   ( 2638): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2638): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2638): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2638): 	at java.lang.Thread.run(Thread.java:818)
,E/WifiStateMachine(  825): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=37.00 rxSuccessRate=36.00 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  825): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 5 -> obsolete
,E/WifiStateMachine(  825): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=37.00 rxSuccessRate=36.00 targetRoamBSSID=any RSSI=-53
E/WifiStateMachine(  825): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 5 -> obsolete
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 3685): (284) automatic index on view_events(_id)
,I/ActivityManager(  825): Start proc 3774:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,I/MusicLeanback( 3458): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3458): Stop autocaching.
,W/ResourcesManager( 3774): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3774): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3774): VM with version 2.1.0 has multidex support
I/MultiDex( 3774): install
I/MultiDex( 3774): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3774): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3774): Installed default security provider GmsCore_OpenSSL,
,D/GCM     ( 1486): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1486): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1787): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3774): callingUid 10011, callindPid: 3774
,D/LocationInitializer( 1787): Restart initialization of location
,E/MDM     ( 1760): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3458): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3458): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAV2    ( 3518): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1486): Vacuum at: now=1449683710252 tag=VacuumService
,V/GoogleAuthProtoRequest( 3289): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1486): Explicit concurrent mark sweep GC freed 24006(1342KB) AllocSpace objects, 8(693KB) LOS objects, 37% free, 26MB/42MB, paused 1.498ms total 41.510ms
,I/GAV2    ( 3663): Thread[GAThread,5,main]: No campaign data found.
,I/GoogleURLConnFactory( 1486): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3289): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3289): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3289): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3289): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3289): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3289): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1486): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1486): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1486): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1486): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  825): Explicit concurrent mark sweep GC freed 18800(885KB) AllocSpace objects, 3(330KB) LOS objects, 32% free, 33MB/49MB, paused 2.416ms total 87.269ms
,E/Uploader( 1486): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1486): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1486): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1486): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1486): No account for auth token provided
,W/Uploader( 1486): No account for auth token provided
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2711): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2711): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2711): [1] 5.onFinished: Scheduling replication attempt 4.
,E/Uploader( 1486): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1486): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1486): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1486): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  825): Killing 3046:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/ActivityManager(  825): Killing 3354:com.android.settings/1000 (adj 15): empty #17
,W/Uploader( 1486): No account for auth token provided
,W/Uploader( 1486): No account for auth token provided
,W/Uploader( 1486): No account for auth token provided
,W/Uploader( 1486): No account for auth token provided
,W/Uploader( 1486):  no longer exists, so no auth token.
,W/Uploader( 1486): No account for auth token provided
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1486): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1486): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1486): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1486): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1486): No account for auth token provided
,W/Uploader( 1486): No account for auth token provided,
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1486): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1486): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1486): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1486): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1486): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1486): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1486): No account for auth token provided,
,W/Uploader( 1486): No account for auth token provided
,I/ActivityManager(  825): Killing 3373:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  825): Killing 1524:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  825): Client connection lost with reason: 4
,D/Finsky  ( 2711): [278] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2711): [278] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/HeadsetStateMachine( 3269): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3269): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3289): [337] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3289): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3289): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3289): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3289): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3289): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3289): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2711): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2711): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2711): [1] 5.onFinished: Scheduling replication attempt 5.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1240): run()
I/Keyboard.Facilitator( 1240): flushDynamicLanguageModels()
,I/ConfigService( 1486): onCreate
,V/KeepSync( 3331): Connecting to GoogleApiClient
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2979): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2979): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2979): 	at jdm.a(PG:82)
E/HttpOperation( 2979): 	at jcs.o(PG:406)
E/HttpOperation( 2979): 	at jcn.a(PG:1379)
E/HttpOperation( 2979): 	at jcs.i(PG:143)
E/HttpOperation( 2979): 	at blb.a(PG:3937)
E/HttpOperation( 2979): 	at czp.a(PG:18188)
E/HttpOperation( 2979): 	at czp.a(PG:9081)
E/HttpOperation( 2979): 	at czq.run(PG:1686)
E/HttpOperation( 2979): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2979): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2979): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2979): 	at jdj.a(PG:4091)
E/HttpOperation( 2979): 	at jdj.a(PG:1125)
E/HttpOperation( 2979): 	at jdm.a(PG:77)
E/HttpOperation( 2979): 	... 12 more
E/HttpOperation( 2979): Caused by: faj: BadAuthentication
E/HttpOperation( 2979): 	at fal.a(PG:38)
E/HttpOperation( 2979): 	at jdj.a(PG:4089)
E/HttpOperation( 2979): 	... 14 more
,E/ClientConnectionOperation( 1787): Handling authorization failure
E/ClientConnectionOperation( 1787): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1787): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1787): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1787): 	... 7 more
,V/KeepSync( 3331): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3331): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3331): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3331): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2979): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2979): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2979): 	at jdm.a(PG:82)
E/HttpOperation( 2979): 	at jcs.o(PG:406)
E/HttpOperation( 2979): 	at jcn.a(PG:1379)
E/HttpOperation( 2979): 	at jcs.i(PG:143)
E/HttpOperation( 2979): 	at hec.a(PG:42)
E/HttpOperation( 2979): 	at hee.a(PG:102)
E/HttpOperation( 2979): 	at czr.a(PG:65)
E/HttpOperation( 2979): 	at kka.a(PG:108)
E/HttpOperation( 2979): 	at czp.a(PG:19176)
E/HttpOperation( 2979): 	at czp.a(PG:9081)
E/HttpOperation( 2979): 	at czq.run(PG:1686)
E/HttpOperation( 2979): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2979): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2979): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2979): 	at jdj.a(PG:4091)
E/HttpOperation( 2979): 	at jdj.a(PG:1125)
E/HttpOperation( 2979): 	at jdm.a(PG:77)
E/HttpOperation( 2979): 	... 15 more
E/HttpOperation( 2979): Caused by: faj: BadAuthentication
E/HttpOperation( 2979): 	at fal.a(PG:38)
E/HttpOperation( 2979): 	at jdj.a(PG:4089)
E/HttpOperation( 2979): 	... 17 more
,E/ExperimentLoader( 2979): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 2979): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2979): 	at jdm.a(PG:82)
E/ExperimentLoader( 2979): 	at jcs.o(PG:406)
E/ExperimentLoader( 2979): ,	at jcn.a(PG:1379)
E/ExperimentLoader( 2979): 	at jcs.i(PG:143)
E/ExperimentLoader( 2979): 	at hec.a(PG:42)
E/ExperimentLoader( 2979): 	at hee.a(PG:102)
E/ExperimentLoader( 2979): 	at czr.a(PG:65),
E/ExperimentLoader( 2979): 	at kka.a(PG:108)
E/ExperimentLoader( 2979): 	at czp.a(PG:19176)
E/ExperimentLoader( 2979): 	at czp.a(PG:9081)
E/ExperimentLoader( 2979): 	at czq.run(PG:1686)
E/ExperimentLoader( 2979): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/ExperimentLoader( 2979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2979): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2979): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/ExperimentLoader( 2979): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2979): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2979): 	at jdm.a(PG:77)
E/ExperimentLoader( 2979): 	... 15 more
,E/ExperimentLoader( 2979): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2979): 	at fal.a(PG:38)
E/ExperimentLoader( 2979): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2979): 	... 17 more
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 196134, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3331): IOException
E/KeepSync( 3331): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3331): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3331): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3331): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3331): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3331): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3331): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3331): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3331): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3331): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3331): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3331): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3331): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3331): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3331): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3331): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3331): 	... 10 more
W/KeepSync( 3331): Sync result 2
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 197153, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3518): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3518): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  825): Explicit concurrent mark sweep GC freed 27844(1207KB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 1.727ms total 92.052ms
,E/BooksAccountManager( 3518): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3518): Soft error
E/BooksSync( 3518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3518): Sync error
E/BooksSync( 3518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3518): Finished books sync
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 198115, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1486): onDestroy
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2711): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2711): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2711): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 3269): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3269): Disconnected process message: 10, size: 0
,I/art     ( 1486): Explicit concurrent mark sweep GC freed 70035(3MB) AllocSpace objects, 9(748KB) LOS objects, 36% free, 27MB/43MB, paused 2.108ms total 68.069ms
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2979): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2979): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2979): 	at jdm.a(PG:82)
E/HttpOperation( 2979): 	at jcs.o(PG:406)
E/HttpOperation( 2979): 	at jcn.a(PG:1379)
E/HttpOperation( 2979): 	at jcs.i(PG:143)
E/HttpOperation( 2979): 	at blb.a(PG:3937)
E/HttpOperation( 2979): 	at czp.a(PG:18188)
E/HttpOperation( 2979): 	at czp.a(PG:9081)
E/HttpOperation( 2979): 	at czq.run(PG:1686)
E/HttpOperation( 2979): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2979): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2979): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2979): 	at jdj.a(PG:4091)
E/HttpOperation( 2979): 	at jdj.a(PG:1125)
E/HttpOperation( 2979): 	at jdm.a(PG:77)
E/HttpOperation( 2979): 	... 12 more
E/HttpOperation( 2979): Caused by: faj: BadAuthentication
E/HttpOperation( 2979): 	at fal.a(PG:38)
E/HttpOperation( 2979): 	at jdj.a(PG:4089)
E/HttpOperation( 2979): 	... 14 more
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2979): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2979): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2979): 	at jdm.a(PG:82)
E/HttpOperation( 2979): 	at jcs.o(PG:406)
E/HttpOperation( 2979): 	at jcn.a(PG:1379)
E/HttpOperation( 2979): 	at jcs.i(PG:143)
E/HttpOperation( 2979): 	at hec.a(PG:42)
E/HttpOperation( 2979): 	at hee.a(PG:102)
E/HttpOperation( 2979): 	at czr.a(PG:65)
E/HttpOperation( 2979): 	at kka.a(PG:108)
E/HttpOperation( 2979): 	at czp.a(PG:19176)
E/HttpOperation( 2979): 	at czp.a(PG:9081)
E/HttpOperation( 2979): 	at czq.run(PG:1686)
E/HttpOperation( 2979): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2979): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2979): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2979): 	at jdj.a(PG:4091)
E/HttpOperation( 2979): 	at jdj.a(PG:1125)
E/HttpOperation( 2979): 	at jdm.a(PG:77)
E/HttpOperation( 2979): 	... 15 more
E/HttpOperation( 2979): Caused by: faj: BadAuthentication
E/HttpOperation( 2979): 	at fal.a(PG:38)
E/HttpOperation( 2979): 	at jdj.a(PG:4089)
E/HttpOperation( 2979): 	... 17 more
E/ExperimentLoader( 2979): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2979): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2979): 	at jdm.a(PG:82)
E/ExperimentLoader( 2979): 	at jcs.o(PG:406)
E/ExperimentLoader( 2979): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2979): 	at jcs.i(PG:143)
E/ExperimentLoader( 2979): 	at hec.a(PG:42)
E/ExperimentLoader( 2979): 	at hee.a(PG:102)
E/ExperimentLoader( 2979): 	at czr.a(PG:65)
E/ExperimentLoader( 2979): 	at kka.a(PG:108)
E/ExperimentLoader( 2979): 	at czp.a(PG:19176)
E/ExperimentLoader( 2979): 	at czp.a(PG:9081)
E/ExperimentLoader( 2979): 	at czq.run(PG:1686)
E/ExperimentLoader( 2979): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2979): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2979): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2979): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2979): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2979): 	at jdm.a(PG:77)
E/ExperimentLoader( 2979): 	... 15 more
E/ExperimentLoader( 2979): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2979): 	at fal.a(PG:38)
E/ExperimentLoader( 2979): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2979): 	... 17 more
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 286195, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3289): [338] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3289): [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3289): [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3289): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3289): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3289): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3289): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3269): Disconnected process message: 10, size: 0
,I/BooksSync( 3518): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3331): Connecting to GoogleApiClient
,I/BooksConfig( 3518): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1787): Handling authorization failure
E/ClientConnectionOperation( 1787): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1787): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1787): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1787): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1787): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1787): 	... 7 more
,V/KeepSync( 3331): GoogleApiClient failed to connect with error code: 4,
,E/SQLiteLog( 3331): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3331): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3331): (284) automatic index on blob_node(is_deleted),
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3518): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3518): Soft error
E/BooksSync( 3518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3518): Sync error
E/BooksSync( 3518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3518): Finished books sync
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 288516, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3331): IOException
E/KeepSync( 3331): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3331): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3331): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3331): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3331): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3331): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3331): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3331): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3331): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3331): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3331): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3331): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3331): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3331): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3331): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3331): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3331): 	... 10 more
W/KeepSync( 3331): Sync result 2
,D/SyncManager(  825): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 287451, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3269): Disconnected process message: 10, size: 0
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1486): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1486): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1486): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1486): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1486): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1486): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1486): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2711): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2711): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2711): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2711): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2711): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2711): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2711): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2711): Ignoring header User-Agent because its value was null.
,I/jxcore-log( 3209): Toggling radios to false
I/jxcore-log( 3209): 
,D/BluetoothManagerService(  825): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  825): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@365be464 mBinding = false
,D/BluetoothManagerService(  825): Message: 2
,D/WifiService(  825): setWifiEnabled: false pid=3209, uid=10265
,E/WifiService(  825): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService(  825): Sending off request.
D/BluetoothAdapterState( 3269): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3269): Setting state to 13
I/BluetoothAdapterState( 3269): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3269): onBluetoothDisable()
,D/BluetoothManagerService(  825): Message: 60
I/BluetoothAdapterState( 3269): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService(  825): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  825): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3269): onReceive,
D/BluetoothMapService( 3269): STATE_TURNING_OFF
,D/BluetoothMapService( 3269): MAP Service closeService in
D/BluetoothMapMasInstance( 3269): MAP Service shutdown
V/BluetoothMapMasInstance( 3269): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3269): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3269): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3269): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3269): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3269): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3269): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3269): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
I/BtOppRfcommListener( 3269): stopping Accept Thread
E/BtOppRfcommListener( 3269): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 3269): BluetoothSocket listen thread finished
,I/jxcore-log( 3209): Radios toggled
I/jxcore-log( 3209): 
E/WifiStateMachine(  825): WifiStateMachine: Leaving Connected state,
E/WifiConfigStore(  825): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  825): do suspend true
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1486): Read error: ssl=0x9cd57800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1486): SSL shutdown failed: ssl=0x9cd57800: I/O error during system call, Broken pipe
,D/ConnectivityService(  825): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,I/ActivityManager(  825): Start proc 3883:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/BluetoothAdapterProperties( 3269): Scan Mode:20
D/BluetoothAdapterState( 3269): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
W/bt-btif ( 3269): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/btif_config_util( 3269): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-l2cap( 3269): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3269): L2CAP - PSM: 0x0017 not found for deregistration
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService(  825): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  825): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  825): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  825): scanCount==0 - aborting
,D/WifiScanningService(  825): SCAN_AVAILABLE : 1
D/WifiScanningService(  825): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  825): DefaultState
D/RttService(  825): SCAN_AVAILABLE : 1
D/RttService(  825): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNetworkAgent(  825): NetworkAgent: NetworkAgent channel lost
E/native  (  825): do suspend true
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  825): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/ConnectivityService(  825): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  825): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1075): CM callback handler got msg 524292
D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  825): Disconnected - quitting
D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  825): MasterInitialState.processMessage what=3
D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  825): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  825): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/NetworkMonitor( 3458): type=WIFI subType= reason=null isConnected=false
,D/Tethering(  825): MasterInitialState.processMessage what=3
E/ConnectivityService(  825): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/wpa_supplicant( 3286): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3286): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,W/ContextImpl( 3883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  825): getDataEnabled: retVal=false
,D/BluetoothManagerService(  825): Message: 20
D/BluetoothManagerService(  825): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b24e2d0:true
,I/ActivityManager(  825): Start proc 3906:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothManagerService(  825): Message: 30
,E/GpsLocationProvider(  825): No APN found to select.
,D/BluetoothManagerService(  825): Message: 30
,D/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1286): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  825): getDataEnabled: retVal=false
D/LocalBluetoothProfileManager( 3883): Adding local MAP profile
,D/BluetoothMap( 3883): Create BluetoothMap proxy object
,D/BluetoothManagerService(  825): Message: 30
,E/GpsLocationProvider(  825): No APN found to select.
,D/LocalBluetoothProfileManager( 3883): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3883): finishStartingService: stopping service
,D/BluetoothInputDevice( 3883): Proxy object connected
,D/HidProfile( 3883): Bluetooth service connected
,D/BluetoothPan( 3883): BluetoothPAN Proxy object connected
,D/PanProfile( 3883): Bluetooth service connected
,D/BluetoothMap( 3883): Proxy object connected
D/MapProfile( 3883): Bluetooth service connected
D/BluetoothMap( 3883): getConnectedDevices()
,D/BluetoothMap( 3883): Bluetooth is Not enabled
,I/ActivityManager(  825): Killing 3538:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,W/bt-btif ( 3269): ag scb idx 1 not allocated
E/bt-btif ( 3269): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3269): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3269): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3269): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3269): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 3269): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3269): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3269): RX termination
W/bt_userial( 3269): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3269): Leaving userial_read_thread()
D/bt_userial( 3269): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3269): hw_epilog_process
I/bt_userial_vendor( 3269): device fd = 53 close
,I/art     (  825): Explicit concurrent mark sweep GC freed 37037(1655KB) AllocSpace objects, 10(725KB) LOS objects, 31% free, 34MB/50MB, paused 1.949ms total 72.242ms
D/BluetoothManagerService(  825): Message: 30
,D/Tethering(  825): InitialState.processMessage what=4
,I/wpa_supplicant( 3286): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  825): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiMonitor(  825): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/GKI_LINUX( 3269): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3269): GKI_exit_task 0 done
I/GKI_LINUX( 3269): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3269): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3269): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 3269): Exit Disconnected: -1
D/BluetoothHeadset(  825): Proxy object disconnected,
D/BluetoothHeadset( 1075): Proxy object disconnected
D/BluetoothHeadset(  825): Proxy object disconnected
D/BluetoothHeadset(  825): Proxy object disconnected
D/BluetoothHeadset( 1286): Proxy object disconnected
,D/BluetoothAdapterState( 3269): Stopping profile services that were post enabled,
D/A2dpService( 3269): Received stop request...Stopping profile...
D/A2dpStateMachine( 3269): Exit Disconnected: -1
D/BluetoothA2dp( 1075): Proxy object disconnected
,D/BluetoothA2dp(  825): Proxy object disconnected
,D/HidService( 3269): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 1075): Proxy object disconnected
D/BluetoothInputDevice( 3883): Proxy object disconnected
,D/HidProfile( 3883): Bluetooth service disconnected
D/HealthService( 3269): Received stop request...Stopping profile...
D/PanService( 3269): Received stop request...Stopping profile...
,D/BluetoothPan( 1075): BluetoothPAN Proxy object disconnected
D/HeadsetStateMachine( 3269): Unbinding service...
,D/BluetoothPan( 3883): BluetoothPAN Proxy object disconnected
D/PanProfile( 3883): Bluetooth service disconnected
,W/BluetoothHeadsetServiceJni( 3269): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3269): Cleaning up Bluetooth Handsfree callback object
,D/BtGatt.DebugUtils( 3269): handleDebugAction() action=null
,D/BtGatt.GattService( 3269): Received stop request...Stopping profile...
,D/BtGatt.GattService( 3269): stop(),
D/BtGatt.AdvertiseManager( 3269): advertise clients cleared
D/BluetoothMapService( 3269): Received stop request...Stopping profile...
,D/BluetoothMapService( 3269): stop()
D/BluetoothMapEmailAppObserver( 3269): deinitObservers()
D/BluetoothMapEmailAppObserver( 3269): removeReceiver()
D/BluetoothMap( 1075): Proxy object disconnected
,I/GKI_LINUX( 3269): gki_task task_id=2 [A2DP-MEDIA] terminating
D/BluetoothMap( 3883): Proxy object disconnected
D/MapProfile( 3883): Bluetooth service disconnected
I/GKI_LINUX( 3269): GKI_exit_task 2 done
,I/GKI_LINUX( 3269): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3269): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3269): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3269): Cleaning up Bluetooth GID callback object
,W/BluetoothHealthServiceJni( 3269): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3269): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3269): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3269): Cleaning up Bluetooth PAN callback object,
D/BluetoothMapService( 3269): MAP Service closeService in
D/BluetoothAdapterState( 3269): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 3269): cleanup()
,D/BluetoothMapService( 3269): MAP Service closeService in
D/BluetoothAdapterProperties( 3269): Setting state to 10
I/BluetoothAdapterState( 3269): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  825): Message: 60,
D/BluetoothManagerService(  825): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  825): Broadcasting onBluetoothStateChange(false) to 17 receivers.
I/BluetoothAdapterState( 3269): Entering OffState
D/BluetoothHeadset( 1286): onBluetoothStateChange: up=false
,D/BluetoothMap( 1075): onBluetoothStateChange: up=false
D/BluetoothHeadset(  825): onBluetoothStateChange: up=false
D/BluetoothHeadset(  825): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1075): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 1075): onBluetoothStateChange: up=false
D/BluetoothHeadsetClient( 1075): onBluetoothStateChange: up=false
E/BluetoothHeadsetClient( 1075): 
E/BluetoothHeadsetClient( 1075): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@2adcb9bf
E/BluetoothHeadsetClient( 1075): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029),
E/BluetoothHeadsetClient( 1075): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1075): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1075): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1075): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55),
E/BluetoothHeadsetClient( 1075): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothA2dp(  825): onBluetoothStateChange: up=false
D/BluetoothA2dpSink( 1075): onBluetoothStateChange: up=false
,E/BluetoothA2dpSink( 1075): 
E/BluetoothA2dpSink( 1075): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@294d788c
E/BluetoothA2dpSink( 1075): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1075): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1075): 	,at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1075): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1075): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1075): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothInputDevice( 3883): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1075): onBluetoothStateChange: up=false
D/BluetoothMap( 3883): onBluetoothStateChange: up=false
D/BluetoothHeadset(  825): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3883): onBluetoothStateChange: up=false
D/BluetoothAvrcpController( 1075): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1075): 
E/BluetoothAvrcpController( 1075): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@38ff2bd5,
E/BluetoothAvrcpController( 1075): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1075): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1075): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551),
E/BluetoothAvrcpController( 1075): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1075): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1075): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothManagerService(  825): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  825): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService(  825): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@365be464 mBinding = false
D/BluetoothManagerService(  825): Sending unbind request.
,D/BluetoothManagerService(  825): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1075): 697026898: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1075): 697026898: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1075): 697026898: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3269): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3269): GKI_exit_task 1 done
I/GKI_LINUX( 3269): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 3269): cleanupNative: return from cleanup
I/art     ( 3269): System.exit called, status: 0
I/AndroidRuntime( 3269): VM exiting with result code 0, cleanup skipped.
,W/Settings( 2638): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1760): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  825): Process com.android.bluetooth (pid 3269) has died
,D/StrictMode( 3906): StrictMode policy violation; ~duration=286 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3906): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3906): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3906): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3906): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3906): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3906): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3906): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3906): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3906): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3906): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3906): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3906): StrictMode policy violation; ~duration=285 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3906): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3906): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3906): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3906): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3906): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3906): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3906): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3906): StrictMode policy violation; ~duration=277 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3906): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3906): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3906): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3906): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3906): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3906): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3906): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3906): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3906): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3906): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3906): StrictMode policy violation; ~duration=269 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3906): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3906): 	at android.app.SharedPreferencesImpl.awaitLoad,edLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3906): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3906): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3906): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3906): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3906): StrictMode policy violation; ~duration=259 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3906): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3906): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3906): 	at android.app.SharedPreferencesImpl.getInt(SharedPreferencesImpl.java:238)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.shared.b.a.a(PG:1035)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.shared.b.a.a(PG:944)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3906): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3906): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3906): StrictMode policy violation; ~duration=252 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3906): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3906): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3906): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3906): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3906): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3906): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3906): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3906): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3906): StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3906): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3906): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3906): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3906): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3906): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3906): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3906): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3906): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3906): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3906): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3906): # via Binder call with stack:
D/StrictMode( 3906): android.os.StrictMode$LogStackTrace
D/StrictMode( 3906): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3906): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3906): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3906): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3906): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3906): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3906): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3906): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3906): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3906): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3906): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3906): StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3906): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3906): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3906): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3906): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3906): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3906): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3906): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3906): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3906): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3906): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3906): StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3906): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3906): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3906): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3906): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3906): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3906): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3906): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3906): StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3906): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3906): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3906): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3906): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3906): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3906): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3906): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3906): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3906): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3906): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3906): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3906): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3906): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 3906): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  825): Message: 20
D/BluetoothManagerService(  825): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31306f18:true
,I/ActivityManager(  825): Killing 3570:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1486): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/MusicLeanback( 3458): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/ActivityManager(  825): Start proc 3934:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/SprintDMReceiver( 3934): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3934): simOperator:  IMSI: null
D/SprintDMReceiver( 3934): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1787): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1787): onCreate
,D/SystemUpdateService( 1787): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1787): active receiver: enabled
,I/SystemUpdateService( 1787): showing system update notification
,I/iu.Environment( 1787): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1787): num queued entries: 0
,I/iu.UploadsManager( 1787): num updated entries: 0
,I/iu.SyncManager( 1787): NEXT; no task
,D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  825): skipping global notification
,I/Babel   ( 2638): connection state changed from CONNECTED to DISCONNECTED
,V/SystemUpdateService( 1787): retry (wakeup: false) in 3599939 ms
,I/ActivityManager(  825): Start proc 3954:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1787): onDestroy
,I/ActivityManager(  825): Killing 3708:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/GAv4    ( 3954): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3954):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3954):   adb logcat -s GAv4
,W/GAv4    ( 3954): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3954): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3954): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3954): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3954): Time to load native libraries: 1 ms (timestamps 6328-6329)
I/LibraryLoader( 3954): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3954): Binding Chromium to main looper Looper (main, tid 1) {33d63d38}
,I/LibraryLoader( 3954): Expected native library version number "",actual native library version number ""
,I/chromium( 3954): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3954): Initializing chromium process, singleProcess=true
W/art     ( 3954): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3954): ApplicationContext is null in ApplicationStatus
,W/chromium( 3954): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3954): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3954): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3954): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3954): Requires BLUETOOTH permission
,I/NSApplication( 3954): Starting up...
,I/ActivityManager(  825): Killing 3728:com.google.android.deskclock/u0a44 (adj 15): empty #17
,V/MusicLeanback( 3458): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 3934): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3934): simOperator:  IMSI: null
D/SprintDMReceiver( 3934): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1787): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1787): onCreate
,D/SystemUpdateService( 1787): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1787): active receiver: enabled
,I/SystemUpdateService( 1787): showing system update notification
,I/ValidateNoPeople(  825): skipping global notification
,V/SystemUpdateService( 1787): retry (wakeup: false) in 3599968 ms
,D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1787): onDestroy
,W/ContextImpl( 3883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  825): Start proc 4014:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,D/DockEventReceiver( 3883): finishStartingService: stopping service
,W/ResourcesManager( 4014): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 4014): Adding HeadsetService
D/AdapterServiceConfig( 4014): Adding A2dpService
D/AdapterServiceConfig( 4014): Adding HidService
D/AdapterServiceConfig( 4014): Adding HealthService
D/AdapterServiceConfig( 4014): Adding PanService
D/AdapterServiceConfig( 4014): Adding GattService
D/AdapterServiceConfig( 4014): Adding BluetoothMapService
,I/ActivityManager(  825): Killing 3663:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1486): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  825): Failed to find a new network - expiring NetTransition Wakelock
,V/GoogleAuthProtoRequest( 3289): [339] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3289): [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3289): [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3289): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3289): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3289): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3289): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  825): Start proc 4061:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4061): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4061):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4061):   adb logcat -s GAv4
,W/GAv4    ( 4061): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4061): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4061): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  825): Killing 3685:com.android.providers.calendar/u0a3 (adj 15): empty #17
,V/GoogleAuthProtoRequest( 3289): [340] a.<init>: mAccountName set to: thalitester@gmail.com
,I/EventLogService( 1787): Opted in for usage reporting
I/EventLogService( 1787): Aggregate from 1449682303501 (log), 1449682303501 (data)
,I/art     ( 1486): Explicit concurrent mark sweep GC freed 61246(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.031ms total 33.131ms
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3289): [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3289): [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3289): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3289): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3289): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3289): 	at com.a.a.k.run(SourceFile:110)
,W/EventLogAggregator( 1787): Unknown tag: snet_gcore
W/EventLogAggregator( 1787): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1787): dumping service [account]
,I/art     (  825): Explicit concurrent mark sweep GC freed 32552(1684KB) AllocSpace objects, 5(362KB) LOS objects, 32% free, 33MB/49MB, paused 1.354ms total 81.598ms
,I/UsageStatsService(  825): User[0] Flushing usage stats to disk
,V/GoogleAuthProtoRequest( 3289): [341] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3289): [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.,
W/ExperimentUpdateService( 3289): [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3289): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3289): 	at com.google.android.gms.gcm.c.run(Unknown Source)
,W/ExperimentUpdateService( 3289): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3289): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3289): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3289): 	at com.a.a.k.run(SourceFile:110)
,I/ProcessStatsService(  825): Prepared write state in 23ms
,I/ProcessStatsService(  825): Pruning old procstats: /data/system/procstats/state-2015-12-09-06-35-32.bin
,I/GLSUser ( 1486): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1486): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1486): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1486): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1486): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1800000ms)
```
