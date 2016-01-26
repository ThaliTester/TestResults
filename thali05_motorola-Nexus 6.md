#### Test 564496605d11e75_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2699): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2699): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2699): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3118): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3118): CheckJNI is OFF
D/AndroidRuntime( 3118): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{36d17098 token=Token{d4c9a7b ActivityRecord{a62820a u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3118): Shutting down VM
V/WindowManager(  820): Adding window Window{1cd52b2d u0 Starting com.test.thalitest} at 2 of 7 (after Window{31e842cf u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1488): Closing mic
I/MicrophoneInputStream( 1488): mic_close com.google.android.apps.gsa.speech.audio.u@2b0ae199
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
I/ActivityManager(  820): Start proc 3132:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1488): Hotword detection finished
I/HotwordRecognitionRnr( 1488): Stopping hotword detection.
I/ActivityManager(  820): Killing 2790:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660110099
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/kickstart(  874): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_lock
,I/WebViewFactory( 3132): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3132): Time to load native libraries: 2 ms (timestamps 1752-1754)
I/LibraryLoader( 3132): Expected native library version number "",actual native library version number ""
,E/kickstart(  874): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1,
I/kickstart(  874): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,V/WebViewChromiumFactoryProvider( 3132): Binding Chromium to main looper Looper (main, tid 1) {1b7a86ad}
I/LibraryLoader( 3132): Expected native library version number "",actual native library version number ""
,I/chromium( 3132): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3132): Initializing chromium process, singleProcess=true
,W/art     ( 3132): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3132): ApplicationContext is null in ApplicationStatus
,W/chromium( 3132): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3132): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3132): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3132): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3132): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a84399d:true
,D/BluetoothAdapter( 3132): 294278702: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3132): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3132): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3132): CordovaWebView is running on device made by: motorola
,W/art     ( 3132): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3132): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3132): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3132): Validating map...
,V/WindowManager(  820): Adding window Window{40bc40d u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1cd52b2d u0 Starting com.test.thalitest})
,W/chromium( 3132): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3132): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3132): Enabling debug mode 0
,I/art     (  820): Explicit concurrent mark sweep GC freed 19308(904KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.232ms total 56.416ms
,I/Keyboard.Facilitator( 1213): onFinishInput()
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +776ms
,W/BindingManager( 3132): Cannot call determinedVisibility() - never saw a connection for the pid: 3132
,D/JsMessageQueue( 3132): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3132): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580397568
,I/chromium( 3132): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/kickstart(  874): STATUS: Received file 'm9kefs1'
I/kickstart(  874): STATUS: 950272 bytes transferred in 0.986633 seconds
I/kickstart(  874): STATUS: Successfully downloaded files from target 
,I/kickstart(  874): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  874): STATUS: Sahara protocol completed
,W/jxcore-log( 3132): Initializing JXcore engine
W/jxcore-log( 3132): JXcore engine is ready
,W/Thread-322( 3186): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[11510]" dev="sockfs" ino=11510 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-322( 3186): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-322( 3186): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11675]" dev="sockfs" ino=11675 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-322( 3186): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20167]" dev="sockfs" ino=20167 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3132): Starting JXcore engine
,W/jxcore-log( 3132): Platform android
W/jxcore-log( 3132): 
W/jxcore-log( 3132): Process ARCH arm
W/jxcore-log( 3132): 
,I/jxcore-log( 3132): JXcore Cordova bridge is ready!
I/jxcore-log( 3132): 
W/jxcore-log( 3132): JXcore engine is started
,I/jxcore-log( 3132): Toggling radios to true
I/jxcore-log( 3132): 
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  820): Message: 1
D/BluetoothManagerService(  820): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  820): setWifiEnabled: true pid=3132, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  820): New client listening to asynchronous messages
,I/jxcore-log( 3132): Radios toggled
I/jxcore-log( 3132): 
I/jxcore-log( 3132): My device name is: motorola-Nexus 6
I/jxcore-log( 3132): 
,D/SoftapController(  353): Softap fwReload - Ok
,D/CommandListener(  353): Setting iface cfg
D/CommandListener(  353): Trying to bring down wlan0
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
I/ActivityManager(  820): Start proc 3191:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,D/WifiMonitor(  820): startMonitoring(wlan0) with mConnected = false
E/WifiHW  (  820): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/ActivityManager(  820): Start proc 3209:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
I/wpa_supplicant( 3197): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3191): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3197): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  820): Start proc 3236:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  820): Killing 2658:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,D/AdapterServiceConfig( 3191): Adding HeadsetService
D/AdapterServiceConfig( 3191): Adding A2dpService
D/AdapterServiceConfig( 3191): Adding HidService
D/AdapterServiceConfig( 3191): Adding HealthService
,D/AdapterServiceConfig( 3191): Adding PanService
D/AdapterServiceConfig( 3191): Adding GattService
D/AdapterServiceConfig( 3191): Adding BluetoothMapService
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f71b8e6:true
D/BluetoothAdapterState( 3191): make
,I/bluedroid( 3191): init
I/BluetoothAdapterState( 3191): Entering OffState
,I/bte_conf( 3191): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3191): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3191): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3191): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3191): get_profile_interface socket
I/bluedroid( 3191): get_profile_interface map_client
I/GKI_LINUX( 3191): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3191): Address is:F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  820): Bluetooth Adapter name changed to Nexus 6
D/BluetoothAdapterProperties( 3191): Name is: Nexus 6
D/BluetoothManagerService(  820): Stored Bluetooth name: Nexus 6
,D/BluetoothManagerService(  820): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  820): Message: 40
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3191): config_hci_snoop_log
,D/BluetoothManagerService(  820): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  820): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3191): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3191): Setting state to 11
I/BluetoothAdapterState( 3191): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3191): make
,I/BluetoothBondStateMachine( 3191): StableState(): Entering Off State
,D/BluetoothAdapterService( 3191): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f023de2
,D/HeadsetService( 3191): Received start request. Starting profile...
,I/BluetoothAdapterState( 3191): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/BluetoothHeadsetServiceJni( 3191): classInitNative: succeeds
D/HeadsetStateMachine( 3191): make
,D/HeadsetStateMachine( 3191): max_hf_connections = 1
I/bluedroid( 3191): get_profile_interface handsfree
,D/HeadsetStateMachine( 3191): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 3191): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f023de2
,D/BluetoothA2dp(  820): Proxy object connected
,D/A2dpService( 3191): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3191): classInitNative: succeeds
,I/bluedroid( 3191): get_profile_interface avrcp
,E/RemoteController( 3191): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3191): classInitNative: succeeds
D/A2dpStateMachine( 3191): make
I/bluedroid( 3191): get_profile_interface a2dp
I/GKI_LINUX( 3191): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothHidServiceJni( 3191): classInitNative: succeeds
D/BluetoothAdapterService( 3191): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f023de2
D/A2dpStateMachine( 3191): Enter Disconnected: -2
,D/BluetoothA2dp( 1064): Proxy object connected
D/HidService( 3191): Received start request. Starting profile...
I/bluedroid( 3191): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3191): classInitNative: succeeds
D/BluetoothAdapterService( 3191): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f023de2
D/HealthService( 3191): Received start request. Starting profile...
D/BluetoothInputDevice( 1064): Proxy object connected
I/bluedroid( 3191): get_profile_interface health
I/BluetoothPanServiceJni( 3191): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3191): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f023de2
D/PanService( 3191): Received start request. Starting profile...
D/BluetoothPan( 1064): BluetoothPAN Proxy object connected
D/BluetoothPanServiceJni( 3191): initializeNative(L110): pan
I/bluedroid( 3191): get_profile_interface pan
I/BtGatt.JNI( 3191): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3191): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f023de2
D/BtGatt.DebugUtils( 3191): handleDebugAction() action=null
D/BtGatt.GattService( 3191): Received start request. Starting profile...
D/BtGatt.GattService( 3191): start()
I/bluedroid( 3191): get_profile_interface gatt
D/BluetoothAdapterService( 3191): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f023de2
D/BtGatt.AdvertiseManager( 3191): advertise manager created
D/BluetoothAdapterService( 3191): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f023de2
D/BluetoothMap( 1064): Proxy object connected
D/BluetoothMapService( 3191): Received start request. Starting profile...
D/BluetoothMapService( 3191): start()
D/BluetoothMapEmailSettingsLoader( 3191): Found 0 applications
D/BluetoothMapEmailAppObserver( 3191): createReceiver()
D/BluetoothMapEmailAppObserver( 3191): initObservers()
D/BluetoothMapEmailAppObserver( 3191): getEnabledAccountItems()
D/HeadsetStateMachine( 3191): Proxy object connected
D/HeadsetStateMachine( 3191): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3191): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3191): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3191): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3191): enable
I/bt_hci_bdroid( 3191): init
I/GKI_LINUX( 3191): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3191): btu_task pending for preload complete event
I/bt_vendor( 3191): init
I/bt_vnd_conf( 3191): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3191): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3191): userial_init
,I/art     ( 1511): Explicit concurrent mark sweep GC freed 25327(1351KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 3.805ms total 25.780ms
,I/bt_userial_vendor( 3191): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3191): device fd = 53 open
,D/bt_userial( 3191): Entering userial_read_thread()
,I/bt_hwcfg( 3191): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3191): Chipset BCM4354A2
,D/bt_hwcfg( 3191): Target name = [BCM4354A2]
I/bt_hwcfg( 3191): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/ActivityManager(  820): Start proc 3278:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  820): Killing 2822:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/ActivityManager(  820): Killing 2757:com.google.android.gm/u0a78 (adj 15): empty #17
,D/Tethering(  820): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  820): Killing 2339:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/wpa_supplicant( 3197): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3197): Could not read interface p2p-dev-wlan0 flags: No such device
,I/bt_hwcfg( 3191): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3191): Settlement delay -- 100 ms
I/bt_hwcfg( 3191): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3191): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3191): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3191): vendor lib fwcfg completed
,I/bt-btu  ( 3191): btu_task received preload complete event
,I/        ( 3191): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3191): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3191): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3191): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3191): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3191): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3191): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3191): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3191): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3191): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3191): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3191): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3191): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3191): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3191): BTE_InitTraceLevels -- TRC_BTIF
,D/WifiConfigStore(  820): Loading config and enabling all networks 
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@e1ab41e}
,E/WifiConfigStore(  820): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  820): Start proc 3296:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/WifiNative-HAL(  820): Setting external_sim to 1
D/WifiStateMachine(  820): Setting OUI to 92-68-C3
I/WifiNative-HAL(  820): startHal
D/wifi    (  820): setting scan oui 0xb4b71328
D/WifiHAL (  820): Sending mac address OUI
,E/WifiStateMachine(  820): cancelDelayedScan -> 1
,W/Settings( 2612): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/CommandListener(  353): Failed to retrieve HW addr for p2p0 (No such device)
D/CommandListener(  353): Setting iface cfg
E/WifiP2pService(  820): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  820): startMonitoring(p2p0) with mConnected = true
,D/WifiScanningService(  820): SCAN_AVAILABLE : 3
D/RttService(  820): SCAN_AVAILABLE : 3
D/RttService(  820): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  820): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  820): startHal
,I/wpa_supplicant( 3197): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/bt-btm  ( 3191): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2dba085 
E/bt-btm  ( 3191): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2dba085 
,E/native  (  820): do suspend false
,D/WifiNative-HAL(  820): p2pGetDeviceAddress
,D/wifi    (  820): getting scan capabilities on interface[0] = 0xb4b71328
D/WifiHAL (  820): Creating message to get scan capablities; iface = 5
D/WifiHAL (  820): In GetCapabilities::handleResponse
D/WifiHAL (  820): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  820): StartedState
,D/WifiNative-HAL(  820): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,D/BluetoothAdapterProperties( 3191): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3191): Calling BTA_HhEnable
,E/bt-btif ( 3191): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3191): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothAdapterProperties( 3191): Name is: Nexus 6
,D/BluetoothManagerService(  820): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  820): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3191): Scan Mode:20
D/BluetoothAdapterProperties( 3191): Discoverable Timeout:120
,D/bte_conf( 3191): Device ID record 1 : primary
D/bte_conf( 3191):   vendorId            = 000f
D/bte_conf( 3191):   vendorIdSource      = 0001
D/bte_conf( 3191):   product             = 1200
D/bte_conf( 3191):   version             = 1436
D/bte_conf( 3191):   clientExecutableURL = 
D/bte_conf( 3191):   serviceDescription  = 
,D/bte_conf( 3191):   documentationURL    = ,
D/bte_conf( 3191): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3191): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 3191): ScanMode =  20
,D/BluetoothAdapterProperties( 3191): State =  11
D/BluetoothAdapterProperties( 3191): Setting state to 12
I/BluetoothAdapterState( 3191): Bluetooth adapter state changed: 11-> 12,
I/BluetoothAdapterState( 3191): Entering On State
D/BluetoothPanServiceJni( 3191): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan,
D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  820): Broadcasting onBluetoothStateChange(true) to 13 receivers.,
W/bt-btm  ( 3191): Stopping oneshot timer,
E/bt_h4   ( 3191): vendor lib postload completed
D/BluetoothA2dpSink( 1064): onBluetoothStateChange: up=true
,D/BluetoothAdapterProperties( 3191): Scan Mode:21
D/BluetoothAdapterProperties( 3191): Discoverable Timeout:120
E/BluetoothA2dpSink( 1064): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothA2dp( 1064): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1064): onBluetoothStateChange: up=true
D/BluetoothManagerService(  820): Creating new ProfileServiceConnections object for profile: 1
,D/BluetoothHeadsetClient( 1064): onBluetoothStateChange: up=true
,E/BluetoothHeadsetClient( 1064): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothPan( 1064): onBluetoothStateChange(on) call bindService
,W/bt-btm  ( 3191): Stopping oneshot timer
,D/BluetoothMap( 1064): onBluetoothStateChange: up=true,
D/BluetoothInputDevice( 1064): onBluetoothStateChange: up=true
D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1284): onBluetoothStateChange: up=true
D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothA2dp(  820): onBluetoothStateChange: up=true
D/BluetoothAvrcpController( 1064): onBluetoothStateChange: up=true
,E/BluetoothAvrcpController( 1064): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
W/bt-btm  ( 3191): Stopping oneshot timer
,D/BluetoothManagerService(  820): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  820): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  820): Message: 40
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
W/bt-btm  ( 3191): Stopping oneshot timer
,D/BluetoothMapService( 3191): onReceive
D/BluetoothMapService( 3191): STATE_ON
D/BluetoothMapMasInstance( 3191): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3191): MAS initSocket()
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,W/bt-btm  ( 3191): Stopping oneshot timer
,W/BluetoothAdapter( 3191): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3191): Accepting socket connection...
,W/bt-btm  ( 3191): Stopping oneshot timer
,W/bt-btm  ( 3191): Stopping oneshot timer
,D/BluetoothManagerService(  820): Message: 400
,D/BluetoothHeadset( 1064): Proxy object connected
,D/StrictMode( 3296): StrictMode policy violation; ~duration=218 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3296): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3296): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3296): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3296): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3296): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3296): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3296): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=217 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3296): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3296): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3296): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3296): StrictMode policy violation; ~duration=215 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3296): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3296): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3296): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3296): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3296): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3296): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3296): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=211 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3296): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3296): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=204 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPol,icy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3296): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3296): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3296): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3296): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3296): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3296): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3296): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3296): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3296): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3296): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3296): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3296): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3296): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3296): # via Binder call with stack:
D/StrictMode( 3296): android.os.StrictMode$LogStackTrace
D/StrictMode( 3296): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3296): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3296): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3296): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3296): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3296): 	at android.content.ContentResolver.query(ContentResolver.java:422)
,D/StrictMode( 3296): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3296): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3296): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3296): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3296): 	at java.io.File.exists(File.java:363)
,D/StrictMode( 3296): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3296): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3296): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3296): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
,D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3296): 	,at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3296): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3296): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3296): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
,D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3296): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3296): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3296): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3296): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3296): 	,at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3296): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3296): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3296): 	,at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3296): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3296): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3296): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3296): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3296): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3296): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3296): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
,D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/Stric,tMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
D/BluetoothManagerService(  820): Message: 400
,D/BluetoothHeadset( 1284): Proxy object connected
D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
W/com.google.a.a.a.b.a( 3296): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1867e185:true
,I/ActivityManager(  820): Killing 2213:com.android.defcontainer/u0a7 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1511): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3278): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3191): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9b9ec32:true
,D/AuthorizationBluetoothService( 1511): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/LocalBluetoothProfileManager( 3278): Adding local A2DP profile
W/BluetoothAdapter( 3191): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3191): Accept thread started.
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3278): Adding local HEADSET profile
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3278): Adding local MAP profile
D/BluetoothMap( 3278): Create BluetoothMap proxy object
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3278): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3278): finishStartingService: stopping service
,D/BluetoothA2dp( 3278): Proxy object connected
,D/A2dpProfile( 3278): Bluetooth service connected
,D/BluetoothInputDevice( 3278): Proxy object connected
,D/HidProfile( 3278): Bluetooth service connected
,D/BluetoothPan( 3278): BluetoothPAN Proxy object connected
D/PanProfile( 3278): Bluetooth service connected
D/BluetoothMap( 3278): Proxy object connected
D/MapProfile( 3278): Bluetooth service connected
D/BluetoothMap( 3278): getConnectedDevices()
,D/BluetoothPbap( 3278): Proxy object connected
,D/PbapServerProfile( 3278): Bluetooth service connected
,D/BluetoothManagerService(  820): Message: 400
,D/BluetoothHeadset( 3278): Proxy object connected
,D/HeadsetProfile( 3278): Bluetooth service connected
,I/wpa_supplicant( 3197): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  820):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  820):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3,
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0,
,E/WifiConfigStore(  820): will read network variables netId=0
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0,
E/WifiConfigStore(  820): will read network variables netId=0
,I/wpa_supplicant( 3197): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3197): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3197): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3197): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 1
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 1
E/WifiStateMachine(  820):  RSSI mgmt: -49
E/WifiStateMachine(  820):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 0 tx_time=54 rx_time=170 scan_time=0
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/dhcpcd  ( 3338): version 5.5.6 starting
,I/dhcpcd  ( 3338): wlan0: rebinding lease of 192.168.1.122
,I/jxcore-log( 3132): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3132): 
,I/dhcpcd  ( 3338): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,D/HeadsetStateMachine( 3191): Disconnected process message: 10, size: 0
,I/jxcore-log( 3132): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3132): 
,I/jxcore-log( 3132): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3132): 
,I/dhcpcd  ( 3338): wlan0: leased 192.168.1.122 for 86400 seconds,
,I/jxcore-log( 3132): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3132): 
,I/jxcore-log( 3132): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3132): 
,I/jxcore-log( 3132): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3132): 
,I/jxcore-log( 3132): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3132): 
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  820): Adding iface wlan0 to network 100
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  820): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,V/BackupManagerService(  820): Scheduling immediate backup pass
,V/BackupManagerService(  820): Running a backup pass
V/BackupManagerService(  820): clearing pending backups
,D/NetworkChangeNotifierAutoDetect( 1488): Network connectivity changed, type is: 2
,I/NetworkMonitor( 2861): type=WIFI subType= reason=null isConnected=true
,V/PerformBackupTask(  820): Beginning backup of 14 targets
,V/MusicLeanback( 2861): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PerformBackupTask(  820): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  820): doBackup() invoked
,I/PMBA    (  820): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  820): Getting widget state for user: 0
,D/AlarmManagerService(  820): Setting time of day to sec=1453807604
W/AlarmManagerService(  820): Unable to set rtc to 1453807604: Invalid argument
,D/PhoneInterfaceManager( 1284): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1284): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 26 Jan 2016 11:26:44 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453807604818], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453807603801]}
,I/ActivityManager(  820): Start proc 3379:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/GpsLocationProvider(  820): No APN found to select.
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 293us total 35.416ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 17.090ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 243us total 10.936ms
,D/GpsLocationProvider(  820): NTP server returned: 1453807604795 (Tue Jan 26 12:26:44 GMT+01:00 2016) reference: 130627 certainty: 12 system time offset: -98
,I/GoogleURLConnFactory( 1511): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 3379): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,I/art     (  820): Explicit concurrent mark sweep GC freed 49683(2MB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.746ms total 69.578ms
,D/SprintDMHelper( 3379): simOperator:  IMSI: null
D/SprintDMReceiver( 3379): Not Sprint UICC, don't do anything.
,W/DriveInitializer( 1734): Background init thread started
,I/ConfigService( 1511): onCreate
,I/ConfigFetchService( 1734): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1734): running network task: configservice_periodic
,E/WakeLock( 1734): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1734): launchTask
,W/GmsBackupTransport( 1705): Unknown package in backup request: @pm@
,I/ConfigFetchService( 1734): service connected
,W/DriveInitializer( 1734): Awaiting to be initialized
V/GmsBackupTransport( 1705): starting performBackup for @pm@
,V/GmsBackupTransport( 1705): performBackup done for @pm@
,I/SystemUpdateService( 1734): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1734): onCreate
,D/SystemUpdateService( 1734): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1734): active receiver: enabled
,I/CheckinService( 1734): Checking schedule, now: 1453807605069 next: 1453799337970
I/CheckinService( 1734): active receiver: enabled
,V/ConfigFetchTask( 1734): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Uh5S-9kQDTn8zH-bR-Bwant1SuQi0klDVdh02PgtJWCi9g7ojXPEtnSQkCfJl9dO7zh9gIA-GxudOra9Wkpr1zgpsmb55Ddm-Haw-UH0Auaj-rhHtNGxgYOtZBGcW2APZBswQz7rA5vNiPkYEO5ddOwAD-G6HLaZwjDNkL-ldGfyovj-9D-P71mLpHdgTrzaEoHc-8wSKVOtyzBSi8Pow8NSj1y-wOFti0hM41sRX1l95oPfc
,I/SystemUpdateService( 1734): showing system update notification
,I/CheckinService( 1734): Preparing to send checkin request
I/EventLogService( 1734): Accumulating logs since 1453806544032
,I/art     ( 1511): Explicit concurrent mark sweep GC freed 12850(681KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 980us total 49.204ms
,I/ValidateNoPeople(  820): skipping global notification
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SystemUpdateService( 1734): retry (wakeup: false) in 3599970 ms
,D/ConfigFetchService( 1734): ConfigApi connection successful.
,D/SystemUpdateService( 1734): onDestroy
,I/EventLogService( 1734): Opted in for usage reporting
,W/DriveInitializer( 1734): Background init thread ended
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.SyncManager( 1734): SYNC; picasa accounts
,D/NetworkLogImpl( 1734): Loaded NetworkSpeedPredictor
E/Auth.Api.Credentials( 1734): [CredentialSyncAdapter] Unknown sync event.
,I/iu.Environment( 1734): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1511): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1511): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1511): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1511): 	at android.os.Binder.execTransact(Binder.java:446)
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1734): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/GmsBackupTransport( 1705): Error sending final backup to server: 
W/GmsBackupTransport( 1705): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1705): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1705): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1705): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1705): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1705): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1705): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1705): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1705): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1705): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1705): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1705): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1705): 	... 1 more
,D/BackupManagerService(  820): Now staging backup of com.google.android.talk
,D/ChimeraCfgMgr( 1734): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/HttpOperation( 3046): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3046): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3046): 	at jdm.a(PG:82)
E/HttpOperation( 3046): 	at jcs.o(PG:406)
E/HttpOperation( 3046): 	at jcn.a(PG:1379)
E/HttpOperation( 3046): 	at jcs.i(PG:143)
E/HttpOperation( 3046): 	at blb.a(PG:3937)
E/HttpOperation( 3046): 	at czp.a(PG:18188)
E/HttpOperation( 3046): 	at czp.a(PG:9081)
E/HttpOperation( 3046): 	at czq.run(PG:1686)
E/HttpOperation( 3046): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3046): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3046): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3046): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3046): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3046): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3046): 	at jdj.a(PG:4091)
E/HttpOperation( 3046): 	at jdj.a(PG:1125)
E/HttpOperation( 3046): 	at jdm.a(PG:77)
E/HttpOperation( 3046): 	... 12 more
E/HttpOperation( 3046): Caused by: faj: BadAuthentication
E/HttpOperation( 3046): 	at fal.a(PG:38)
E/HttpOperation( 3046): 	at jdj.a(PG:4089)
E/HttpOperation( 3046): 	... 14 more
,D/BackupManagerService(  820): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  820): Now staging backup of com.android.providers.settings
,I/ActivityManager(  820): Start proc 3447:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/BackupManagerService(  820): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  820): Now staging backup of com.google.android.gm
,D/BackupManagerService(  820): Now staging backup of com.android.providers.userdictionary
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/iu.UploadsManager( 1734): num queued entries: 0
D/BackupManagerService(  820): Now staging backup of com.android.nfc
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/BackupManagerService(  820): Now staging backup of com.google.android.apps.genie.geniewidget
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.UploadsManager( 1734): num updated entries: 0
,D/BackupManagerService(  820): Now staging backup of com.google.android.marvin.talkback
,I/iu.SyncManager( 1734): NEXT; no task
V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BackupManagerService(  820): Now staging backup of com.google.android.inputmethod.latin
D/BackupManagerService(  820): Now staging backup of com.google.android.calendar
D/BackupManagerService(  820): Now staging backup of com.android.vending
D/BackupManagerService(  820): Now staging backup of android
D/BackupManagerService(  820): Now staging backup of com.google.android.googlequicksearchbox
,E/HttpOperation( 3046): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3046): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3046): 	at jdm.a(PG:82)
E/HttpOperation( 3046): 	at jcs.o(PG:406)
E/HttpOperation( 3046): 	at jcn.a(PG:1379)
E/HttpOperation( 3046): 	at jcs.i(PG:143)
E/HttpOperation( 3046): 	at hec.a(PG:42)
E/HttpOperation( 3046): 	at hee.a(PG:102)
E/HttpOperation( 3046): 	at czr.a(PG:65)
E/HttpOperation( 3046): 	at kka.a(PG:108)
E/HttpOperation( 3046): 	at czp.a(PG:19176)
E/HttpOperation( 3046): 	at czp.a(PG:9081)
E/HttpOperation( 3046): 	at czq.run(PG:1686)
E/HttpOperation( 3046): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3046): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3046): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3046): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3046): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3046): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3046): 	at jdj.a(PG:4091)
E/HttpOperation( 3046): 	at jdj.a(PG:1125)
E/HttpOperation( 3046): 	at jdm.a(PG:77)
E/HttpOperation( 3046): 	... 15 more
E/HttpOperation( 3046): Caused by: faj: BadAuthentication
E/HttpOperation( 3046): 	at fal.a(PG:38)
E/HttpOperation( 3046): 	at jdj.a(PG:4089)
E/HttpOperation( 3046): 	... 17 more
,E/ExperimentLoader( 3046): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3046): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3046): 	at jdm.a(PG:82)
E/ExperimentLoader( 3046): 	at jcs.o(PG:406)
E/ExperimentLoader( 3046): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3046): 	at jcs.i(PG:143)
E/ExperimentLoader( 3046): 	at hec.a(PG:42)
E/ExperimentLoader( 3046): 	at hee.a(PG:102)
E/ExperimentLoader( 3046): 	at czr.a(PG:65)
E/ExperimentLoader( 3046): 	at kka.a(PG:108)
E/ExperimentLoader( 3046): 	at czp.a(PG:19176)
E/ExperimentLoader( 3046): 	at czp.a(PG:9081)
E/ExperimentLoader( 3046): 	at czq.run(PG:1686)
E/ExperimentLoader( 3046): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3046): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3046): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3046): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3046): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3046): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3046): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3046): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3046): 	at jdm.a(PG:77)
E/ExperimentLoader( 3046): 	... 15 more
E/ExperimentLoader( 3046): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3046): 	at fal.a(PG:38)
E/ExperimentLoader( 3046): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3046): 	... 17 more
,I/GmsBackupTransport( 1705): Next backup will happen in 43199893 millis.
,W/Kids    ( 1734): [AccountUtils] Account not ready
W/Kids    ( 1734): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1734): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1734): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1734): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1734): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1734): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1734): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1734): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1734): 	at java.lang.Thread.run(Thread.java:818)
,I/BackupManagerService(  820): Backup pass finished.
,I/Babel   ( 2612): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1511): Connected
,D/GCM     ( 1511): Message class com.google.f.a.a.p
,W/EventLogAggregator( 1734): Unknown tag: snet_gcore
W/EventLogAggregator( 1734): Unknown tag: snet_launch_service
,I/GAv4    ( 3447): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 3447):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3447):   adb logcat -s GAv4
D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 36543, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/GAv4    ( 3447): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/GoogleAuthProtoRequest( 3209): [322] a.<init>: mAccountName set to: thalitester@gmail.com
I/CheckinRequestBuilder( 1734): Checkin reason type: 12 attempt count: 1
,W/GAv4    ( 3447): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/WifiService(  820): New client listening to asynchronous messages
,W/GAv4    ( 3447): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/ActivityThread( 1734): Failed to find provider info for com.google.android.wearable.settings
,V/KeepSync( 3236): Connecting to GoogleApiClient
,I/ActivityManager(  820): Start proc 3479:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/BaseAppContext( 1734): Using Auth Proxy for data requests.
I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/BaseAppContext( 1734): Using Auth Proxy for data requests.
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ConfigFetchTask( 1734): updating config table for com.google.android.gms
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1734): Handling authorization failure
E/ClientConnectionOperation( 1734): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1734): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1734): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1734): 	... 7 more
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 27382(1807KB) AllocSpace objects, 14(247KB) LOS objects, 35% free, 29MB/45MB, paused 1.169ms total 51.131ms
,V/KeepSync( 3236): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3236): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3236): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3236): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1511): Explicit concurrent mark sweep GC freed 32593(1843KB) AllocSpace objects, 4(87KB) LOS objects, 37% free, 26MB/42MB, paused 998us total 51.282ms
,W/ExperimentUpdateService( 3209): [322] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,I/ConfigFetchService( 1734): fetch service done; releasing wakelock
,I/ConfigFetchService( 1734): stopping self
,W/ExperimentUpdateService( 3209): [322] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3209): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3209): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3209): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3209): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3209): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3209): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3209): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3209): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3209): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3209): 	at com.a.a.k.run(SourceFile:110)
I/WebViewFactory( 3447): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     (  820): Explicit concurrent mark sweep GC freed 27658(1288KB) AllocSpace objects, 5(122KB) LOS objects, 32% free, 33MB/49MB, paused 1.595ms total 75.049ms
,I/LibraryLoader( 3447): Time to load native libraries: 15 ms (timestamps 1765-1780)
I/LibraryLoader( 3447): Expected native library version number "",actual native library version number ""
,I/ActivityManager(  820): Start proc 3518:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
V/WebViewChromiumFactoryProvider( 3447): Binding Chromium to main looper Looper (main, tid 1) {2a064516}
I/LibraryLoader( 3447): Expected native library version number "",actual native library version number ""
I/chromium( 3447): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3447): Initializing chromium process, singleProcess=true
W/art     ( 3447): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3447): ApplicationContext is null in ApplicationStatus
,W/chromium( 3447): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3447): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3447): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3447): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/ResourcesManager( 3518): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3518): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAV2    ( 3479): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3479): Created application version: 3.6.8 (30608)
,V/JNIHelp ( 3518): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3518): Installed default security provider GmsCore_OpenSSL
,W/AudioManagerAndroid( 3447): Requires BLUETOOTH permission
,I/NSApplication( 3447): Starting up...
,I/ActivityManager(  820): Start proc 3569:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,E/YouTube MDX( 3518): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/dex2oat ( 3588): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-920124939.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-920124939.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksSync( 3479): Starting books sync for 61035162, extras: ade
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dex2oat ( 3588): dex2oat took 85.167ms (threads: 4) arena alloc=194KB java alloc=12KB native alloc=1091KB free=6MB
,E/KeepSync( 3236): IOException
E/KeepSync( 3236): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3236): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3236): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3236): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3236): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3236): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3236): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3236): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3236): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3236): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3236): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3236): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3236): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3236): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3236): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3236): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3236): 	... 10 more
W/KeepSync( 3236): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 36546, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 2954:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,W/CheckinRequestBuilder( 1734): awaiting user notification for token
,I/ActivityManager(  820): Start proc 3623:com.google.android.apps.docs.editors.docs/u0a47 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,W/InstanceID/Rpc( 3518): Found 10011
,I/ActivityManager(  820): Start proc 3659:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,I/BooksConfig( 3479): GmsCore Version = 7.8.99 (2134222-430)
,W/ResourcesManager( 3659): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3659): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  820): Start proc 3687:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  820): Killing 2976:com.android.musicfx/u0a18 (adj 15): empty #17
,I/MultiDex( 3659): VM with version 2.1.0 has multidex support
I/MultiDex( 3659): install
I/MultiDex( 3659): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3659): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3479): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3479): Soft error
E/BooksSync( 3479): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3479): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3479): Sync error
E/BooksSync( 3479): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3479): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/ProviderInstaller( 3659): Installed default security provider GmsCore_OpenSSL
,I/BooksSync( 3479): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36547, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 3005:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/WVCdm   (  357): Instantiating CDM.
,I/WVCdm   (  357): CdmEngine::OpenSession
I/WVCdm   (  357): Level3 Library Dec 11 2014 16:13:16
,I/GHttpClientFactory( 2861): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 2861): Using platform SSLCertificateSocketFactory
W/WVCdm   (  357): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  357): Service_Initialize: starts!
D/QSEECOMAPI: (  357): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  357): App is not loaded in QSEE
,I/MusicLifecycle( 2861): Sync started
,I/GoogleURLConnFactory( 3659): Using platform SSLCertificateSocketFactory
,D/QSEECOMAPI: (  357): Loaded image: APP id = 3
,D/DrmWidevineDash(  357): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3a92000
E/DrmWidevineDash(  357): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3a92000
,D/DrmLibTime(  313): got the req here! ret=0
D/DrmLibTime(  313): command id, time_cmd_id = 770
D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  313): QSEE Time Listener: seconds: 1453807607
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 339429009
D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1453807607; nsec = 339429009
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: starts!
,I/art     (  820): Explicit concurrent mark sweep GC freed 18251(798KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.721ms total 51.788ms
,V/GoogleAuthProtoRequest( 3209): [323] a.<init>: mAccountName set to: thalitester@gmail.com
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  357): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: starts! SID=0xb3f01940
D/DrmWidevineDash(  357): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_GetRandom: starts! randomData=0xb4c4e888, dataLength=8
,D/DrmWidevineDash(  357): OEMCrypto_GetRandom: ends! returns 0
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4cf2000, wrapped_rsa_key_length=1280
V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  357): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  357): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  357): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  357): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: starts! deviceID=0xb583d340, idLength=0xb3e03710
,D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  357): PrepareKeyRequest: nonce=2922819036
D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4036600
D/DrmWidevineDash(  357): message_length=1599, signature=0xb587ffc0, signature_length=3017815796
,W/ExperimentUpdateService( 3209): [323] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3209): [323] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3209): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3209): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3209): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3209): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3209): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3209): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3209): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3209): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3209): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3209): 	at com.a.a.k.run(SourceFile:110)
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
,I/GAv4    ( 3623): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3623):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3623):   adb logcat -s GAv4
,W/GAv4    ( 3623): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 3623): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 3623): Analytics setup for ID UA-21125203-4, app name Docs, version 1.4.292.15.30
I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 3623): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/GLSActivity( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1511): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1511): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1511): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1511): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ActivityManager(  820): Start proc 3731:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,I/MusicLifecycle( 2861): Sync ended
W/MusicSyncAdapter( 2861): Sync failed due to an authentication issue.
,I/ActivityManager(  820): Killing 1402:android.process.acore/u0a5 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 36563, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 163724, reason: Periodic
,W/ResourcesManager( 3623): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3623): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/WVCdm   (  357): CdmEngine::OpenSession
,I/WVCdm   (  357): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  357): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  357): Service_Initialize: starts!
D/QSEECOMAPI: (  357): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  357): App is not loaded in QSEE
,E/SQLiteLog( 3731): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,V/JNIHelp ( 3623): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  820): Start proc 3765:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,I/ProviderInstaller( 3623): Installed default security provider GmsCore_OpenSSL
,D/QSEECOMAPI: (  357): Loaded image: APP id = 3
,D/DrmWidevineDash(  357): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3a92000
E/DrmWidevineDash(  357): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3a92000
,D/DrmLibTime(  313): got the req here! ret=0
D/DrmLibTime(  313): command id, time_cmd_id = 770
D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  313): QSEE Time Listener: seconds: 1453807607
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 982027863
D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1453807607; nsec = 982027863
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: starts!
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@183505b4}
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  357): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: starts! SID=0xb3f01940
,D/DrmWidevineDash(  357): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  357): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_GetRandom: starts! randomData=0xb40a9230, dataLength=8
,D/DrmWidevineDash(  357): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4cf1a00, wrapped_rsa_key_length=1280
I/AnalyticsLogBase( 3731): PlayLogger.onLoggerConnected
D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  357): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  357): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  357): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  357): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: starts! deviceID=0xb583d380, idLength=0xbe9532f0
,D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  357): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  357): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  357): PrepareKeyRequest: nonce=1527955097
D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4038200
D/DrmWidevineDash(  357): message_length=1634, signature=0xb5bfa640, signature_length=3197448916
,I/ActivityManager(  820): Start proc 3790:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  820): Killing 1766:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/TimeService( 3790): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453807608084
D/        ( 3790): TimeServiceNative: User Time to be set is 1453807608084
D/QC-time-services( 3790): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3790): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3790): Lib:time_genoff_operation: pargs->ts_val = 1453807608084
D/QC-time-services( 3790): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  372): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  372): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453807608084
D/QC-time-services(  372): Daemon:genoff_opr: Base = 2, val = 1453807608084, operation = 0
D/QC-time-services(  372): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/13/70 7:39:15
D/QC-time-services(  372): Daemon:Value read from RTC seconds = 14110755000
D/QC-time-services(  372): Daemon:new time 1453807608084 
D/QC-time-services(  372): Daemon: delta 1439696853084 genoff 1439696853084 
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696853084 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  357): CdmEngine::CloseSession
,D/DrmWidevineDash(  357): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  357): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  357): L3 Terminate.
D/DrmWidevineDash(  357): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  357): Service_Uninitialize: starts!
D/QSEECOMAPI: (  357): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  357): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  357): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_Terminate: ends! returns 0
,D/QC-time-services(  372): Updating the TOD offset
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696853084 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  372): Daemon:Update to modem bit set
D/QC-time-services(  372): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  372): Daemon: Base = 2, Value being sent to MODEM = 1137842808084
,E/QC-time-services( 3790): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  372): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  372): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  820): Start proc 3813:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,I/ActivityManager(  820): Killing 2699:com.android.vending/u0a19 (adj 15): empty #17
,I/dex2oat ( 3811): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/art     (  368): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 13.602ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 8.564ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 8.492ms
,I/dex2oat ( 3811): dex2oat took 38.622ms (threads: 4) arena alloc=59KB java alloc=18KB native alloc=1119KB free=6MB
,I/Adreno  ( 3659): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 3765): Sync request not initiated by GCP app. Dropping
,I/Adreno  ( 3659): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/ActivityManager(  820): Start proc 3841:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  820): Killing 3278:com.android.settings/1000 (adj 15): empty #17
,I/EventLogService( 1734): Opted in for usage reporting
,I/ActivityManager(  820): Killing 3296:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/GAv4    ( 3841): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3841):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3841):   adb logcat -s GAv4
,W/GAv4    ( 3841): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3841): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/Auth.Api.Credentials( 1734): [CredentialSyncAdapter] Unknown sync event.
,W/GAv4    ( 3841): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1511): Explicit concurrent mark sweep GC freed 24276(1352KB) AllocSpace objects, 5(551KB) LOS objects, 36% free, 27MB/43MB, paused 917us total 67.429ms
,I/ActivityManager(  820): Start proc 3873:com.google.android.apps.docs.editors.sheets/u0a48 for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,I/ActivityManager(  820): Killing 3379:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,E/DefaultHttpIssuer( 3623): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 3623): java.io.IOException
E/DefaultHttpIssuer( 3623): 	at fur.b(PG:162)
E/DefaultHttpIssuer( 3623): 	at fup.b(PG:6072)
E/DefaultHttpIssuer( 3623): 	at com.google.android.apps.docs.flags.ClientFlagSynchronizer.a(PG:1080)
E/DefaultHttpIssuer( 3623): 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.c(PG:26263)
E/DefaultHttpIssuer( 3623): 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.b(PG:611)
E/DefaultHttpIssuer( 3623): 	at gtm.run(PG:2507)
E/DefaultHttpIssuer( 3623): 	at gtk.run(PG:3031)
,E/BaseSyncManager( 3623): ClientFlagSyncException
E/BaseSyncManager( 3623): com.google.android.apps.docs.flags.ClientFlagSynchronizer$ClientFlagSyncException: IO Exception opening: https://ssl.gstatic.com/docs/android/editors/docs/client_flags socket is closed
E/BaseSyncManager( 3623): 	at com.google.android.apps.docs.flags.ClientFlagSynchronizer.b(PG:4108)
E/BaseSyncManager( 3623): 	at com.google.android.apps.docs.flags.ClientFlagSynchronizer.a(PG:1060)
E/BaseSyncManager( 3623): 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.c(PG:26263)
E/BaseSyncManager( 3623): 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.b(PG:611)
E/BaseSyncManager( 3623): 	at gtm.run(PG:2507)
E/BaseSyncManager( 3623): 	at gtk.run(PG:3031)
E/BaseSyncManager( 3623): Caused by: java.net.SocketException: socket is closed
E/BaseSyncManager( 3623): 	at com.google.android.gms.org.conscrypt.s.write(SourceFile:758)
E/BaseSyncManager( 3623): 	at kcm.a_(PG:78)
E/BaseSyncManager( 3623): 	at kby.a_(PG:155)
E/BaseSyncManager( 3623): 	at kcp.flush(PG:221)
E/BaseSyncManager( 3623): 	at kab$d.b(PG:381)
E/BaseSyncManager( 3623): 	at kan.a(PG:279)
E/BaseSyncManager( 3623): 	at jzu.a(PG:10245)
E/BaseSyncManager( 3623): 	at jzj$a.a(PG:890)
E/BaseSyncManager( 3623): 	at jxv.a(PG:50089)
E/BaseSyncManager( 3623): 	at jxv$a.a(PG:230)
E/BaseSyncManager( 3623): 	at jxv.a(PG:3201)
E/BaseSyncManager( 3623): 	at fxi.a(PG:127)
E/BaseSyncManager( 3623): 	at fun.a(PG:47)
E/BaseSyncManager( 3623): 	at fum.a(PG:22)
E/BaseSyncManager( 3623): 	at fuo.a(PG:68)
E/BaseSyncManager( 3623): 	at fur.b(PG:92)
E/BaseSyncManager( 3623): 	at fur.a(PG:80)
E/BaseSyncManager( 3623): 	at fup.b(PG:6140)
E/BaseSyncManager( 3623): 	at fup.a(PG:2096)
E/BaseSyncManager( 3623): 	at fup.a(PG:1062)
E/BaseSyncManager( 3623): 	at com.google.android.apps.docs.flags.ClientFlagSynchronizer.b(PG:4106)
E/BaseSyncManager( 3623): 	... 5 more
,I/GCM     ( 1734): Message from null null
E/GCM     ( 1734): Dropping message from null
,V/Herrevad( 1734): NQAS connected
,I/ConfigFetchService( 1734): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1734): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1734): GmsCore config value changed; rescheduling
I/ConfigFetchService( 1734): service connected
,D/ConfigFetchService( 1734): ConfigApi connection successful.
,I/ConfigFetchService( 1734): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1734): stopping self
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@e1ab41e}
,I/art     (  820): Explicit concurrent mark sweep GC freed 23067(1026KB) AllocSpace objects, 8(410KB) LOS objects, 32% free, 33MB/49MB, paused 1.614ms total 53.034ms
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1511): Vacuum at: now=1453807609316 tag=VacuumService
,D/GCM     ( 1511): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1511): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1734): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs.editors.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  820): Start proc 3903:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 1734): Restart initialization of location
,W/ResourcesManager( 3903): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3903): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Ads     ( 1734): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,E/Babel   ( 2612): UserRecoverableAuthException.
,E/Babel   ( 2612): eei: BadAuthentication
E/Babel   ( 2612): 	at eeg.a(Unknown Source)
E/Babel   ( 2612): 	at eeg.a(Unknown Source)
E/Babel   ( 2612): 	at eeg.a(Unknown Source)
E/Babel   ( 2612): 	at g.a(Unknown Source)
E/Babel   ( 2612): 	at cae.a(SourceFile:3089)
E/Babel   ( 2612): 	at cae.a(SourceFile:1131)
E/Babel   ( 2612): 	at cws.a(SourceFile:4333)
E/Babel   ( 2612): 	at cws.a(SourceFile:1419)
E/Babel   ( 2612): 	at crl.a(SourceFile:492)
E/Babel   ( 2612): 	at crl.a(SourceFile:1468)
E/Babel   ( 2612): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2612): 	at cas.b(SourceFile:106)
E/Babel   ( 2612): 	at cap.d(SourceFile:335)
E/Babel   ( 2612): 	at caq.run(SourceFile:81)
E/Babel   ( 2612): Error getting auth token
E/Babel   ( 2612): dvm
E/Babel   ( 2612): 	at g.a(Unknown Source)
E/Babel   ( 2612): 	at cae.a(SourceFile:3089)
E/Babel   ( 2612): 	at cae.a(SourceFile:1131)
E/Babel   ( 2612): 	at cws.a(SourceFile:4333)
E/Babel   ( 2612): 	at cws.a(SourceFile:1419)
E/Babel   ( 2612): 	at crl.a(SourceFile:492)
E/Babel   ( 2612): 	at crl.a(SourceFile:1468)
E/Babel   ( 2612): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2612): 	at cas.b(SourceFile:106)
E/Babel   ( 2612): 	at cap.d(SourceFile:335)
E/Babel   ( 2612): 	at caq.run(SourceFile:81)
,E/Babel   ( 2612): Account registration failed 1-Redacted-21
E/Babel   ( 2612): cyp: null -- null
E/Babel   ( 2612): 	at cae.a(SourceFile:3121)
E/Babel   ( 2612): 	at cae.a(SourceFile:1131)
E/Babel   ( 2612): 	at cws.a(SourceFile:4333)
E/Babel   ( 2612): 	at cws.a(SourceFile:1419)
E/Babel   ( 2612): 	at crl.a(SourceFile:492)
E/Babel   ( 2612): 	at crl.a(SourceFile:1468)
E/Babel   ( 2612): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2612): 	at cas.b(SourceFile:106)
E/Babel   ( 2612): 	at cap.d(SourceFile:335)
E/Babel   ( 2612): 	at caq.run(SourceFile:81)
,I/art     ( 2612): Note: end time exceeds epoch: 
,W/GLSActivity( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1511): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1511): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1511): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1511): 	at android.os.Binder.execTransact(Binder.java:446)
I/MultiDex( 3903): VM with version 2.1.0 has multidex support
I/MultiDex( 3903): install
I/MultiDex( 3903): VM has multidex support, MultiDex support library is disabled.
,E/DefaultHttpIssuer( 3623): Attempt to consume entity of HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 3623): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 3623): java.io.IOException
E/DefaultHttpIssuer( 3623): 	at fur.b(PG:162)
E/DefaultHttpIssuer( 3623): 	at fup.b(PG:6072)
E/DefaultHttpIssuer( 3623): 	at gtb.b(PG:213)
E/DefaultHttpIssuer( 3623): 	at gtb.a(PG:125)
E/DefaultHttpIssuer( 3623): 	at gyh.a(PG:224)
E/DefaultHttpIssuer( 3623): 	at com.google.android.apps.docs.sync.syncadapter.BaseSyncManager.b(PG:618)
E/DefaultHttpIssuer( 3623): 	at gtm.run(PG:2507)
E/DefaultHttpIssuer( 3623): 	at gtk.run(PG:3031)
,V/JNIHelp ( 3903): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/BaseSyncManager( 3623): AuthenticatorException
E/BaseSyncManager( 3623): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 3623): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/BaseSyncManager( 3623): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 3623): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/BaseSyncManager( 3623): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 3623): 	at android.os.Binder.execTransact(Binder.java:446)
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@183505b4}
,I/GoogleURLConnFactory( 1511): Using platform SSLCertificateSocketFactory
,I/ProviderInstaller( 3903): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 3903): callingUid 10011, callindPid: 3903
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1705): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1511): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1511): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  820): Start proc 3942:com.google.android.apps.genie.geniewidget/u0a80 for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService
,W/ResourcesManager( 1511): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinTask( 1734): Sending checkin request (9674 bytes)
,I/MusicLeanback( 2861): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2861): Stop autocaching.
,I/ActivityManager(  820): Killing 3447:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,E/Babel   ( 2612): Unexpected exception while authenticating.
E/Babel   ( 2612): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2612): 	at eeg.b(Unknown Source)
E/Babel   ( 2612): 	at eeg.b(Unknown Source)
E/Babel   ( 2612): 	at g.a(Unknown Source)
E/Babel   ( 2612): 	at cae.b(SourceFile:1146)
E/Babel   ( 2612): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2612): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2612): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2612): 	at java.lang.Thread.run(Thread.java:818)
,I/GAv4    ( 3873): Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3873):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3873):   adb logcat -s GAv4
,W/GAv4    ( 3873): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3873): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 3873): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.332.11.30
,W/GAv4    ( 3873): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     ( 1511): Explicit concurrent mark sweep GC freed 32803(1863KB) AllocSpace objects, 12(1323KB) LOS objects, 37% free, 27MB/43MB, paused 952us total 34.433ms
V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AuthorizationBluetoothService( 1511): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/GCM     ( 1511): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/GmsCoreStatsServiceLauncher( 1734): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1705): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1734): Restart initialization of location
,E/Uploader( 1511): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1511): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1511): No account for auth token provided
,I/NewsWeather( 3942): NewsAccounts 2, AllSystemAccounts 1
,I/NewsWeather( 3942): Last usage 1447148544093, idle 6659066 seconds, sync interval 2592000 seconds
,I/NewsWeather( 3942): setPeriodicSync in 2592000 seconds
,E/GmsUtils( 2861): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 2861): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/CheckinResponseProcessor( 1734): From server: 2 gservices updates and 0 deletes
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@331a6564}
,W/ResourcesManager( 3942): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3942): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Uploader( 1511): No account for auth token provided
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 3942): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3942): Installed default security provider GmsCore_OpenSSL
I/GoogleURLConnFactory( 3942): binding HttpService
,W/ResourcesManager( 3873): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3873): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/CertBlacklister(  820): Certificate blacklist changed, updating...
,I/CertBlacklister(  820): Certificate blacklist updated
,I/GservicesProvider( 1511): main difference update completed
,W/Uploader( 1511): No account for auth token provided
,V/JNIHelp ( 3873): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     (  820): Explicit concurrent mark sweep GC freed 23844(1189KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.157ms total 67.849ms
,I/NewsWeather( 3942): Skip sync for lookup editions
I/NewsWeather( 3942): syncNewsAppData traffic type BACKGROUND_POLL
,I/ActivityManager(  820): Start proc 4009:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,I/CheckinRequestBuilder( 1734): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1734): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 3132): Test app app.js loaded
I/jxcore-log( 3132): 
,I/chromium( 3132): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3132): setDiscoveryMode: Mode set to BLE
,I/ProviderInstaller( 3873): Installed default security provider GmsCore_OpenSSL
,I/jxcore-log( 3132): BLE advertisement is supported
I/jxcore-log( 3132): 
,W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
I/Babel_telephony( 2612): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,W/Babel   ( 2612): BAM#gBA: invalid account id: -1
W/Babel   ( 2612): BAM#gBA: invalid account id: -1
I/Babel_telephony( 2612): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,W/Uploader( 1511): No account for auth token provided
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=50.22 rxSuccessRate=54.69 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,I/ActivityManager(  820): Start proc 4035:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=50.22 rxSuccessRate=54.69 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,E/UpdateRequestReceiver( 4035): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/Uploader( 1511): No account for auth token provided
,E/UpdateRequestReceiver( 4035): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4035): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4035): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  820): Killing 1488:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,E/DefaultHttpIssuer( 3873): Attempt to close HttpIssuer when no request is executing.
,E/BaseSyncManager( 3873): ClientFlagSyncException
E/BaseSyncManager( 3873): com.google.android.apps.docs.flags.f$a: IO Exception opening: https://ssl.gstatic.com/docs/android/editors/sheets/client_flags?1453807610431= stream was reset: PROTOCOL_ERROR
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.flags.f.a(PG:1108)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.sync.syncadapter.n.a(PG:23060)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.sync.syncadapter.n.c(PG:612)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.sync.syncadapter.q.run(PG:3508)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.sync.syncadapter.o.run(PG:3031)
E/BaseSyncManager( 3873): Caused by: java.io.IOException: stream was reset: PROTOCOL_ERROR
E/BaseSyncManager( 3873): 	at com.squareup.okhttp.internal.spdy.aa.b(PG:145)
E/BaseSyncManager( 3873): 	at com.squareup.okhttp.internal.http.u.b(PG:104)
E/BaseSyncManager( 3873): 	at com.squareup.okhttp.internal.http.h.d(PG:917)
E/BaseSyncManager( 3873): 	at com.squareup.okhttp.internal.http.h.a(PG:95)
E/BaseSyncManager( 3873): 	at com.squareup.okhttp.internal.http.h$a.a(PG:902)
E/BaseSyncManager( 3873): 	at com.squareup.okhttp.e.a(PG:50089)
E/BaseSyncManager( 3873): 	at com.squareup.okhttp.e$a.a(PG:230)
E/BaseSyncManager( 3873): 	at com.squareup.okhttp.e.a(PG:3201)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.net.okhttp.c.a(PG:156)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.http.executors.b.a(PG:47)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.http.executors.a.a(PG:22)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.http.executors.c.a(PG:69)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.http.issuers.c.b(PG:96)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.http.issuers.c.a(PG:84)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.http.issuers.a.b(PG:6140)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.http.issuers.a.a(PG:2096)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.http.issuers.a.a(PG:1062)
E/BaseSyncManager( 3873): 	at com.google.android.apps.docs.flags.f.a(PG:1106)
E/BaseSyncManager( 3873): 	... 4 more
,I/art     ( 1511): Explicit concurrent mark sweep GC freed 35478(1970KB) AllocSpace objects, 13(1180KB) LOS objects, 37% free, 27MB/43MB, paused 7.924ms total 101.605ms
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 35061(2MB) AllocSpace objects, 17(271KB) LOS objects, 35% free, 29MB/45MB, paused 1.343ms total 81.841ms
,D/WifiService(  820): Client connection lost with reason: 4
,I/SystemUpdateService( 1734): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1734): onCreate
,I/ActivityManager(  820): Killing 3569:com.android.chrome/u0a40 (adj 15): empty #17
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/GCM     ( 1511): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/SystemUpdateService( 1734): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SystemEventReceiver( 1734): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1734): Updating ocr activity enabled=false
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs.editors.sheets, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Uploader( 1511): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1511): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1705): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/SystemUpdateService( 1734): active receiver: enabled
,I/NewsWeather( 3942): onConnected null
,I/GCoreUlr( 1705): DispatchingService.onCreate()
,W/GLSActivity( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1511): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1511): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1511): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1511): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DefaultHttpIssuer( 3873): Attempt to consume entity of HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 3873): Attempt to close HttpIssuer when no request is executing.
,W/GCoreFlp( 1705): No location to return for getLastLocation()
,W/GCoreFlp( 1705): No location to return for getLastLocation()
E/BaseSyncManager( 3873): AuthenticatorException
E/BaseSyncManager( 3873): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 3873): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/BaseSyncManager( 3873): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 3873): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/BaseSyncManager( 3873): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 3873): 	at android.os.Binder.execTransact(Binder.java:446)
,I/NewsWeather( 3942): Location onConnected: location null
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@331a6564}
,I/ActivityManager(  820): Killing 3518:com.google.android.youtube/u0a86 (adj 15): empty #17
,I/NewsWeather( 3942): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,I/GAV2    ( 3479): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 1511): Explicit concurrent mark sweep GC freed 17479(985KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 27MB/43MB, paused 1.770ms total 62.795ms
,I/SystemUpdateService( 1734): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1734): retry (wakeup: false) in 3599689 ms
,I/art     ( 1705): Explicit concurrent mark sweep GC freed 11913(650KB) AllocSpace objects, 4(64KB) LOS objects, 37% free, 26MB/42MB, paused 2.786ms total 35.598ms
,E/DataBuffer( 1705): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@105b6b72)
,I/art     (  820): Explicit concurrent mark sweep GC freed 11878(579KB) AllocSpace objects, 6(473KB) LOS objects, 32% free, 33MB/49MB, paused 1.235ms total 79.093ms
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GCoreUlr( 1705): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.genie.geniewidget, service: oauth2:https://www.googleapis.com/auth/newsreader
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/newsreader without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Uploader( 1511): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1511): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660110099
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/CheckinRequestBuilder( 1734): awaiting user notification for token
,E/NewsWeather( 3942): Exception reported
E/NewsWeather( 3942): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 3942): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 3942): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.pa(SourceFile:152)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:102)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.d.a(SourceFile:284)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.l.au(SourceFile:164)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.l.as(SourceFile:92)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.l.onPerformSync(SourceFile:81)
E/NewsWeather( 3942): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/NewsWeather( 3942): Signed-in user with null auth token
E/NewsWeather( 3942): Transport error in DownSync
E/NewsWeather( 3942): Down sync of news app Failed, error code: SYNC_IO_ERROR
,I/NewsWeather( 3942): Detected SyncErrorCodeCategory SOFT_ERROR
,I/NewsWeather( 3942): Abort on too many retries? false
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  820): Killing 3046:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, currentRunTime 36563, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1511): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1511): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/art     ( 1511): Explicit concurrent mark sweep GC freed 12380(677KB) AllocSpace objects, 6(661KB) LOS objects, 36% free, 27MB/43MB, paused 1.344ms total 43.062ms
,I/GCoreUlr( 1705): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1705): Unbound from all location providers
,I/GCoreUlr( 1705): DispatchingService.onDestroy()
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 8522(507KB) AllocSpace objects, 5(80KB) LOS objects, 35% free, 29MB/45MB, paused 1.590ms total 35.850ms
,I/GCoreUlr( 1705): Unbound from all location providers
,W/Uploader( 1511): No account for auth token provided
,D/SystemUpdateService( 1734): onDestroy
,I/EventLogService( 1734): Opted in for usage reporting
,I/CheckinTask( 1734): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1734): Checking schedule, now: 1453807611790 next: 1453848754782
I/CheckinService( 1734): active receiver: disabled
,W/Uploader( 1511): No account for auth token provided
,I/ActivityManager(  820): Start proc 4090:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver
,I/CheckinService( 1734): Checking schedule, now: 1453807611829 next: 1453848754782
,I/CheckinService( 1734): active receiver: disabled
,W/Uploader( 1511): No account for auth token provided
,W/Uploader( 1511): No account for auth token provided
,W/Uploader( 1511):  no longer exists, so no auth token.
,W/Uploader( 1511): No account for auth token provided
,I/GservicesUpdateTask( 4090): Updating Gservices keys
,D/ChimeraCfgMgr( 1734): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1734): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1511): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Uploader( 1511): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1511): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Kids    ( 1734): [AccountUtils] Account not ready
W/Kids    ( 1734): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1734): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1734): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1734): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1734): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1734): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1734): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1734): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1734): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  820): Killing 3479:com.google.android.apps.books/u0a34 (adj 15): empty #17
,W/Uploader( 1511): No account for auth token provided
,W/Uploader( 1511): No account for auth token provided
,W/Uploader( 1511): No account for auth token provided
,W/Uploader( 1511): No account for auth token provided
,W/Uploader( 1511): No account for auth token provided
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1511): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1511): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GAV2    ( 3731): Thread[GAThread,5,main]: No campaign data found.
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1511): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1511): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1511): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1511): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1511): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1511): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1511): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  820): Killing 3236:com.google.android.keep/u0a79 (adj 15): empty #17
,I/ConfigService( 1511): onDestroy
,I/ActivityManager(  820): Start proc 4132:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,I/ActivityManager(  820): Killing 3790:com.qualcomm.timeservice/1000 (adj 15): empty #17
,D/Finsky  ( 4132): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 4132): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  820): Start proc 4168:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 4132): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4132): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  820): Killing 3813:com.google.android.apps.cloudprint/u0a41 (adj 15): empty #17
,W/ResourcesManager( 4168): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4168): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 4168): VM with version 2.1.0 has multidex support
I/MultiDex( 4168): install
,I/MultiDex( 4168): VM has multidex support, MultiDex support library is disabled.
,I/art     (  820): Explicit concurrent mark sweep GC freed 25723(1235KB) AllocSpace objects, 8(316KB) LOS objects, 31% free, 34MB/50MB, paused 1.460ms total 79.999ms
,V/JNIHelp ( 4168): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     ( 1511): Explicit concurrent mark sweep GC freed 34578(1989KB) AllocSpace objects, 9(916KB) LOS objects, 36% free, 27MB/43MB, paused 1.178ms total 34.934ms
,D/Finsky  ( 4132): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4132): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4132): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4132): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ProviderInstaller( 4168): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1511): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1511): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1734): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3903): callingUid 10011, callindPid: 3903
,D/LocationInitializer( 1734): Restart initialization of location
,E/MDM     ( 1705): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/Finsky  ( 4132): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4132): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4132): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4132): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ActivityManager(  820): Killing 3765:com.google.android.apps.cloudprint:sync/u0a41 (adj 15): empty #17
,D/Finsky  ( 4132): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4132): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 4132): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 4132): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 4132): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4132): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4132): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1705): client connected with version: 7571000
,I/ActivityManager(  820): Killing 3841:com.google.android.deskclock/u0a44 (adj 15): empty #17
,W/PackageSettings(  820): Skipping PackageSetting{1a9226b9 com.example.hello/10273} due to missing metadata
,I/ActivityManager(  820): Killing 3209:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  820): Start proc 4211:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,V/GmsNetworkLocationProvi( 1705): DISABLE
,D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  820): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  820): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/GmsNetworkLocationProvi( 1705): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/BackupManagerService(  820): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  820): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3bd71cb6
,V/GmsNetworkLocationProvi( 1705): ENABLE
,V/GmsNetworkLocationProvi( 1705): SET-REQUEST
,V/GmsNetworkLocationProvi( 1705): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/BackupManagerService(  820): Scheduling immediate backup pass
,V/BackupManagerService(  820): Running a backup pass
,V/BackupManagerService(  820): clearing pending backups
,V/PerformBackupTask(  820): Beginning backup of 14 targets
,D/PerformBackupTask(  820): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  820): doBackup() invoked
,I/PMBA    (  820): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/Launcher( 1313): Deferring update until onResume
,D/PackageBroadcastService( 1734): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/BackupRestoreController(  820): Getting widget state for user: 0
,I/PackageBroadcastService( 1734): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 4090): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1313): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@228d1b5c new=com.google.android.velvet.VelvetApplication@228d1b5c
,I/Icing   ( 1734): updateResources: need to parse f{com.google.android.gms}
,I/ContactLocale( 4211): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  820): Start proc 4238:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 346us total 14.958ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 224us total 12.487ms
,W/GmsBackupTransport( 1705): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1705): starting performBackup for @pm@
,W/ResourcesManager( 4238): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 224us total 10.086ms
,V/GmsBackupTransport( 1705): performBackup done for @pm@
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UpdateIcingCorporaServi( 4090): UpdateCorporaTask done [took 117 ms] updated apps [took 117 ms] 
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1511): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1511): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1511): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1511): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1511): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1511): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1511): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1705): Error sending final backup to server: 
W/GmsBackupTransport( 1705): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1705): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1705): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1705): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1705): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1705): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1705): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1705): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1705): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1705): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1705): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1705): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1705): 	... 1 more
,D/BackupManagerService(  820): Now staging backup of com.google.android.talk
,D/BackupManagerService(  820): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  820): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  820): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  820): Now staging backup of com.google.android.gm
,D/BackupManagerService(  820): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  820): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  820): Now staging backup of com.android.nfc
,D/BackupManagerService(  820): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  820): Now staging backup of com.android.vending
,D/BackupManagerService(  820): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  820): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  820): Now staging backup of android
,D/BackupManagerService(  820): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1705): Next backup will happen in 43199969 millis.
,I/BackupManagerService(  820): Backup pass finished.
,I/art     (  820): Explicit concurrent mark sweep GC freed 29258(1733KB) AllocSpace objects, 11(1024KB) LOS objects, 32% free, 33MB/49MB, paused 1.465ms total 65.957ms
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=8.51 rxSuccessRate=8.99 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 5220
,I/ActivityManager(  820): Killing 3623:com.google.android.apps.docs.editors.docs/u0a47 (adj 15): empty #17
,I/ActivityManager(  820): Killing 2861:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (230 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  820): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  820): Excessive delay in setPowerMode(): 286ms
,I/DreamManagerService(  820): Entering dreamland.
I/PowerManagerService(  820): Dozing...
I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 6
,E/native  (  820): do suspend false
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@74869f0}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.97 rxSuccessRate=1.54 targetRoamBSSID=any RSSI=-49
,I/Keyboard.Facilitator( 1213): onFinishInput()
,E/WifiStateMachine(  820): cancelDelayedScan -> 8
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.24 rxSuccessRate=0.38 targetRoamBSSID=any RSSI=-49
,E/native  (  820): do suspend true
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4132): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4132): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4132): [1] 5.onFinished: Scheduling replication attempt 5.,
,E/WifiConfigStore(  820):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  820):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
,I/GoogleURLConnFactory( 1705): Using platform SSLCertificateSocketFactory
W/GoogleHttpClient( 1705): Ignoring unsupported parameter: http.conn-manager.max-per-route
,I/art     ( 1511): Explicit concurrent mark sweep GC freed 24753(1357KB) AllocSpace objects, 13(1433KB) LOS objects, 37% free, 26MB/42MB, paused 1.428ms total 49.687ms
,I/ActivityManager(  820): Start proc 4274:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@74869f0}
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GoogleAuthProtoRequest( 4274): [456] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 4274): [455] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova,
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4274): [456] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.,
W/ExperimentUpdateService( 4274): [456] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4274): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4274): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4274): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4274): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 4274): [455] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4274): [455] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4274): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4274): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4274): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4274): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  820): Killing 3731:com.google.android.calendar/u0a37 (adj 15): empty #17
,V/GoogleAuthProtoRequest( 4274): [457] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4274): [457] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4274): [457] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4274): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4274): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4274): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4274): 	at com.a.a.k.run(SourceFile:110)
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 8 -> obsolete
,D/HeadsetStateMachine( 3191): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3191): Disconnected process message: 10, size: 0
,I/ActivityManager(  820): Start proc 4306:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/ActivityManager(  820): Start proc 4323:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,W/GAV2    ( 4306): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4306): Created application version: 3.6.8 (30608)
,I/BooksSync( 4306): Starting books sync for 61035162, extras: ade
,I/art     ( 1511): Explicit concurrent mark sweep GC freed 13219(647KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 26MB/42MB, paused 1.031ms total 23.044ms
,I/art     (  820): Explicit concurrent mark sweep GC freed 33432(1649KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.141ms total 49.894ms
,V/KeepSync( 4323): Connecting to GoogleApiClient
,I/BooksConfig( 4306): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1734): Handling authorization failure
E/ClientConnectionOperation( 1734): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1734): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1734): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1734): 	,at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1734): 	... 7 more
V/KeepSync( 4323): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4323): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4323): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4323): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 4306): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 4306): Soft error,
E/BooksSync( 4306): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4306): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4306): Sync error
E/BooksSync( 4306): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4306): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4306): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163517, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4323): IOException
E/KeepSync( 4323): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4323): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4323): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4323): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4323): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4323): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4323): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4323): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4323): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4323): 	... 10 more
W/KeepSync( 4323): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 163578, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Start proc 4368:com.google.android.apps.docs.editors.docs/u0a47 for service com.google.android.apps.docs.editors.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4238): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4238): 	at jdm.a(PG:82)
E/HttpOperation( 4238): 	at jcs.o(PG:406)
E/HttpOperation( 4238): 	at jcn.a(PG:1379)
E/HttpOperation( 4238): 	at jcs.i(PG:143)
E/HttpOperation( 4238): 	at blb.a(PG:3937)
E/HttpOperation( 4238): 	at czp.a(PG:18188)
E/HttpOperation( 4238): 	at czp.a(PG:9087)
E/HttpOperation( 4238): 	at czq.run(PG:1686)
E/HttpOperation( 4238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4238): 	at jdj.a(PG:4091)
E/HttpOperation( 4238): 	at jdj.a(PG:1125)
E/HttpOperation( 4238): 	at jdm.a(PG:77)
E/HttpOperation( 4238): 	... 12 more
E/HttpOperation( 4238): Caused by: faj: BadAuthentication
E/HttpOperation( 4238): 	at fal.a(PG:38)
E/HttpOperation( 4238): 	at jdj.a(PG:4089)
E/HttpOperation( 4238): 	... 14 more
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4238): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4238): 	at jdm.a(PG:82)
E/HttpOperation( 4238): 	at jcs.o(PG:406)
E/HttpOperation( 4238): 	at jcn.a(PG:1379)
E/HttpOperation( 4238): 	at jcs.i(PG:143)
E/HttpOperation( 4238): 	at blb.a(PG:3937)
E/HttpOperation( 4238): 	at czp.a(PG:18188)
E/HttpOperation( 4238): 	at czp.a(PG:9081)
E/HttpOperation( 4238): 	at czq.run(PG:1686)
E/HttpOperation( 4238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4238): 	at jdj.a(PG:4091)
E/HttpOperation( 4238): 	at jdj.a(PG:1125)
E/HttpOperation( 4238): 	at jdm.a(PG:77)
E/HttpOperation( 4238): 	... 12 more
E/HttpOperation( 4238): Caused by: faj: BadAuthentication
E/HttpOperation( 4238): 	at fal.a(PG:38)
E/HttpOperation( 4238): 	at jdj.a(PG:4089)
E/HttpOperation( 4238): 	... 14 more
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4132): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4132): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4132): [1] 5.onFinished: Giving up after 6 failures.
,E/HttpOperation( 4238): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4238): 	at jdm.a(PG:82)
E/HttpOperation( 4238): 	at jcs.o(PG:406)
E/HttpOperation( 4238): 	at jcn.a(PG:1379)
E/HttpOperation( 4238): 	at jcs.i(PG:143)
E/HttpOperation( 4238): 	at hec.a(PG:42)
E/HttpOperation( 4238): 	at hee.a(PG:102)
E/HttpOperation( 4238): 	at czr.a(PG:65)
E/HttpOperation( 4238): 	at kka.a(PG:108)
E/HttpOperation( 4238): 	at czp.a(PG:19176)
E/HttpOperation( 4238): 	at czp.a(PG:9081)
E/HttpOperation( 4238): 	at czq.run(PG:1686)
E/HttpOperation( 4238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4238): 	at jdj.a(PG:4091)
E/HttpOperation( 4238): 	at jdj.a(PG:1125)
E/HttpOperation( 4238): 	at jdm.a(PG:77)
E/HttpOperation( 4238): 	... 15 more
E/HttpOperation( 4238): Caused by: faj: BadAuthentication
E/HttpOperation( 4238): 	at fal.a(PG:38)
E/HttpOperation( 4238): 	at jdj.a(PG:4089)
E/HttpOperation( 4238): 	... 17 more
E/ExperimentLoader( 4238): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4238): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4238): 	at jdm.a(PG:82)
E/ExperimentLoader( 4238): 	at jcs.o(PG:406)
E/ExperimentLoader( 4238): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4238): 	at jcs.i(PG:143)
E/ExperimentLoader( 4238): 	at hec.a(PG:42)
E/ExperimentLoader( 4238): 	at hee.a(PG:102)
E/ExperimentLoader( 4238): 	at czr.a(PG:65)
E/ExperimentLoader( 4238): 	at kka.a(PG:108)
E/ExperimentLoader( 4238): 	at czp.a(PG:19176)
E/ExperimentLoader( 4238): 	at czp.a(PG:9081)
E/ExperimentLoader( 4238): 	at czq.run(PG:1686)
E/ExperimentLoader( 4238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4238): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4238): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4238): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4238): 	at jdm.a(PG:77)
E/ExperimentLoader( 4238): 	... 15 more
E/ExperimentLoader( 4238): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4238): 	at fal.a(PG:38)
E/ExperimentLoader( 4238): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4238): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131309, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 2160:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/GAv4    ( 4368): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4368):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4368):   adb logcat -s GAv4
,W/GAv4    ( 4368): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Killing 4035:com.google.android.configupdater/u0a42 (adj 15): empty #17
,W/GAv4    ( 4368): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4368): Analytics setup for ID UA-21125203-4, app name Docs, version 1.4.292.15.30
,W/GAv4    ( 4368): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/NewsWeather( 3942): Last usage 1447148544093, idle 6659122 seconds, sync interval 2592000 seconds
I/NewsWeather( 3942): setPeriodicSync in 2592000 seconds
,I/NewsWeather( 3942): Skip sync for lookup editions
,I/NewsWeather( 3942): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 3942): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/ResourcesManager( 4368): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4368): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.genie.geniewidget, service: oauth2:https://www.googleapis.com/auth/newsreader
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/newsreader without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/NewsWeather( 3942): Exception reported
E/NewsWeather( 3942): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 3942): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 3942): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.pa(SourceFile:152)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:102)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.d.a(SourceFile:284)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.l.au(SourceFile:164)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.l.as(SourceFile:92)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.l.onPerformSync(SourceFile:81)
E/NewsWeather( 3942): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/NewsWeather( 3942): Signed-in user with null auth token
E/NewsWeather( 3942): Transport error in DownSync
E/NewsWeather( 3942): Down sync of news app Failed, error code: SYNC_IO_ERROR
I/NewsWeather( 3942): Detected SyncErrorCodeCategory SOFT_ERROR
I/NewsWeather( 3942): Abort on too many retries? false
,V/JNIHelp ( 4368): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, currentRunTime 169124, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ProviderInstaller( 4368): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  820): Killing 4009:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 4306): Thread[GAThread,5,main]: No campaign data found.
,V/GoogleAuthProtoRequest( 4274): [458] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 32574(1423KB) AllocSpace objects, 7(206KB) LOS objects, 32% free, 33MB/49MB, paused 2.890ms total 75.588ms
,W/ExperimentUpdateService( 4274): [458] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4274): [458] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4274): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4274): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4274): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4274): 	at com.a.a.k.run(SourceFile:110)
,D/Finsky  ( 4132): [425] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4132): [425] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/Keyboard.Facilitator.LanguageModelFlusher( 1213): run()
I/Keyboard.Facilitator( 1213): flushDynamicLanguageModels()
,I/ConfigService( 1511): onCreate
,I/ConfigService( 1511): onDestroy
,D/HeadsetStateMachine( 3191): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3191): Disconnected process message: 10, size: 0
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4238): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4238): 	at jdm.a(PG:82)
E/HttpOperation( 4238): 	at jcs.o(PG:406)
E/HttpOperation( 4238): 	at jcn.a(PG:1379)
E/HttpOperation( 4238): 	at jcs.i(PG:143)
E/HttpOperation( 4238): 	at blb.a(PG:3937)
E/HttpOperation( 4238): 	at czp.a(PG:18188)
E/HttpOperation( 4238): 	at czp.a(PG:9081)
E/HttpOperation( 4238): 	at czq.run(PG:1686)
E/HttpOperation( 4238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4238): 	at jdj.a(PG:4091)
E/HttpOperation( 4238): 	at jdj.a(PG:1125)
E/HttpOperation( 4238): 	at jdm.a(PG:77)
E/HttpOperation( 4238): 	... 12 more
E/HttpOperation( 4238): Caused by: faj: BadAuthentication
E/HttpOperation( 4238): 	at fal.a(PG:38)
E/HttpOperation( 4238): 	at jdj.a(PG:4089)
E/HttpOperation( 4238): 	... 14 more
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4238): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4238): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4238): 	at jdm.a(PG:82)
E/HttpOperation( 4238): 	at jcs.o(PG:406)
E/HttpOperation( 4238): 	at jcn.a(PG:1379)
E/HttpOperation( 4238): 	at jcs.i(PG:143)
E/HttpOperation( 4238): 	at hec.a(PG:42)
E/HttpOperation( 4238): 	at hee.a(PG:102)
E/HttpOperation( 4238): 	at czr.a(PG:65)
E/HttpOperation( 4238): 	at kka.a(PG:108)
E/HttpOperation( 4238): 	at czp.a(PG:19176)
E/HttpOperation( 4238): 	at czp.a(PG:9081)
E/HttpOperation( 4238): 	at czq.run(PG:1686)
E/HttpOperation( 4238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4238): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4238): Caused by: android.accounts.AuthenticatorException: Recoverable error,
E/HttpOperation( 4238): 	at jdj.a(PG:4091)
E/HttpOperation( 4238): 	at jdj.a(PG:1125)
E/HttpOperation( 4238): 	at jdm.a(PG:77)
E/HttpOperation( 4238): 	... 15 more
E/HttpOperation( 4238): Caused by: faj: BadAuthentication
E/HttpOperation( 4238): 	at fal.a(PG:38)
E/HttpOperation( 4238): 	,at jdj.a(PG:4089)
E/HttpOperation( 4238): 	... 17 more
E/ExperimentLoader( 4238): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4238): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4238): 	at jdm.a(PG:82)
E/ExperimentLoader( 4238): 	at jcs.o(PG:406)
E/ExperimentLoader( 4238): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4238): 	at jcs.i(PG:143)
,E/ExperimentLoader( 4238): 	at hec.a(PG:42)
E/ExperimentLoader( 4238): 	at hee.a(PG:102)
E/ExperimentLoader( 4238): 	at czr.a(PG:65)
E/ExperimentLoader( 4238): 	at kka.a(PG:108)
E/ExperimentLoader( 4238): 	at czp.a(PG:19176)
E/ExperimentLoader( 4238): 	at czp.a(PG:9081)
E/ExperimentLoader( 4238): 	,at czq.run(PG:1686)
E/ExperimentLoader( 4238): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4238): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4238): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4238): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4238): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4238): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4238): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4238): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4238): 	at jdm.a(PG:77)
E/ExperimentLoader( 4238): 	... 15 more
E/ExperimentLoader( 4238): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4238): 	at fal.a(PG:38)
E/ExperimentLoader( 4238): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4238): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 223010, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 4274): [459] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1511): Explicit concurrent mark sweep GC freed 37820(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 27MB/43MB, paused 1.136ms total 38.566ms
,W/ExperimentUpdateService( 4274): [459] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4274): [459] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4274): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4274): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4274): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4274): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4274): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4274): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 4306): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4323): Connecting to GoogleApiClient
I/BooksConfig( 4306): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1734): Handling authorization failure
E/ClientConnectionOperation( 1734): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1734): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1734): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1734): 	... 7 more
,V/KeepSync( 4323): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4323): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4323): (284) automatic index on blob_node(is_deleted),
E/SQLiteLog( 4323): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4306): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4306): Soft error
E/BooksSync( 4306): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4306): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4306): Sync error
E/BooksSync( 4306): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4306): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4306): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 252801, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NewsWeather( 3942): Last usage 1447148544093, idle 6659211 seconds, sync interval 2592000 seconds
I/NewsWeather( 3942): setPeriodicSync in 2592000 seconds
,I/NewsWeather( 3942): Skip sync for lookup editions
I/NewsWeather( 3942): syncNewsAppData traffic type BACKGROUND_POLL
,E/KeepSync( 4323): IOException
E/KeepSync( 4323): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4323): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4323): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4323): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4323): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4323): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4323): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4323): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4323): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4323): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4323): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4323): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4323): 	... 10 more
W/KeepSync( 4323): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 254040, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,I/NewsWeather( 3942): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,I/GLSUser ( 1511): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.genie.geniewidget, service: oauth2:https://www.googleapis.com/auth/newsreader
I/GLSUser ( 1511): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/newsreader without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1511): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1511): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1511): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/NewsWeather( 3942): Exception reported
E/NewsWeather( 3942): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 3942): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 3942): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.pa(SourceFile:152)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:102)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.d.a(SourceFile:284)
E/NewsWeather( 3942): ,	at com.google.android.apps.genie.geniewidget.sync.l.au(SourceFile:164)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.l.as(SourceFile:92)
E/NewsWeather( 3942): 	at com.google.android.apps.genie.geniewidget.sync.l.onPerformSync(SourceFile:81)
E/NewsWeather( 3942): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/NewsWeather( 3942): Signed-in user with null auth token
E/NewsWeather( 3942): Transport error in DownSync
,E/NewsWeather( 3942): Down sync of news app Failed, error code: SYNC_IO_ERROR
I/NewsWeather( 3942): Detected SyncErrorCodeCategory SOFT_ERROR
I/NewsWeather( 3942): Abort on too many retries? false
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, currentRunTime 255844, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3191): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3191): Disconnected process message: 10, size: 0
,I/jxcore-log( 3132): --= Surplus to requirements =--
I/jxcore-log( 3132): 
I/jxcore-log( 3132): ****TEST TOOK:  ms ****
I/jxcore-log( 3132): 
I/jxcore-log( 3132): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3132): 
,D/AndroidRuntime( 4473): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4473): CheckJNI is OFF
,D/AndroidRuntime( 4473): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
,I/ActivityManager(  820): Killing 3132:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  820): Skipping PackageSetting{1a9226b9 com.example.hello/10273} due to missing metadata
,I/WindowState(  820): WIN DEATH: Window{40bc40d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  820): Client connection lost with reason: 4
E/libprocessgroup(  820): failed to kill 1 processes for processgroup 3132
,W/ActivityManager(  820): Force removing ActivityRecord{a62820a u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  820): Display changed displayId=0
,I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,W/ActivityManager(  820): Spurious death for ProcessRecord{1e0179b0 3132:com.test.thalitest/u0a265}, curProc for 3132: null
,D/TaskPersister(  820): removeObsoleteFile: deleting file=28_task.xml
,I/Keyboard.Facilitator( 1213): resetDictionaries() : en_US
,D/BuaReceiver( 2936): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1213): run()
,D/VoicemailCleanupService( 4211): Cleaning up data for package: com.test.thalitest
,I/art     ( 1064): Explicit concurrent mark sweep GC freed 55605(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 883us total 45.827ms
,I/ActivityManager(  820): Start proc 4489:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/Decoder ( 1213): createOrResetDecoder
,I/art     (  820): Explicit concurrent mark sweep GC freed 34962(1832KB) AllocSpace objects, 11(458KB) LOS objects, 31% free, 34MB/50MB, paused 1.215ms total 90.406ms
,I/art     (  820): Explicit concurrent mark sweep GC freed 3098(156KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 1.359ms total 45.785ms
,I/art     (  820): WaitForGcToComplete blocked for 122.180ms for cause Explicit
,I/ConfigService( 1511): onCreate
,D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/ActivityManager(  820): Start proc 4511:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,I/ActivityManager(  820): Killing 3687:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1213): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1213): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1213): run()
I/StatsUtilsManager( 1213): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1213): shouldRecordStats() = Too Soon
,I/art     (  820): Explicit concurrent mark sweep GC freed 2910(133KB) AllocSpace objects, 3(330KB) LOS objects, 32% free, 33MB/49MB, paused 1.221ms total 86.626ms
,I/art     ( 4473): System.exit called, status: 0
I/AndroidRuntime( 4473): VM exiting with result code 0.
,W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3132 uid 10265
,I/Keyboard.Facilitator( 1213): onFinishInput()
,W/ContextImpl( 4511): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1511): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1511): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/art     ( 1313): Explicit concurrent mark sweep GC freed 11769(660KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.119ms total 29.055ms
,D/PackageBroadcastService( 1734): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1734): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1734): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1734): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1734): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1734): Clearing selected account for com.test.thalitest
,I/LocationSettingsChecker( 1734): Removing dialog suppression flag for package com.test.thalitest
,W/FileUtils( 1734): Failed to chmod(/data/data/com.google.android.gms/databases/phenotype.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteDatabase( 1734): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1734): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1734): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1734): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1734): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1734): 	at com.google.android.g,ms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1734): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1734): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1734): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1734): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1734): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1734): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ConfigFetchService( 1734): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1734): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
W/SQLiteOpenHelper( 1734): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1734): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1734): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1734): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1734): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
--------- beginning of crash
E/AndroidRuntime( 1734): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1734): Process: com.google.android.gms, PID: 1734
E/AndroidRuntime( 1734): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1734): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1734): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1734): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1734): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1734): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1734): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1734): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1734): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1734): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1734): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ConfigFetchService( 1734): service connected
I/Icing   ( 1734): doRemovePackageData com.test.thalitest
E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
W/ResourcesManager(  820): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  820): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/OpenGLRenderer(  820): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  820): Validating map...
,I/PeopleContactsSync( 1734): CP2 sync disabled
W/BaseAppContext( 1734): Using Auth Proxy for data requests.
W/BaseAppContext( 1734): Using Auth Proxy for data requests.
E/SQLiteDatabase( 1734): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1734): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1734): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1734): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1734): Runtime exception while performing operation
E/ClearPendingStateOp( 1734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1734): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1734): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1734): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1734): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1734): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1734): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1734): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1734): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1734): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1734): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1734): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1734): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1734): 	at java.lang.Thread.run(Thread.java:818)
,E/DropBoxManagerService(  820): Can't write: system_app_wtf
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
W/LocationOracleImpl( 4090): Best location was null
E/Search.SharedPreferencesProto( 4090): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/OpenGLRenderer(  820): Initialized EGL, version 1.4
E/SQLiteDatabase( 4090): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/jar_store.db'.
E/SQLiteDatabase( 4090): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4090): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4090): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4090): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4090): 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
E/SQLiteDatabase( 4090): 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
E/SQLiteDatabase( 4090): 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
E/SQLiteDatabase( 4090): 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
E/SQLiteDatabase( 4090): 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
E/SQLiteDatabase( 4090): 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
E/SQLiteDatabase( 4090): 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
E/SQLiteDatabase( 4090): 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
E/SQLiteDatabase( 4090): 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
E/SQLiteDatabase( 4090): 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
E/SQLiteDatabase( 4090): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4090): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4090): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4090): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4090): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/SQLiteOpenHelper( 4090): Couldn't open jar_store.db for writing (will try read-only):
E/SQLiteOpenHelper( 4090): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4090): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4090): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4090): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4090): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4090): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4090): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4090): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4090): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4090): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4090): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4090): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4090): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4090): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4090): 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
E/SQLiteOpenHelper( 4090): 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
E/SQLiteOpenHelper( 4090): 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
E/SQLiteOpenHelper( 4090): 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
E/SQLiteOpenHelper( 4090): 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
E/SQLiteOpenHelper( 4090): 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
E/SQLiteOpenHelper( 4090): 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
E/SQLiteOpenHelper( 4090): 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
E/SQLiteOpenHelper( 4090): 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
E/SQLiteOpenHelper( 4090): 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
E/SQLiteOpenHelper( 4090): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4090): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4090): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4090): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 4090): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/OpenGLRenderer(  820): Enabling debug mode 0
W/SQLiteOpenHelper( 4090): Opened jar_store.db in read-only mode
I/VS.Container( 4090): create_recognizer
,D/Launcher.Workspace( 1313): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1313): 11683562 - stripEmptyScreens()
E/SQLiteLog( 1313): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,I/UpdateIcingCorporaServi( 4090): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1313): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@228d1b5c new=com.google.android.velvet.VelvetApplication@228d1b5c
,E/SQLiteLog( 4090): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 1313): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,I/HotwordRecognitionRnr( 4090): Starting hotword detection.
I/ActivityManager(  820): Start proc 4574:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/MicrophoneInputStream( 4090): mic_starting com.google.android.apps.gsa.speech.audio.u@3b17050c
,I/AudioFlinger(  357): AudioFlinger's thread 0xb40f0000 ready to run
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 4090): mic_started com.google.android.apps.gsa.speech.audio.u@3b17050c
,D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,I/ActivityManager(  820): Start proc 4595:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,E/SharedPreferencesImpl( 4090): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,E/AndroidRuntime( 4090): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 4090): Process: com.google.android.googlequicksearchbox:search, PID: 4090
E/AndroidRuntime( 4090): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4090): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4090): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 4090): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 4090): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 4090): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 4090): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 4090): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 4090): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 4090): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 4090): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 4090): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 4090): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4090): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4090): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4090): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
,I/HotwordDetector( 4090): Closing mic
I/MicrophoneInputStream( 4090): mic_close com.google.android.apps.gsa.speech.audio.u@3b17050c
,W/FileUtils( 4090): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/FileBytesWriter( 4090): Failed to write new file: loracle.new
,W/FileUtils( 4090): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/FileBytesWriter( 4090): Failed to write new file: loracle.new
,E/Search.SharedPreferencesProto( 4090): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,W/TRUiThreadExecutor( 4090): Task does not implement UiTask: com.google.common.g.a.p@19ba6309
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@9cd628e}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
,D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 4090): Hotword detection finished
,I/HotwordRecognitionRnr( 4090): Stopping hotword detection.
,D/GFEEDBACK_SendErrorReportOperation( 1734): Error doing instant send: java.io.IOException: failed to create reports directory
,E/GFEEDBACK_SendErrorReportOperation( 1734): Error saving report: java.io.IOException: failed to create reports directory
,I/GAv4    ( 4574): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4574):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4574):   adb logcat -s GAv4
,W/GAv4    ( 4574): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4574): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4574): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 4574): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4574): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.,
E/SQLiteDatabase( 4574): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4574): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463),
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4574): ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694),
E/SQLiteDatabase( 4574): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4574): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4574): 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4574): 	at fdw$a.getWritableDatabase(Unknown Source)
,E/SQLiteDatabase( 4574): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4574): 	at fdw.a(Unknown Source)
,E/SQLiteDatabase( 4574): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4574): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4574): 	,at feb.run(Unknown Source)
E/SQLiteDatabase( 4574): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4574): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4574): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4574): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/SQLiteDatabase( 4574): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4574): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 4574): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4574): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4574): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4574): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4574): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4574): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4574): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4574): 	,at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4574): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4574): 	,at fdw.a(Unknown Source)
E/SQLiteDatabase( 4574): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4574): 	at fdy.b(Unknown Source)
,E/SQLiteDatabase( 4574): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4574): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4574): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4574): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4574): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4574): ,	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4574): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4574): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4574): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4574): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4574): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4574): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4574): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806),
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4574): ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4574): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4574): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4574): 	,at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4574): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4574): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4574): 	at aen.run(PG:536)
,W/GAv4    ( 4574): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4574): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4574): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4574): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4574): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4574): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4574): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4574): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4574): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4574): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4574): 	at aej.c(PG:139)
E/SQLiteDatabase( 4574): 	at aej.b(PG:398)
E/SQLiteDatabase( 4574): 	at agf.f(PG:417)
E/SQLiteDatabase( 4574): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4574): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4574): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4574): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4574): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4574): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 4574): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4574): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4574): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4574): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4574): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4574): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4574): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4574): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4574): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4574): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4574): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4574): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4574): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4574): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4574): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4574): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4574): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4574): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4574): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4574): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4574): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4574): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4574): 	at java.lang.Thread.run(Thread.java:818)
,W/GAv4    ( 4574): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4574): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4574): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4574): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4574): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4574): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4574): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4574): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/CAKEMIX_CRASHED( 4574): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4574): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4574): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4574): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4574): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4574): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4574): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4574): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4574): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,E/CAKEMIX_CRASHED( 4574): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4574): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4574): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4574): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4574): 	at aen.run(PG:536)
,W/ResourcesManager( 4574): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4574): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  820): Start proc 4636:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,I/ActivityManager(  820): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{11efb6c0 token=Token{2d8d0043 ActivityRecord{1ec141f2 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
,I/Process ( 4574): Sending signal. PID: 4574 SIG: 9
,E/lowmemorykiller(  256): Error writing /proc/4574/oom_score_adj; errno=22
,E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  820): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  820): android.os.TransactionTooLargeException
W/ActivityManager(  820): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  820): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  820): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  820): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  820): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  820): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  820): 	at android.os.Binder.execTransact(Binder.java:446)
,E/native  ( 1213): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1213): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/ActivityManager(  820): Start proc 4653:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,W/ActivityManager(  820): Spurious death for ProcessRecord{3441199a 4653:com.google.android.apps.docs/u0a46}, curProc for 4574: null
,W/OpenGLRenderer( 1313): Incorrectly called buildLayer on View: ew, destroying layer...
,E/native  ( 1213): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1213): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/SQLiteDatabase( 4636): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4636): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4636): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4636): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4636): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4636): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4636): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4636): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4636): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4636): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4636): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4636): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4636): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4636): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4636): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4636): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4636): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4636): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4636): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/AndroidRuntime( 4636): Shutting down VM
,E/AndroidRuntime( 4636): FATAL EXCEPTION: main
E/AndroidRuntime( 4636): Process: com.android.documentsui, PID: 4636
E/AndroidRuntime( 4636): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4636): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4636): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4636): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4636): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4636): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4636): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4636): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4636): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4636): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4636): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4636): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4636): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4636): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4636): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4636): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4636): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4636): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4636): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4636): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4636): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4636): 	... 9 more
,E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
,E/native  ( 1213): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1213): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1213): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1213): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/ActivityManager(  820): Start proc 4674:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/ActivityManager(  820): Killing 3659:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
,I/art     (  368): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 288us total 12.847ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 210us total 11.435ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 8.614ms
,I/ActivityManager(  820): Killing 4168:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/ExternalStorage( 4674): After updating volumes, found 1 active roots
,I/GAv4    ( 4653): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4653):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4653):   adb logcat -s GAv4
,W/GAv4    ( 4653): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4653): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4653): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SQLiteDatabase( 4653): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4653): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4653): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4653): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4653): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4653): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4653): 	,at fdw.a(Unknown Source)
E/SQLiteDatabase( 4653): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4653): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4653): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4653): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4653): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4653): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4653): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4653): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4653): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 4653): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4653): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.,
E/SQLiteDatabase( 4653): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4653): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
,E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4653): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4653): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4653): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4653): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4653): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4653): 	at fdw.e(Unknown Source),
E/SQLiteDatabase( 4653): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4653): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4653): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4653): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4653): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4653): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4653): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4653): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4653): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
W/GAv4    ( 4653): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4653): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
,W/AnalyticsTrackerProxyImpl( 4653): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4653): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 4653): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4653): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4653): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4653): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4653): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4653): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4653): ,	at hix$a.a(PG:125)
E/SQLiteDatabase( 4653): 	at aen.run(PG:536)
,E/SQLiteDatabase( 4653): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
,E/SQLiteDatabase( 4653): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4653): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4653): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806),
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4653): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4653): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4653): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4653): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4653): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
,E/SQLiteDatabase( 4653): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4653): 	at ael.a(PG:1521),
E/SQLiteDatabase( 4653): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4653): 	,at aej.c(PG:139)
E/SQLiteDatabase( 4653): 	at aej.b(PG:398)
,E/SQLiteDatabase( 4653): 	at agf.f(PG:417)
E/SQLiteDatabase( 4653): 	at oe.run(PG:1112),
,E/SQLiteDatabase( 4653): ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4653): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/SQLiteDatabase( 4653): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4653): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4653): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 4653): Failed to delete from CachedSearch133,
E/AbstractDatabaseInstance( 4653): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4653): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4653): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4653): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4653): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4653): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4653): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4653): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4653): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4653): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4653): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4653): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4653): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4653): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4653): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4653): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4653): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4653): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4653): 	at aej.b(PG:398)
E/AbstractDatabaseInstan,ce( 4653): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4653): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4653): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4653): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4653): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4653): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4653): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 4653): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4653): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4653): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/ErrorNotificationActivity( 4653): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
,I/ProviderInstaller( 4653): Installed default security provider GmsCore_OpenSSL
,D/OpenGLRenderer( 4653): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 4653): Validating map...
,V/WindowManager(  820): Adding window Window{2fff91dd u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 10 (after Window{31e842cf u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,V/WindowManager(  820): Adding window Window{947dc23 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 11 (before Window{2fff91dd u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
,W/GAv4    ( 4653): Error opening database: android.database.sqlite.SQLiteException: Database open failed,
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4653): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4653): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,W/GAv4    ( 4653): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4653): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
,W/GAv4    ( 4653): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4653): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4653): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/GAv4    ( 4653): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/CAKEMIX_CRASHED( 4653): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4653): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4653): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4653): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4653): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4653): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4653): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4653): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4653): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4653): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4653): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4653): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4653): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4653): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4653): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4653): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4653): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4653): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4653): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/ActivityManager(  820): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,I/Process ( 4653): Sending signal. PID: 4653 SIG: 9
,I/WindowState(  820): WIN DEATH: Window{2fff91dd u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
,I/ActivityThread( 4636): Removing dead content provider:android.content.ContentProviderProxy@3065e0a9
W/InputDispatcher(  820): channel '947dc23 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  820): channel '947dc23 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
I/ActivityManager(  820): Process com.google.android.apps.docs (pid 4653) has died
,W/ActivityManager(  820): Force removing ActivityRecord{1ec141f2 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}: app died, no saved state,
I/WindowState(  820): WIN DEATH: Window{947dc23 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity}
W/InputDispatcher(  820): Attempted to unregister already unregistered input channel '947dc23 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
,W/Documents( 4636): Failed to load some roots from com.google.android.apps.docs.storage: android.os.DeadObjectException
,D/Documents( 4636): Update found 6 roots in 1065ms
,I/art     (  820): Explicit concurrent mark sweep GC freed 21641(1241KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 34MB/50MB, paused 2.410ms total 97.306ms
,E/SQLiteDatabase( 1511): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1511): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 1511): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1511): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
,E/SQLiteOpenHelper( 1511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1511): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1511): Opened phenotype.db in read-only mode
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	,at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
,E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): ,	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@9cd628e}
,I/ConfigService( 1511): onDestroy
,E/Search.SharedPreferencesProto( 4090): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,W/WindowManager(  820): App freeze timeout expired.
,E/SQLiteDatabase( 1511): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1511): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 1511): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1511): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1511): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1511): 	,at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1511): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1511): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1511): Opened phenotype.db in read-only mode
,E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	,at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416),
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178),
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database,
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): ,	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153),
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818),
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	,at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	,at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.d,atabase.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1511): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1511): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1511): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1511): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1511): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1511): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  820): Start proc 4722:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,E/SharedPreferencesImpl( 4090): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,E/QMI_FW  (  820): xport_send: Sendto failed for port 3840
E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660110099
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/QMI_FW  (  820): xport_send: Sendto failed for port 3840
E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660110099
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/SQLiteDatabase( 1511): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148),
E/SQLiteDatabase( 1511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,E/SQLiteDatabase( 1511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,E/SQLiteDatabase( 1511): ,	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
```
