#### Test 57348078846ce9d_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2718): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2718): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2718): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3135): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3135): CheckJNI is OFF
D/AndroidRuntime( 3135): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  819): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  819): addAppToken: AppWindowToken{35e8f392 token=Token{1978c51d ActivityRecord{e0409f4 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3135): Shutting down VM
V/WindowManager(  819): Adding window Window{1f7fb0bf u0 Starting com.test.thalitest} at 2 of 7 (after Window{29044461 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1512): Closing mic
I/MicrophoneInputStream( 1512): mic_close com.google.android.apps.gsa.speech.audio.u@3681219f
I/ActivityManager(  819): Start proc 3149:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1512): Stopping hotword detection.
I/HotwordRecognitionRnr( 1512): Hotword detection finished
I/ActivityManager(  819): Killing 2811:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660019987
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/WebViewFactory( 3149): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3149): Time to load native libraries: 2 ms (timestamps 1812-1814)
I/LibraryLoader( 3149): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3149): Binding Chromium to main looper Looper (main, tid 1) {10f4103f}
,I/LibraryLoader( 3149): Expected native library version number "",actual native library version number ""
I/chromium( 3149): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3149): Initializing chromium process, singleProcess=true
,W/art     ( 3149): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3149): ApplicationContext is null in ApplicationStatus
,I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
,W/chromium( 3149): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3149): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3149): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3149): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3149): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,D/BluetoothManagerService(  819): Message: 20
D/BluetoothAdapter( 3149): 151203320: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33cc47af:true
,W/art     ( 3149): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3149): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3149): CordovaWebView is running on device made by: motorola
,W/art     ( 3149): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3149): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3149): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3149): Validating map...
,V/WindowManager(  819): Adding window Window{34a47a9f u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{1f7fb0bf u0 Starting com.test.thalitest})
,W/chromium( 3149): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3149): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3149): Enabling debug mode 0
,I/ActivityManager(  819): Displayed com.test.thalitest/.MainActivity: +678ms
,I/Keyboard.Facilitator( 1222): onFinishInput()
,W/BindingManager( 3149): Cannot call determinedVisibility() - never saw a connection for the pid: 3149
,D/JsMessageQueue( 3149): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3149): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1578494464
,I/chromium( 3149): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/kickstart(  870): STATUS: Received file 'm9kefs1'
I/kickstart(  870): STATUS: 950272 bytes transferred in 0.989614 seconds
I/kickstart(  870): STATUS: Successfully downloaded files from target 
,I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  870): STATUS: Sahara protocol completed
,W/jxcore-log( 3149): Initializing JXcore engine
W/jxcore-log( 3149): JXcore engine is ready
,W/Thread-327( 3205): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10818]" dev="sockfs" ino=10818 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-327( 3205): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-327( 3205): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9564]" dev="sockfs" ino=9564 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-327( 3205): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20019]" dev="sockfs" ino=20019 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3149): Starting JXcore engine
,W/jxcore-log( 3149): Platform android
W/jxcore-log( 3149): 
W/jxcore-log( 3149): Process ARCH arm
W/jxcore-log( 3149): 
,I/jxcore-log( 3149): JXcore Cordova bridge is ready!
I/jxcore-log( 3149): 
W/jxcore-log( 3149): JXcore engine is started
,I/jxcore-log( 3149): Toggling radios to true
I/jxcore-log( 3149): 
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  819): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  819): Message: 1,
D/BluetoothManagerService(  819): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  819): New client listening to asynchronous messages
D/WifiService(  819): setWifiEnabled: true pid=3149, uid=10265
E/WifiService(  819): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3149): Radios toggled
I/jxcore-log( 3149): 
I/jxcore-log( 3149): My device name is: motorola-Nexus 6
I/jxcore-log( 3149): 
,D/SoftapController(  353): Softap fwReload - Ok
,D/CommandListener(  353): Setting iface cfg
D/CommandListener(  353): Trying to bring down wlan0
,D/CommandListener(  353): Clearing all IP addresses on wlan0,
,E/WifiMonitor(  819): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  819): Start proc 3209:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
D/WifiMonitor(  819): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  819): Start proc 3225:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,I/wpa_supplicant( 3212): Successfully initialized wpa_supplicant
,I/art     (  819): Explicit concurrent mark sweep GC freed 21407(996KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.191ms total 50.024ms
,I/wpa_supplicant( 3212): rfkill: Cannot open RFKILL control device
,W/ResourcesManager( 3209): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/ActivityManager(  819): Start proc 3254:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  819): Killing 2677:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,D/AdapterServiceConfig( 3209): Adding HeadsetService
D/AdapterServiceConfig( 3209): Adding A2dpService
D/AdapterServiceConfig( 3209): Adding HidService
D/AdapterServiceConfig( 3209): Adding HealthService
D/AdapterServiceConfig( 3209): Adding PanService
D/AdapterServiceConfig( 3209): Adding GattService
D/AdapterServiceConfig( 3209): Adding BluetoothMapService
,D/BluetoothManagerService(  819): Message: 20
D/BluetoothAdapterState( 3209): make
,D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a27498f:true
,I/bluedroid( 3209): init
I/BluetoothAdapterState( 3209): Entering OffState
,I/bte_conf( 3209): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3209): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3209): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3209): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3209): get_profile_interface socket
I/bluedroid( 3209): get_profile_interface map_client
I/GKI_LINUX( 3209): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService(  819): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  819): Message: 40
D/BluetoothManagerService(  819): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothAdapterProperties( 3209): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothAdapterProperties( 3209): Name is: Nexus 6
,D/BluetoothManagerService(  819): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  819): Stored Bluetooth name: Nexus 6
I/bluedroid( 3209): config_hci_snoop_log
D/BluetoothManagerService(  819): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  819): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3209): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3209): Setting state to 11
I/BluetoothAdapterState( 3209): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  819): Message: 60
D/BluetoothManagerService(  819): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  819): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3209): make
,I/BluetoothBondStateMachine( 3209): StableState(): Entering Off State
,I/BluetoothAdapterState( 3209): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3209): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24984d0c
D/HeadsetService( 3209): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3209): classInitNative: succeeds
D/HeadsetStateMachine( 3209): make
,D/HeadsetStateMachine( 3209): max_hf_connections = 1
I/bluedroid( 3209): get_profile_interface handsfree
D/HeadsetStateMachine( 3209): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3209): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24984d0c
,D/BluetoothA2dp(  819): Proxy object connected
D/BluetoothA2dp( 1070): Proxy object connected
,D/A2dpService( 3209): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3209): classInitNative: succeeds
I/bluedroid( 3209): get_profile_interface avrcp
,E/RemoteController( 3209): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3209): classInitNative: succeeds
D/A2dpStateMachine( 3209): make
,I/bluedroid( 3209): get_profile_interface a2dp
I/GKI_LINUX( 3209): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/A2dpStateMachine( 3209): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3209): classInitNative: succeeds
D/BluetoothAdapterService( 3209): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24984d0c
D/HidService( 3209): Received start request. Starting profile...
I/bluedroid( 3209): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3209): classInitNative: succeeds
D/BluetoothAdapterService( 3209): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24984d0c
D/HealthService( 3209): Received start request. Starting profile...
I/art     ( 1487): Explicit concurrent mark sweep GC freed 24653(1317KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 5.225ms total 68.702ms
I/bluedroid( 3209): get_profile_interface health
I/BluetoothPanServiceJni( 3209): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3209): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24984d0c
D/BluetoothInputDevice( 1070): Proxy object connected
D/PanService( 3209): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3209): initializeNative(L110): pan
I/bluedroid( 3209): get_profile_interface pan
I/BtGatt.JNI( 3209): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3209): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24984d0c
D/BtGatt.DebugUtils( 3209): handleDebugAction() action=null
D/BtGatt.GattService( 3209): Received start request. Starting profile...
D/BtGatt.GattService( 3209): start()
I/bluedroid( 3209): get_profile_interface gatt
D/BluetoothAdapterService( 3209): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24984d0c
D/BtGatt.AdvertiseManager( 3209): advertise manager created
D/BluetoothPan( 1070): BluetoothPAN Proxy object connected
D/BluetoothAdapterService( 3209): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24984d0c
D/BluetoothMap( 1070): Proxy object connected
D/BluetoothMapService( 3209): Received start request. Starting profile...
D/BluetoothMapService( 3209): start()
D/BluetoothMapEmailSettingsLoader( 3209): Found 0 applications
D/BluetoothMapEmailAppObserver( 3209): createReceiver()
D/BluetoothMapEmailAppObserver( 3209): initObservers()
D/BluetoothMapEmailAppObserver( 3209): getEnabledAccountItems()
D/HeadsetStateMachine( 3209): Proxy object connected
D/HeadsetStateMachine( 3209): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3209): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 3209): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3209): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3209): enable
I/bt_hci_bdroid( 3209): init
I/GKI_LINUX( 3209): gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3209): btu_task pending for preload complete event
,I/bt_vendor( 3209): init
I/bt_vnd_conf( 3209): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3209): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3209): userial_init
,I/ActivityManager(  819): Start proc 3295:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  819): Killing 2847:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/bt_userial_vendor( 3209): userial vendor open: opening /dev/ttyHS0
I/bt_userial_vendor( 3209): device fd = 53 open
D/bt_userial( 3209): Entering userial_read_thread()
,I/bt_hwcfg( 3209): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3209): Chipset BCM4354A2
D/bt_hwcfg( 3209): Target name = [BCM4354A2]
I/bt_hwcfg( 3209): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,D/Tethering(  819): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  819): Killing 2778:com.google.android.gm/u0a78 (adj 15): empty #17
,I/wpa_supplicant( 3212): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3212): Could not read interface p2p-dev-wlan0 flags: No such device
,I/ActivityManager(  819): Killing 2348:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/WifiConfigStore(  819): Loading config and enabling all networks 
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@21257868}
,E/WifiConfigStore(  819): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/bt_hwcfg( 3209): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3209): Settlement delay -- 100 ms
I/bt_hwcfg( 3209): Setting fw settlement delay to 100 
,I/ActivityManager(  819): Start proc 3314:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/WifiNative-HAL(  819): Setting external_sim to 1
,D/WifiStateMachine(  819): Setting OUI to 92-68-C3
I/WifiNative-HAL(  819): startHal
D/wifi    (  819): setting scan oui 0xb4b0c928
D/WifiHAL (  819): Sending mac address OUI
,W/Settings( 2647): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine(  819): cancelDelayedScan -> 1
,D/WifiScanningService(  819): SCAN_AVAILABLE : 3
D/RttService(  819): SCAN_AVAILABLE : 3
W/CommandListener(  353): Failed to retrieve HW addr for p2p0 (No such device)
,D/WifiScanningService(  819): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  819): startHal
D/RttService(  819): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wifi    (  819): getting scan capabilities on interface[0] = 0xb4b0c928
D/WifiHAL (  819): Creating message to get scan capablities; iface = 5
D/WifiHAL (  819): In GetCapabilities::handleResponse
D/WifiHAL (  819): Id = 0, subcmd = 0, len = 28, expected len = 32
D/CommandListener(  353): Setting iface cfg
D/WifiScanningService(  819): StartedState
E/WifiP2pService(  819): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  819): startMonitoring(p2p0) with mConnected = true
I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 355us total 21.089ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 336us total 15.017ms
,I/wpa_supplicant( 3212): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  819): p2pGetDeviceAddress
,D/WifiNative-HAL(  819): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,E/native  (  819): do suspend false
I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 285us total 13.642ms
,I/bt_hwcfg( 3209): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg( 3209): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3209): vendor lib fwcfg completed
I/bt-btu  ( 3209): btu_task received preload complete event
,I/        ( 3209): BTE_InitTraceLevels -- TRC_HCI,
,I/        ( 3209): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 3209): BTE_InitTraceLevels -- TRC_RFCOMM,
I/        ( 3209): BTE_InitTraceLevels -- TRC_AVDT,
I/        ( 3209): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3209): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3209): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3209): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3209): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3209): BTE_InitTraceLevels -- TRC_PAN
,I/        ( 3209): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3209): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3209): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3209): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3209): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3209): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e61085 
,E/bt-btm  ( 3209): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e61085 
,D/StrictMode( 3314): StrictMode policy violation; ~duration=184 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3314): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3314): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3314): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3314): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3314): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3314): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3314): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3314): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3314): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3314): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3314): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3314): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3314): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3314): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3314): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3314): StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3314): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3314): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3314): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3314): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3314): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3314): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3314): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3314): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3314): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3314): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3314): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3314): StrictMode policy violation; ~duration=182 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3314): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3314): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3314): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3314): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3314): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3314): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3314): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3314): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3314): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3314): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3314): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3314): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3314): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3314): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3314): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3314): StrictMode policy violation; ~duration=178 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3314): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3314): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3314): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3314): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3314): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3314): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3314): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3314): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3314): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3314): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3314): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698),
D/StrictMode( 3314): StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3314): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
,D/StrictMode( 3314): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3314): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3314): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
,D/StrictMode( 3314): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3314): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3314): 	at java.lang.System.loadLibrary(System.java:988)
,D/StrictMode( 3314): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
,D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3314): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3314): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553),
D/StrictMode( 3314): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3314): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3314): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3314): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3314): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3314): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
,D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3314): StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
,D/StrictMode( 3314): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3314): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3314): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
,D/StrictMode( 3314): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3314): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3314): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144),
D/StrictMode( 3314): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3314): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3314): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3314): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3314): # via Binder call with stack:
D/StrictMode( 3314): android.os.StrictMode$LogStackTrace
D/StrictMode( 3314): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3314): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3314): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3314): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3314): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3314): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3314): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3314): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/S,trictMode( 3314): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3314): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3314): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3314): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3314): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3314): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3314): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3314): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3314): StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3314): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3314): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3314): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3314): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3314): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3314): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3314): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3314): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3314): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3314): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3314): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3314): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3314): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3314): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3314): StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3314): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3314): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3314): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3314): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3314): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3314): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3314): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3314): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3314): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3314): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3314): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3314): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3314): StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3314): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3314): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3314): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3314): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3314): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3314): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3314): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3314): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3314): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3314): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3314): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3314): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3314): StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3314): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3314): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3314): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3314): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3314): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3314): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3314): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3314): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3314): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3314): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3314): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3314): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3314): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3314): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3314): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3314): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3314): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3314): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3314): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3314): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3314): 	at java.lang.reflect.Method.invoke(Native Method)
D/Stric,tMode( 3314): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3314): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 3314): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  819): Message: 20
D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9cec80:true
,I/ActivityManager(  819): Killing 2243:com.android.defcontainer/u0a7 (adj 15): empty #17
,D/BluetoothAdapterProperties( 3209): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3209): Calling BTA_HhEnable,
E/bt-btif ( 3209): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3209): Address is:F8:CF:C5:D9:E5:61
,W/bt-btm  ( 3209): Stopping oneshot timer,
,D/AuthorizationBluetoothService( 1487): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothAdapterProperties( 3209): Name is: Nexus 6
,D/BluetoothManagerService(  819): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  819): Stored Bluetooth name: Nexus 6
,D/BluetoothAdapterProperties( 3209): Scan Mode:20
D/BluetoothAdapterProperties( 3209): Discoverable Timeout:120
,D/bte_conf( 3209): Device ID record 1 : primary
D/bte_conf( 3209):   vendorId            = 000f
D/bte_conf( 3209):   vendorIdSource      = 0001
D/bte_conf( 3209):   product             = 1200
D/bte_conf( 3209):   version             = 1436
D/bte_conf( 3209):   clientExecutableURL = 
D/bte_conf( 3209):   serviceDescription  = 
D/bte_conf( 3209):   documentationURL    = 
D/bte_conf( 3209): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3209): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3209): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3209): ScanMode =  20
D/BluetoothAdapterProperties( 3209): State =  11
D/BluetoothAdapterProperties( 3209): Setting state to 12
I/BluetoothAdapterState( 3209): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  819): Message: 60
,D/BluetoothManagerService(  819): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12,
D/BluetoothManagerService(  819): Broadcasting onBluetoothStateChange(true) to 13 receivers.
D/BluetoothHeadset(  819): onBluetoothStateChange: up=true
D/BluetoothManagerService(  819): Creating new ProfileServiceConnections object for profile: 1
I/BluetoothAdapterState( 3209): Entering On State
D/BluetoothAdapterProperties( 3209): Scan Mode:21
D/BluetoothAdapterProperties( 3209): Discoverable Timeout:120
,D/BluetoothA2dp( 1070): onBluetoothStateChange: up=true
D/BluetoothPan( 1070): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1324): onBluetoothStateChange: up=true
D/BluetoothA2dp(  819): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 1070): onBluetoothStateChange: up=true
D/BluetoothHeadsetClient( 1070): onBluetoothStateChange: up=true
,E/BluetoothHeadsetClient( 1070): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothMap( 1070): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1070): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  819): onBluetoothStateChange: up=true
D/BluetoothAvrcpController( 1070): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1070): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothHeadset(  819): onBluetoothStateChange: up=true
,D/BluetoothA2dpSink( 1070): onBluetoothStateChange: up=true
,E/BluetoothA2dpSink( 1070): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothManagerService(  819): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  819): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3209): onReceive
D/BluetoothManagerService(  819): Message: 40
D/BluetoothManagerService(  819): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 3209): STATE_ON
,D/BluetoothMapMasInstance( 3209): Map Service startRfcommSocketListener
E/bt_h4   ( 3209): vendor lib postload completed
,D/BluetoothMapMasInstance( 3209): MAS initSocket()
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3209): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3209): Accepting socket connection...
,W/ContextImpl( 3295): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3209): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1487): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  819): Message: 20
,D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1db8cb62:true
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3209): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3209): Accept thread started.
,D/LocalBluetoothProfileManager( 3295): Adding local A2DP profile
,D/BluetoothManagerService(  819): Message: 30
,D/LocalBluetoothProfileManager( 3295): Adding local HEADSET profile
,D/BluetoothManagerService(  819): Message: 30
,D/BluetoothManagerService(  819): Message: 30
,D/BluetoothManagerService(  819): Message: 30
,D/LocalBluetoothProfileManager( 3295): Adding local MAP profile
,D/BluetoothMap( 3295): Create BluetoothMap proxy object
,D/BluetoothManagerService(  819): Message: 30
,D/BluetoothManagerService(  819): Message: 30
,D/LocalBluetoothProfileManager( 3295): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3295): finishStartingService: stopping service
,D/BluetoothA2dp( 3295): Proxy object connected
,D/A2dpProfile( 3295): Bluetooth service connected
,D/BluetoothInputDevice( 3295): Proxy object connected
,D/HidProfile( 3295): Bluetooth service connected
,D/BluetoothPan( 3295): BluetoothPAN Proxy object connected
,D/PanProfile( 3295): Bluetooth service connected
,D/BluetoothMap( 3295): Proxy object connected
D/MapProfile( 3295): Bluetooth service connected
D/BluetoothMap( 3295): getConnectedDevices()
,D/BluetoothPbap( 3295): Proxy object connected
D/PbapServerProfile( 3295): Bluetooth service connected
,D/BluetoothManagerService(  819): Message: 400
D/BluetoothHeadset(  819): Proxy object connected
,D/BluetoothManagerService(  819): Message: 400
,D/BluetoothHeadset( 1324): Proxy object connected
,D/BluetoothManagerService(  819): Message: 400
,D/BluetoothHeadset( 1070): Proxy object connected
,D/BluetoothManagerService(  819): Message: 400
D/BluetoothHeadset(  819): Proxy object connected
D/BluetoothManagerService(  819): Message: 400
D/BluetoothHeadset(  819): Proxy object connected
,D/BluetoothManagerService(  819): Message: 400
,D/BluetoothHeadset( 3295): Proxy object connected
,D/HeadsetProfile( 3295): Bluetooth service connected
,I/wpa_supplicant( 3212): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  819): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  819):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  819):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  819): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  819): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  819): writeKnownNetworkHistory write linked 1
E/WifiStateMachine(  819): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  819): will read network variables netId=0
,D/HeadsetStateMachine( 3209): Disconnected process message: 10, size: 0
,E/WifiStateMachine(  819): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  819): will read network variables netId=0
,I/wpa_supplicant( 3212): wlan0: Trying to associate with SSID 'NG7005g',
,I/wpa_supplicant( 3212): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3212): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3212): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  819): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  353): Setting iface cfg
,E/WifiStateMachine(  819): Start Dhcp Watchdog 1
,E/WifiStateMachine(  819):  WifiLinkLayerStats: 
E/WifiStateMachine(  819):  my bss beacon rx: 1
E/WifiStateMachine(  819):  RSSI mgmt: -50
E/WifiStateMachine(  819):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  819):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  819):  on_time : 0 tx_time=59 rx_time=306 scan_time=0
,D/ConnectivityService(  819): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  819): do suspend false
,E/WifiStateMachine(  819): scanCount==0 - aborting
,I/dhcpcd  ( 3357): version 5.5.6 starting
,I/dhcpcd  ( 3357): wlan0: rebinding lease of 192.168.1.122
,I/jxcore-log( 3149): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3149): 
,I/dhcpcd  ( 3357): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/jxcore-log( 3149): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3149): 
,I/dhcpcd  ( 3357): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  819): Adding iface wlan0 to network 100
,E/WifiStateMachine(  819): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  819): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  819): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  819): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  819): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  819): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  819): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  819): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Connected,
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g",
D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  819):    accepting network in place of null,
,D/ConnectivityService(  819): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  819): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  819): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1070): CM callback handler got msg 524290
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1324): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1324): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  819): getDataEnabled: retVal=false
D/Tethering(  819): MasterInitialState.processMessage what=3
,V/BackupManagerService(  819): Scheduling immediate backup pass
,V/BackupManagerService(  819): Running a backup pass
V/BackupManagerService(  819): clearing pending backups
I/NetworkMonitor( 2878): type=WIFI subType= reason=null isConnected=true
,V/PerformBackupTask(  819): Beginning backup of 14 targets
,V/MusicLeanback( 2878): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  819): No APN found to select.
,D/PerformBackupTask(  819): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  819): doBackup() invoked
,I/PMBA    (  819): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/ActivityManager(  819): Start proc 3397:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/BackupRestoreController(  819): Getting widget state for user: 0
,D/AlarmManagerService(  819): Setting time of day to sec=1453903013
W/AlarmManagerService(  819): Unable to set rtc to 1453903013: Invalid argument
,I/ConfigFetchService( 1751): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1751): running network task: configservice_periodic
,E/WakeLock( 1751): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,D/SprintDMReceiver( 3397): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ConfigFetchService( 1751): launchTask
,D/GpsLocationProvider(  819): NTP server returned: 1453903013572 (Wed Jan 27 14:56:53 GMT+01:00 2016) reference: 130707 certainty: 11 system time offset: -48
,D/SprintDMHelper( 3397): simOperator:  IMSI: null
,D/SprintDMReceiver( 3397): Not Sprint UICC, don't do anything.
,I/GoogleURLConnFactory( 1487): Using platform SSLCertificateSocketFactory
,I/ConfigService( 1487): onCreate
,W/GmsBackupTransport( 1710): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1710): starting performBackup for @pm@
,V/GmsBackupTransport( 1710): performBackup done for @pm@
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1751): [CredentialSyncAdapter] Unknown sync event.
,I/art     (  819): Explicit concurrent mark sweep GC freed 47990(2MB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.431ms total 62.250ms
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 15634(842KB) AllocSpace objects, 3(71KB) LOS objects, 38% free, 25MB/41MB, paused 1.382ms total 25.676ms
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ConfigFetchService( 1751): service connected
,W/DriveInitializer( 1751): Background init thread started
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1751): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1751): onCreate
,D/SystemUpdateService( 1751): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/ConfigFetchService( 1751): ConfigApi connection successful.
,I/CheckinService( 1751): Checking schedule, now: 1453903013859 next: 1453889903115
I/CheckinService( 1751): active receiver: enabled
,W/GLSActivity( 1487): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1487): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1487): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1487): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1487): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1487): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1487): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1710): Error sending final backup to server: 
W/GmsBackupTransport( 1710): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1710): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1710): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1710): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1710): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1710): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1710): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1710): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1710): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1710): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1710): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1710): 	... 1 more
,D/BackupManagerService(  819): Now staging backup of com.google.android.talk
,I/CheckinService( 1751): Preparing to send checkin request
,I/EventLogService( 1751): Accumulating logs since 1453901584983
,I/SystemUpdateService( 1751): active receiver: enabled
,D/BackupManagerService(  819): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  819): Now staging backup of com.android.providers.settings
,W/DriveInitializer( 1751): Awaiting to be initialized
,W/DriveInitializer( 1751): Background init thread ended
,D/BackupManagerService(  819): Now staging backup of com.android.sharedstoragebackup
,I/SystemUpdateService( 1751): showing system update notification
,D/BackupManagerService(  819): Now staging backup of com.google.android.gm
,D/BackupManagerService(  819): Now staging backup of com.android.providers.userdictionary
,I/ValidateNoPeople(  819): skipping global notification
,V/SystemUpdateService( 1751): retry (wakeup: false) in 3599947 ms
,D/BackupManagerService(  819): Now staging backup of com.android.nfc
,D/BackupManagerService(  819): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  819): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  819): Now staging backup of com.google.android.inputmethod.latin
,I/iu.SyncManager( 1751): SYNC; picasa accounts
,D/NetworkLogImpl( 1751): Loaded NetworkSpeedPredictor
,D/BackupManagerService(  819): Now staging backup of com.google.android.calendar
,I/iu.Environment( 1751): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 1751): Opted in for usage reporting
,D/BackupManagerService(  819): Now staging backup of com.android.vending
D/SystemUpdateService( 1751): onDestroy
,D/BackupManagerService(  819): Now staging backup of android
,D/BackupManagerService(  819): Now staging backup of com.google.android.googlequicksearchbox
,D/ChimeraCfgMgr( 1751): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1751): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1751): num queued entries: 0
I/iu.UploadsManager( 1751): num updated entries: 0
I/iu.SyncManager( 1751): NEXT; no task
,I/GmsBackupTransport( 1710): Next backup will happen in 43199835 millis.
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/BackupManagerService(  819): Backup pass finished.
,I/ActivityManager(  819): Start proc 3461:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/EventLogAggregator( 1751): Unknown tag: snet_gcore
W/EventLogAggregator( 1751): Unknown tag: snet_launch_service
,I/Babel   ( 2647): connection state changed from DISCONNECTED to CONNECTED
,I/ActivityManager(  819): Start proc 3482:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/CheckinRequestBuilder( 1751): Checkin reason type: 12 attempt count: 1
,V/GoogleAuthProtoRequest( 3225): [326] a.<init>: mAccountName set to: thalitester@gmail.com
,D/GCM     ( 1487): Connected
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  819): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,E/HttpOperation( 3064): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3064): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3064): 	at jdm.a(PG:82)
E/HttpOperation( 3064): 	at jcs.o(PG:406)
E/HttpOperation( 3064): 	at jcn.a(PG:1379)
E/HttpOperation( 3064): 	at jcs.i(PG:143)
E/HttpOperation( 3064): 	at blb.a(PG:3937)
E/HttpOperation( 3064): 	at czp.a(PG:18188)
E/HttpOperation( 3064): 	at czp.a(PG:9081)
E/HttpOperation( 3064): 	at czq.run(PG:1686)
E/HttpOperation( 3064): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3064): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3064): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3064): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3064): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3064): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3064): 	at jdj.a(PG:4091)
E/HttpOperation( 3064): 	at jdj.a(PG:1125)
E/HttpOperation( 3064): 	at jdm.a(PG:77)
E/HttpOperation( 3064): 	... 12 more
E/HttpOperation( 3064): Caused by: faj: BadAuthentication
E/HttpOperation( 3064): 	at fal.a(PG:38)
E/HttpOperation( 3064): 	at jdj.a(PG:4089)
E/HttpOperation( 3064): 	... 14 more
,D/WifiService(  819): New client listening to asynchronous messages
,D/ConnectivityService(  819): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/GCM     ( 1487): Message class com.google.f.a.a.p
W/Kids    ( 1751): [AccountUtils] Account not ready
W/Kids    ( 1751): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1751): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1751): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1751): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1751): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1751): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1751): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1751): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1751): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1751): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1751): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1751): 	at java.lang.Thread.run(Thread.java:818)
D/ConnectivityService(  819): reportInetCondition: type=1 ok, revalidate
D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,E/ActivityThread( 1751): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3064): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3064): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3064): 	at jdm.a(PG:82)
E/HttpOperation( 3064): 	at jcs.o(PG:406)
E/HttpOperation( 3064): 	at jcn.a(PG:1379)
E/HttpOperation( 3064): 	at jcs.i(PG:143)
E/HttpOperation( 3064): 	at hec.a(PG:42)
E/HttpOperation( 3064): 	at hee.a(PG:102)
E/HttpOperation( 3064): 	at czr.a(PG:65)
E/HttpOperation( 3064): 	at kka.a(PG:108)
E/HttpOperation( 3064): 	at czp.a(PG:19176)
E/HttpOperation( 3064): 	at czp.a(PG:9081)
E/HttpOperation( 3064): 	at czq.run(PG:1686)
E/HttpOperation( 3064): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3064): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3064): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3064): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3064): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3064): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3064): 	at jdj.a(PG:4091)
E/HttpOperation( 3064): 	at jdj.a(PG:1125)
E/HttpOperation( 3064): 	at jdm.a(PG:77)
E/HttpOperation( 3064): 	... 15 more
E/HttpOperation( 3064): Caused by: faj: BadAuthentication
E/HttpOperation( 3064): 	at fal.a(PG:38)
E/HttpOperation( 3064): 	at jdj.a(PG:4089)
E/HttpOperation( 3064): 	... 17 more
E/ExperimentLoader( 3064): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3064): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3064): 	at jdm.a(PG:82)
E/ExperimentLoader( 3064): 	at jcs.o(PG:406)
E/ExperimentLoader( 3064): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3064): 	at jcs.i(PG:143)
E/ExperimentLoader( 3064): 	at hec.a(PG:42)
E/ExperimentLoader( 3064): 	at hee.a(PG:102)
E/ExperimentLoader( 3064): 	at czr.a(PG:65)
E/ExperimentLoader( 3064): 	at kka.a(PG:108)
E/ExperimentLoader( 3064): 	at czp.a(PG:19176)
E/ExperimentLoader( 3064): 	at czp.a(PG:9081)
E/ExperimentLoader( 3064): 	at czq.run(PG:1686)
E/ExperimentLoader( 3064): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3064): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3064): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3064): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3064): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3064): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3064): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3064): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3064): 	at jdm.a(PG:77)
E/ExperimentLoader( 3064): 	... 15 more
E/ExperimentLoader( 3064): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3064): 	at fal.a(PG:38)
E/ExperimentLoader( 3064): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3064): 	... 17 more
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jan 2016 13:56:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453903014276], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453903013615]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Validated
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): ValidatedState{ when=-98ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=-98ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): EvaluatingState{ when=-73ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): EvaluatingState{ when=-65ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  819): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  819): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  819): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  819): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1070): CM callback handler got msg 524290
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,I/GAv4    ( 3461): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3461):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3461):   adb logcat -s GAv4
,W/GAv4    ( 3461): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GAv4    ( 3461): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 3461): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ExperimentUpdateService( 3225): [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3225): [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3225): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3225): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3225): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3225): 	at com.a.a.k.run(SourceFile:110)
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 37193, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1751): Explicit concurrent mark sweep GC freed 15447(1061KB) AllocSpace objects, 13(208KB) LOS objects, 35% free, 28MB/44MB, paused 2.475ms total 58.244ms
,V/KeepSync( 3254): Connecting to GoogleApiClient
,W/BaseAppContext( 1751): Using Auth Proxy for data requests.
,W/BaseAppContext( 1751): Using Auth Proxy for data requests.
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 22647(1296KB) AllocSpace objects, 3(48KB) LOS objects, 37% free, 26MB/42MB, paused 2.976ms total 28.687ms
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1751): Handling authorization failure
E/ClientConnectionOperation( 1751): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1751): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1751): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1751): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1751): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1751): 	... 7 more
,V/KeepSync( 3254): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3254): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3254): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3254): (284) automatic index on blob_node(is_deleted)
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jan 2016 13:56:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453903014665], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453903014280]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Validated
D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  819): Validated NetworkAgentInfo [WIFI () - 100]
,W/GAV2    ( 3482): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3482): Created application version: 3.6.8 (30608)
,I/WebViewFactory( 3461): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3461): Time to load native libraries: 1 ms (timestamps 1828-1829)
I/LibraryLoader( 3461): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3461): Binding Chromium to main looper Looper (main, tid 1) {1a2b6fa0}
I/LibraryLoader( 3461): Expected native library version number "",actual native library version number ""
I/chromium( 3461): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3461): Initializing chromium process, singleProcess=true
W/art     ( 3461): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3461): ApplicationContext is null in ApplicationStatus
,I/art     (  819): Explicit concurrent mark sweep GC freed 27451(1335KB) AllocSpace objects, 5(122KB) LOS objects, 32% free, 33MB/49MB, paused 1.244ms total 57.520ms
,W/chromium( 3461): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3461): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3461): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3461): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 3461): Starting up...
,W/AudioManagerAndroid( 3461): Requires BLUETOOTH permission
,W/CheckinRequestBuilder( 1751): awaiting user notification for token
,I/ActivityManager(  819): Start proc 3557:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/BooksSync( 3482): Starting books sync for 61035162, extras: ade
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  819): Start proc 3575:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,W/ResourcesManager( 3575): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3575): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/KeepSync( 3254): IOException
E/KeepSync( 3254): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3254): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3254): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3254): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3254): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3254): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3254): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3254): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3254): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3254): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3254): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3254): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3254): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3254): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3254): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3254): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3254): 	... 10 more
W/KeepSync( 3254): Sync result 2
,I/ActivityManager(  819): Killing 2974:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 37196, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/MultiDex( 3575): VM with version 2.1.0 has multidex support
I/MultiDex( 3575): install
I/MultiDex( 3575): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3575): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3575): Installed default security provider GmsCore_OpenSSL
,D/WVCdm   (  357): Instantiating CDM.
,I/WVCdm   (  357): CdmEngine::OpenSession
I/WVCdm   (  357): Level3 Library Dec 11 2014 16:13:16
I/BooksConfig( 3482): GmsCore Version = 7.8.99 (2134222-430)
,W/WVCdm   (  357): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/GoogleURLConnFactory( 3575): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  357): Service_Initialize: starts!
D/QSEECOMAPI: (  357): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  357): App is not loaded in QSEE
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3482): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3482): Soft error
E/BooksSync( 3482): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3482): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3482): Sync error
E/BooksSync( 3482): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3482): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3482): Finished books sync
,I/ActivityManager(  819): Killing 2997:com.android.musicfx/u0a18 (adj 15): empty #17
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37196, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/QSEECOMAPI: (  357): Loaded image: APP id = 3
,D/DrmWidevineDash(  357): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4432000
E/DrmWidevineDash(  357): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4432000
,D/DrmLibTime(  316): got the req here! ret=0
,D/DrmLibTime(  316): command id, time_cmd_id = 770
D/DrmLibTime(  316): time_getutcsec starts!
D/DrmLibTime(  316): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  316): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  316): QSEE Time Listener: seconds: 1453903015
D/DrmLibTime(  316): QSEE Time Listener: nano seconds: 439027759
D/DrmLibTime(  316): time_getutcsec returns 0, sec = 1453903015; nsec = 439027759
D/DrmLibTime(  316): time_getutcsec finished! 
,D/DrmLibTime(  316): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  316): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  357): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: starts! SID=0xb3e03940
D/DrmWidevineDash(  357): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_GetRandom: starts! randomData=0xb4c4ed20, dataLength=8
,D/DrmWidevineDash(  357): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4013000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  357): CdmEngine::QueryKeyControlInfo
,I/ActivityManager(  819): Start proc 3610:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,W/WVCdm   (  357): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  357): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  357): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d67440, idLength=0xb3f01710
I/ActivityManager(  819): Killing 3025:com.google.android.apps.docs/u0a46 (adj 15): empty #17
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
D/WVCdm   (  357): PrepareKeyRequest: nonce=2283629241
D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4d77600
D/DrmWidevineDash(  357): message_length=1599, signature=0xb4c53400, signature_length=3018856180
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  357): CdmEngine::CloseSession
D/DrmWidevineDash(  357): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  357): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  357): L3 Terminate.
D/DrmWidevineDash(  357): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  357): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  357): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  357): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  357): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  819): Start proc 3628:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,W/ResourcesManager( 3628): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3628): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3628): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3628): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 3628): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/WVCdm   (  357): CdmEngine::OpenSession
I/WVCdm   (  357): Level3 Library Dec 11 2014 16:13:16
,I/dex2oat ( 3660): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-972771746.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-972771746.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/WVCdm   (  357): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  357): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  357): Service_Initialize: starts!
D/QSEECOMAPI: (  357): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  357): App is not loaded in QSEE
,W/InstanceID/Rpc( 3628): Found 10011
,I/dex2oat ( 3660): dex2oat took 104.905ms (threads: 4) arena alloc=133KB java alloc=12KB native alloc=962KB free=7MB
,D/QSEECOMAPI: (  357): Loaded image: APP id = 3
,D/DrmWidevineDash(  357): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4432000
E/DrmWidevineDash(  357): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4432000
,D/DrmLibTime(  316): got the req here! ret=0
D/DrmLibTime(  316): command id, time_cmd_id = 770
D/DrmLibTime(  316): time_getutcsec starts!
D/DrmLibTime(  316): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  316): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  316): QSEE Time Listener: seconds: 1453903016
D/DrmLibTime(  316): QSEE Time Listener: nano seconds: 223525988
D/DrmLibTime(  316): time_getutcsec returns 0, sec = 1453903016; nsec = 223525988
D/DrmLibTime(  316): time_getutcsec finished! 
D/DrmLibTime(  316): iotcl_continue_command finished! and return 0 
,D/DrmLibTime(  316): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  357): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  357): hlos api version =  9
D/DrmWidevineDash(  357): tz api version =  9
D/DrmWidevineDash(  357): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  357): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  357): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: starts! SID=0xbecd7520
D/DrmWidevineDash(  357): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  357): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_GetRandom: starts! randomData=0xb58762a0, dataLength=8
D/DrmWidevineDash(  357): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4014800, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  357): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  357): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  357): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  357): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  357): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  357): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d67480, idLength=0xb3e03710
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
D/DrmWidevineDash(  357): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  357): PrepareKeyRequest: nonce=2665066792
D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4022600
D/DrmWidevineDash(  357): message_length=1634, signature=0xb587ffc0, signature_length=3017815796
,D/DrmWidevineDash(  357): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  357): CdmEngine::CloseSession
D/DrmWidevineDash(  357): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  357): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  357): L3 Terminate.
,D/DrmWidevineDash(  357): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  357): Service_Uninitialize: starts!
D/QSEECOMAPI: (  357): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  357): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  357): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  357): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  819): Killing 2428:android.process.acore/u0a5 (adj 15): empty #17
,I/dex2oat ( 3715): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3715): dex2oat took 45.662ms (threads: 4) arena alloc=73KB java alloc=18KB native alloc=990KB free=7MB
,I/Adreno  ( 3575): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/ActivityManager(  819): Start proc 3721:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,E/SQLiteLog( 3721): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/Adreno  ( 3575): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/EventLogService( 1751): Opted in for usage reporting
,I/ActivityManager(  819): Start proc 3751:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3721): PlayLogger.onLoggerConnected
,I/art     (  819): Explicit concurrent mark sweep GC freed 19340(811KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.225ms total 45.446ms
,I/ActivityManager(  819): Killing 1779:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/TimeService( 3751): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453903016861
D/        ( 3751): TimeServiceNative: User Time to be set is 1453903016861
D/QC-time-services( 3751): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3751): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3751): Lib:time_genoff_operation: pargs->ts_val = 1453903016861
D/QC-time-services(  372): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  372): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453903016861
D/QC-time-services(  372): Daemon:genoff_opr: Base = 2, val = 1453903016861, operation = 0
D/QC-time-services(  372): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/14/70 10:9:23
D/QC-time-services(  372): Daemon:Value read from RTC seconds = 14206163000
,D/QC-time-services(  372): Daemon:new time 1453903016861 
D/QC-time-services(  372): Daemon: delta 1439696853861 genoff 1439696853861 
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696853861 to memory
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services( 3751): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  372): Updating the TOD offset
D/QC-time-services(  372): Daemon:genoff_persistent_update: Writing genoff = 1439696853861 to memory,
D/QC-time-services(  372): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  372): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  372): Daemon:Update to modem bit set
D/QC-time-services(  372): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  372): Daemon: Base = 2, Value being sent to MODEM = 1137938216861
E/QC-time-services( 3751): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  372): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  372): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/ActivityManager(  819): Killing 2718:com.android.vending/u0a19 (adj 15): empty #17
,I/ActivityManager(  819): Killing 3295:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  819): Start proc 3773:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/GAv4    ( 3773): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3773):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3773):   adb logcat -s GAv4
,W/GAv4    ( 3773): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3773): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3773): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinTask( 1751): Sending checkin request (9769 bytes)
,I/ActivityManager(  819): Killing 3314:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@21257868}
,V/Herrevad( 1751): NQAS connected
,D/GCM     ( 1487): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1487): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1751): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  819): Start proc 3799:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,D/LocationInitializer( 1751): Restart initialization of location
,I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 465us total 20.135ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 235us total 12.586ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 497us total 11.556ms
,W/ResourcesManager( 3799): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3799): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 19318(1092KB) AllocSpace objects, 5(551KB) LOS objects, 37% free, 27MB/43MB, paused 1.005ms total 38.010ms
,I/MultiDex( 3799): VM with version 2.1.0 has multidex support
I/MultiDex( 3799): install
I/MultiDex( 3799): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3799): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2647): UserRecoverableAuthException.
E/Babel   ( 2647): eei: BadAuthentication
E/Babel   ( 2647): 	at eeg.a(Unknown Source)
E/Babel   ( 2647): 	at eeg.a(Unknown Source)
E/Babel   ( 2647): 	at eeg.a(Unknown Source)
E/Babel   ( 2647): 	at g.a(Unknown Source)
E/Babel   ( 2647): 	at cae.a(SourceFile:3089)
E/Babel   ( 2647): 	at cae.a(SourceFile:1131)
E/Babel   ( 2647): 	at cws.a(SourceFile:4333)
E/Babel   ( 2647): 	at cws.a(SourceFile:1419)
E/Babel   ( 2647): 	at crl.a(SourceFile:492)
E/Babel   ( 2647): 	at crl.a(SourceFile:1468)
E/Babel   ( 2647): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2647): 	at cas.b(SourceFile:106)
E/Babel   ( 2647): 	at cap.d(SourceFile:335)
E/Babel   ( 2647): 	at caq.run(SourceFile:81)
,E/Babel   ( 2647): Error getting auth token
,E/Babel   ( 2647): dvm
E/Babel   ( 2647): 	at g.a(Unknown Source)
E/Babel   ( 2647): 	at cae.a(SourceFile:3089)
E/Babel   ( 2647): 	at cae.a(SourceFile:1131)
E/Babel   ( 2647): 	at cws.a(SourceFile:4333)
E/Babel   ( 2647): 	at cws.a(SourceFile:1419)
E/Babel   ( 2647): 	at crl.a(SourceFile:492)
E/Babel   ( 2647): 	at crl.a(SourceFile:1468)
E/Babel   ( 2647): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2647): 	at cas.b(SourceFile:106)
E/Babel   ( 2647): 	at cap.d(SourceFile:335)
E/Babel   ( 2647): 	at caq.run(SourceFile:81)
,E/Babel   ( 2647): Account registration failed 1-Redacted-21
,E/Babel   ( 2647): cyp: null -- null
E/Babel   ( 2647): 	at cae.a(SourceFile:3121)
E/Babel   ( 2647): 	at cae.a(SourceFile:1131)
E/Babel   ( 2647): 	at cws.a(SourceFile:4333)
E/Babel   ( 2647): 	at cws.a(SourceFile:1419)
E/Babel   ( 2647): 	at crl.a(SourceFile:492)
E/Babel   ( 2647): 	at crl.a(SourceFile:1468)
E/Babel   ( 2647): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2647): 	at cas.b(SourceFile:106)
E/Babel   ( 2647): 	at cap.d(SourceFile:335)
E/Babel   ( 2647): 	at caq.run(SourceFile:81)
,I/ProviderInstaller( 3799): Installed default security provider GmsCore_OpenSSL
,I/CheckinResponseProcessor( 1751): From server: 1 gservices updates and 0 deletes
,D/WearableService( 3799): callingUid 10011, callindPid: 3799
,I/art     ( 2647): Note: end time exceeds epoch: 
,E/MDM     ( 1710): [124] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/AuthorizationBluetoothService( 1487): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1487): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
V/GmsCoreStatsServiceLauncher( 1751): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1710): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1751): Restart initialization of location
,W/ResourcesManager( 1487): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2647): Unexpected exception while authenticating.
E/Babel   ( 2647): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2647): 	at eeg.b(Unknown Source)
E/Babel   ( 2647): 	at eeg.b(Unknown Source)
E/Babel   ( 2647): 	at g.a(Unknown Source)
E/Babel   ( 2647): 	at cae.b(SourceFile:1146)
E/Babel   ( 2647): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2647): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2647): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2647): 	at java.lang.Thread.run(Thread.java:818)
,I/CertBlacklister(  819): Certificate blacklist changed, updating...
,I/CertBlacklister(  819): Certificate blacklist updated
,I/GservicesProvider( 1487): main difference update completed
,I/ActivityManager(  819): Start proc 3835:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
I/CheckinRequestBuilder( 1751): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1751): Failed to find provider info for com.google.android.wearable.settings
,W/Telecom (  819): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 2647): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 2647): BAM#gBA: invalid account id: -1
W/Babel   ( 2647): BAM#gBA: invalid account id: -1
I/Babel_telephony( 2647): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,I/ActivityManager(  819): Start proc 3860:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 22753(1177KB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 26MB/42MB, paused 780us total 22.666ms
,I/art     (  819): Explicit concurrent mark sweep GC freed 16655(777KB) AllocSpace objects, 3(330KB) LOS objects, 32% free, 33MB/49MB, paused 1.144ms total 47.114ms
,E/UpdateRequestReceiver( 3860): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3860): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3860): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3860): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  819): Killing 2878:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/art     ( 1751): Explicit concurrent mark sweep GC freed 38526(2MB) AllocSpace objects, 10(159KB) LOS objects, 35% free, 29MB/45MB, paused 1.081ms total 57.393ms
,I/SystemUpdateService( 1751): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1751): onCreate
,D/SystemUpdateService( 1751): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/SystemEventReceiver( 1751): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1751): Updating ocr activity enabled=false
,D/GCM     ( 1487): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 1710): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/SystemUpdateService( 1751): active receiver: enabled
,I/GCoreUlr( 1710): DispatchingService.onCreate()
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1751): showing system update notification
,I/ValidateNoPeople(  819): skipping global notification
,V/SystemUpdateService( 1751): retry (wakeup: false) in 3599896 ms
,W/CheckinRequestBuilder( 1751): awaiting user notification for token
,I/jxcore-log( 3149): Test app app.js loaded
I/jxcore-log( 3149): 
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 9563(440KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.218ms total 50.019ms
I/chromium( 3149): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 3149): BLE advertisement is supported
I/jxcore-log( 3149): 
,I/GCoreUlr( 1710): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 1710): Explicit concurrent mark sweep GC freed 12720(703KB) AllocSpace objects, 4(64KB) LOS objects, 37% free, 26MB/42MB, paused 1.678ms total 33.276ms
,E/DataBuffer( 1710): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2b1d6a7f)
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=46.66 rxSuccessRate=50.81 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,I/art     ( 1751): Explicit concurrent mark sweep GC freed 8544(494KB) AllocSpace objects, 4(64KB) LOS objects, 35% free, 29MB/45MB, paused 1.027ms total 30.195ms
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=46.66 rxSuccessRate=50.81 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,D/SystemUpdateService( 1751): onDestroy
,I/EventLogService( 1751): Opted in for usage reporting
,I/GCoreUlr( 1710): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1710): Unbound from all location providers
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 4579(182KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 26MB/42MB, paused 847us total 20.070ms
,I/CheckinTask( 1751): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/GCoreUlr( 1710): DispatchingService.onDestroy()
,I/GservicesUpdateTask( 1512): Updating Gservices keys
,I/GCoreUlr( 1710): Unbound from all location providers
,I/CheckinService( 1751): Checking schedule, now: 1453903019272 next: 1453944162248
I/CheckinService( 1751): active receiver: disabled
,I/CheckinService( 1751): Checking schedule, now: 1453903019297 next: 1453944162248
I/CheckinService( 1751): active receiver: disabled
,D/ChimeraCfgMgr( 1751): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1487): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 1751): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1751): [AccountUtils] Account not ready
W/Kids    ( 1751): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1751): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1751): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1751): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1751): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1751): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1751): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1751): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1751): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1751): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1751): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1751): 	at java.lang.Thread.run(Thread.java:818)
,I/GAV2    ( 3482): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 3721): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  819): Killing 3397:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  819): Killing 3461:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/ActivityManager(  819): Killing 3557:com.android.chrome/u0a40 (adj 15): empty #17
,V/ConfigFetchTask( 1751): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XzkPRxvx46aBj8JuUHmIeuTYk_31iKpDKecz-gDRVFS1sd-_GKgv2kz2D-wvy4_-AjfmsFD30kpSYQs8X4UiH2WzbtWljc6AFr8-GkRWf5ifBUQz5rbEHHR7skHy55xftXGBcpQzsULcU4fLhTQXqCruTN4tJyrArBo46ybByHT8QHMuKzD-9PU7PEW2ocsR-51HvrUZ9fqGOOlGtryn2JXFcyF6C65rxQIYy7Wty0NBClxcg
,I/GoogleURLConnFactory( 1751): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  819): Start proc 3918:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/Finsky  ( 3918): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ConfigFetchTask( 1751): updating config table for com.google.android.gms
,I/ConfigFetchService( 1751): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1751): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1751): GmsCore config value changed; rescheduling
I/ConfigFetchService( 1751): fetch service done; releasing wakelock
,D/Finsky  ( 3918): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ConfigFetchService( 1751): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1751): stopping self
,I/ActivityManager(  819): Start proc 3956:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,I/ActivityManager(  819): Killing 3064:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,W/Settings( 3918): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3918): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 3956): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3956): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MultiDex( 3956): VM with version 2.1.0 has multidex support
,I/MultiDex( 3956): install
I/MultiDex( 3956): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3956): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     (  819): Explicit concurrent mark sweep GC freed 21401(1071KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.582ms total 89.361ms
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Finsky  ( 3918): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3918): [1] 2.run: Finished loading 1 libraries.
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 3918): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/Ads     ( 1751): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,V/GoogleAuthProtoRequest( 3225): [328] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ProviderInstaller( 3956): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1487): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1487): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/Finsky  ( 3918): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GmsCoreStatsServiceLauncher( 1751): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WearableService( 3799): callingUid 10011, callindPid: 3799
,E/MDM     ( 1710): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 1751): Restart initialization of location
,W/ExperimentUpdateService( 3225): [328] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3225): [328] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3225): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3225): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3225): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3225): 	at com.a.a.k.run(SourceFile:110)
,V/Finsky  ( 3918): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/VacuumService( 1487): Vacuum at: now=1453903024593 tag=VacuumService
,I/GoogleURLConnFactory( 1487): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 25302(1357KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.020ms total 24.605ms
,E/Uploader( 1487): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1487): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1487): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1487): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3918): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3918): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3918): [1] 5.onFinished: Scheduling replication attempt 4.
,D/Finsky  ( 3918): [400] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3918): [400] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,D/Finsky  ( 3918): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1487): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1487): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1487): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1487): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3918): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Uploader( 1487): No account for auth token provided
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1487): No account for auth token provided
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3918): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/Uploader( 1487): No account for auth token provided
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1487): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1487): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1487): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1487): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1487): No account for auth token provided
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3918): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3918): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3918): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3918): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,W/Uploader( 1487): No account for auth token provided
,D/DeviceConnectionService( 1710): client connected with version: 7571000
,W/Uploader( 1487): No account for auth token provided,
,W/Uploader( 1487): No account for auth token provided
,W/Uploader( 1487): No account for auth token provided
,W/Uploader( 1487):  no longer exists, so no auth token.
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1487): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1487): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1487): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1487): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1487): No account for auth token provided
,W/Uploader( 1487): No account for auth token provided
,W/Uploader( 1487): No account for auth token provided
,W/Uploader( 1487): No account for auth token provided
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  819): Explicit concurrent mark sweep GC freed 22989(1003KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 1.484ms total 87.218ms,
,E/Uploader( 1487): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1487): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1487): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1487): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1487): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1487): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1487): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1487): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1487): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1487): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1487): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1487): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1487): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1487): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1487): No account for auth token provided
,W/Uploader( 1487): No account for auth token provided
,W/Uploader( 1487): No account for auth token provided
,W/PackageSettings(  819): Skipping PackageSetting{2be9aaeb com.example.hello/10273} due to missing metadata
,I/ConfigService( 1487): onDestroy
,I/InputReader(  819): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  819): Start proc 4006:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,V/GmsNetworkLocationProvi( 1710): DISABLE
,D/BackupManagerService(  819): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  819): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  819): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  819): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  819): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2ce9aa43
,I/Launcher( 1351): Deferring update until onResume
,V/BackupManagerService(  819): Scheduling immediate backup pass
,V/GmsNetworkLocationProvi( 1710): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/BackupManagerService(  819): Running a backup pass
V/GmsNetworkLocationProvi( 1710): ENABLE
,I/ActivityManager(  819): Killing 3482:com.google.android.apps.books/u0a34 (adj 15): empty #17
,V/BackupManagerService(  819): clearing pending backups
,V/PerformBackupTask(  819): Beginning backup of 14 targets
,D/PerformBackupTask(  819): invokeAgentForBackup on @pm@
V/BackupServiceBinder(  819): doBackup() invoked
,I/PMBA    (  819): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  819): Getting widget state for user: 0
,I/ContactLocale( 4006): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,V/GmsNetworkLocationProvi( 1710): SET-REQUEST
,D/PackageBroadcastService( 1751): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 1512): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageBroadcastService( 1751): Null package name or gms related package.  Ignoreing.
,V/GmsNetworkLocationProvi( 1710): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,W/Launcher( 1351): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@36c12136 new=com.google.android.velvet.VelvetApplication@36c12136
,I/Icing   ( 1751): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 1512): UpdateCorporaTask done [took 44 ms] updated apps [took 43 ms] 
,I/ActivityManager(  819): Start proc 4032:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,W/GmsBackupTransport( 1710): Unknown package in backup request: @pm@
V/GmsBackupTransport( 1710): starting performBackup for @pm@
,V/GmsBackupTransport( 1710): performBackup done for @pm@
,W/ResourcesManager( 4032): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1487): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1487): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1487): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1487): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1487): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1487): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1487): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1710): Error sending final backup to server: 
W/GmsBackupTransport( 1710): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1710): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1710): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1710): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1710): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1710): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1710): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1710): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1710): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1710): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1710): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1710): 	... 1 more
,D/BackupManagerService(  819): Now staging backup of com.google.android.talk
,D/BackupManagerService(  819): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  819): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  819): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  819): Now staging backup of com.google.android.gm
,D/BackupManagerService(  819): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  819): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  819): Now staging backup of com.android.nfc
,D/BackupManagerService(  819): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  819): Now staging backup of com.android.vending
,D/BackupManagerService(  819): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  819): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  819): Now staging backup of android
,D/BackupManagerService(  819): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1710): Next backup will happen in 43199967 millis.
,I/BackupManagerService(  819): Backup pass finished.
,I/ActivityManager(  819): Killing 3628:com.google.android.youtube/u0a86 (adj 15): empty #17
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=16.43 rxSuccessRate=13.87 targetRoamBSSID=any RSSI=-50
,E/WifiStateMachine(  819): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/ActivityManager(  819): Killing 3254:com.google.android.keep/u0a79 (adj 15): empty #17
,I/ActivityManager(  819): Killing 3751:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/PowerManagerService(  819): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  819): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (2186 us)
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 62731(3MB) AllocSpace objects, 5(408KB) LOS objects, 36% free, 27MB/43MB, paused 2.304ms total 31.383ms
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3918): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
D/Finsky  ( 3918): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3918): [1] 5.onFinished: Scheduling replication attempt 5.
,I/DisplayManagerService(  819): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  819): Display changed displayId=0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  819): Excessive delay in setPowerMode(): 261ms,
,I/DreamManagerService(  819): Entering dreamland.
I/PowerManagerService(  819): Dozing...
,I/DreamController(  819): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  819): cancelDelayedScan -> 6
,E/native  (  819): do suspend false
,D/WifiService(  819): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@13a66850}
,I/Keyboard.Facilitator( 1222): onFinishInput()
,E/WifiStateMachine(  819): cancelDelayedScan -> 8
,E/native  (  819): do suspend true
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-50
,D/audio_hw_primary(  357): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  357): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,I/art     (  819): Explicit concurrent mark sweep GC freed 38484(2MB) AllocSpace objects, 14(601KB) LOS objects, 31% free, 34MB/50MB, paused 1.822ms total 89.196ms
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/WifiService(  819): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@13a66850}
,E/WifiStateMachine(  819): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  819): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 8 -> obsolete
,V/GoogleAuthProtoRequest( 3225): [329] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3225): [330] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3225): [330] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3225): [330] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3225): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3225): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3225): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3225): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3225): [329] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3225): [329] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3225): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3225): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3225): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3225): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3918): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3918): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3918): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 3209): Disconnected process message: 10, size: 0,
,D/HeadsetStateMachine( 3209): Disconnected process message: 10, size: 0
,I/ActivityManager(  819): Start proc 4070:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/ActivityManager(  819): Start proc 4087:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/GAV2    ( 4087): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4087): Created application version: 3.6.8 (30608)
,I/BooksSync( 4087): Starting books sync for 61035162, extras: ade
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 14841(767KB) AllocSpace objects, 17(1874KB) LOS objects, 38% free, 26MB/42MB, paused 1.475ms total 43.380ms
,V/KeepSync( 4070): Connecting to GoogleApiClient
,I/BooksConfig( 4087): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1751): Handling authorization failure
E/ClientConnectionOperation( 1751): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1751): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1751): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1751): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1751): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1751): 	... 7 more
,V/KeepSync( 4070): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4070): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4070): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4070): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4087): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4087): Soft error
E/BooksSync( 4087): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4087): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4087): Sync error
E/BooksSync( 4087): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4087): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4087): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163315, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4070): IOException
E/KeepSync( 4070): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4070): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4070): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4070): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4070): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4070): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4070): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4070): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4070): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4070): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4070): ,	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4070): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4070): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4070): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4070): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4070): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4070): 	... 10 more,
W/KeepSync( 4070): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 162205, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
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
,I/ActivityManager(  819): Killing 3773:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/ActivityManager(  819): Killing 3721:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  819): Explicit concurrent mark sweep GC freed 33503(1505KB) AllocSpace objects, 7(489KB) LOS objects, 32% free, 33MB/49MB, paused 2.676ms total 82.930ms
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
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
E/HttpOperation( 4032): 	at hec.a(PG:42)
E/HttpOperation( 4032): 	at hee.a(PG:102)
E/HttpOperation( 4032): 	at czr.a(PG:65)
E/HttpOperation( 4032): 	at kka.a(PG:108)
E/HttpOperation( 4032): 	at czp.a(PG:19176),
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
E/HttpOperation( 4032): 	... 15 more,
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
E/ExperimentLoader( 4032): ,	at hee.a(PG:102)
E/ExperimentLoader( 4032): 	at czr.a(PG:65)
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
E/ExperimentLoader( 4032): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4032): 	at jdm.a(PG:77)
E/ExperimentLoader( 4032): 	... 15 more
E/ExperimentLoader( 4032): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4032): 	,at fal.a(PG:38)
E/ExperimentLoader( 4032): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4032): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 131564, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/GAV2    ( 4087): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 3918): [400] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3918): [400] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/Keyboard.Facilitator.LanguageModelFlusher( 1222): run()
I/Keyboard.Facilitator( 1222): flushDynamicLanguageModels()
,I/ConfigService( 1487): onCreate
,I/ConfigService( 1487): onDestroy
,D/HeadsetStateMachine( 3209): Disconnected process message: 10, size: 0
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
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
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4032): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4032): java.io.IOException: Cannot obtain authentication token
,E/HttpOperation( 4032): 	at jdm.a(PG:82)
E/HttpOperation( 4032): 	at jcs.o(PG:406)
E/HttpOperation( 4032): 	at jcn.a(PG:1379)
E/HttpOperation( 4032): 	at jcs.i(PG:143)
,E/HttpOperation( 4032): 	at hec.a(PG:42)
E/HttpOperation( 4032): 	at hee.a(PG:102)
E/HttpOperation( 4032): 	at czr.a(PG:65)
E/HttpOperation( 4032): 	,at kka.a(PG:108)
E/HttpOperation( 4032): 	at czp.a(PG:19176)
E/HttpOperation( 4032): 	at czp.a(PG:9081)
E/HttpOperation( 4032): 	at czq.run(PG:1686)
,E/HttpOperation( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/HttpOperation( 4032): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4032): 	at jdj.a(PG:4091)
E/HttpOperation( 4032): 	at jdj.a(PG:1125)
E/HttpOperation( 4032): 	at jdm.a(PG:77)
E/HttpOperation( 4032): 	... 15 more
E/HttpOperation( 4032): Caused by: faj: BadAuthentication
E/HttpOperation( 4032): 	at fal.a(PG:38)
E/HttpOperation( 4032): 	at jdj.a(PG:4089)
E/HttpOperation( 4032): ,	... 17 more
E/ExperimentLoader( 4032): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 4032): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4032): 	at jdm.a(PG:82)
E/ExperimentLoader( 4032): 	at jcs.o(PG:406)
E/ExperimentLoader( 4032): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4032): ,	at jcs.i(PG:143)
E/ExperimentLoader( 4032): 	at hec.a(PG:42)
E/ExperimentLoader( 4032): 	at hee.a(PG:102)
E/ExperimentLoader( 4032): 	at czr.a(PG:65)
,E/ExperimentLoader( 4032): 	at kka.a(PG:108)
E/ExperimentLoader( 4032): 	at czp.a(PG:19176)
E/ExperimentLoader( 4032): 	at czp.a(PG:9081)
E/ExperimentLoader( 4032): ,	at czq.run(PG:1686)
E/ExperimentLoader( 4032): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4032): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4032): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4032): ,	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4032): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4032): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4032): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4032): 	at jdm.a(PG:77)
E/ExperimentLoader( 4032): 	... 15 more
E/ExperimentLoader( 4032): Caused by: faj: BadAuthentication
,E/ExperimentLoader( 4032): 	at fal.a(PG:38)
E/ExperimentLoader( 4032): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4032): 	... 17 more
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 222891, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3225): [331] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3225): [332] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3225): [331] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3225): [331] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3225): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3225): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3225): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3225): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3225): [332] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3225): [332] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3225): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3225): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3225): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3225): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3225): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3225): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 4087): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4070): Connecting to GoogleApiClient,
,I/BooksConfig( 4087): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1751): Handling authorization failure
E/ClientConnectionOperation( 1751): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1751): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1751): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1751): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1751): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1751): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1751): 	... 7 more
,V/KeepSync( 4070): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4070): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4070): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4070): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1487): Explicit concurrent mark sweep GC freed 41574(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 27MB/43MB, paused 1.084ms total 38.926ms
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1487): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1487): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1487): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1487): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1487): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4087): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4087): Soft error
E/BooksSync( 4087): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4087): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4087): Sync error
E/BooksSync( 4087): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4087): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4087): Finished books sync
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 253260, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 4070): IOException
E/KeepSync( 4070): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4070): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4070): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4070): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4070): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4070): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4070): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4070): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4070): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4070): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4070): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4070): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4070): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4070): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4070): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4070): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4070): 	... 10 more
W/KeepSync( 4070): Sync result 2
,D/SyncManager(  819): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 251923, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3209): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3209): Disconnected process message: 10, size: 0
,I/jxcore-log( 3149): TAP version 13
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # multiplex can send data
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 1 String should be length:200
,I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # enqueue and run in order
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 2 firstPromise setTimeout
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 3 firstPromise result
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 4 firstPromise testValue
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 5 secondPromise setTimeout
I/jxcore-log( 3149): 
I/jxcore-log( 3149): ok 6 secondPromise result
I/jxcore-log( 3149): 
I/jxcore-log( 3149): ok 7 secondPromise testValue
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 8 thirdPromise in promise
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 9 thirdPromise result
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 10 thirdPromise testValue
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # basic
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 11 sane
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # another
I/jxcore-log( 3149): ,
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 12 sane
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 13 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 14 null
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 15 (unnamed assert)
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 16 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 17 should not throw
I/jxcore-log( 3149): 
I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 18 (unnamed assert)
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 19 (unnamed assert)
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 20 should not throw
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 21 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 22 should be equal
I/jxcore-log( 3149): 
I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 23 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # failed to get mobile documents path
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 24 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 25 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 26 should be equal
I/jxcore-log( 3149): 
I/jxcore-log( 3149): ok 27 should be equal
I/jxcore-log( 3149): 
I/jxcore-log( 3149): # setup
,I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #init should register the networkChanged event
,I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
,I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 28 should be equal,
,I/jxcore-log( 3149): 
I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startBroadcasting should throw on null device name
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 29 should throw
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 30 should throw
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 31 should throw
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 32 should throw,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startBroadcasting should throw on negative port,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 33 should throw,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startBroadcasting should throw on too large port,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 34 should throw,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startBroadcasting should call Mobile("StartBroadcasting") without an error,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 35 should be equal,
I/jxcore-log( 3149): 
I/jxcore-log( 3149): ok 36 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 37 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 38 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 39 should be equal
I/jxcore-log( 3149): 
I/jxcore-log( 3149): ok 40 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 41 should be equal
I/jxcore-log( 3149): 
I/jxcore-log( 3149): ok 42 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 43 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 44 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 45 should be equal
I/jxcore-log( 3149): 
I/jxcore-log( 3149): ok 46 should be equal
I/jxcore-log( 3149): 
I/jxcore-log( 3149): ok 47 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 48 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 49 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 50 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 51 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3149): ,
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 52 should be equal
I/jxcore-log( 3149): ,
I/jxcore-log( 3149): ok 53 should be equal
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199331.3149
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61,
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199331.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199331.3149
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903199331.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3209): registerClient() - UUID=9c523925-8276-4a09-b48c-dce1f50dd1a3,
D/BtGatt.GattService( 3209): onClientRegistered() - UUID=9c523925-8276-4a09-b48c-dce1f50dd1a3, clientIf=5
D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3209): message : 0
,D/BtGatt.AdvertiseManager( 3209): starting multi advertising
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=446db93b-cb8a-4dca-b4a1-ff059196d4b6
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=446db93b-cb8a-4dca-b4a1-ff059196d4b6, clientIf=6
D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3209): start scan with filters
,D/BtGatt.ScanManager( 3209): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothAdapterService( 3209): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24984d0c
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199331.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199331.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199331.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199331.3149
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 3149): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3149): 
,I/io.jxcore.node.ConnectionHelper( 3149): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 3209): message : 1
D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5
,D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): Client app is not null!
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3209): stopScan() - queue size =1
,D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
D/BtGatt.ScanManager( 3209): stop scan
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
I/wpa_supplicant( 3212): P2P-FIND-STOPPED 
I/jxcore-log( 3149): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199561.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199561.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback,
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199561.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903199561.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3209): registerClient() - UUID=05b91465-2a91-4348-bb9c-28464ae12cc6
D/BtGatt.GattService( 3209): onClientRegistered() - UUID=05b91465-2a91-4348-bb9c-28464ae12cc6, clientIf=5
,D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3209): message : 0
,D/BtGatt.AdvertiseManager( 3209): starting multi advertising,
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=ddd2c321-68f9-4ca8-b79a-eceff28e0827
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=ddd2c321-68f9-4ca8-b79a-eceff28e0827, clientIf=6
D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3209): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3209): handling starting scan
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199561.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199561.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199561.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/wpa_supplicant( 3212): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199561.3149
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started,
I/io.jxcore.node.ConnectionHelper( 3149): start: OK
I/wpa_supplicant( 3212): P2P-FIND-STOPPED 
I/jxcore-log( 3149): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 3149): 
I/io.jxcore.node.ConnectionHelper( 3149): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...
,I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/BtGatt.AdvertiseManager( 3209): message : 1
D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3209): Client app is not null!
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3209): stopScan() - queue size =1
,D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0,
,D/BtGatt.ScanManager( 3209): stop scan
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped
,D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3149): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199646.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199646.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199646.3149,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903199646.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3209): registerClient() - UUID=2c3284b4-2e9a-4d8c-8de8-a4f374c170ef
D/BtGatt.GattService( 3209): onClientRegistered() - UUID=2c3284b4-2e9a-4d8c-8de8-a4f374c170ef, clientIf=5
,D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3209): message : 0
D/BtGatt.AdvertiseManager( 3209): starting multi advertising
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=6fc46166-7051-470a-b5c4-6ad0b8b45d15
D/BtGatt.GattService( 3209): onClientRegistered() - UUID=6fc46166-7051-470a-b5c4-6ad0b8b45d15, clientIf=6
,D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3209): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3209): handling starting scan
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199646.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199646.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199646.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
I/wpa_supplicant( 3212): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199646.3149
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 3212): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/jxcore-log( 3149): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 3149): 
,I/io.jxcore.node.ConnectionHelper( 3149): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 3209): message : 1
D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5
D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3209): Client app is not null!
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 3209): stopScan() - queue size =1
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false
D/BtGatt.ScanManager( 3209): stop scan
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped,
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3149): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199722.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199722.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
,I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199722.3149
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903199722.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3209): registerClient() - UUID=608fc004-9cda-4a45-a4d8-14615722dc02
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=608fc004-9cda-4a45-a4d8-14615722dc02, clientIf=5
D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3209): message : 0
,D/BtGatt.AdvertiseManager( 3209): starting multi advertising
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=a81447eb-8f0b-4409-bdc2-4a1f101103d0
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=a81447eb-8f0b-4409-bdc2-4a1f101103d0, clientIf=6
,D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3209): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3209): handling starting scan
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199722.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199722.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199722.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
,D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
I/wpa_supplicant( 3212): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending,
,D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199722.3149
,I/io.jxcore.node.ConnectionHelper( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 3212): P2P-FIND-STOPPED 
,I/jxcore-log( 3149): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 3149): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 3149): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED,
D/BtGatt.AdvertiseManager( 3209): message : 1,
D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5,
,D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3209): Client app is not null!
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 3209): stopScan() - queue size =1
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): stop scan
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
I/jxcore-log( 3149): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199791.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199791.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199791.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903199791.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3209): registerClient() - UUID=9a01e6bd-f527-47ad-b696-3f243aa2f877,
D/BtGatt.GattService( 3209): onClientRegistered() - UUID=9a01e6bd-f527-47ad-b696-3f243aa2f877, clientIf=5,
D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3209): message : 0
,D/BtGatt.AdvertiseManager( 3209): starting multi advertising
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0,
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=c6dac2d3-8e35-4ec9-b4d9-41a6d5a73efb
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=c6dac2d3-8e35-4ec9-b4d9-41a6d5a73efb, clientIf=6
D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3209): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3209): handling starting scan
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199791.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199791.3149","ra":"F8:CF:C5:D9:E5:61"}
D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199791.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 3212): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199791.3149
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
I/jxcore-log( 3149): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 3149): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 3149): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
I/wpa_supplicant( 3212): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,D/BtGatt.AdvertiseManager( 3209): message : 1
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5
,D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3209): Client app is not null!
,D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 3209): stopScan() - queue size =1
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3149): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
,D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): stop scan
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199851.3149
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199851.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199851.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903199851.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3209): registerClient() - UUID=04d82171-932a-4109-8ab7-7d419ea0e10c
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=04d82171-932a-4109-8ab7-7d419ea0e10c, clientIf=5
D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3209): message : 0
,D/BtGatt.AdvertiseManager( 3209): starting multi advertising,
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=00e76961-e1c9-410d-96ed-5a34fe6279ed
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=00e76961-e1c9-410d-96ed-5a34fe6279ed, clientIf=6
,D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3209): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3209): handling starting scan
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199851.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199851.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199851.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199851.3149
I/wpa_supplicant( 3212): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 3212): P2P-FIND-STOPPED 
I/jxcore-log( 3149): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 3149): 
I/io.jxcore.node.ConnectionHelper( 3149): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED
,D/BtGatt.AdvertiseManager( 3209): message : 1
,D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5
,D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): Client app is not null!
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3209): stopScan() - queue size =1
,D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED
,D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): stop scan
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3149): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199923.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199923.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199923.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903199923.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3209): registerClient() - UUID=3dc51b60-4fb3-4451-81b8-0ffc48a29730,
D/BtGatt.GattService( 3209): onClientRegistered() - UUID=3dc51b60-4fb3-4451-81b8-0ffc48a29730, clientIf=5
D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3209): message : 0
,D/BtGatt.AdvertiseManager( 3209): starting multi advertising,
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=24f16487-9ae6-4060-b64a-5c75fdcd4d6a
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=24f16487-9ae6-4060-b64a-5c75fdcd4d6a, clientIf=6
D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3209): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3209): handling starting scan
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199923.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199923.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903199923.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/art     (  819): Explicit concurrent mark sweep GC freed 34633(1619KB) AllocSpace objects, 7(300KB) LOS objects, 32% free, 33MB/49MB, paused 1.609ms total 86.267ms
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903199923.3149
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,I/jxcore-log( 3149): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 3149): 
I/io.jxcore.node.ConnectionHelper( 3149): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 3212): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED
D/BtGatt.AdvertiseManager( 3209): message : 1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3209): Client app is not null!
,D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3209): stopScan() - queue size =1
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
D/BtGatt.ScanManager( 3209): stop scan
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3149): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200095.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200095.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200095.3149
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903200095.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3209): registerClient() - UUID=f3ec611c-5beb-4957-a810-964e5864b74e
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=f3ec611c-5beb-4957-a810-964e5864b74e, clientIf=5
D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3209): message : 0
,D/BtGatt.AdvertiseManager( 3209): starting multi advertising
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=64064897-5694-4377-bb55-1d286953b268
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=64064897-5694-4377-bb55-1d286953b268, clientIf=6
D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3209): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3209): handling starting scan
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200095.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200095.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200095.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
,D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 3212): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200095.3149
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 3149): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3149): 
I/wpa_supplicant( 3212): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3149): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...,
D/BtGatt.AdvertiseManager( 3209): message : 1
D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5
,D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3209): Client app is not null!
,D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3209): stopScan() - queue size =1,
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
,D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): stop scan
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped
,I/jxcore-log( 3149): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200148.3149
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200148.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
,I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200148.3149
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903200148.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3209): registerClient() - UUID=1ff6f2b1-af0e-4b5c-b3bf-7d0cd011f2ad,
D/BtGatt.GattService( 3209): onClientRegistered() - UUID=1ff6f2b1-af0e-4b5c-b3bf-7d0cd011f2ad, clientIf=5
D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3209): message : 0
,D/BtGatt.AdvertiseManager( 3209): starting multi advertising
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=3213879c-1456-4d1a-ac15-4ec330cf9cf6
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=3213879c-1456-4d1a-ac15-4ec330cf9cf6, clientIf=6
D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3209): start scan with filters
,D/BtGatt.ScanManager( 3209): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200148.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200148.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200148.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 3212): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/io.jxcore.node.ConnectionHelper( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200148.3149
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/jxcore-log( 3149): ok 70 Should be able to call startBroadcasting without error,
I/jxcore-log( 3149): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3149): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant( 3212): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/BtGatt.AdvertiseManager( 3209): message : 1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5
D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3209): Client app is not null!
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3209): stopScan() - queue size =1
,D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): stop scan
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3149): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200224.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200224.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200224.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903200224.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3209): registerClient() - UUID=0d15300f-c6af-42ee-a0e7-7c5e0245dc28
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=0d15300f-c6af-42ee-a0e7-7c5e0245dc28, clientIf=5
D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3209): message : 0
,D/BtGatt.AdvertiseManager( 3209): starting multi advertising,
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=859e1be7-904a-44db-915b-41a63ed6dcc8
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=859e1be7-904a-44db-915b-41a63ed6dcc8, clientIf=6
,D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 3209): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3209): handling starting scan
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200224.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200224.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200224.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200224.3149
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
I/wpa_supplicant( 3212): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3149): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 3149): 
I/io.jxcore.node.ConnectionHelper( 3149): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
I/wpa_supplicant( 3212): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/BtGatt.AdvertiseManager( 3209): message : 1
D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 3209): Client app is not null!
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 3209): stopScan() - queue size =1
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): stop scan
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
I/jxcore-log( 3149): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI,
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200402.3149
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200402.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200402.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903200402.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3209): registerClient() - UUID=21b7eabe-f33d-446d-81f3-0a341d2359d6
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=21b7eabe-f33d-446d-81f3-0a341d2359d6, clientIf=5,
D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3209): message : 0
,D/BtGatt.AdvertiseManager( 3209): starting multi advertising
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0,
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=77a95fac-8cbd-4e41-b2d0-cb50b2107609
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=77a95fac-8cbd-4e41-b2d0-cb50b2107609, clientIf=6
D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3209): start scan with filters
,D/BtGatt.ScanManager( 3209): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0,
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200402.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200402.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200402.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200402.3149
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 3149): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 3149): 
I/wpa_supplicant( 3212): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/jxcore-log( 3149): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 3149): 
,I/io.jxcore.node.ConnectionHelper( 3149): stop,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
D/BtGatt.AdvertiseManager( 3209): message : 1
,D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5
,D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0,
D/BtGatt.GattService( 3209): Client app is not null!
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3209): stopScan() - queue size =1
,D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...,
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): stop scan
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3149): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200850.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200850.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...,
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
,I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200850.3149
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903200850.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0,
,D/BtGatt.GattService( 3209): registerClient() - UUID=3a421820-5c70-48c1-aa5d-b0adfecb54c5
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=3a421820-5c70-48c1-aa5d-b0adfecb54c5, clientIf=5
D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 3209): message : 0
,D/BtGatt.AdvertiseManager( 3209): starting multi advertising
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=68be7d05-2d71-4133-a33c-d0bab470c37f
,D/BtGatt.GattService( 3209): onClientRegistered() - UUID=68be7d05-2d71-4133-a33c-d0bab470c37f, clientIf=6
,D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3209): start scan with filters
D/BtGatt.ScanManager( 3209): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200850.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200850.3149","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903200850.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903200850.3149
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
I/io.jxcore.node.ConnectionHelper( 3149): start: OK
,D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 3212): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
I/wpa_supplicant( 3212): P2P-FIND-STOPPED ,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/jxcore-log( 3149): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 3149): ,
I/io.jxcore.node.ConnectionHelper( 3149): connect: Trying to connect to peer with ID foobar
,W/io.jxcore.node.ConnectionHelper( 3149): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,E/io.jxcore.node.ConnectionHelper( 3149): connect: Invalid Bluetooth address: foobar
,I/jxcore-log( 3149): ok 78 Should not connect to a bad peer
I/jxcore-log( 3149): 
,I/io.jxcore.node.ConnectionHelper( 3149): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 3209): message : 1
,D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5
,D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): Client app is not null!
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3209): stopScan() - queue size =1
,D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
I/jxcore-log( 3149): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/BtGatt.ScanManager( 3209): stop scan
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/ActivityManager(  819): Start proc 4195:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903201080.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): initialize: My bluetooth address is F8:CF:C5:D9:E5:61,
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903201080.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3149): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): start: OK
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3149): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903201080.3149
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): createAdvertiseData: From: 1453903201080.3149 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3149): F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -49, -59, -39, -27, 97]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3149): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 3209): registerClient() - UUID=c8509810-7a51-460f-8a53-d5058d91c9b7
D/BtGatt.GattService( 3209): onClientRegistered() - UUID=c8509810-7a51-460f-8a53-d5058d91c9b7, clientIf=5
D/BluetoothLeAdvertiser( 3149): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 3209): message : 0
,D/BtGatt.AdvertiseManager( 3209): starting multi advertising
,D/BtGatt.GattService( 3209): onAdvertiseInstanceEnabled() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): onAdvertiseDataSet() - clientIf=5, status=0
,D/BtGatt.GattService( 3209): registerClient() - UUID=c2c75ab7-1bdc-4c78-b398-2db01d3c38ea
D/BtGatt.GattService( 3209): onClientRegistered() - UUID=c2c75ab7-1bdc-4c78-b398-2db01d3c38ea, clientIf=6
D/BluetoothLeScanner( 3149): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 3209): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 3209): handling starting scan
D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3149): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903201080.3149","ra":"F8:CF:C5:D9:E5:61"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): start: {"pi":"F8:CF:C5:D9:E5:61","pn":"1453903201080.3149","ra":"F8:CF:C5:D9:E5:61"},
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): start: Identity string: "{"pi":"F8:CF:C5:D9:E5:61","pn":"1453903201080.3149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp"
D/BtGatt.GattService( 3209): onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: Peer ID: F8:CF:C5:D9:E5:61, peer name: 1453903201080.3149
,D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=1
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3149): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 3149): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log( 3149): 
,D/io.jxcore.node.ConnectionHelper( 3149): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 3149): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 3149): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3149): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/wpa_supplicant( 3212): P2P-FIND-STOPPED 
I/jxcore-log( 3149): ok 81 Disconnect should fail to a non-existant peer 
I/jxcore-log( 3149): 
I/io.jxcore.node.ConnectionHelper( 3149): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): restart: Restarting...,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: RESTARTING
I/GAv4    ( 4195): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4195):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4195):   adb logcat -s GAv4
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3149): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3149): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3149): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3149): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 3209): message : 1
D/BtGatt.AdvertiseManager( 3209): stop advertise for client 5
,D/BtGatt.GattService( 3209): onAdvertiseInstanceDisabled() - clientIf=5, status=0,
D/BtGatt.GattService( 3209): Client app is not null!
D/BtGatt.GattService( 3209): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 3209): stopScan() - queue size =1
,D/BtGatt.GattService( 3209): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3149): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3149): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3149): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3149): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3149): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3149): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3149): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3149): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3149): Service requests cleared successfully
,I/jxcore-log( 3149): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 3149): 
D/BtGatt.GattService( 3209): onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 3209): callback done for clientIf - 6 status - 0
D/BtGatt.ScanManager( 3209): stop scan
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 3209): configureRegularScanParams() - queue emtpy, scan stopped
W/GAv4    ( 4195): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,W/GAv4    ( 4195): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4195): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  819): Killing 3835:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/jxcore-log( 3149): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 83 host address should match
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 84 port should match
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 85 USN should have changed from the first one
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # messages with invalid location or USN should be ignored
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 86 should not have emitted with invalid port
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): WARN thaliWifiInfrastructure Received an invalid USN value: 
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 87 should not have emitted with invalid USN
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 88 irrelevant messages should be ignored
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 89 relevant messages should not be ignored
I/jxcore-log( 3149): 
I/jxcore-log( 3149): ok 90 messages from this device should be ignored
I/jxcore-log( 3149): 
I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #start should fail if called twice in a row
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 91 specific error should be received
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,E/jxcore-log( 3149): ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
,E/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 92 specific error should be received,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startUpdateAdvertisingAndListening should fail if router server starting fails,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown,
I/jxcore-log( 3149): 
,E/jxcore-log( 3149): ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE,
E/jxcore-log( 3149): 
I/jxcore-log( 3149): ok 93 specific error expected
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 94 server should respond with code 200
,I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #stop can be called multiple times in a row
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 95 should be in stopped state
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 96 should still be in stopped state
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #startListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 97 should be in listening state
,I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 98 should still be in listening state
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #stopListeningForAdvertisements can be called multiple times in a row,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown,
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 99 should not be in listening state,
I/jxcore-log( 3149): 
I/jxcore-log( 3149): ok 100 should still not be in listening state
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # #stopAdvertisingAndListening can be called multiple times in a row
I/jxcore-log( 3149): ,
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 101 should not be in advertising state
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 102 should still not be in advertising state
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # setup
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # functions are run from a queue in the right order
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): # teardown
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): ok 103 call order must match
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): Tests Complete
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 3149): 
,I/jxcore-log( 3149): Toggling radios to false
I/jxcore-log( 3149): 
,I/chromium( 3149): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63),
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  819): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2cbc27f6 mBinding = false
,I/chromium( 3149): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothManagerService(  819): Message: 2
,D/BluetoothManagerService(  819): Sending off request.
D/WifiService(  819): setWifiEnabled: false pid=3149, uid=10265
E/WifiService(  819): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothAdapterState( 3209): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3209): Setting state to 13
,I/BluetoothAdapterState( 3209): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3209): onBluetoothDisable()
I/BluetoothAdapterState( 3209): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothManagerService(  819): Message: 60
,D/BluetoothManagerService(  819): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  819): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3209): onReceive
,D/BluetoothMapService( 3209): STATE_TURNING_OFF
D/BluetoothMapService( 3209): MAP Service closeService in
D/BluetoothMapMasInstance( 3209): MAP Service shutdown
V/BluetoothMapMasInstance( 3209): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3209): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3209): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3209): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3209): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3209): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3209): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3209): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,I/BtOppRfcommListener( 3209): stopping Accept Thread
E/BtOppRfcommListener( 3209): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 3209): BluetoothSocket listen thread finished
E/WifiStateMachine(  819): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  819): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  819): do suspend true
,I/jxcore-log( 3149): Radios toggled
I/jxcore-log( 3149): 
I/jxcore-log( 3149): ****TEST TOOK:  ms ****
I/jxcore-log( 3149): 
I/jxcore-log( 3149): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3149): 
,D/CommandListener(  353): Clearing all IP addresses on wlan0
V/NativeCrypto( 1487): Read error: ssl=0x9d1aa400: I/O error during system call, Connection timed out
V/NativeCrypto( 1487): SSL shutdown failed: ssl=0x9d1aa400: I/O error during system call, Broken pipe
D/ConnectivityService(  819): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
I/jxcore-log( 3149): Toggling radios to false
I/jxcore-log( 3149): 
I/ActivityManager(  819): Start proc 4221:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  819): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/BluetoothAdapterProperties( 3209): Scan Mode:20
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/BluetoothAdapterState( 3209): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
W/bt-btif ( 3209): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3209): L2CAP - PSM: 0x0019 not found for deregistration
D/btif_config_util( 3209): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-l2cap( 3209): L2CAP - PSM: 0x0017 not found for deregistration
E/WifiStateMachine(  819): scanCount==0 - aborting
,D/BluetoothManagerService(  819): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  819): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2cbc27f6 mBinding = false
D/BluetoothManagerService(  819): Message: 2
D/BluetoothManagerService(  819): Sending off request.
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  819): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiService(  819): setWifiEnabled: false pid=3149, uid=10265
D/WifiScanningService(  819): SCAN_AVAILABLE : 1
D/RttService(  819): SCAN_AVAILABLE : 1
D/WifiScanningService(  819): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiService(  819): Invoking mWifiStateMachine.setWifiEnabled
D/WifiScanningService(  819): DefaultState
E/native  (  819): do suspend true
D/RttService(  819): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterState( 3209): CURRENT_STATE=PENDING, MESSAGE = USER_TURN_ON, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 3209): CURRENT_STATE=PENDING: Alreadying turning off bluetooth... Ignoring USER_TURN_OFF...
,I/jxcore-log( 3149): Radios toggled
I/jxcore-log( 3149): 
,D/CommandListener(  353): Clearing all IP addresses on wlan0
,D/ConnectivityService(  819): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1070): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  819): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  819): Disconnected - quitting
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
,D/ConnectivityService(  819): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  819): MasterInitialState.processMessage what=3
D/Tethering(  819): MasterInitialState.processMessage what=3
,D/ConnectivityService(  819): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/PhoneInterfaceManager( 1324): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1324): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,E/WifiStateMachine(  819): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
D/TelephonyManager(  819): getDataEnabled: retVal=false
D/WifiNetworkAgent(  819): NetworkAgent: NetworkAgent channel lost
,E/GpsLocationProvider(  819): No APN found to select.
,D/PhoneInterfaceManager( 1324): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1324): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  819): getDataEnabled: retVal=false
,W/ContextImpl( 4221): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/GpsLocationProvider(  819): No APN found to select.
,D/BluetoothManagerService(  819): Message: 20
,D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a7acd82:true
,I/wpa_supplicant( 3212): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3212): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/ActivityManager(  819): Start proc 4248:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothManagerService(  819): Message: 30
,D/BluetoothManagerService(  819): Message: 30
,D/LocalBluetoothProfileManager( 4221): Adding local MAP profile
,D/BluetoothMap( 4221): Create BluetoothMap proxy object
,D/BluetoothManagerService(  819): Message: 30
,I/art     (  368): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 324us total 19.085ms
,D/BluetoothManagerService(  819): Message: 30
,D/LocalBluetoothProfileManager( 4221): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4221): finishStartingService: stopping service
,D/BluetoothInputDevice( 4221): Proxy object connected
D/HidProfile( 4221): Bluetooth service connected
,D/BluetoothPan( 4221): BluetoothPAN Proxy object connected
D/PanProfile( 4221): Bluetooth service connected
,D/BluetoothMap( 4221): Proxy object connected
,D/MapProfile( 4221): Bluetooth service connected
D/BluetoothMap( 4221): getConnectedDevices()
D/BluetoothMap( 4221): Bluetooth is Not enabled
,I/ActivityManager(  819): Killing 3860:com.google.android.configupdater/u0a42 (adj 15): empty #17
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 371us total 18.634ms
,I/art     (  368): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 329us total 14.121ms
,W/bt-btif ( 3209): ag scb idx 1 not allocated
E/bt-btif ( 3209): BTA AG is already disabled, ignoring ...
,W/bt-l2cap( 3209): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3209): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3209): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3209): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3209): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3209): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3209): RX termination
W/bt_userial( 3209): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3209): Leaving userial_read_thread()
,D/bt_userial( 3209): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3209): hw_epilog_process
I/bt_userial_vendor( 3209): device fd = 53 close
,D/AndroidRuntime( 4245): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4245): CheckJNI is OFF
,I/GKI_LINUX( 3209): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3209): GKI_exit_task 0 done
,I/GKI_LINUX( 3209): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3209): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
I/wpa_supplicant( 3212): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  819): InitialState.processMessage what=4
,D/HeadsetService( 3209): Received stop request...Stopping profile...
D/HeadsetStateMachine( 3209): Exit Disconnected: -1
E/WifiMonitor(  819): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
D/BluetoothHeadset(  819): Proxy object disconnected
D/BluetoothHeadset(  819): Proxy object disconnected
D/BluetoothHeadset(  819): Proxy object disconnected
D/BluetoothHeadset( 1324): Proxy object disconnected
D/BluetoothHeadset( 1070): Proxy object disconnected
D/A2dpService( 3209): Received stop request...Stopping profile...
D/A2dpStateMachine( 3209): Exit Disconnected: -1
,D/BluetoothA2dp(  819): Proxy object disconnected
D/BluetoothA2dp( 1070): Proxy object disconnected
,D/Tethering(  819): sendTetherStateChangedBroadcast 0, 0, 0
,D/HidService( 3209): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 3209): Stopping profile services that were post enabled
D/BluetoothInputDevice( 4221): Proxy object disconnected
D/HidProfile( 4221): Bluetooth service disconnected
D/BluetoothInputDevice( 1070): Proxy object disconnected
D/HeadsetStateMachine( 3209): Unbinding service...
W/BluetoothHeadsetServiceJni( 3209): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3209): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 3209): Received stop request...Stopping profile...
D/PanService( 3209): Received stop request...Stopping profile...
D/BluetoothPan( 4221): BluetoothPAN Proxy object disconnected
D/PanProfile( 4221): Bluetooth service disconnected
D/BluetoothPan( 1070): BluetoothPAN Proxy object disconnected
I/GKI_LINUX( 3209): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3209): GKI_exit_task 2 done
I/GKI_LINUX( 3209): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BtGatt.DebugUtils( 3209): handleDebugAction() action=null
,D/BtGatt.GattService( 3209): Received stop request...Stopping profile...
D/BtGatt.GattService( 3209): stop()
D/BtGatt.AdvertiseManager( 3209): advertise clients cleared
,D/BluetoothMapService( 3209): Received stop request...Stopping profile...
,D/BluetoothMapService( 3209): stop()
D/BluetoothMapEmailAppObserver( 3209): deinitObservers(),
D/BluetoothMapEmailAppObserver( 3209): removeReceiver()
D/BluetoothMap( 1070): Proxy object disconnected,
W/BluetoothHidServiceJni( 3209): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3209): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3209): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3209): Cleaning up Bluetooth Health Interface...
,D/BluetoothMap( 4221): Proxy object disconnected
,W/BluetoothHealthServiceJni( 3209): Cleaning up Bluetooth Health object
,D/MapProfile( 4221): Bluetooth service disconnected
W/BluetoothPanServiceJni( 3209): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3209): Cleaning up Bluetooth PAN callback object
,D/BluetoothMapService( 3209): MAP Service closeService in
,D/BluetoothAdapterState( 3209): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 3209): Setting state to 10
D/BluetoothMapService( 3209): cleanup()
I/BluetoothAdapterState( 3209): Bluetooth adapter state changed: 13-> 10
,D/BluetoothMapService( 3209): MAP Service closeService in
D/BluetoothManagerService(  819): Message: 60
D/BluetoothManagerService(  819): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  819): Broadcasting onBluetoothStateChange(false) to 17 receivers.
D/BluetoothHeadset(  819): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 3209): Entering OffState
,D/BluetoothA2dp( 1070): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1324): onBluetoothStateChange: up=false
D/BluetoothA2dp(  819): onBluetoothStateChange: up=false
,D/BluetoothMap( 4221): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 1070): onBluetoothStateChange: up=false
D/BluetoothHeadsetClient( 1070): onBluetoothStateChange: up=false
,E/BluetoothHeadsetClient( 1070): 
E/BluetoothHeadsetClient( 1070): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@215cedba
E/BluetoothHeadsetClient( 1070): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1070): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1070): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
,E/BluetoothHeadsetClient( 1070): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1070): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothHeadsetClient( 1070): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothPbap( 4221): onBluetoothStateChange: up=false
D/BluetoothMap( 1070): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 4221): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1070): onBluetoothStateChange: up=false
D/BluetoothHeadset(  819): onBluetoothStateChange: up=false
D/BluetoothAvrcpController( 1070): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1070): ,
E/BluetoothAvrcpController( 1070): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@1cdc146b
E/BluetoothAvrcpController( 1070): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1070): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1070): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1070): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
,E/BluetoothAvrcpController( 1070): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1070): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset(  819): onBluetoothStateChange: up=false
D/BluetoothA2dpSink( 1070): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1070): 
E/BluetoothA2dpSink( 1070): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@daf7bc8
E/BluetoothA2dpSink( 1070): ,	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1070): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1070): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1070): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1070): 	,at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1070): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothManagerService(  819): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  819): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/AndroidRuntime( 4245): Calling main entry com.android.commands.pm.Pm,
D/BluetoothManagerService(  819): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2cbc27f6 mBinding = false
D/BluetoothManagerService(  819): Sending unbind request.
D/BluetoothManagerService(  819): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapter( 1070): 731638126: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1070): 731638126: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  819): Killing 3149:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
D/BluetoothAdapter( 1070): 731638126: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3209): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3209): GKI_exit_task 1 done
I/GKI_LINUX( 3209): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3209): cleanupNative: return from cleanup
I/art     ( 3209): System.exit called, status: 0
I/AndroidRuntime( 3209): VM exiting with result code 0, cleanup skipped.
,W/PackageSettings(  819): Skipping PackageSetting{2be9aaeb com.example.hello/10273} due to missing metadata
,I/WindowState(  819): WIN DEATH: Window{34a47a9f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  819): Client connection lost with reason: 4
,W/ActivityManager(  819): Force removing ActivityRecord{e0409f4 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
,V/ActivityManager(  819): Display changed displayId=0
,I/ActivityManager(  819): Process com.android.bluetooth (pid 3209) has died
,I/ActivityManager(  819): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,W/ActivityManager(  819): Spurious death for ProcessRecord{23d88083 3149:com.test.thalitest/u0a265}, curProc for 3149: null
D/TaskPersister(  819): removeObsoleteFile: deleting file=28_task.xml
,I/Keyboard.Facilitator( 1222): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1222): run()
,W/Settings( 2647): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1070): Explicit concurrent mark sweep GC freed 54134(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 71MB/87MB, paused 2.555ms total 47.509ms
,W/Settings( 1710): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/InputReader(  819): Reconfiguring input devices.  changes=0x00000010
,I/Decoder ( 1222): createOrResetDecoder
,I/art     ( 1512): Explicit concurrent mark sweep GC freed 7969(539KB) AllocSpace objects, 2(51KB) LOS objects, 22% free, 26MB/34MB, paused 629us total 82.036ms
,D/JobSchedulerService(  819): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  819): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/ConfigService( 1487): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1222): run()
,W/InputMethodManagerService(  819): Got RemoteException sending setActive(false) notification to pid 3149 uid 10265
,I/Keyboard.Facilitator( 1222): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1222): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loading LM = contacts
,W/art     (  819): Suspending all threads took: 5.417ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1222): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1222): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1222): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1222): run()
I/StatsUtilsManager( 1222): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1222): shouldRecordStats() = Too Soon
,W/LocationOracleImpl( 1512): Best location was null
,D/StrictMode( 4248): StrictMode policy violation; ~duration=548 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4248): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4248): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4248): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4248): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4248): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 4248): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 4248): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=548 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4248): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4248): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4248): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=545 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4248): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4248): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4248): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4248): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4248): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4248): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 4248): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=538 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4248): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 4248): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=505 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4248): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4248): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4248): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoade,r.java:77)
D/StrictMode( 4248): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4248): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 4248): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 4248): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 4248): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 4248): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 4248): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 4248): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 4248): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 4248): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 4248): # via Binder call with stack:
D/StrictMode( 4248): android.os.StrictMode$LogStackTrace
D/StrictMode( 4248): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 4248): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 4248): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 4248): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 4248): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 4248): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 4248): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 4248): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 4248): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4248): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4248): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4248): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4248): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4248): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 4248): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4248): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4248): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4248): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4248): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4248): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4248): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4248): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4248): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4248): StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4248): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4248): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4248): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4248): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4248): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4248): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4248): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 4248): 	at com.google.p.j.a(PG:121)
D/StrictMode( 4248): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 4248): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 4248): 	at com.google.p.e.a(PG:170)
D/StrictMode( 4248): 	at com.google.p.e.b(PG:21)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4248): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4248): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4248): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4248): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4248): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4248): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4248): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4248): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4248): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4248): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
I/art     ( 1351): Explicit concurrent mark sweep GC freed 11676(653KB) AllocSpace objects, 11(1298KB) LOS objects, 31% free, 35MB/51MB, paused 1.167ms total 27.235ms
I/HotwordRecognitionRnr( 1512): Starting hotword detection.
I/MicrophoneInputStream( 1512): mic_starting com.google.android.apps.gsa.speech.audio.u@540d715
W/com.google.a.a.a.b.a( 4248): Application name is not set. Call Builder#setApplicationName.
I/AudioFlinger(  357): AudioFlinger's thread 0xb4cd7000 ready to run
I/art     (  819): Explicit concurrent mark sweep GC freed 30410(1906KB) AllocSpace objects, 4(252KB) LOS objects, 32% free, 33MB/49MB, paused 8.237ms total 212.077ms
I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1512): mic_started com.google.android.apps.gsa.speech.audio.u@540d715
D/audio_hw_primary(  357): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  357): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  357): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  357): enable_snd_device: snd_device(55: voice-rec-mic)
D/audio_hw_primary(  357): enable_audio_route: apply and update mixer path: audio-record
,D/BluetoothManagerService(  819): Message: 20
D/BluetoothManagerService(  819): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@111bc795:true
D/AuthorizationBluetoothService( 1487): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/art     ( 4245): System.exit called, status: 0
I/AndroidRuntime( 4245): VM exiting with result code 0.
,I/ActivityManager(  819): Start proc 4306:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,I/HotwordWorker( 1512): onReady
,D/Launcher.Workspace( 1351): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1351): 11683562 - stripEmptyScreens()
,I/MusicStore( 4306): Database version: 120
,E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660019987
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/ResourcesManager( 4306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
,V/JNIHelp ( 4306): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4306): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4306): GMSCore installation verified
,I/ConfigStore( 4306): Config Database version: 1
,E/SQLiteDatabase( 4306): Failed to open database '/data/data/com.google.android.music/databases/config.db'.
E/SQLiteDatabase( 4306): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4306): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4306): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4306): 	at com.google.android.music.store.ConfigStore.getDatabase(ConfigStore.java:64)
E/SQLiteDatabase( 4306): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 4306): 	at com.google.android.music.store.ConfigContentProvider.query(ConfigContentProvider.java:129)
E/SQLiteDatabase( 4306): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4306): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4306): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 4306): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 4306): 	at com.google.android.music.utils.ConfigCache.get(ConfigCache.java:136)
E/SQLiteDatabase( 4306): 	at com.google.android.music.utils.ConfigUtils.getString(ConfigUtils.java:673)
E/SQLiteDatabase( 4306): 	at com.google.android.music.utils.ConfigUtils.getBoolean(ConfigUtils.java:709)
E/SQLiteDatabase( 4306): 	at com.google.android.music.utils.ConfigUtils.isPlayLoggingEnabled(ConfigUtils.java:399)
E/SQLiteDatabase( 4306): 	at com.google.android.music.eventlog.MusicEventLogger.<init>(MusicEventLogger.java:152)
E/SQLiteDatabase( 4306): 	at com.google.android.music.eventlog.MusicEventLogger.getInstance(MusicEventLogger.java:270)
E/SQLiteDatabase( 4306): 	at com.google.android.music.MusicApplication.onCreate(MusicApplication.java:87)
E/SQLiteDatabase( 4306): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
E/SQLiteDatabase( 4306): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
E/SQLiteDatabase( 4306): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
E/SQLiteDatabase( 4306): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
E/SQLiteDatabase( 4306): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4306): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4306): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4306): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4306): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4306): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4306): 	at com.android.internal.os.,ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4306): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 4306): FATAL EXCEPTION: main
E/AndroidRuntime( 4306): Process: com.google.android.music:main, PID: 4306
E/AndroidRuntime( 4306): java.lang.RuntimeException: Unable to create application com.google.android.music.MusicApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4306): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4556)
E/AndroidRuntime( 4306): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
E/AndroidRuntime( 4306): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
E/AndroidRuntime( 4306): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4306): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4306): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4306): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4306): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4306): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4306): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4306): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4306): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4306): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4306): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4306): 	at com.google.android.music.store.ConfigStore.getDatabase(ConfigStore.java:64)
E/AndroidRuntime( 4306): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 4306): 	at com.google.android.music.store.ConfigContentProvider.query(ConfigContentProvider.java:129)
E/AndroidRuntime( 4306): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AndroidRuntime( 4306): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AndroidRuntime( 4306): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/AndroidRuntime( 4306): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/AndroidRuntime( 4306): 	at com.google.android.music.utils.ConfigCache.get(ConfigCache.java:136)
E/AndroidRuntime( 4306): 	at com.google.android.music.utils.ConfigUtils.getString(ConfigUtils.java:673)
E/AndroidRuntime( 4306): 	at com.google.android.music.utils.ConfigUtils.getBoolean(ConfigUtils.java:709)
E/AndroidRuntime( 4306): 	at com.google.android.music.utils.ConfigUtils.isPlayLoggingEnabled(ConfigUtils.java:399)
E/AndroidRuntime( 4306): 	at com.googl,e.android.music.eventlog.MusicEventLogger.<init>(MusicEventLogger.java:152)
E/AndroidRuntime( 4306): 	at com.google.android.music.eventlog.MusicEventLogger.getInstance(MusicEventLogger.java:270)
E/AndroidRuntime( 4306): 	at com.google.android.music.MusicApplication.onCreate(MusicApplication.java:87)
E/AndroidRuntime( 4306): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
E/AndroidRuntime( 4306): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
E/AndroidRuntime( 4306): 	... 9 more
E/DropBoxManagerService(  819): Can't write: system_app_crash
E/DropBoxManagerService(  819): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  819): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  819): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  819): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  819): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  819): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  819): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  819): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  819): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  819): 	... 5 more
,D/OpenGLRenderer(  819): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   (  819): Validating map...
,I/OpenGLRenderer(  819): Initialized EGL, version 1.4
,D/OpenGLRenderer(  819): Enabling debug mode 0
,I/HotwordDetector( 1512): Closing mic
I/MicrophoneInputStream( 1512): mic_close com.google.android.apps.gsa.speech.audio.u@540d715
,E/Search.SharedPreferencesProto( 1512): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  819): Killing 3610:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,D/audio_hw_primary(  357): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  357): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  357): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 1512): Hotword detection finished
,I/HotwordRecognitionRnr( 1512): Stopping hotword detection.
,E/native  ( 1222): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1222): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1222): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1222): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1222): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1222): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1222): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1222): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/kickstart(  870): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
E/kickstart(  870): ERROR: function: sahara_main:1143 Sahara protocol error
,E/kickstart(  870): ERROR: function: main:268 Uploading  Image using Sahara protocol failed
,I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,I/ConfigService( 1487): onDestroy
,E/QMI_FW  (  819): xport_send: Sendto failed for port 3840
E/LocSvc_api_v02(  819): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660019987
E/LocSvc_IzatApiV02(  819): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0

```
