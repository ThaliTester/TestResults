#### Test 51790364c93db41_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1489): Explicit concurrent mark sweep GC freed 26188(1400KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.446ms total 59.127ms
D/Finsky  ( 2701): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2701): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2701): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3164): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3164): CheckJNI is OFF
D/AndroidRuntime( 3164): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  824): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  824): addAppToken: AppWindowToken{e1a7996 token=Token{2bec50b1 ActivityRecord{1caef758 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
V/WindowManager(  824): Adding window Window{581bfb3 u0 Starting com.test.thalitest} at 3 of 8 (after Window{244cfac0 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1532): Closing mic
I/MicrophoneInputStream( 1532): mic_close com.google.android.apps.gsa.speech.audio.u@21f86a1a
D/AndroidRuntime( 3164): Shutting down VM
D/audio_hw_primary(  361): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  361): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  361): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1532): Stopping hotword detection.
I/HotwordRecognitionRnr( 1532): Hotword detection finished
I/ActivityManager(  824): Start proc 3179:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
W/GCoreFlp( 1747): No location to return for getLastLocation()
I/ActivityManager(  824): Killing 2660:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/ActivityManager(  824): Killing 2791:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/WebViewFactory( 3179): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659663635
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/LibraryLoader( 3179): Time to load native libraries: 4 ms (timestamps 1658-1662)
,I/LibraryLoader( 3179): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3179): Binding Chromium to main looper Looper (main, tid 1) {3fb7ef1d}
,I/LibraryLoader( 3179): Expected native library version number "",actual native library version number ""
I/chromium( 3179): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3179): Initializing chromium process, singleProcess=true,
,W/art     ( 3179): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3179): ApplicationContext is null in ApplicationStatus
,W/chromium( 3179): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.,
,I/kickstart(  874): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  874): STATUS: Wrote to /sys/power/wake_lock
W/chromium( 3179): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3179): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
,E/libEGL  ( 3179): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3179): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/kickstart(  874): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  874): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,D/BluetoothManagerService(  824): Message: 20
,D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3879fba3:true
,D/BluetoothAdapter( 3179): 801928588: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3179): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3179): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3179): CordovaWebView is running on device made by: motorola
,W/art     ( 3179): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3179): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3179): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3179): Validating map...
,V/WindowManager(  824): Adding window Window{30b11393 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{581bfb3 u0 Starting com.test.thalitest})
,W/chromium( 3179): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3179): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3179): Enabling debug mode 0
,I/ActivityManager(  824): Displayed com.test.thalitest/.MainActivity: +987ms (total +1m49s463ms)
,I/Keyboard.Facilitator( 1209): onFinishInput()
,W/BindingManager( 3179): Cannot call determinedVisibility() - never saw a connection for the pid: 3179
,D/JsMessageQueue( 3179): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3179): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576401152
,D/JX-Cordova( 3179): jxcore cordova android initializing
,I/kickstart(  874): STATUS: Received file 'm9kefs1'
I/kickstart(  874): STATUS: 950272 bytes transferred in 0.998806 seconds
I/kickstart(  874): STATUS: Successfully downloaded files from target 
I/kickstart(  874): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  874): STATUS: Sahara protocol completed,
,W/jxcore-log( 3179): Initializing JXcore engine
W/jxcore-log( 3179): JXcore engine is ready
,W/jxcore-log( 3179): Starting JXcore engine
,W/.test.thalitest( 3179): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[13028]" dev="sockfs" ino=13028 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3179): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3179): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11830]" dev="sockfs" ino=11830 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3179): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19222]" dev="sockfs" ino=19222 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3179): Platform android
W/jxcore-log( 3179): 
W/jxcore-log( 3179): Process ARCH arm
W/jxcore-log( 3179): 
,I/jxcore-log( 3179): JXcore Cordova bridge is ready!
I/jxcore-log( 3179): 
W/jxcore-log( 3179): JXcore engine is started
,I/Choreographer( 3179): Skipped 129 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3179): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3179): Toggling radios to true
I/jxcore-log( 3179): 
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  824): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  824): Message: 1
D/BluetoothManagerService(  824): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  824): New client listening to asynchronous messages
,D/WifiService(  824): setWifiEnabled: true pid=3179, uid=10265
E/WifiService(  824): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  357): Softap fwReload - Ok
,I/jxcore-log( 3179): Radios toggled
I/jxcore-log( 3179): 
,D/CommandListener(  357): Setting iface cfg
,D/CommandListener(  357): Trying to bring down wlan0
,D/CommandListener(  357): Clearing all IP addresses on wlan0
,I/ActivityManager(  824): Start proc 3235:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
E/WifiMonitor(  824): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/WifiMonitor(  824): startMonitoring(wlan0) with mConnected = false
E/WifiHW  (  824): Unable to open connection to supplicant on "@android:wpa_wlan0": Permission denied
,I/ActivityManager(  824): Start proc 3253:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,W/ResourcesManager( 3235): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3248): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3248): rfkill: Cannot open RFKILL control device
,I/art     (  824): Explicit concurrent mark sweep GC freed 17059(861KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.603ms total 72.264ms
,D/AdapterServiceConfig( 3235): Adding HeadsetService
D/AdapterServiceConfig( 3235): Adding A2dpService
D/AdapterServiceConfig( 3235): Adding HidService
,D/AdapterServiceConfig( 3235): Adding HealthService
D/AdapterServiceConfig( 3235): Adding PanService
,D/AdapterServiceConfig( 3235): Adding GattService
D/AdapterServiceConfig( 3235): Adding BluetoothMapService
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d10b94:true
D/BluetoothAdapterState( 3235): make
,I/bluedroid( 3235): init
I/BluetoothAdapterState( 3235): Entering OffState
,I/bte_conf( 3235): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3235): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3235): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3235): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3235): get_profile_interface socket
I/bluedroid( 3235): get_profile_interface map_client
I/GKI_LINUX( 3235): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3235): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  824): Bluetooth Adapter name changed to Nexus 6
D/BluetoothAdapterProperties( 3235): Name is: Nexus 6
D/BluetoothManagerService(  824): Stored Bluetooth name: Nexus 6
,D/BluetoothManagerService(  824): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  824): Message: 40
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3235): config_hci_snoop_log
,D/BluetoothManagerService(  824): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  824): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3235): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3235): Setting state to 11
I/BluetoothAdapterState( 3235): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  824): Message: 60
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  824): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3235): make
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,D/BluetoothAdapterService( 3235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3999d592
,D/HeadsetService( 3235): Received start request. Starting profile...
I/BluetoothAdapterState( 3235): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/BluetoothHeadsetServiceJni( 3235): classInitNative: succeeds
D/HeadsetStateMachine( 3235): make
,D/HeadsetStateMachine( 3235): max_hf_connections = 1
I/bluedroid( 3235): get_profile_interface handsfree
,D/HeadsetStateMachine( 3235): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3999d592
,D/BluetoothA2dp(  824): Proxy object connected
D/BluetoothA2dp( 1061): Proxy object connected
,D/A2dpService( 3235): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3235): classInitNative: succeeds
I/bluedroid( 3235): get_profile_interface avrcp
,E/RemoteController( 3235): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3235): classInitNative: succeeds
D/A2dpStateMachine( 3235): make
,I/bluedroid( 3235): get_profile_interface a2dp
,I/GKI_LINUX( 3235): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3235): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3235): classInitNative: succeeds
D/BluetoothAdapterService( 3235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3999d592
,D/BluetoothInputDevice( 1061): Proxy object connected
D/HidService( 3235): Received start request. Starting profile...
I/bluedroid( 3235): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3235): classInitNative: succeeds
D/BluetoothAdapterService( 3235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3999d592
,D/HealthService( 3235): Received start request. Starting profile...
,I/bluedroid( 3235): get_profile_interface health
I/BluetoothPanServiceJni( 3235): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3999d592
,D/BluetoothPan( 1061): BluetoothPAN Proxy object connected,
D/PanService( 3235): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3235): initializeNative(L110): pan
I/bluedroid( 3235): get_profile_interface pan
I/BtGatt.JNI( 3235): classInitNative(L873): classInitNative: Success!
,D/BluetoothAdapterService( 3235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3999d592
D/BtGatt.DebugUtils( 3235): handleDebugAction() action=null
D/BtGatt.GattService( 3235): Received start request. Starting profile...
D/BtGatt.GattService( 3235): start()
I/bluedroid( 3235): get_profile_interface gatt
D/BluetoothAdapterService( 3235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3999d592
,D/BtGatt.AdvertiseManager( 3235): advertise manager created
,D/BluetoothAdapterService( 3235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3999d592,
,D/BluetoothMap( 1061): Proxy object connected
,D/BluetoothMapService( 3235): Received start request. Starting profile...
D/BluetoothMapService( 3235): start()
,D/BluetoothMapEmailSettingsLoader( 3235): Found 0 applications,
D/BluetoothMapEmailAppObserver( 3235): createReceiver()
D/BluetoothMapEmailAppObserver( 3235): initObservers(),
,D/BluetoothMapEmailAppObserver( 3235): getEnabledAccountItems(),
,D/HeadsetStateMachine( 3235): Proxy object connected
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0,
D/HeadsetPhoneState( 3235): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3235): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3235): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3235): enable
I/bt_hci_bdroid( 3235): init
I/GKI_LINUX( 3235): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3235): btu_task pending for preload complete event
,I/bt_vendor( 3235): init
I/bt_vnd_conf( 3235): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3235): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,D/bt_userial( 3235): userial_init
,I/ActivityManager(  824): Start proc 3297:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  824): Killing 2829:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/bt_userial_vendor( 3235): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3235): device fd = 53 open,
D/bt_userial( 3235): Entering userial_read_thread(),
,I/bt_hwcfg( 3235): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3235): Chipset BCM4354A2
D/bt_hwcfg( 3235): Target name = [BCM4354A2]
,I/bt_hwcfg( 3235): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/ActivityManager(  824): Start proc 3320:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/art     (  372): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 459us total 17.207ms
,I/art     (  372): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 287us total 16.010ms
,D/Tethering(  824): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  824): Killing 2759:com.google.android.gm/u0a78 (adj 15): empty #17
,I/art     (  372): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 370us total 11.157ms
,I/wpa_supplicant( 3248): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3248): Could not read interface p2p-dev-wlan0 flags: No such device
,I/bt_hwcfg( 3235): bt vendor lib: set UART baud 115200,
D/bt_hwcfg( 3235): Settlement delay -- 100 ms
I/bt_hwcfg( 3235): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3235): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg( 3235): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3235): vendor lib fwcfg completed
I/bt-btu  ( 3235): btu_task received preload complete event
,I/ActivityManager(  824): Killing 2353:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/        ( 3235): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3235): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 3235): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3235): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3235): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3235): BTE_InitTraceLevels -- TRC_A2D
,I/        ( 3235): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3235): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3235): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3235): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3235): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3235): BTE_InitTraceLevels -- TRC_GATT
,I/        ( 3235): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3235): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3235): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3235): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2dae085 
E/bt-btm  ( 3235): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2dae085 
,D/WifiConfigStore(  824): Loading config and enabling all networks 
D/BluetoothAdapterProperties( 3235): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3235): Calling BTA_HhEnable
E/bt-btif ( 3235): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3235): Address is:F8:CF:C5:D9:E5:61
,W/bt-btm  ( 3235): Stopping oneshot timer
D/BluetoothAdapterProperties( 3235): Name is: Nexus 6,
D/BluetoothManagerService(  824): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  824): Stored Bluetooth name: Nexus 6
,D/WifiService(  824): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2291bd8c}
,E/WifiConfigStore(  824): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  824): Start proc 3339:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothAdapterProperties( 3235): Scan Mode:20
D/BluetoothAdapterProperties( 3235): Discoverable Timeout:120
,D/bte_conf( 3235): Device ID record 1 : primary
D/bte_conf( 3235):   vendorId            = 000f
D/bte_conf( 3235):   vendorIdSource      = 0001
D/bte_conf( 3235):   product             = 1200
,D/bte_conf( 3235):   version             = 1436
D/bte_conf( 3235):   clientExecutableURL = 
,D/bte_conf( 3235):   serviceDescription  = 
D/bte_conf( 3235):   documentationURL    = 
D/bte_conf( 3235): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3235): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothPanServiceJni( 3235): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 3235): ScanMode =  20
D/BluetoothAdapterProperties( 3235): State =  11
D/BluetoothAdapterProperties( 3235): Setting state to 12
I/BluetoothAdapterState( 3235): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  824): Message: 60
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  824): Broadcasting onBluetoothStateChange(true) to 13 receivers.
I/BluetoothAdapterState( 3235): Entering On State
D/BluetoothA2dp( 1061): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3235): Scan Mode:21
,D/BluetoothAdapterProperties( 3235): Discoverable Timeout:120
D/BluetoothInputDevice( 1061): onBluetoothStateChange: up=true
D/BluetoothAvrcpController( 1061): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1061): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
W/Settings( 2629): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothPan( 1061): onBluetoothStateChange(on) call bindService
D/WifiNative-HAL(  824): Setting external_sim to 1
D/WifiStateMachine(  824): Setting OUI to 92-68-C3
I/WifiNative-HAL(  824): startHal
D/wifi    (  824): setting scan oui 0xa0b70850
,D/WifiHAL (  824): Sending mac address OUI
D/BluetoothA2dp(  824): onBluetoothStateChange: up=true
D/BluetoothMap( 1061): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1272): onBluetoothStateChange: up=true
D/BluetoothManagerService(  824): Creating new ProfileServiceConnections object for profile: 1
,D/BluetoothA2dpSink( 1061): onBluetoothStateChange: up=true
,E/BluetoothA2dpSink( 1061): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothHeadset(  824): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1061): onBluetoothStateChange: up=true
D/BluetoothHeadset(  824): onBluetoothStateChange: up=true
,D/BluetoothHeadsetClient( 1061): onBluetoothStateChange: up=true
E/BluetoothHeadsetClient( 1061): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
,D/BluetoothHeadset(  824): onBluetoothStateChange: up=true
D/BluetoothManagerService(  824): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  824): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  824): Message: 40
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3235): onReceive
D/BluetoothMapService( 3235): STATE_ON
,D/BluetoothMapMasInstance( 3235): Map Service startRfcommSocketListener
E/WifiStateMachine(  824): cancelDelayedScan -> 1
,D/BluetoothMapMasInstance( 3235): MAS initSocket()
,W/CommandListener(  357): Failed to retrieve HW addr for p2p0 (No such device)
,D/WifiScanningService(  824): SCAN_AVAILABLE : 3
D/RttService(  824): SCAN_AVAILABLE : 3
D/CommandListener(  357): Setting iface cfg
D/WifiScanningService(  824): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  824): startHal
E/bt_h4   ( 3235): vendor lib postload completed
D/wifi    (  824): getting scan capabilities on interface[0] = 0xa0b70850
D/WifiHAL (  824): Creating message to get scan capablities; iface = 5
D/WifiHAL (  824): In GetCapabilities::handleResponse
D/WifiHAL (  824): Id = 0, subcmd = 0, len = 28, expected len = 32
,E/WifiP2pService(  824): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiScanningService(  824): StartedState
D/WifiMonitor(  824): startMonitoring(p2p0) with mConnected = true
D/RttService(  824): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3235): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3235): Accepting socket connection...,
,I/wpa_supplicant( 3248): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  824): p2pGetDeviceAddress
,D/WifiNative-HAL(  824): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,E/native  (  824): do suspend false
,D/BluetoothManagerService(  824): Message: 400
D/BluetoothHeadset( 1272): Proxy object connected
,D/BluetoothManagerService(  824): Message: 400
D/BluetoothHeadset(  824): Proxy object connected
D/BluetoothManagerService(  824): Message: 400
D/BluetoothHeadset( 1061): Proxy object connected
D/BluetoothManagerService(  824): Message: 400
D/BluetoothHeadset(  824): Proxy object connected
D/BluetoothManagerService(  824): Message: 400
D/BluetoothHeadset(  824): Proxy object connected
,D/StrictMode( 3339): StrictMode policy violation; ~duration=190 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3339): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3339): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3339): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3339): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3339): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3339): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3339): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3339): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3339): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3339): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3339): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3339): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3339): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3339): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3339): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3339): StrictMode policy violation; ~duration=190 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3339): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3339): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3339): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3339): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3339): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3339): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3339): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3339): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3339): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3339): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3339): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3339): StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3339): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3339): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3339): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3339): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3339): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3339): 	at java.lang.Runtime.loadLibrary(Runtime.java:360),
D/StrictMode( 3339): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3339): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3339): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3339): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3339): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3339): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3339): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3339): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3339): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3339): StrictMode policy violation; ~duration=185 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3339): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3339): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3339): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3339): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3339): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3339): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3339): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3339): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3339): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3339): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3339): StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3339): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3339): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3339): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3339): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3339): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3339): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3339): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3339): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3339): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3339): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3339): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3339): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3339): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3339): StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3339): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3339): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3339): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3339): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3339): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3339): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3339): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3339): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3339): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3339): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3339): # via Binder call with stack:
D/StrictMode( 3339): android.os.StrictMode$LogStackTrace
D/StrictMode( 3339): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3339): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3339): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3339): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3339): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3339): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3339): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3339): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/S,trictMode( 3339): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3339): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3339): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3339): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3339): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3339): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3339): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3339): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3339): StrictMode policy violation; ~duration=48 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3339): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3339): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3339): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3339): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3339): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3339): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3339): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3339): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3339): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3339): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3339): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3339): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3339): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3339): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3339): StrictMode policy violation; ~duration=47 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3339): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3339): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3339): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3339): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3339): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3339): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3339): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3339): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3339): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3339): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3339): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3339): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3339): StrictMode policy violation; ~duration=47 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3339): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3339): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3339): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3339): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3339): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3339): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3339): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3339): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3339): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3339): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3339): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3339): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3339): StrictMode policy violation; ~duration=46 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3339): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3339): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3339): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3339): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3339): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3339): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3339): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3339): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3339): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3339): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3339): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3339): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3339): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3339): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3339): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3339): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3339): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3339): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3339): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3339): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3339): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,W/com.google.a.a.a.b.a( 3339): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  824): Message: 20
,D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@175191cb:true
,I/ActivityManager(  824): Killing 2864:com.google.android.music:main/u0a66 (adj 15): empty #17,
,D/AuthorizationBluetoothService( 1489): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  824): Message: 20
,D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1de06f43:true
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3235): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1489): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LocalBluetoothProfileManager( 3320): Adding local A2DP profile
,D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3235): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3320): Adding local HEADSET profile
I/BtOppRfcommListener( 3235): Accept thread started.
,D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): Message: 30
,D/LocalBluetoothProfileManager( 3320): Adding local MAP profile
,D/BluetoothMap( 3320): Create BluetoothMap proxy object
,D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): Message: 30
,D/LocalBluetoothProfileManager( 3320): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3320): finishStartingService: stopping service
,D/BluetoothA2dp( 3320): Proxy object connected
D/A2dpProfile( 3320): Bluetooth service connected
,D/BluetoothInputDevice( 3320): Proxy object connected
D/HidProfile( 3320): Bluetooth service connected
,D/BluetoothPan( 3320): BluetoothPAN Proxy object connected
,D/PanProfile( 3320): Bluetooth service connected
,D/BluetoothMap( 3320): Proxy object connected
D/MapProfile( 3320): Bluetooth service connected
D/BluetoothMap( 3320): getConnectedDevices()
,D/BluetoothPbap( 3320): Proxy object connected
D/PbapServerProfile( 3320): Bluetooth service connected
,D/BluetoothManagerService(  824): Message: 400
,D/BluetoothHeadset( 3320): Proxy object connected
,D/HeadsetProfile( 3320): Bluetooth service connected
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/jxcore-log( 3179): Got Device Bluetooth address: F8:CF:C5:D9:E5:61,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): my name is : motorola-Nexus 6_PT7950
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): attempting to connect to test coordinator
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): check test folder
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): found test : ./testFindPeers.js
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): found test : ./testReConnect.js
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): found test : ./testSendData.js
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): Test app app.js loaded
I/jxcore-log( 3179): 
,I/Choreographer( 3179): Skipped 134 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/chromium( 3179): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3248): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  824): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  824):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  824):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  824): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3,
E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  824): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  824): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  824): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  824): will read network variables netId=0
,E/WifiStateMachine(  824): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  824): will read network variables netId=0
,I/wpa_supplicant( 3248): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3248): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3248): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3248): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  824): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} },
E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  357): Setting iface cfg
,E/WifiStateMachine(  824): Start Dhcp Watchdog 1
,E/WifiStateMachine(  824):  WifiLinkLayerStats: 
E/WifiStateMachine(  824):  my bss beacon rx: 1
E/WifiStateMachine(  824):  RSSI mgmt: -44
E/WifiStateMachine(  824):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  824):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  on_time : 0 tx_time=58 rx_time=112 scan_time=0
,D/ConnectivityService(  824): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  824): do suspend false,
,E/WifiStateMachine(  824): scanCount==0 - aborting
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/dhcpcd  ( 3383): version 5.5.6 starting
,I/dhcpcd  ( 3383): wlan0: rebinding lease of 192.168.1.110
,I/dhcpcd  ( 3383): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 3383): wlan0: leased 192.168.1.110 for 86400 seconds
,D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  824): Adding iface wlan0 to network 100
,E/WifiStateMachine(  824): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  824): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  824): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  824): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  824): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  824): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  824): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  824): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  824): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  824):    accepting network in place of null,
D/ConnectivityService(  824): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  824): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  824): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100],
,D/CSLegacyTypeTracker(  824): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true,
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
,D/ConnectivityManager.CallbackHandler( 1061): CM callback handler got msg 524290
,D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,D/Tethering(  824): MasterInitialState.processMessage what=3
V/BackupManagerService(  824): Scheduling immediate backup pass
E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  824): getDataEnabled: retVal=false
,I/ActivityManager(  824): Start proc 3420:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,V/BackupManagerService(  824): Running a backup pass
,V/BackupManagerService(  824): clearing pending backups
,V/PerformBackupTask(  824): Beginning backup of 14 targets
,E/GpsLocationProvider(  824): No APN found to select.
,D/PerformBackupTask(  824): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  824): doBackup() invoked
,D/AlarmManagerService(  824): Setting time of day to sec=1448458103
W/AlarmManagerService(  824): Unable to set rtc to 1448458103: Invalid argument
,I/PMBA    (  824): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 25 Nov 2015 13:28:23 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448458103646], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448458103466]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Validated
D/ConnectivityService(  824): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  824): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  824): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  824): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  824): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1061): CM callback handler got msg 524290
,D/GpsLocationProvider(  824): NTP server returned: 1448458103633 (Wed Nov 25 14:28:23 GMT+01:00 2015) reference: 150384 certainty: 21 system time offset: -47
,I/BackupRestoreController(  824): Getting widget state for user: 0
,W/GmsBackupTransport( 1747): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1747): starting performBackup for @pm@
,V/GmsBackupTransport( 1747): performBackup done for @pm@
,I/MusicStore( 3420): Database version: 120
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3253): [331] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 8816(440KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 939us total 21.888ms
,E/Auth.Api.Credentials( 1777): [CredentialSyncAdapter] Unknown sync event.
,I/art     (  824): Explicit concurrent mark sweep GC freed 46371(2MB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 2.079ms total 59.009ms
,W/GLSActivity( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1489): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1489): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1489): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1489): 	at android.os.Binder.execTransact(Binder.java:446)
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
,D/BackupManagerService(  824): Now staging backup of com.google.android.talk
,W/DriveInitializer( 1777): Background init thread started
,D/BackupManagerService(  824): Now staging backup of com.google.android.dialer
,W/DriveInitializer( 1777): Awaiting to be initialized
,D/BackupManagerService(  824): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  824): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  824): Now staging backup of com.google.android.gm
,D/BackupManagerService(  824): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  824): Now staging backup of com.android.nfc
,D/BackupManagerService(  824): Now staging backup of com.google.android.apps.genie.geniewidget
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
D/BackupManagerService(  824): Now staging backup of com.google.android.marvin.talkback
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BackupManagerService(  824): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  824): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  824): Now staging backup of com.android.vending
,W/ExperimentUpdateService( 3253): [331] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
D/BackupManagerService(  824): Now staging backup of android
,W/ExperimentUpdateService( 3253): [331] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3253): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3253): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3253): 	at com.a.a.k.run(SourceFile:110)
,D/BackupManagerService(  824): Now staging backup of com.google.android.googlequicksearchbox
,W/ResourcesManager( 3420): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3420): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GmsBackupTransport( 1747): Next backup will happen in 43199900 millis.
,I/BackupManagerService(  824): Backup pass finished.
,V/JNIHelp ( 3420): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/DriveInitializer( 1777): Background init thread ended
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
V/GoogleAuthProtoRequest( 3253): [332] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2949): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at blb.a(PG:3937)
E/HttpOperation( 2949): 	at czp.a(PG:18188)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 12 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 14 more
,I/ProviderInstaller( 3420): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 3420): GMSCore installation verified
,I/ConfigStore( 3420): Config Database version: 1
,W/ExperimentUpdateService( 3253): [332] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3253): [332] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3253): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3253): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3253): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2949): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at hec.a(PG:42)
E/HttpOperation( 2949): 	at hee.a(PG:102)
E/HttpOperation( 2949): 	at czr.a(PG:65)
E/HttpOperation( 2949): 	at kka.a(PG:108)
E/HttpOperation( 2949): 	at czp.a(PG:19176)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 15 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 17 more
,E/ExperimentLoader( 2949): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): 	at jdm.a(PG:82)
E/ExperimentLoader( 2949): 	at jcs.o(PG:406)
E/ExperimentLoader( 2949): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2949): 	at jcs.i(PG:143)
E/ExperimentLoader( 2949): 	at hec.a(PG:42)
E/ExperimentLoader( 2949): 	at hee.a(PG:102)
E/ExperimentLoader( 2949): 	at czr.a(PG:65)
E/ExperimentLoader( 2949): 	at kka.a(PG:108)
E/ExperimentLoader( 2949): 	at czp.a(PG:19176)
E/ExperimentLoader( 2949): 	at czp.a(PG:9081)
E/ExperimentLoader( 2949): 	at czq.run(PG:1686)
E/ExperimentLoader( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2949): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2949): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2949): 	at jdm.a(PG:77)
E/ExperimentLoader( 2949): 	... 15 more
E/ExperimentLoader( 2949): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2949): 	at fal.a(PG:38)
E/ExperimentLoader( 2949): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2949): 	... 17 more
,V/KeepSync( 3297): Connecting to GoogleApiClient
,I/MediaRouter( 3420): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3420): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3420): type=WIFI subType= reason=null isConnected=true
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,I/NetworkMonitor( 3420): type=WIFI subType= reason=null isConnected=true
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  824): Start proc 3484:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GHttpClientFactory( 3420): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3420): Using platform SSLCertificateSocketFactory
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 36321, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,E/ClientConnectionOperation( 1777): Handling authorization failure
E/ClientConnectionOperation( 1777): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1777): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1777): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1777): 	... 7 more
,V/KeepSync( 3297): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,D/SprintDMReceiver( 3484): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,D/SprintDMHelper( 3484): simOperator:  IMSI: null
D/SprintDMReceiver( 3484): Not Sprint UICC, don't do anything.
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 16998(1000KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 818us total 23.589ms
,I/ActivityManager(  824): Start proc 3504:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/SystemUpdateService( 1777): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1777): onCreate
,D/SystemUpdateService( 1777): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1777): active receiver: enabled
,I/SystemUpdateService( 1777): showing system update notification
,I/ValidateNoPeople(  824): skipping global notification
,V/SystemUpdateService( 1777): retry (wakeup: false) in 3599975 ms
,I/iu.SyncManager( 1777): SYNC; picasa accounts
,D/NetworkLogImpl( 1777): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1777): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/SystemUpdateService( 1777): onDestroy
,I/iu.UploadsManager( 1777): num queued entries: 0
,I/iu.UploadsManager( 1777): num updated entries: 0
,I/iu.SyncManager( 1777): NEXT; no task
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  824): Start proc 3533:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3297): IOException
E/KeepSync( 3297): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3297): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3297): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3297): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3297): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3297): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3297): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3297): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3297): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3297): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3297): 	... 10 more
W/KeepSync( 3297): Sync result 2
,W/Kids    ( 1777): [AccountUtils] Account not ready
W/Kids    ( 1777): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1777): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1777): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1777): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1777): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1777): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1777): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1777): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1777): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1777): 	at java.lang.Thread.run(Thread.java:818)
,I/Babel   ( 2629): connection state changed from DISCONNECTED to CONNECTED
,I/ActivityManager(  824): Killing 2203:com.android.providers.calendar/u0a3 (adj 15): empty #17
D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 36322, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/art     (  824): Explicit concurrent mark sweep GC freed 27638(1292KB) AllocSpace objects, 5(120KB) LOS objects, 32% free, 33MB/49MB, paused 5.122ms total 57.251ms
,D/GCM     ( 1489): Connected
,D/GCM     ( 1489): Message class com.google.f.a.a.p
,I/GAv4    ( 3533): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3533):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3533):   adb logcat -s GAv4
,I/VacuumService( 1489): Vacuum at: now=1448458104654 tag=VacuumService
,W/GAv4    ( 3533): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GoogleURLConnFactory( 1489): Using platform SSLCertificateSocketFactory
,W/GAv4    ( 3533): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3533): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/GAV2    ( 3504): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/WebViewFactory( 3533): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/BooksApp( 3504): Created application version: 3.6.8 (30608)
,I/LibraryLoader( 3533): Time to load native libraries: 0 ms (timestamps 1617-1617)
I/LibraryLoader( 3533): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3533): Binding Chromium to main looper Looper (main, tid 1) {207ef1c6}
,I/LibraryLoader( 3533): Expected native library version number "",actual native library version number ""
,I/chromium( 3533): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3533): Initializing chromium process, singleProcess=true,
W/art     ( 3533): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3533): ApplicationContext is null in ApplicationStatus
,W/chromium( 3533): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3533): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3533): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3533): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3533): Requires BLUETOOTH permission
,I/BooksSync( 3504): Starting books sync for 61035162, extras: ade
I/NSApplication( 3533): Starting up...
,I/ActivityManager(  824): Killing 1389:android.process.acore/u0a5 (adj 15): empty #17
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  824): Start proc 3611:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,W/Uploader( 1489): No account for auth token provided
,I/BooksConfig( 3504): GmsCore Version = 7.8.99 (2134222-430)
,I/jxcore-log( 3179): BLE supported!!
I/jxcore-log( 3179): 
,W/Uploader( 1489): No account for auth token provided
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1489): No account for auth token provided
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3504): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3504): Soft error
E/BooksSync( 3504): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3504): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3504): Sync error
E/BooksSync( 3504): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3504): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3504): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36323, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  824): Killing 3084:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  824): Killing 3062:com.google.android.partnersetup/u0a16 (adj 15): empty #18
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,I/ActivityManager(  824): Start proc 3633:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,I/ActivityManager(  824): Killing 1816:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,E/SQLiteLog( 3633): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  824): Start proc 3653:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/Uploader( 1489): No account for auth token provided
,W/ResourcesManager( 3653): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3653): Created com.android.providers.calendar.CalendarAlarmManager@3a7d9bf4(com.android.providers.calendar.CalendarProvider2@3fb7ef1d)
,W/Uploader( 1489): No account for auth token provided
,I/ActivityManager(  824): Start proc 3675:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3633): PlayLogger.onLoggerConnected
,W/Uploader( 1489): No account for auth token provided
,I/ActivityManager(  824): Killing 3112:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/TimeService( 3675): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448458106625
D/        ( 3675): TimeServiceNative: User Time to be set is 1448458106625
,D/QC-time-services( 3675): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3675): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3675): Lib:time_genoff_operation: pargs->ts_val = 1448458106625
,D/QC-time-services( 3675): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  376): Daemon: Connection accepted:time_genoff
D/QC-time-services(  376): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448458106625
,D/QC-time-services(  376): Daemon:genoff_opr: Base = 2, val = 1448458106625, operation = 0
D/QC-time-services(  376): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/12/70 9:41:27
D/QC-time-services(  376): Daemon:Value read from RTC seconds = 8761287000
,D/QC-time-services(  376): Daemon:new time 1448458106625 
D/QC-time-services(  376): Daemon: delta 1439696819625 genoff 1439696819625 
D/QC-time-services(  376): Daemon:genoff_persistent_update: Writing genoff = 1439696819625 to memory
,D/QC-time-services(  376): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  376): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  376): Updating the TOD offset
,D/QC-time-services(  376): Daemon:genoff_persistent_update: Writing genoff = 1439696819625 to memory
D/QC-time-services(  376): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  376): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services( 3675): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  376): Daemon:Update to modem bit set
D/QC-time-services(  376): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  376): Daemon: Base = 2, Value being sent to MODEM = 1132493306625
,E/QC-time-services(  376): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  376): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489):  no longer exists, so no auth token.
,I/art     (  824): Explicit concurrent mark sweep GC freed 20319(881KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 2.154ms total 102.516ms
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  824): Start proc 3695:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  824): Killing 3019:com.android.defcontainer/u0a7 (adj 15): empty #17
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GAv4    ( 3695): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3695):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3695):   adb logcat -s GAv4
,W/GAv4    ( 3695): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3695): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/Uploader( 1489): No account for auth token provided
,W/GAv4    ( 3695): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/Uploader( 1489): No account for auth token provided
,I/ActivityManager(  824): Killing 2701:com.android.vending/u0a19 (adj 15): empty #17
,I/CalendarProvider2( 3653): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
V/Herrevad( 1777): NQAS connected
,W/ContentResolver( 3653): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/WifiService(  824): New client listening to asynchronous messages
,D/WifiService(  824): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2291bd8c}
,I/art     ( 1777): Explicit concurrent mark sweep GC freed 16114(1239KB) AllocSpace objects, 17(272KB) LOS objects, 35% free, 28MB/44MB, paused 1.397ms total 74.022ms
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 45726(2MB) AllocSpace objects, 6(384KB) LOS objects, 36% free, 27MB/43MB, paused 985us total 27.214ms
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2629): UserRecoverableAuthException.
,E/Babel   ( 2629): eei: BadAuthentication
E/Babel   ( 2629): 	at eeg.a(Unknown Source)
E/Babel   ( 2629): 	at eeg.a(Unknown Source)
E/Babel   ( 2629): 	at eeg.a(Unknown Source)
E/Babel   ( 2629): 	at g.a(Unknown Source)
E/Babel   ( 2629): 	at cae.a(SourceFile:3089)
E/Babel   ( 2629): 	at cae.a(SourceFile:1131)
E/Babel   ( 2629): 	at cws.a(SourceFile:4333)
E/Babel   ( 2629): 	at cws.a(SourceFile:1419)
E/Babel   ( 2629): 	at crl.a(SourceFile:492)
E/Babel   ( 2629): 	at crl.a(SourceFile:1468)
E/Babel   ( 2629): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2629): 	at cas.b(SourceFile:106)
E/Babel   ( 2629): 	at cap.d(SourceFile:335)
E/Babel   ( 2629): 	at caq.run(SourceFile:81)
E/Babel   ( 2629): Error getting auth token
E/Babel   ( 2629): dvm
E/Babel   ( 2629): 	at g.a(Unknown Source)
E/Babel   ( 2629): 	at cae.a(SourceFile:3089)
E/Babel   ( 2629): 	at cae.a(SourceFile:1131)
E/Babel   ( 2629): 	at cws.a(SourceFile:4333)
E/Babel   ( 2629): 	at cws.a(SourceFile:1419)
E/Babel   ( 2629): 	at crl.a(SourceFile:492)
E/Babel   ( 2629): 	at crl.a(SourceFile:1468)
E/Babel   ( 2629): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2629): 	at cas.b(SourceFile:106)
E/Babel   ( 2629): 	at cap.d(SourceFile:335)
E/Babel   ( 2629): 	at caq.run(SourceFile:81)
,E/Babel   ( 2629): Account registration failed 1-Redacted-21
,E/Babel   ( 2629): cyp: null -- null
E/Babel   ( 2629): 	at cae.a(SourceFile:3121)
E/Babel   ( 2629): 	at cae.a(SourceFile:1131)
E/Babel   ( 2629): 	at cws.a(SourceFile:4333)
E/Babel   ( 2629): 	at cws.a(SourceFile:1419)
E/Babel   ( 2629): 	at crl.a(SourceFile:492)
E/Babel   ( 2629): 	at crl.a(SourceFile:1468)
E/Babel   ( 2629): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2629): 	at cas.b(SourceFile:106)
E/Babel   ( 2629): 	at cap.d(SourceFile:335)
E/Babel   ( 2629): 	at caq.run(SourceFile:81)
,I/art     ( 2629): Note: end time exceeds epoch: 
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1489): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2629): Unexpected exception while authenticating.
E/Babel   ( 2629): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2629): 	at eeg.b(Unknown Source)
E/Babel   ( 2629): 	at eeg.b(Unknown Source)
E/Babel   ( 2629): 	at g.a(Unknown Source)
E/Babel   ( 2629): 	at cae.b(SourceFile:1146)
E/Babel   ( 2629): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2629): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2629): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2629): 	at java.lang.Thread.run(Thread.java:818)
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,E/SQLiteLog( 3653): (284) automatic index on view_events(_id)
,I/ActivityManager(  824): Start proc 3740:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,I/MusicLeanback( 3420): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3420): Stop autocaching.
,I/art     (  372): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 2.658ms total 17.404ms
,W/ResourcesManager( 3740): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3740): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  372): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 336us total 29.566ms
,I/art     (  372): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 337us total 13.956ms
,I/MultiDex( 3740): VM with version 2.1.0 has multidex support
I/MultiDex( 3740): install
I/MultiDex( 3740): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3740): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3740): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1489): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1489): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/WearableService( 3740): callingUid 10011, callindPid: 3740
,V/GmsCoreStatsServiceLauncher( 1777): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/LocationInitializer( 1777): Restart initialization of location
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=44.22 rxSuccessRate=33.94 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,E/MDM     ( 1747): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=44.22 rxSuccessRate=33.94 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,E/GmsUtils( 3420): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3420): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 3504): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 3633): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/ActivityManager(  824): Start proc 3778:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/Finsky  ( 3778): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3778): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  824): Start proc 3814:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,I/ActivityManager(  824): Killing 3320:com.android.settings/1000 (adj 15): empty #17
,W/Settings( 3778): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3778): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  824): Killing 3339:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,W/ResourcesManager( 3814): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3814): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 3778): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3778): [1] 2.run: Finished loading 1 libraries.
,I/MultiDex( 3814): VM with version 2.1.0 has multidex support
I/MultiDex( 3814): install
I/MultiDex( 3814): VM has multidex support, MultiDex support library is disabled.
I/art     (  824): Explicit concurrent mark sweep GC freed 16766(777KB) AllocSpace objects, 5(551KB) LOS objects, 32% free, 33MB/49MB, paused 1.276ms total 94.726ms
,D/Finsky  ( 3778): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 3814): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 3778): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ProviderInstaller( 3814): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1489): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1489): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1777): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/Finsky  ( 3778): [415] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 3740): callingUid 10011, callindPid: 3740
,E/MDM     ( 1747): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1777): Restart initialization of location
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3778): [415] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/Finsky  ( 3778): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3778): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3778): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3778): [1] 5.onFinished: Scheduling replication attempt 4.
,D/Finsky  ( 3778): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3778): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 28241(1529KB) AllocSpace objects, 17(1874KB) LOS objects, 37% free, 26MB/42MB, paused 1.550ms total 59.904ms
,W/Finsky  ( 3778): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/PowerManagerService(  824): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  824): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (214 us)
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3778): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3778): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3778): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3778): [1] DailyHygiene.reschedule: Scheduling new run in 869 minutes (failures=5)
,D/DeviceConnectionService( 1747): client connected with version: 7571000
,I/DisplayManagerService(  824): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  824): Display changed displayId=0
,D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6082000
,D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0,
D/SurfaceControl(  824): Excessive delay in setPowerMode(): 288ms
,I/DreamManagerService(  824): Entering dreamland.
,I/PowerManagerService(  824): Dozing...
,I/DreamController(  824): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  361): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  361): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  824): cancelDelayedScan -> 5
,E/native  (  824): do suspend false
,D/WifiService(  824): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1893a98f}
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=3.26 rxSuccessRate=4.62 targetRoamBSSID=any RSSI=-44
,I/Keyboard.Facilitator( 1209): onFinishInput()
,E/WifiStateMachine(  824): cancelDelayedScan -> 7
,E/native  (  824): do suspend true
,D/audio_hw_primary(  361): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  361): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,D/WifiService(  824): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1893a98f}
,E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/ActivityManager(  824): Killing 3484:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  824): Killing 3533:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.50 rxSuccessRate=1.00 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,V/GoogleAuthProtoRequest( 3253): [333] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3253): [334] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3253): [334] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3253): [334] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3253): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3253): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3253): 	at com.a.a.k.run(SourceFile:110)
,I/art     (  824): Explicit concurrent mark sweep GC freed 29793(1464KB) AllocSpace objects, 6(284KB) LOS objects, 32% free, 33MB/49MB, paused 2.851ms total 53.804ms
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3253): [333] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3253): [333] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3253): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3253): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3253): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3778): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
,D/Finsky  ( 3778): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3778): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,V/KeepSync( 3297): Connecting to GoogleApiClient
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1777): Handling authorization failure
E/ClientConnectionOperation( 1777): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1777): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1777): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1777): 	... 7 more
,V/KeepSync( 3297): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
E/HttpOperation( 2949): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406),
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at blb.a(PG:3937)
E/HttpOperation( 2949): 	at czp.a(PG:18188)
E/HttpOperation( 2949): 	at czp.a(PG:9087),
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
,E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error,
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 12 more,
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 14 more
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2949): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at blb.a(PG:3937)
E/HttpOperation( 2949): 	at czp.a(PG:18188)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 12 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 14 more
,E/KeepSync( 3297): IOException
E/KeepSync( 3297): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3297): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3297): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3297): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3297): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3297): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3297): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3297): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3297): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3297): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3297): 	... 10 more
W/KeepSync( 3297): Sync result 2
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 181344, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2949): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at hec.a(PG:42)
E/HttpOperation( 2949): 	at hee.a(PG:102)
E/HttpOperation( 2949): 	at czr.a(PG:65)
E/HttpOperation( 2949): 	at kka.a(PG:108)
E/HttpOperation( 2949): 	at czp.a(PG:19176)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 15 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 17 more
,E/ExperimentLoader( 2949): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): 	at jdm.a(PG:82)
E/ExperimentLoader( 2949): 	at jcs.o(PG:406)
E/ExperimentLoader( 2949): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2949): 	at jcs.i(PG:143)
E/ExperimentLoader( 2949): 	at hec.a(PG:42)
E/ExperimentLoader( 2949): 	,at hee.a(PG:102)
E/ExperimentLoader( 2949): 	at czr.a(PG:65)
E/ExperimentLoader( 2949): 	at kka.a(PG:108)
E/ExperimentLoader( 2949): 	at czp.a(PG:19176)
,E/ExperimentLoader( 2949): 	at czp.a(PG:9081)
E/ExperimentLoader( 2949): 	at czq.run(PG:1686)
E/ExperimentLoader( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2949): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2949): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2949): 	at jdm.a(PG:77)
E/ExperimentLoader( 2949): 	... 15 more
E/ExperimentLoader( 2949): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2949): 	at fal.a(PG:38)
,E/ExperimentLoader( 2949): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2949): 	... 17 more
,I/BooksSync( 3504): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3504): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 151008, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3504): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3504): Soft error
,E/BooksSync( 3504): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3504): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3504): Sync error
E/BooksSync( 3504): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3504): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3504): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 183891, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3778): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3778): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3778): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1209): run()
I/Keyboard.Facilitator( 1209): flushDynamicLanguageModels()
,I/ConfigService( 1489): onCreate
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/ConfigService( 1489): onDestroy
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2949): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
,E/HttpOperation( 2949): 	at blb.a(PG:3937)
E/HttpOperation( 2949): 	at czp.a(PG:18188)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
,E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 12 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3179): 
,E/HttpOperation( 2949): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at hec.a(PG:42)
E/HttpOperation( 2949): 	at hee.a(PG:102),
E/HttpOperation( 2949): 	at czr.a(PG:65)
E/HttpOperation( 2949): 	at kka.a(PG:108)
E/HttpOperation( 2949): 	at czp.a(PG:19176)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 15 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 17 more
,E/ExperimentLoader( 2949): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): 	at jdm.a(PG:82)
E/ExperimentLoader( 2949): 	at jcs.o(PG:406)
E/ExperimentLoader( 2949): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2949): 	at jcs.i(PG:143)
E/ExperimentLoader( 2949): 	at hec.a(PG:42)
E/ExperimentLoader( 2949): 	at hee.a(PG:102)
E/ExperimentLoader( 2949): 	at czr.a(PG:65)
E/ExperimentLoader( 2949): 	at kka.a(PG:108)
E/ExperimentLoader( 2949): 	at czp.a(PG:19176)
E/ExperimentLoader( 2949): 	at czp.a(PG:9081)
E/ExperimentLoader( 2949): 	at czq.run(PG:1686)
E/ExperimentLoader( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2949): ,	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2949): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2949): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2949): 	at jdm.a(PG:77)
E/ExperimentLoader( 2949): 	... 15 more
E/ExperimentLoader( 2949): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2949): 	at fal.a(PG:38)
E/ExperimentLoader( 2949): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2949): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 243180, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3179): 
,V/GoogleAuthProtoRequest( 3253): [335] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3253): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 41637(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.454ms total 42.443ms
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3253): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3253): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3253): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3253): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3253): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3253): [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3253): [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3253): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3253): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3253): 	at com.a.a.k.run(SourceFile:110)
,I/art     (  824): Explicit concurrent mark sweep GC freed 35031(1552KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.467ms total 63.806ms
,I/jxcore-log( 3179): DBG, CoordinatorConnector connect called
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Coordinator is now connected to the server!
I/jxcore-log( 3179): 
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/BooksSync( 3504): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3297): Connecting to GoogleApiClient
,I/BooksConfig( 3504): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1777): Handling authorization failure
E/ClientConnectionOperation( 1777): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1777): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1777): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1777): 	... 7 more
,V/KeepSync( 3297): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3504): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3504): Soft error
E/BooksSync( 3504): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3504): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3504): Sync error
E/BooksSync( 3504): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3504): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3504): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 274783, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3297): IOException
E/KeepSync( 3297): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3297): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3297): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3297): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3297): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3297): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3297): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3297): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3297): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3297): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3297): 	... 10 more
W/KeepSync( 3297): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 271105, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2949): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at blb.a(PG:3937)
E/HttpOperation( 2949): 	at czp.a(PG:18188)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 12 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2949): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at hec.a(PG:42)
E/HttpOperation( 2949): 	at hee.a(PG:102)
E/HttpOperation( 2949): 	at czr.a(PG:65)
E/HttpOperation( 2949): 	at kka.a(PG:108)
E/HttpOperation( 2949): 	at czp.a(PG:19176)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 15 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 17 more
E/ExperimentLoader( 2949): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): 	at jdm.a(PG:82)
E/ExperimentLoader( 2949): 	at jcs.o(PG:406)
E/ExperimentLoader( 2949): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2949): 	at jcs.i(PG:143)
E/ExperimentLoader( 2949): 	at hec.a(PG:42)
E/ExperimentLoader( 2949): 	at hee.a(PG:102)
E/ExperimentLoader( 2949): 	at czr.a(PG:65)
E/ExperimentLoader( 2949): 	at kka.a(PG:108)
E/ExperimentLoader( 2949): 	at czp.a(PG:19176)
E/ExperimentLoader( 2949): 	at czp.a(PG:9081)
E/ExperimentLoader( 2949): 	at czq.run(PG:1686)
E/ExperimentLoader( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2949): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2949): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2949): 	at jdm.a(PG:77)
E/ExperimentLoader( 2949): 	... 15 more
E/ExperimentLoader( 2949): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2949): 	at fal.a(PG:38)
E/ExperimentLoader( 2949): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2949): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 335294, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/jxcore-log( 3179): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector command called,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":20,"addressList":[{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"B4:CE:F6:AB:A4
,I/jxcore-log( 3179): Start now : testSendData.js
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 20
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): check server
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): serverPort is 43271
I/jxcore-log( 3179): 
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3179): Stoping All
,I/        ( 3179): Stopping services
,I/        ( 3179): Stop Bluetooth
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/        ( 3179): Start-My BT: F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3179):  mInstanceString : {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7950","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3179): All stuff available and enabled
I/        ( 3179): Stoping All
I/        ( 3179): Stopping services
,I/        ( 3179): Stop Bluetooth
I/        ( 3179): Starting All
I/        ( 3179): Stopping services
I/        ( 3179): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7950","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@3a48be71
I/        ( 3179): Stopping services
,I/        ( 3179): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7950","ra":"F8:CF:C5:D9:E5:61"},
I/        ( 3179): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7950","ra":"F8:CF:C5:D9:E5:61"}, length : 82
I/        ( 3179): peerDiscoveryTimer timeout value:6506
,I/        ( 3179): Stop Bluetooth
,I/        ( 3179): StartBluetooth listener
I/        ( 3179): StartBluetooth listener
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3179): StartBroadcasting started ok
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: 34:FC:EF:9D:93:0B,
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:32:35.186Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3179): 
I/BTListenerThread( 3179): starting to listen
I/BTListenerThread( 3179): waiting to accept incoming Connection
I/jxcore-log( 3179): 2015-11-25T13:32:35.187Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:32:35.187Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3179): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/jxcore-log( 3179): 2015-11-25T13:32:35.199Z SendDataTCPServer.js: TCP/IP server is bound to port: 43271
I/jxcore-log( 3179): 
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3179): We already were running, thus doing nothing
,I/        ( 3179): Added local service
,I/        ( 3179): Cleared service requests
I/        ( 3179): Stopped peer discovery
I/        ( 3179): Started peer discovery
I/        ( 3179): Discovery state changed to Started.
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 1 peers.
I/SS      ( 3179): Peer(1): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2882","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:,
I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2882","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT2882, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT2882, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,D/btif_config( 3235): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/ActivityManager(  824): Start proc 3939:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c2bf0:true
,I/ActivityManager(  824): Killing 1532:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  824): Client connection lost with reason: 4
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0,
D/BluetoothAdapterProperties( 3235): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3179): Starting to Handshake
,I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTConnectToThread( 3179): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3179): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3179): HandshakeOk : LGE-LG-D802_PT4660
I/HS      ( 3179): Hand Shake finished outgoing for : LGE-LG-D802_PT4660
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, LGE-LG-D802_PT4660
,I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket,
I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): mHTTPPort  set to : 60277
,I/BtConnectorHelper( 3179): Request socket is using : 60277
I/BtToRequestSocket( 3179): Now accepting connections
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :60277
I/jxcore-log( 3179): 2015-11-25T13:32:41.215Z SendDataConnector.js: CLIENT connected to 60277, error: null
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:32:41.216Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 60277
,I/BtToRequestSocket( 3179): Set local streams
,I/jxcore-log( 3179): 2015-11-25T13:32:41.228Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): rin ended ---------------------------;
,V/GoogleAuthProtoRequest( 3253): [337] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3253): [338] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3253): [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3253): [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3253): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3253): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.a.a.a(SourceFile:167)
,W/ExperimentUpdateService( 3253): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3253): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3253): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3253): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3253): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3253): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3253): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3179): 2015-11-25T13:32:41.881Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3179): 2015-11-25T13:32:42.646Z SendDataConnector.js: CLIENT is data received : 20000
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:43.313Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:43.833Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:44.335Z SendDataConnector.js: CLIENT is data received : 50000,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:44.908Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:45.084Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:45.262Z SendDataConnector.js: CLIENT is data received : 80000,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:45.664Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:46.314Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:46.315Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:46.324Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:46.325Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
,I/BtConnectorHelper( 3179): Disconnect outgoing peer: 34:FC:EF:9D:93:0B
,I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3179): Close LocalOutputStream,
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
,I/BtToRequestSocket( 3179): Close server socket
I/jxcore-log( 3179): 2015-11-25T13:32:46.340Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: F8:95:C7:87:85:54
,I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:32:46.341Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:32:46.341Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:32:46.342Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3179): Connecting to null, at F8:95:C7:87:85:54
I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:9D:93:0B done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f25eb4 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f25eb4 rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): No ag scb for peer addr
,I/        ( 3179): Cleared service requests,
,I/        ( 3179): Started peer discovery
,W/bt-btif ( 3235): info:x10,
D/        ( 3235): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f25eb4 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2607c rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,D/btif_config( 3235): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 3235): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2607c rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3235): onReceive,
,I/ActivityManager(  824): Start proc 3967:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@175a7120:true
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  824): Start proc 3993:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
I/BluetoothClassifier( 3967): Bluetooth Device Name: Thali Test's G2
,I/ActivityManager(  824): Killing 3675:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  824): Killing 3611:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 3 peers.
I/SS      ( 3179): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3179): Peer(3): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3179): Started service discovery
,V/KeepSync( 3297): Connecting to GoogleApiClient
,I/art     (  824): Explicit concurrent mark sweep GC freed 31037(1402KB) AllocSpace objects, 6(284KB) LOS objects, 32% free, 33MB/49MB, paused 1.438ms total 78.620ms
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1777): Handling authorization failure
E/ClientConnectionOperation( 1777): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1777): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1777): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1777): 	... 7 more
,V/KeepSync( 3297): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3297): IOException
E/KeepSync( 3297): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3297): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3297): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3297): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3297): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3297): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3297): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3297): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3297): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3297): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3297): 	... 10 more
W/KeepSync( 3297): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 421291, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:,
I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3179): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3179): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1287","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1287","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT1287, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT1287, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,W/bt-l2cap( 3235): L2CAP - no CCB for conn rsp, LCID: 70 RCID: 74
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3179): we got incoming connection
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3179): waiting to accept incoming Connection
W/bt-btif ( 3235): new conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3179): Starting to Handshake
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTListenerThread( 3179): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3179): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2882","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.,
I/HS      ( 3179): Incoming connection Hand Shake finished for : LGE-LG-D722_PT2882
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, LGE-LG-D722_PT2882,
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BTConnectedThread
,I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271
,I/BtToRequestSocket( 3179): --DoOneRunRound ended
,I/jxcore-log( 3179): 2015-11-25T13:32:56.443Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3179): 
,I/BTConnectToThread( 3179): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3179): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2882","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3179): HandshakeOk : LGE-LG-D722_PT2882,
I/HS      ( 3179): Hand Shake finished outgoing for : LGE-LG-D722_PT2882
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, LGE-LG-D722_PT2882
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket,
I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3179): mHTTPPort  set to : 39799
I/BtConnectorHelper( 3179): Request socket is using : 39799
I/BtToRequestSocket( 3179): Now accepting connections
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :39799
I/jxcore-log( 3179): 2015-11-25T13:32:56.757Z SendDataConnector.js: CLIENT connected to 39799, error: null
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:32:56.758Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 39799
I/BtToRequestSocket( 3179): Set local streams
,I/jxcore-log( 3179): 2015-11-25T13:32:56.766Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
I/BtToRequestSocket( 3179): rin ended ---------------------------;
,I/jxcore-log( 3179): 2015-11-25T13:32:56.827Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:56.861Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:56.867Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:56.897Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:56.917Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:32:56.926Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:56.951Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:56.961Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:56.996Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.211Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.263Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.274Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.317Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.325Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.366Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.402Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.411Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.420Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.450Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.458Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.464Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.471Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.493Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.531Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.543Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.567Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.568Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.571Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.572Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
I/BtConnectorHelper( 3179): Disconnect outgoing peer: F8:95:C7:87:85:54
I/BtToSocketBase( 3179): Stop ReceivingThread
,I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
,I/BtToSocketBase( 3179): Close bt socket
I/BtToRequestSocket( 3179): Close server socket
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3179): 2015-11-25T13:32:57.581Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- round done--------
,I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:32:57.584Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:32:57.584Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:32:57.585Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 44:80:EB:7B:5A:05,
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:85:54 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/jxcore-log( 3179): 2015-11-25T13:32:57.602Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.607Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.612Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:57.679Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2607c rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14),
,I/jxcore-log( 3179): 2015-11-25T13:32:58.216Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:58.222Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:58.287Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:58.354Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/jxcore-log( 3179): 2015-11-25T13:32:58.557Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:58.625Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:58.692Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:58.759Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:58.846Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:58.928Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:58.994Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:59.063Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:59.129Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:59.196Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:59.264Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:59.332Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:32:59.395Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): invalid rfc slot id: 4,
I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT2882
,I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
,I/BtToSocketBase( 3179): Close local in
,I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3179): Close bt out
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3179): Close bt socket,
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT2882
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
,I/jxcore-log( 3179): 2015-11-25T13:32:59.539Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8083"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8083"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8083, peerAddress: 34:FC:EF:11:B1:66
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8083, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66,
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2607c rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3235): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 3235): RFCOMM_DisconnectInd LCID:0x47
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/        ( 3179): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT760, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT760, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 8
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:33:03.171Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:03.172Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:03.174Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2882","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2882","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT2882, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT2882, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3179): 2015-11-25T13:33:08.175Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:08.177Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,D/btif_config( 3235): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3235): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3179): Found 6 peers.,
I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/jxcore-log( 3179): 2015-11-25T13:33:13.182Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:13.183Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3179): ,
I/jxcore-log( 3179): 2015-11-25T13:33:13.184Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:13.184Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/BTConnectToThread( 3179): Starting to connect
I/        ( 3179): Connecting to null, at 44:80:EB:7B:5A:05
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2640c rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3179): we got incoming connection
,I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTListenerThread( 3179): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTListenerThread( 3179): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3179): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
I/HS      ( 3179): Incoming connection Hand Shake finished for : LGE-LG-H815_PT1965
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, LGE-LG-H815_PT1965
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BTConnectedThread
I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271,
I/BtToRequestSocket( 3179): --DoOneRunRound ended
,I/jxcore-log( 3179): 2015-11-25T13:33:15.054Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:15.503Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:15.670Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:15.736Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:15.804Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:15.949Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:16.088Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:16.196Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:16.289Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:16.404Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3179): 2015-11-25T13:33:16.707Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:16.855Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.031Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.099Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.320Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.323Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.459Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3179): 2015-11-25T13:33:17.682Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.721Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.739Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.775Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.874Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.910Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.916Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.919Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:17.997Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.112Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.184Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.191Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.204Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.252Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:33:18.289Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.320Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.324Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.337Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.364Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.373Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.410Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.423Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.428Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.435Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.470Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.476Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.491Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.502Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.513Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.551Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.565Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:18.570Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): invalid rfc slot id: 7
,I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1965
,I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1965
I/BtToSocketBase( 3179): Close LocalOutputStream
,I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
,I/BtToSocketBase( 3179): Close bt socket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
W/bt-rfcomm( 3235): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3235): RFCOMM_DisconnectInd LCID:0x4b
,I/jxcore-log( 3179): 2015-11-25T13:33:18.623Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2640c rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:,
I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-btif ( 3235): info:x10,
D/        ( 3235): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp,
,D/btif_config( 3235): btif_get_device_type: Device [44:80:eb:7b:5a:05] type 1,
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,W/bt-btm  ( 3235): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2640c rs_disc_pending=2
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3235): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3235): onReceive,
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3179): Starting to Handshake
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.,
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTConnectToThread( 3179): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3179): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BTConnectToThread( 3179): HandshakeOk : motorola-XT1072_PT9583
,I/HS      ( 3179): Hand Shake finished outgoing for : motorola-XT1072_PT9583
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, motorola-XT1072_PT9583
,I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
I/BluetoothClassifier( 3967): Bluetooth Device Name: G4-1
I/BtToRequestSocket( 3179): mHTTPPort  set to : 46245
I/BtConnectorHelper( 3179): Request socket is using : 46245
,I/BtToRequestSocket( 3179): Now accepting connections
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :46245
,I/jxcore-log( 3179): 2015-11-25T13:33:22.779Z SendDataConnector.js: CLIENT connected to 46245, error: null
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:22.779Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 46245
I/BtToRequestSocket( 3179): Set local streams
,I/jxcore-log( 3179): 2015-11-25T13:33:22.788Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): rin ended ---------------------------;
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3179): 2015-11-25T13:33:22.911Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18049
,I/jxcore-log( 3179): 2015-11-25T13:33:22.953Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11119
,I/jxcore-log( 3179): 2015-11-25T13:33:23.009Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:23.047Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2209
,I/jxcore-log( 3179): 2015-11-25T13:33:23.095Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:23.143Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:23.199Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:23.250Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:23.280Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:23.334Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:23.335Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:23.339Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:23.339Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
,I/BtConnectorHelper( 3179): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
,I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3179): Close LocalOutputStream
,I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
,I/BtToSocketBase( 3179): Close bt socket
I/BtToRequestSocket( 3179): Close server socket
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3179): 2015-11-25T13:33:23.347Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- round done--------,
I/jxcore-log( 3179): 
W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:23.353Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:23.353Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:23.353Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at E0:DB:10:1F:C9:5E
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 44:80:EB:7B:5A:05 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BooksSync( 3504): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3504): GmsCore Version = 7.8.99 (2134222-430)
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3504): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
E/BooksSync( 3504): Soft error
E/BooksSync( 3504): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3504): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3504): Sync error
E/BooksSync( 3504): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3504): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3504): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 428114, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f265d4 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,D/btif_config( 3235): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1,
E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/        ( 3179): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1287","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1287","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT1287, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT1287, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
D/BluetoothAdapterProperties( 3235): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: XT1072
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8083"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8083"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8083, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8083, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f265d4 rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3179): Starting to Handshake
,I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTConnectToThread( 3179): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3179): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3179): HandshakeOk : samsung-SM-N9005_PT760
I/HS      ( 3179): Hand Shake finished outgoing for : samsung-SM-N9005_PT760
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, samsung-SM-N9005_PT760
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): mHTTPPort  set to : 44488
I/BtConnectorHelper( 3179): Request socket is using : 44488
,I/BtToRequestSocket( 3179): Now accepting connections
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :44488
,I/jxcore-log( 3179): 2015-11-25T13:33:30.070Z SendDataConnector.js: CLIENT connected to 44488, error: null
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:30.071Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 44488
,I/BtToRequestSocket( 3179): Set local streams
,I/BtToRequestSocket( 3179): rin ended ---------------------------;
,I/jxcore-log( 3179): 2015-11-25T13:33:30.082Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4504
,I/jxcore-log( 3179): 2015-11-25T13:33:30.256Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:30.373Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:30.493Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:30.603Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:30.688Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3179): 2015-11-25T13:33:30.824Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:30.900Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:31.019Z SendDataConnector.js: CLIENT is data received : 80000,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:31.075Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:31.089Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:31.089Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:31.094Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:31.095Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
,I/BtConnectorHelper( 3179): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 3179): Stop ReceivingThread
,I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToRequestSocket( 3179): Close server socket
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3179): 2015-11-25T13:33:31.104Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3179): 
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:31.107Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:31.108Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:31.109Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 34:FC:EF:11:B1:66
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f265d4 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f265d4 rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/GLSActivity( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,W/GLSActivity( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1489): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1489): ,	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1489): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1489): 	,at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3778): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 3778): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3778): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3778): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3778): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867),
E/PlayEventLogger( 3778): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3778): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3778): Ignoring header User-Agent because its value was null.
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3235): PORT_StartCnf failed result:5,
,E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,W/bt-btif ( 3235): invalid rfc slot id: 12
E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btm  ( 3235): Device not in IRK list
E/bt-btif ( 3235): Do not find the bg connection mask for the remote device
I/BluetoothBondStateMachine( 3235): No record of the device:null
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 9 Address: 34:FC:EF:11:B1:66 newState: 0
E/BluetoothBondStateMachine( 3235): In stable state, received invalid newState: 10
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
I/jxcore-log( 3179): 2015-11-25T13:33:38.563Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:38.564Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:38.564Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,W/bt-btm  ( 3235): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f265d4 rs_disc_pending=2
E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Note3-1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3179): Found 10 peers.
,I/SS      ( 3179): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3179): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 3179): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT501"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT501"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT501, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT501, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3179): 2015-11-25T13:33:43.566Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:43.567Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6613, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6613, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3179): 2015-11-25T13:33:48.571Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:48.572Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:48.572Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:48.573Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
I/        ( 3179): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 34:FC:EF:11:B1:66
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,D/btif_config( 3235): btif_get_device_type: Device [34:fc:ef:11:b1:66] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1,
E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 3235): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3179): Starting to Handshake
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTConnectToThread( 3179): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3179): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8083"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3179): HandshakeOk : LGE-Nexus 5_PT8083
I/HS      ( 3179): Hand Shake finished outgoing for : LGE-Nexus 5_PT8083
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped,
I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, LGE-Nexus 5_PT8083
,I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): mHTTPPort  set to : 43187
,I/BtConnectorHelper( 3179): Request socket is using : 43187
,I/BtToRequestSocket( 3179): Now accepting connections
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :43187
,I/jxcore-log( 3179): 2015-11-25T13:33:50.181Z SendDataConnector.js: CLIENT connected to 43187, error: null
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:50.181Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 43187
,I/BtToRequestSocket( 3179): Set local streams
I/BtToRequestSocket( 3179): rin ended ---------------------------;
,I/jxcore-log( 3179): 2015-11-25T13:33:50.191Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:20888
,I/jxcore-log( 3179): 2015-11-25T13:33:50.315Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): ,
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19039
,I/jxcore-log( 3179): 2015-11-25T13:33:50.489Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:50.549Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8149
,I/jxcore-log( 3179): 2015-11-25T13:33:50.643Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:50.735Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:50.787Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:50.946Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:51.007Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:51.089Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:51.152Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:51.153Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:51.158Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:51.159Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
I/BtConnectorHelper( 3179): Disconnect outgoing peer: 34:FC:EF:11:B1:66
I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
,I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
,I/BtToRequestSocket( 3179): Close server socket
I/jxcore-log( 3179): 2015-11-25T13:33:51.170Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:51.172Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:51.173Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:33:51.173Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
I/        ( 3179): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 7C:F9:0E:34:8A:A0
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 9 peers.
,I/SS      ( 3179): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3179): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3179): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3179): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending,
I/        ( 3179): Started service discovery
,W/bt-btif ( 3235): info:x10,
D/        ( 3235): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/        ( 3179): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT501"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT501"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT501, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT501, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3179): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6613, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6613, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,I/        ( 3179): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3125"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3125"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT3125, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT3125, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/btif_config( 3235): btif_get_device_type: Device [7c:f9:0e:34:8a:a0] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3235): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3179): Starting to Handshake
,I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTConnectToThread( 3179): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3179): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3179): HandshakeOk : samsung-SM-G900F_PT8472
I/HS      ( 3179): Hand Shake finished outgoing for : samsung-SM-G900F_PT8472
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, samsung-SM-G900F_PT8472
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): mHTTPPort  set to : 53700
,I/BtConnectorHelper( 3179): Request socket is using : 53700
I/BtToRequestSocket( 3179): Now accepting connections
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :53700
,I/jxcore-log( 3179): 2015-11-25T13:33:59.879Z SendDataConnector.js: CLIENT connected to 53700, error: null
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:33:59.879Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 53700
,I/BtToRequestSocket( 3179): Set local streams
I/BtToRequestSocket( 3179): rin ended ---------------------------;
,I/jxcore-log( 3179): 2015-11-25T13:33:59.889Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:403
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/jxcore-log( 3179): 2015-11-25T13:34:00.732Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:01.109Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:01.385Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:01.520Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:01.882Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/jxcore-log( 3179): 2015-11-25T13:34:02.246Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:02.733Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:03.440Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3179): 2015-11-25T13:34:04.186Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:05.345Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:05.346Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:05.350Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:05.352Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
,I/BtConnectorHelper( 3179): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
,I/BtToSocketBase( 3179): Stop ReceivingThread
,I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3179): Close localHostSocket
,I/BtToSocketBase( 3179): Close bt in,
I/BtToSocketBase( 3179): Close bt out
,I/BtToSocketBase( 3179): Close bt socket
I/BtToRequestSocket( 3179): Close server socket
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3179): 2015-11-25T13:34:05.362Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:05.366Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:05.367Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:05.368Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
I/        ( 3179): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3179): Connecting to null, at 34:FC:EF:11:AE:67
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:34:8A:A0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26964 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26b2c rs_disc_pending=1,
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14),
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/btif_config( 3235): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/        ( 3179): Cleared service requests
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
D/BluetoothAdapterProperties( 3235): Failed to remove device: 34:FC:EF:11:AE:67
,I/        ( 3179): Started peer discovery
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: S5-1
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3179): Starting to Handshake
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26b2c rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3179): got MESSAGE_READ 77 bytes.,
I/BTConnectToThread( 3179): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6456","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3179): HandshakeOk : LGE-Nexus 5_PT6456
I/HS      ( 3179): Hand Shake finished outgoing for : LGE-Nexus 5_PT6456
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, LGE-Nexus 5_PT6456
,I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): mHTTPPort  set to : 36934
I/BtConnectorHelper( 3179): Request socket is using : 36934
I/BtToRequestSocket( 3179): Now accepting connections
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :36934
,I/jxcore-log( 3179): 2015-11-25T13:34:11.604Z SendDataConnector.js: CLIENT connected to 36934, error: null
,I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:11.604Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 36934
I/BtToRequestSocket( 3179): Set local streams
I/BtToRequestSocket( 3179): rin ended ---------------------------;
I/jxcore-log( 3179): 2015-11-25T13:34:11.614Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4504
,I/jxcore-log( 3179): 2015-11-25T13:34:12.794Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18049
,I/jxcore-log( 3179): 2015-11-25T13:34:13.024Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3179): 2015-11-25T13:34:15.107Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:15.225Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 3179): 2015-11-25T13:34:15.293Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:15.662Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:16.044Z SendDataConnector.js: CLIENT is data received : 70000,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:16.642Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:16.915Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): info:x10,
,D/        ( 3235): remote version info [44:80:eb:7b:5a:05]: 7, f, 610c
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26b2c rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:34:17.597Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:17.598Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:17.604Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:17.605Z SendDataConnector.js: CLIENT closeClientSocket,
I/jxcore-log( 3179): 
I/BtConnectorHelper( 3179): Disconnect outgoing peer: 34:FC:EF:11:AE:67
I/BtToSocketBase( 3179): Stop ReceivingThread,
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToRequestSocket( 3179): Close server socket
I/jxcore-log( 3179): 2015-11-25T13:34:17.612Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67,
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:17.615Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:17.616Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:17.617Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
I/        ( 3179): Selected device address: B4:CE:F6:AB:A4:6A, name: null
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at B4:CE:F6:AB:A4:6A
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:AE:67 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND,
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/SS      ( 3179): Found 10 peers.
I/SS      ( 3179): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3179): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3179): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3179): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3179): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2,
I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255,
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3179): we got incoming connection
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTListenerThread( 3179): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3179): Started service discovery
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26244 rs_disc_pending=0,
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3179): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3179): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
I/HS      ( 3179): Incoming connection Hand Shake finished for : motorola-XT1072_PT9583
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, motorola-XT1072_PT9583
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BTConnectedThread
I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271,
I/BtToRequestSocket( 3179): --DoOneRunRound ended,
I/jxcore-log( 3179): 2015-11-25T13:34:20.680Z SendDataTCPServer.js: TCP/IP server connected,
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:34:21.090Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.096Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.153Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.162Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.252Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.277Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.310Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
I/jxcore-log( 3179): 2015-11-25T13:34:21.337Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data,
I/jxcore-log( 3179): 
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:34:21.425Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data,
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26244 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,I/jxcore-log( 3179): 2015-11-25T13:34:21.666Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3179): 
D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/jxcore-log( 3179): 2015-11-25T13:34:21.700Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3179): 
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3179): 2015-11-25T13:34:21.742Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.767Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.775Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.795Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26cf4 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
I/jxcore-log( 3179): 2015-11-25T13:34:21.831Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.883Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.896Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.907Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.930Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.970Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:21.988Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.057Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.090Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3179): 
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,I/jxcore-log( 3179): 2015-11-25T13:34:22.125Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.132Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3179): 2015-11-25T13:34:22.155Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.204Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.241Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.254Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.265Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.286Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.329Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.360Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.367Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.423Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1985","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1985","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT1985, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT1985, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3179): 2015-11-25T13:34:22.434Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.492Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.500Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:34:22.508Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.542Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.549Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.581Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.601Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:22.605Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): invalid rfc slot id: 10,
I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT9583
,I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT9583
,I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
,I/BtToSocketBase( 3179): Close bt socket
,I/jxcore-log( 3179): 2015-11-25T13:34:22.724Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26244 rs_disc_pending=0,
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,D/btif_config( 3235): btif_get_device_type: Device [b4:ce:f6:ab:a4:6a] type 1,
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1,
E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
D/BluetoothAdapterProperties( 3235): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3179): Starting to Handshake
,I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 53481(2MB) AllocSpace objects, 6(661KB) LOS objects, 36% free, 27MB/43MB, paused 2.676ms total 57.656ms
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2949): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
,E/HttpOperation( 2949): 	at blb.a(PG:3937)
E/HttpOperation( 2949): 	at czp.a(PG:18188)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 12 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 14 more
,I/BTConnectToThread( 3179): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3179): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3179): HandshakeOk : HTC-HTC Desire 820_PT2890
I/HS      ( 3179): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT2890
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT2890
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): mHTTPPort  set to : 46228
,I/BtConnectorHelper( 3179): Request socket is using : 46228
I/BtToRequestSocket( 3179): Now accepting connections
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2949): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at hec.a(PG:42)
E/HttpOperation( 2949): 	at hee.a(PG:102)
E/HttpOperation( 2949): 	at czr.a(PG:65)
E/HttpOperation( 2949): 	at kka.a(PG:108)
E/HttpOperation( 2949): 	at czp.a(PG:19176)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): ,	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 15 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	,at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 17 more
E/ExperimentLoader( 2949): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): ,	at jdm.a(PG:82)
E/ExperimentLoader( 2949): 	at jcs.o(PG:406)
E/ExperimentLoader( 2949): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2949): 	at jcs.i(PG:143),
E/ExperimentLoader( 2949): 	at hec.a(PG:42)
E/ExperimentLoader( 2949): 	at hee.a(PG:102)
E/ExperimentLoader( 2949): 	at czr.a(PG:65)
,E/ExperimentLoader( 2949): 	at kka.a(PG:108)
E/ExperimentLoader( 2949): 	at czp.a(PG:19176)
E/ExperimentLoader( 2949): 	at czp.a(PG:9081)
E/ExperimentLoader( 2949): 	,at czq.run(PG:1686)
E/ExperimentLoader( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2949): ,	at jdj.a(PG:4091)
E/ExperimentLoader( 2949): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2949): 	at jdm.a(PG:77)
E/ExperimentLoader( 2949): 	... 15 more,
E/ExperimentLoader( 2949): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2949): 	at fal.a(PG:38)
E/ExperimentLoader( 2949): 	at jdj.a(PG:4089)
,E/ExperimentLoader( 2949): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 489655, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :46228
I/jxcore-log( 3179): 2015-11-25T13:34:25.128Z SendDataConnector.js: CLIENT connected to 46228, error: null
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:25.128Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 46228
,I/BtToRequestSocket( 3179): Set local streams
I/jxcore-log( 3179): 2015-11-25T13:34:25.136Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
I/BtToRequestSocket( 3179): rin ended ---------------------------;
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:403
,I/jxcore-log( 3179): 2015-11-25T13:34:25.946Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:26.212Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:26.636Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:26.872Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:27.191Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3179): 2015-11-25T13:34:27.427Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:27.902Z SendDataConnector.js: CLIENT is data received : 70000,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:28.221Z SendDataConnector.js: CLIENT is data received : 80000
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:28.470Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26244 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26cf4 rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:34:29.019Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:29.020Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:29.025Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:29.026Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
,I/BtConnectorHelper( 3179): Disconnect outgoing peer: B4:CE:F6:AB:A4:6A
,I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
,I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToRequestSocket( 3179): Close server socket
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3179): 2015-11-25T13:34:29.040Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:29.042Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3179): ,
I/jxcore-log( 3179): 2015-11-25T13:34:29.043Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:29.043Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 7C:F9:0E:37:96:AB, name: null
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 7C:F9:0E:37:96:AB
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B4:CE:F6:AB:A4:6A done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26cf4 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 18
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:34:34.184Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:34.185Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:34.186Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3179): Found 7 peers.,
,I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3179): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/        ( 3179): Started service discovery
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8083"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT8083"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT8083, peerAddress: 34:FC:EF:11:B1:66
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT8083, WifiDirectName: , WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4546","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:,
I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4546","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4546, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4546, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3179): 2015-11-25T13:34:39.187Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:39.188Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3179): 
,D/btif_config( 3235): btif_get_device_type: Device [80:01:84:8a:b3:68] type 1,
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3235): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255
I/BTListenerThread( 3179): we got incoming connection
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255,
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3179): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTListenerThread( 3179): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 3179): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT501"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������,
I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
I/HS      ( 3179): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT501
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT501
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BTConnectedThread
I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271
,I/BtToRequestSocket( 3179): --DoOneRunRound ended
,I/jxcore-log( 3179): 2015-11-25T13:34:40.074Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:40.492Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:40.501Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:40.593Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:40.702Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:40.996Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:41.094Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:41.107Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:41.294Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:41.391Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:41.498Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:41.592Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:41.605Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:41.709Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:42.802Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:42.813Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:42.913Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3179): 2015-11-25T13:34:42.999Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:43.040Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:43.115Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:44.022Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:44.125Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:44.193Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:44.193Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:44.194Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:44.194Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 7C:F9:0E:37:96:AB
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3179): 2015-11-25T13:34:44.317Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27084 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:34:46.535Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:46.634Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:46.828Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:47.025Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:47.128Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:47.432Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,I/jxcore-log( 3179): 2015-11-25T13:34:48.032Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3179): 
,D/btif_config( 3235): btif_get_device_type: Device [7c:f9:0e:37:96:ab] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
D/BluetoothAdapterProperties( 3235): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3179): Starting to Handshake
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTConnectToThread( 3179): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 3179): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4546","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3179): HandshakeOk : samsung-SM-A500FU_PT4546
I/HS      ( 3179): Hand Shake finished outgoing for : samsung-SM-A500FU_PT4546
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, samsung-SM-A500FU_PT4546
,I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3179): mHTTPPort  set to : 36618
,I/BtConnectorHelper( 3179): Request socket is using : 36618
I/BtToRequestSocket( 3179): Now accepting connections
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27084 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :36618
,I/jxcore-log( 3179): 2015-11-25T13:34:49.003Z SendDataConnector.js: CLIENT connected to 36618, error: null
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:49.004Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 36618
,I/BtToRequestSocket( 3179): Set local streams
,I/BtToRequestSocket( 3179): rin ended ---------------------------;
,I/jxcore-log( 3179): 2015-11-25T13:34:49.014Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3179): 2015-11-25T13:34:49.143Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:49.210Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3179): 2015-11-25T13:34:49.265Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:49.354Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 3179): 2015-11-25T13:34:49.408Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:49.499Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:49.556Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data,
I/jxcore-log( 3179): 
I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/SS      ( 3179): Found 6 peers.,
I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3179): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/jxcore-log( 3179): 2015-11-25T13:34:49.592Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:49.645Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:49.729Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:49.745Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:49.815Z SendDataConnector.js: CLIENT is data received : 100000
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:49.816Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:49.817Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:49.817Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
I/BtConnectorHelper( 3179): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
,I/BtToRequestSocket( 3179): Close server socket
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3179): 2015-11-25T13:34:49.821Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB,
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:49.822Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:49.822Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:49.822Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
I/        ( 3179): Selected device address: 08:EC:A9:50:75:41, name: null
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 08:EC:A9:50:75:41
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:37:96:AB done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3179): 2015-11-25T13:34:49.850Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3179): 
,I/        ( 3179): Started service discovery
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27084 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,I/jxcore-log( 3179): 2015-11-25T13:34:51.258Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:51.359Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:51.365Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:51.458Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:51.471Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:51.672Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:51.966Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:51.973Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:52.073Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:52.575Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3179): 
,D/btif_config( 3235): btif_get_device_type: Device [08:ec:a9:50:75:41] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/jxcore-log( 3179): 2015-11-25T13:34:52.663Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data,
,I/jxcore-log( 3179): 
I/BluetoothBondStateMachine( 3235): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/jxcore-log( 3179): 2015-11-25T13:34:52.672Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:52.718Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:52.729Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26ebc rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:34:52.775Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:52.832Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:52.896Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3179): 
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3235): Failed to remove device: 08:EC:A9:50:75:41
I/BluetoothBondStateMachine( 3235): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/jxcore-log( 3179): 2015-11-25T13:34:53.167Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3179): 
I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,I/jxcore-log( 3179): 2015-11-25T13:34:53.170Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): invalid rfc slot id: 17,
,I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT501
I/BtToSocketBase( 3179): Stop ReceivingThread
,I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
,I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT501
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
,I/BtToSocketBase( 3179): Close bt socket
I/jxcore-log( 3179): 2015-11-25T13:34:53.241Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3179): Starting to Handshake
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: A5-1
,I/BTConnectToThread( 3179): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 3179): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3179): HandshakeOk : samsung-SM-A300FU_PT6613
I/HS      ( 3179): Hand Shake finished outgoing for : samsung-SM-A300FU_PT6613
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, samsung-SM-A300FU_PT6613
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): mHTTPPort  set to : 52322
,I/BtConnectorHelper( 3179): Request socket is using : 52322
I/BtToRequestSocket( 3179): Now accepting connections
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :52322
I/jxcore-log( 3179): 2015-11-25T13:34:54.425Z SendDataConnector.js: CLIENT connected to 52322, error: null
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:54.425Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 52322,
,I/BtToRequestSocket( 3179): Set local streams,
,I/jxcore-log( 3179): 2015-11-25T13:34:54.434Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,I/jxcore-log( 3179): 
I/BtToRequestSocket( 3179): rin ended ---------------------------;
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3179): 2015-11-25T13:34:54.728Z SendDataConnector.js: CLIENT is data received : 10000,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:54.796Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3179): 2015-11-25T13:34:54.944Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:55.032Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 3179): 2015-11-25T13:34:55.094Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:55.269Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:55.330Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:55.406Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:55.453Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:55.489Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:55.490Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:55.496Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:34:55.497Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
,I/BtConnectorHelper( 3179): Disconnect outgoing peer: 08:EC:A9:50:75:41,
I/BtToSocketBase( 3179): Stop ReceivingThread
,I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToRequestSocket( 3179): Close server socket
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3179): 2015-11-25T13:34:55.506Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:55.514Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:55.515Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:34:55.515Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:3F:54:73:64:C0, name: null
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 58:3F:54:73:64:C0
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27084 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3235): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 3235): RFCOMM_DisconnectInd LCID:0x4f
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: A3-1,
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4546","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:,
I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4546","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4546, peerAddress: 7C:F9:0E:37:96:AB,
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4546, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 22
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:35:00.653Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:00.656Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:00.657Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/jxcore-log( 3179): 2015-11-25T13:35:05.662Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:05.663Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/jxcore-log( 3179): 2015-11-25T13:35:10.667Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:10.668Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:10.669Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:10.669Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:3F:54:73:64:C0, name: null
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 58:3F:54:73:64:C0
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 23
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:35:15.827Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:15.827Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:15.828Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3179): Found 7 peers.,
I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b,
,I/SS      ( 3179): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3179): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 3179): 2015-11-25T13:35:20.830Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:20.831Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:25.835Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:25.836Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:25.837Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:25.837Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:3F:54:73:64:C0, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 58:3F:54:73:64:C0
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3235): invalid rfc slot id: 24
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:35:31.000Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:31.001Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:31.001Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:36.002Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:36.003Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3179): Found 7 peers.
I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3179): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3179): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery,
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032,
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3179): 2015-11-25T13:35:41.008Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:41.009Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:41.009Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:41.010Z SendDataConnector.js: do connect now,
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:3F:54:73:64:C0, name: null,
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 58:3F:54:73:64:C0,
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,D/btif_config( 3235): btif_get_device_type: Device [58:3f:54:73:64:c0] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
D/BluetoothAdapterProperties( 3235): Failed to remove device: 58:3F:54:73:64:C0
I/BluetoothBondStateMachine( 3235): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3179): Starting to Handshake
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTConnectToThread( 3179): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3179): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3179): HandshakeOk : LGE-LG-D855_PT4505
,I/HS      ( 3179): Hand Shake finished outgoing for : LGE-LG-D855_PT4505
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, LGE-LG-D855_PT4505
,I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3179): mHTTPPort  set to : 51375
,I/BtConnectorHelper( 3179): Request socket is using : 51375
I/BtToRequestSocket( 3179): Now accepting connections
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :51375
,I/jxcore-log( 3179): 2015-11-25T13:35:44.186Z SendDataConnector.js: CLIENT connected to 51375, error: null
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:44.187Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:44.194Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 51375
I/BtToRequestSocket( 3179): Set local streams
,I/BtToRequestSocket( 3179): rin ended ---------------------------;
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24843
,I/jxcore-log( 3179): 2015-11-25T13:35:44.515Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:44.589Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12963
,I/jxcore-log( 3179): 2015-11-25T13:35:44.636Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:44.735Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4053
,I/jxcore-log( 3179): 2015-11-25T13:35:44.811Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:44.903Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:45.016Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:45.068Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:45.112Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:45.214Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:45.214Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:45.228Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:45.229Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
,I/BtConnectorHelper( 3179): Disconnect outgoing peer: 58:3F:54:73:64:C0
,I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
,I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToRequestSocket( 3179): Close server socket
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3179): 2015-11-25T13:35:45.237Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:45.240Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:45.241Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:45.242Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: B0:C5:59:3F:75:69, name: null
I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at B0:C5:59:3F:75:69
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27414 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27414 rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,D/btif_config( 3235): btif_get_device_type: Device [b0:c5:59:3f:75:69] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1,
E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27414 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
D/BluetoothAdapterProperties( 3235): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3179): Starting to Handshake
,I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTConnectToThread( 3179): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3179): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3179): HandshakeOk : samsung-SM-G900F_PT2848
I/HS      ( 3179): Hand Shake finished outgoing for : samsung-SM-G900F_PT2848
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, samsung-SM-G900F_PT2848
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3179): mHTTPPort  set to : 59552
I/BtConnectorHelper( 3179): Request socket is using : 59552
I/BtToRequestSocket( 3179): Now accepting connections
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :59552
,I/jxcore-log( 3179): 2015-11-25T13:35:48.127Z SendDataConnector.js: CLIENT connected to 59552, error: null
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:48.130Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 59552
,I/BtToRequestSocket( 3179): Set local streams
I/jxcore-log( 3179): 2015-11-25T13:35:48.141Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): rin ended ---------------------------;
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f275dc rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:35:48.689Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3179): 2015-11-25T13:35:48.937Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: G3-1
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/jxcore-log( 3179): 2015-11-25T13:35:50.210Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:50.265Z SendDataConnector.js: CLIENT is data received : 40000,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:50.346Z SendDataConnector.js: CLIENT is data received : 50000,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:50.808Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:51.110Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:51.171Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:51.289Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:51.320Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:51.321Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:51.325Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:51.326Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
,I/BtConnectorHelper( 3179): Disconnect outgoing peer: B0:C5:59:3F:75:69
I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
,I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
,I/BtToSocketBase( 3179): Close bt socket
I/BtToRequestSocket( 3179): Close server socket
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3179): 2015-11-25T13:35:51.331Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3179): 
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:51.332Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:51.332Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:51.332Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 08:EC:A9:50:76:27, name: null
I/        ( 3179): Connecting to null, at 08:EC:A9:50:76:27
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f275dc rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f275dc rs_disc_pending=0,
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [b4:ce:f6:ab:a4:6a]: 6, 1d, 7d3
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820,
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f275dc rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26cf4 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26cf4 rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3179): we got incoming connection
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3179): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTListenerThread( 3179): got MESSAGE_READ 84 bytes.
,I/BTListenerThread( 3179): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3179): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT2890
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT2890
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BTConnectedThread
,I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271
,I/BtToRequestSocket( 3179): --DoOneRunRound ended,
I/jxcore-log( 3179): 2015-11-25T13:35:56.723Z SendDataTCPServer.js: TCP/IP server connected
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.097Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.107Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.166Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.204Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.227Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.241Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.302Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.341Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.353Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.372Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.385Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.448Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.480Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.494Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.505Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.517Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.527Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:35:57.561Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.610Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.624Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.648Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.681Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.686Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.711Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.769Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.801Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.813Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.844Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.856Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:35:57.874Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.915Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.929Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.956Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.967Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:57.979Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:58.013Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:58.068Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:58.096Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:58.110Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:58.120Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:58.160Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:35:58.164Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:58.237Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:58.270Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:58.284Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:35:58.292Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): invalid rfc slot id: 19
I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT2890
I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
,I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
,I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3179): 2015-11-25T13:35:58.369Z SendDataTCPServer.js: TCP/IP server is ended
,I/jxcore-log( 3179): 
W/bt-rfcomm( 3235): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 3235): RFCOMM_DisconnectInd LCID:0x4d
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3179): Found 6 peers.
I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4546","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4546","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4546, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4546, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,D/btif_config( 3235): btif_get_device_type: Device [08:ec:a9:50:76:27] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
D/BluetoothAdapterProperties( 3235): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3179): Starting to Handshake
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTConnectToThread( 3179): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 3179): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1985","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3179): HandshakeOk : samsung-SM-A300FU_PT1985
I/HS      ( 3179): Hand Shake finished outgoing for : samsung-SM-A300FU_PT1985
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, samsung-SM-A300FU_PT1985
,I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): mHTTPPort  set to : 56778
,I/BtConnectorHelper( 3179): Request socket is using : 56778
I/BtToRequestSocket( 3179): Now accepting connections
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :56778
,I/jxcore-log( 3179): 2015-11-25T13:36:10.539Z SendDataConnector.js: CLIENT connected to 56778, error: null
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:10.540Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 56778
I/BtToRequestSocket( 3179): Set local streams
I/jxcore-log( 3179): 2015-11-25T13:36:10.547Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): rin ended ---------------------------;
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:20888
,I/jxcore-log( 3179): 2015-11-25T13:36:10.749Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19039
,I/jxcore-log( 3179): 2015-11-25T13:36:10.855Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:11.072Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9139
,I/jxcore-log( 3179): 2015-11-25T13:36:11.301Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:11.478Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:11.694Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:11.813Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:11.997Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:12.097Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:12.102Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:12.103Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:12.106Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:12.107Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
,I/BtConnectorHelper( 3179): Disconnect outgoing peer: 08:EC:A9:50:76:27
,I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
,I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToRequestSocket( 3179): Close server socket
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3179): 2015-11-25T13:36:12.119Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:12.122Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:12.123Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:12.123Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND,
I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
I/BTConnectToThread( 3179): Starting to connect
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f277a4 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3179): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT501"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT501"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT501, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT501, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 29
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:36:13.721Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:13.722Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:13.723Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f277a4 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f277a4 rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/        ( 3179): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3179): 2015-11-25T13:36:18.724Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:18.725Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b,
,I/        ( 3179): Cleared service requests,
I/        ( 3179): Started peer discovery
,I/jxcore-log( 3179): 2015-11-25T13:36:23.729Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:23.729Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:23.730Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:23.731Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 30
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:36:25.045Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:25.046Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:25.046Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/SS      ( 3179): Found 5 peers.,
I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 3179): 2015-11-25T13:36:30.048Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:30.049Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 3179): 2015-11-25T13:36:35.053Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:35.054Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:35.054Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:35.055Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null,
,I/BTConnectToThread( 3179): Starting to connect
,I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 31
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:36:35.783Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:35.784Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:35.784Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:36:40.787Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:40.788Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,V/GoogleAuthProtoRequest( 3253): [339] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  824): Explicit concurrent mark sweep GC freed 47667(2MB) AllocSpace objects, 5(268KB) LOS objects, 31% free, 34MB/50MB, paused 2.194ms total 58.373ms
,W/ExperimentUpdateService( 3253): [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3253): [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3253): ,	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3253): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3253): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.a.a.a(SourceFile:167)
,W/ExperimentUpdateService( 3253): 	at com.a.a.a.g.a(SourceFile:79)
,W/ExperimentUpdateService( 3253): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3253): ,	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3253): [340] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3253): [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3253): [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3253): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3253): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3253): 	at com.a.a.k.run(SourceFile:110)
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [e0:db:10:1f:c9:5e]: 6, f, 410d
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3179): we got incoming connection
,I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread,
,I/BTListenerThread( 3179): waiting to accept incoming Connection,
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTListenerThread( 3179): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3179): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
I/HS      ( 3179): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT760
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, samsung-SM-N9005_PT760
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): Creating BTConnectedThread
I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271,
I/BtToRequestSocket( 3179): --DoOneRunRound ended
,I/jxcore-log( 3179): 2015-11-25T13:36:44.243Z SendDataTCPServer.js: TCP/IP server connected,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.649Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.652Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.682Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.691Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:36:44.698Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.733Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.771Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.784Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.822Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.836Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.870Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.884Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.900Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.906Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.940Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.983Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:44.989Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.035Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.046Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.071Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.109Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.120Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.163Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.231Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.239Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.247Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.251Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.305Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.340Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.349Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:45.353Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.360Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.366Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.392Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.430Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.441Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.480Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.489Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.520Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): invalid rfc slot id: 28
,I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT760
I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT760
I/BtToSocketBase( 3179): Close LocalOutputStream
,I/BtToSocketBase( 3179): Close localHostSocket,
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToSocketBase( 3179): Close bt socket
W/bt-rfcomm( 3235): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3235): RFCOMM_DisconnectInd LCID:0x4f
,I/jxcore-log( 3179): 2015-11-25T13:36:45.597Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.792Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:45.792Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:45.793Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:45.794Z SendDataConnector.js: do connect now,
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 6 peers.,
,I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3179): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3179): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f265d4 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f265d4 rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Note3-1
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [08:ec:a9:50:76:27]: 7, f, 6109,
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3179): we got incoming connection
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTListenerThread( 3179): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTListenerThread( 3179): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 3179): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1985","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3179): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT1985
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, samsung-SM-A300FU_PT1985
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): Creating BTConnectedThread
,I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271
,I/BtToRequestSocket( 3179): --DoOneRunRound ended
,I/jxcore-log( 3179): 2015-11-25T13:36:51.607Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:52.186Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:52.191Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:52.198Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:52.215Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:52.219Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:52.302Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:52.315Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data,
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): info:x10,
D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d,
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:36:52.384Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3179): 
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 33
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3179): 2015-11-25T13:36:52.630Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:52.630Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:52.631Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1985","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1985","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT1985, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT1985, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f277a4 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:36:53.407Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.411Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.417Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.423Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2796c rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:36:53.521Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.561Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.602Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.608Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.618Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.626Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.694Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.795Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:36:53.801Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.808Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.819Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.850Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.899Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.913Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:53.937Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.001Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.018Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.104Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.111Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.119Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.131Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.203Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.209Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.219Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.229Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.295Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:36:54.330Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.399Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.431Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.437Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.528Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.537Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
,I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2796c rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:36:54.633Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:36:54.841Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data,
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): invalid rfc slot id: 32,
I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT1985
I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
,I/BtToSocketBase( 3179): Close LocalOutputStream
,I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3179): 2015-11-25T13:36:55.153Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): 
,V/KeepSync( 3297): Connecting to GoogleApiClient
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1777): Handling authorization failure
E/ClientConnectionOperation( 1777): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1777): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1777): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1777): 	... 7 more
,V/KeepSync( 3297): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,E/KeepSync( 3297): IOException
E/KeepSync( 3297): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3297): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3297): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3297): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3297): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3297): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3297): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3297): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3297): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3297): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3297): 	... 10 more
W/KeepSync( 3297): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 662452, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f277a4 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:36:57.633Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:36:57.634Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Thali Test (Galaxy A3),
,I/jxcore-log( 3179): 2015-11-25T13:37:02.638Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:37:02.639Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:37:02.640Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:37:02.640Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3,
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 35
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:37:03.084Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:37:03.085Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:37:03.090Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:37:03.093Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:37:03.100Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:37:03.101Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): ,
I/jxcore-log( 3179): 2015-11-25T13:37:03.101Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): ,
,I/        ( 3179): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3179): Connecting to null, at 58:2A:F7:ED:96:BE
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2796c rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): info:x10,
D/        ( 3235): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL,
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2796c rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3179): Found 7 peers.
I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3179): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3179): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/        ( 3179): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT760, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT760, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:,
I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 7 peers.
,I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3179): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3179): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT760, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT760, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3235): invalid rfc slot id: 36
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:37:45.069Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
,I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:37:45.070Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:37:45.070Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 9 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3179): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3179): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3179): 2015-11-25T13:37:50.072Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:37:50.074Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28,
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3179): 2015-11-25T13:37:55.080Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:37:55.080Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:37:55.081Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:37:55.082Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BooksSync( 3504): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3504): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3504): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3504): Soft error
E/BooksSync( 3504): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3504): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3504): Sync error
E/BooksSync( 3504): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3504): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3504): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 706189, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 37
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:38:00.241Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:00.242Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:00.243Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 8 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3179): Started service discovery
,I/jxcore-log( 3179): 2015-11-25T13:38:05.243Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:38:05.244Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3179): 2015-11-25T13:38:10.249Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:10.250Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:10.250Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:38:10.251Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:2A:F7:ED:96:BE, name: null,
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 38
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:38:15.412Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:15.412Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:15.413Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3179): Found 8 peers.,
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3179): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3179): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/jxcore-log( 3179): 2015-11-25T13:38:20.413Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:20.414Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78,
,I/        ( 3179): Started service discovery,
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:,
,I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3179): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6613, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6613, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3179): 2015-11-25T13:38:25.419Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:25.419Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:38:25.420Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:38:25.420Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3179): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [58:2a:f7:ed:96:be]: 6, f, 410d
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [7c:f9:0e:34:8a:a0]: 6, 10f, 608
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26964 rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255,
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200,
I/BTListenerThread( 3179): we got incoming connection
,I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3179): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=0,
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26964 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3179): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3179): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3179): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT8472
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, samsung-SM-G900F_PT8472
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BTConnectedThread
,I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/jxcore-log( 3179): 2015-11-25T13:38:33.016Z SendDataTCPServer.js: TCP/IP server connected
,I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271
,I/BtToRequestSocket( 3179): --DoOneRunRound ended,
,I/jxcore-log( 3179): 2015-11-25T13:38:33.549Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:33.553Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:33.668Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:33.719Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:33.825Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:33.839Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:33.892Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:33.895Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:33.912Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:33.970Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:33.976Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.011Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.055Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.059Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/jxcore-log( 3179): 2015-11-25T13:38:34.114Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.175Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.186Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.191Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.195Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.201Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.241Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.246Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.281Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.293Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.298Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.331Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.361Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.365Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.372Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.377Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.411Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.419Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:38:34.495Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:38:34.530Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): invalid rfc slot id: 34
I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT8472
I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT8472
I/BtToSocketBase( 3179): Close LocalOutputStream
,I/BtToSocketBase( 3179): Close localHostSocket
,I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
,I/BtToSocketBase( 3179): Close bt socket
I/jxcore-log( 3179): 2015-11-25T13:38:34.618Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26964 rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3235): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 3235): RFCOMM_DisconnectInd LCID:0x4a
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 8 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: S5-1,
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3179): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6613, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6613, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2949): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at blb.a(PG:3937)
E/HttpOperation( 2949): 	at czp.a(PG:18188)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 12 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2949): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at hec.a(PG:42)
E/HttpOperation( 2949): 	at hee.a(PG:102)
E/HttpOperation( 2949): 	at czr.a(PG:65)
E/HttpOperation( 2949): 	at kka.a(PG:108)
E/HttpOperation( 2949): 	at czp.a(PG:19176)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 15 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 17 more
,E/ExperimentLoader( 2949): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 2949): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): 	at jdm.a(PG:82)
E/ExperimentLoader( 2949): 	at jcs.o(PG:406)
E/ExperimentLoader( 2949): ,	at jcn.a(PG:1379)
E/ExperimentLoader( 2949): 	at jcs.i(PG:143)
E/ExperimentLoader( 2949): 	at hec.a(PG:42)
E/ExperimentLoader( 2949): ,	at hee.a(PG:102)
E/ExperimentLoader( 2949): 	at czr.a(PG:65)
E/ExperimentLoader( 2949): 	at kka.a(PG:108)
E/ExperimentLoader( 2949): ,	at czp.a(PG:19176)
E/ExperimentLoader( 2949): 	at czp.a(PG:9081)
E/ExperimentLoader( 2949): 	at czq.run(PG:1686)
E/ExperimentLoader( 2949): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/ExperimentLoader( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2949): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2949): 	at jdj.a(PG:1125)
,E/ExperimentLoader( 2949): 	at jdm.a(PG:77)
E/ExperimentLoader( 2949): 	... 15 more
E/ExperimentLoader( 2949): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2949): 	at fal.a(PG:38),
E/ExperimentLoader( 2949): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2949): 	... 17 more
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 768776, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 7 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3235): invalid rfc slot id: 39
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:39:06.927Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:06.928Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:06.929Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/jxcore-log( 3179): 2015-11-25T13:39:11.931Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:11.932Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3179): Found 8 peers.
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 3179): 2015-11-25T13:39:16.936Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:16.936Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:16.937Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:16.937Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3179): Connecting to null, at 58:2A:F7:ED:96:BE,
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 41
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:39:22.097Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:22.098Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:22.101Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:22.103Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:22.106Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:22.107Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:22.107Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
I/        ( 3179): Selected device address: E0:DB:10:14:E2:C0, name: null
I/        ( 3179): Connecting to null, at E0:DB:10:14:E2:C0
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 42
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3179): 2015-11-25T13:39:23.097Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:23.099Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:23.099Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27cfc rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 9 peers.
I/SS      ( 3179): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3179): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3179): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6613, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6613, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:39:28.101Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:28.102Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6456","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6456","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6456, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6456, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,I/jxcore-log( 3179): 2015-11-25T13:39:33.105Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:33.106Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:33.106Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:33.107Z SendDataConnector.js: do connect now,
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: E0:DB:10:14:E2:C0, name: null,
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 43
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:39:33.389Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:33.390Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:33.391Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27cfc rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:39:38.392Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:38.393Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [34:fc:ef:9d:93:0b]: 7, f, 2205
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Thali Test's G2
,D/btif_config( 3235): btif_get_device_type: Device [34:fc:ef:9d:93:0b] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1,
,E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3235): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 3235): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,I/        ( 3179): Cleared service requests,
,I/        ( 3179): Started peer discovery
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3179): we got incoming connection
,I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTListenerThread( 3179): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTListenerThread( 3179): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3179): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3179): Incoming connection Hand Shake finished for : LGE-LG-D802_PT4660
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, LGE-LG-D802_PT4660
,I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BTConnectedThread
I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271
,I/BtToRequestSocket( 3179): --DoOneRunRound ended
I/jxcore-log( 3179): 2015-11-25T13:39:42.922Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:43.387Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:43.397Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:43.398Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:43.399Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:43.399Z SendDataConnector.js: do connect now,
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3179): 2015-11-25T13:39:43.442Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f25eb4 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:39:43.706Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:43.713Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:43.933Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:44.079Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:44.169Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:44.467Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:44.631Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:44.712Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:44.857Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f25eb4 rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:39:45.941Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.089Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.128Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.199Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.203Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.410Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.417Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data,
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [e0:db:10:14:e2:c0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:39:46.498Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.592Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.599Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3179): 
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 45
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3179): 2015-11-25T13:39:46.770Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.770Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.771Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f25eb4 rs_disc_pending=1,
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:39:46.840Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.854Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.905Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.912Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:46.996Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.045Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.052Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.127Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.160Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.247Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.294Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.353Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.389Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.450Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.479Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.554Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.639Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:47.743Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:48.088Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:48.164Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 10 peers.,
I/SS      ( 3179): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3179): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3179): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3179): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3179): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/jxcore-log( 3179): 2015-11-25T13:39:48.354Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:48.385Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:48.413Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:48.523Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:48.547Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:48.596Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:48.650Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:48.819Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:48.925Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:49.015Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:49.145Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3179): 
,I/        ( 3179): Started service discovery
,I/jxcore-log( 3179): 2015-11-25T13:39:49.252Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f25eb4 rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): invalid rfc slot id: 40
,I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT4660
I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3179): 2015-11-25T13:39:49.864Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): ,
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3179): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT760, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT760, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f25eb4 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27cfc rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3235): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3235): RFCOMM_DisconnectInd LCID:0x4f
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/jxcore-log( 3179): 2015-11-25T13:39:51.771Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:51.772Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive,
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Thali Test's G2
,I/jxcore-log( 3179): 2015-11-25T13:39:56.776Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:39:56.777Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:56.777Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:39:56.778Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: E0:DB:10:14:E2:C0, name: null,
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 11 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Android_2dc2 52:55:27:f0:ff:f0,
I/SS      ( 3179): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3179): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(9): Note3-1 ea:50:8b:de:28:a3,
I/SS      ( 3179): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(11): Android_8ae2 52:55:27:f0:fd:0b,
D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0,
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery,
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032,
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 46
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:40:11.814Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:40:11.815Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:11.817Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27cfc rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3179): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT760, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT760, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:40:16.819Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:16.820Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:21.823Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:21.824Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:40:21.824Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
,I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:40:21.825Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3179): Connecting to null, at E0:DB:10:14:E2:C0,
,I/        ( 3179): Cleared service requests,
,I/        ( 3179): Started peer discovery,
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [e0:db:10:14:e2:c0]: 6, f, 4106
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 47
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:40:22.609Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:22.610Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:22.614Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:22.620Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:40:22.621Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:40:22.621Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:40:22.621Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: F4:F1:E1:5C:3B:E2, name: null
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at F4:F1:E1:5C:3B:E2
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27cfc rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27ec4 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27ec4 rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,D/btif_config( 3235): btif_get_device_type: Device [f4:f1:e1:5c:3b:e2] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
,E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3235): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3179): Starting to Handshake
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started,
,I/BTConnectToThread( 3179): got MESSAGE_READ 81 bytes.,
I/BTConnectToThread( 3179): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3179): HandshakeOk : motorola-XT1039_PT3278
I/HS      ( 3179): Hand Shake finished outgoing for : motorola-XT1039_PT3278
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, motorola-XT1039_PT3278
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): mHTTPPort  set to : 47263
,I/BtConnectorHelper( 3179): Request socket is using : 47263
I/BtToRequestSocket( 3179): Now accepting connections
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :47263
,I/jxcore-log( 3179): 2015-11-25T13:40:26.313Z SendDataConnector.js: CLIENT connected to 47263, error: null
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:26.315Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 47263
,I/BtToRequestSocket( 3179): Set local streams
I/BtToRequestSocket( 3179): rin ended ---------------------------;
I/jxcore-log( 3179): 2015-11-25T13:40:26.327Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8600
,I/jxcore-log( 3179): 2015-11-25T13:40:26.433Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18049
,I/jxcore-log( 3179): 2015-11-25T13:40:26.478Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3179): 2015-11-25T13:40:26.493Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:26.558Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3199
,I/jxcore-log( 3179): 2015-11-25T13:40:26.600Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:26.703Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:26.781Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:26.839Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:26.863Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:26.863Z SendDataConnector.js: got all data for this round,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:26.868Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:26.868Z SendDataConnector.js: CLIENT closeClientSocket
,I/jxcore-log( 3179): 
I/BtConnectorHelper( 3179): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
I/BtToSocketBase( 3179): Stop ReceivingThread
,I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream,
I/BtToSocketBase( 3179): Close localHostSocket
,I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
,I/BtToSocketBase( 3179): Close bt socket
I/BtToRequestSocket( 3179): Close server socket
,I/jxcore-log( 3179): 2015-11-25T13:40:26.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3179): 
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed,
I/jxcore-log( 3179): ---- round done--------
,I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/jxcore-log( 3179): 2015-11-25T13:40:26.877Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): ,
I/jxcore-log( 3179): 2015-11-25T13:40:26.877Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:26.878Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
I/        ( 3179): Selected device address: 50:2E:6C:AC:21:50, name: null,
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback,
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/        ( 3179): Connecting to null, at 50:2E:6C:AC:21:50
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27ec4 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 49
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:40:32.469Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:32.471Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:32.472Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 11 peers.
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3179): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3179): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3179): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3179): 2015-11-25T13:40:37.476Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:37.495Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:42.499Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:42.500Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:40:42.500Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:42.501Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): ,
,I/        ( 3179): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 50:2E:6C:AC:21:50
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 50
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3179): 2015-11-25T13:40:47.661Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:47.662Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:40:47.663Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,E/bt-l2cap( 3235): L2CAP got conn_comp in bad state: 5  status: 0x15
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: XT1039
,I/jxcore-log( 3179): 2015-11-25T13:40:52.664Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:40:52.665Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:57.668Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:40:57.669Z SendDataConnector.js: Connect (retry count 2) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:57.670Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:40:57.670Z SendDataConnector.js: do connect now,
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 50:2E:6C:AC:21:50
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [f4:f1:e1:5c:3b:e2]: 7, f, 2205
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 51
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:41:02.827Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:02.828Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:02.828Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3179): 2015-11-25T13:41:07.829Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:07.830Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:12.834Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:12.835Z SendDataConnector.js: Connect (retry count 3) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:12.836Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:12.836Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 50:2E:6C:AC:21:50, name: null,
,I/BTConnectToThread( 3179): Starting to connect
,I/        ( 3179): Connecting to null, at 50:2E:6C:AC:21:50
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 52
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:41:17.988Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:17.989Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:17.989Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/jxcore-log( 3179): 2015-11-25T13:41:22.991Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:22.992Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:27.995Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:27.996Z SendDataConnector.js: Connect (retry count 4) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:27.996Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:41:27.997Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/BTConnectToThread( 3179): Starting to connect,
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback,
I/        ( 3179): Connecting to null, at 50:2E:6C:AC:21:50
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 53
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:41:33.157Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:33.158Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:33.161Z SendDataConnector.js: CLIENT Stop now,
,I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:33.165Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- gotta redo : 50:2E:6C:AC:21:50, try count now: 1
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:33.170Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:33.171Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:33.171Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820,
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 50:2E:6C:AC:21:50 done with result: Connection to 50:2E:6C:AC:21:50 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820,
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27084 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 54
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:41:34.583Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:34.584Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:34.585Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 7 peers.
,I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3179): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3179): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3179): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive,
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3179): 2015-11-25T13:41:39.587Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:39.588Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3179): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6613, peerAddress: 08:EC:A9:50:75:41,
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6613, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41,
,I/jxcore-log( 3179): 2015-11-25T13:41:44.592Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:44.593Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:44.593Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:44.594Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820,
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3,
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 55
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:41:45.605Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:45.607Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:45.608Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/jxcore-log( 3179): 2015-11-25T13:41:50.609Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:50.610Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/SS      ( 3179): Found 3 peers.
,I/SS      ( 3179): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,I/jxcore-log( 3179): 2015-11-25T13:41:55.613Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:55.613Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:55.614Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:55.614Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:,
I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 56
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3179): 2015-11-25T13:41:55.967Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:41:55.968Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:41:55.969Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3235): onReceive,
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820,
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/jxcore-log( 3179): 2015-11-25T13:42:00.970Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:42:00.970Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/jxcore-log( 3179): 2015-11-25T13:42:05.974Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:05.975Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:05.976Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:42:05.976Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3179): Starting to connect,
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68,
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 57
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3179): 2015-11-25T13:42:07.309Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:42:07.310Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:07.310Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3235): L2CAP got sec_comp for unknown BD_ADDR
,D/BluetoothMapService( 3235): onReceive,
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: XT1039
,I/art     (  824): Explicit concurrent mark sweep GC freed 58516(2MB) AllocSpace objects, 8(410KB) LOS objects, 31% free, 34MB/50MB, paused 1.629ms total 104.755ms
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3179): Found 5 peers.
I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3179): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,I/        ( 3179): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3179): 2015-11-25T13:42:12.310Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:12.311Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: XT1039
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3179): we got incoming connection
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3179): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTListenerThread( 3179): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3179): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3179): Incoming connection Hand Shake finished for : motorola-XT1039_PT3278
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, motorola-XT1039_PT3278
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): Creating BTConnectedThread
I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271,
I/BtToRequestSocket( 3179): --DoOneRunRound ended
,I/jxcore-log( 3179): 2015-11-25T13:42:12.740Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.123Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.128Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.134Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.143Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.147Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.155Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.162Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.200Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.225Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.231Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.241Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.282Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.325Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.336Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.342Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.349Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.381Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.385Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3179): 2015-11-25T13:42:13.442Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.480Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.492Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.501Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.540Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.543Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.594Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.631Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.648Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.664Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.678Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.686Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [b0:c5:59:3f:75:69]: 7, 1d, 7d3
,I/jxcore-log( 3179): 2015-11-25T13:42:13.720Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3179): 
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3179): 2015-11-25T13:42:13.751Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27ec4 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:42:13.946Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.959Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:13.967Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:14.003Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:14.005Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:42:14.009Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:14.062Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:14.069Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:14.076Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:14.079Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data,
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f275dc rs_disc_pending=0,
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 3235): invalid rfc slot id: 44,
I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT3278
I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
,I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
,I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3179): 2015-11-25T13:42:14.142Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f275dc rs_disc_pending=1,
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3179): we got incoming connection
,I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTListenerThread( 3179): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTListenerThread( 3179): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3179): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
I/HS      ( 3179): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT2848
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, samsung-SM-G900F_PT2848
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): Creating BTConnectedThread
I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271
,I/BtToRequestSocket( 3179): --DoOneRunRound ended
,I/jxcore-log( 3179): 2015-11-25T13:42:15.489Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:15.984Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.019Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.041Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.046Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3179): 
,W/bt-rfcomm( 3235): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3235): RFCOMM_DisconnectInd LCID:0x49
,I/jxcore-log( 3179): 2015-11-25T13:42:16.107Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.112Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.175Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.179Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.223Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.230Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.235Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.296Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.331Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.360Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.366Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.382Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.437Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.486Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.522Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.530Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.580Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.615Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.624Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.746Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27ec4 rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:42:16.851Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:16.891Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.001Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.256Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.314Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.315Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.315Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.316Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
I/jxcore-log( 3179): 2015-11-25T13:42:17.341Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3179): 
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3179): 2015-11-25T13:42:17.394Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.430Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.453Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.520Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.529Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.562Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.565Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.571Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.609Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.639Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.712Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27ec4 rs_disc_pending=1
,I/jxcore-log( 3179): 2015-11-25T13:42:17.716Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3179): 
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:42:17.782Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.849Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.917Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:17.979Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f275dc rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6613, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6613, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,W/bt-btif ( 3235): invalid rfc slot id: 58
,I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2848
I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
,I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2848
,I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt in
,I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToSocketBase( 3179): Close bt socket
I/jxcore-log( 3179): 2015-11-25T13:42:19.003Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f275dc rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3235): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 3235): RFCOMM_DisconnectInd LCID:0x4d
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive,
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524],
I/BluetoothClassifier( 3967): Bluetooth Device Name: XT1039
,W/bt-btif ( 3235): info:x10,
D/        ( 3235): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820,
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f275dc rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3235): process_service_search_attr_rsp,
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 60
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3179): 2015-11-25T13:42:20.358Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:20.359Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:20.362Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:20.365Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:42:20.367Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:42:20.368Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:42:20.368Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to G4-1, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63),
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f275dc rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: G4-1
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive,
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive,
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 7 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6613, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6613, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3179): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-l2cap( 3235): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-l2cap( 3235): L2CAP - con rsp - bad ID. Exp: 6 Got: 3
,W/bt-l2cap( 3235): L2CAP - con rsp - bad ID. Exp: 6 Got: 5
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 9 peers.
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2640c rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,D/btif_config( 3235): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3235): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3235): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3235): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 3235): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3235): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3235): StableState(): Entering Off State
,I/        ( 3179): Cleared service requests,
,I/        ( 3179): Started peer discovery
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3179): Starting to Handshake
,I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3179): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2640c rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3179): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3179): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3179): HandshakeOk : LGE-LG-H815_PT1965
I/HS      ( 3179): Hand Shake finished outgoing for : LGE-LG-H815_PT1965
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : false, LGE-LG-H815_PT1965
I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3179): mHTTPPort  set to : 54941
I/BtConnectorHelper( 3179): Request socket is using : 54941
I/BtToRequestSocket( 3179): Now accepting connections
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/BtConnectorHelper( 3179): Calling ConnectionStatusUpdate with port :54941
,I/jxcore-log( 3179): 2015-11-25T13:43:00.946Z SendDataConnector.js: CLIENT connected to 54941, error: null
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:00.947Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3179): 
,I/BtToRequestSocket( 3179): incoming data from: /127.0.0.1, port: 54941
,I/BtToRequestSocket( 3179): Set local streams
I/BtToRequestSocket( 3179): rin ended ---------------------------;
,I/jxcore-log( 3179): 2015-11-25T13:43:00.957Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3179): 
,D/        ( 3235): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3373
,I/jxcore-log( 3179): 2015-11-25T13:43:01.432Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:01.493Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:01.894Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:01.994Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:02.319Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:02.605Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:02.868Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:03.464Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3179): 
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/jxcore-log( 3179): 2015-11-25T13:43:03.582Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/SS      ( 3179): Found 9 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/jxcore-log( 3179): 2015-11-25T13:43:04.046Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:04.047Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:04.050Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:04.050Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3179): 
,I/BtConnectorHelper( 3179): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToRequestSocket( 3179): Close server socket
I/jxcore-log( 3179): 2015-11-25T13:43:04.056Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:04.058Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:04.059Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:04.059Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C,
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:3C:51 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2640c rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 3235): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/EventLogService( 1777): Opted in for usage reporting
,I/EventLogService( 1777): Aggregate from 1448457135603 (log), 1448457135603 (data)
,W/EventLogAggregator( 1777): Unknown tag: snet_gcore
W/EventLogAggregator( 1777): Unknown tag: snet_launch_service
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 66510(3MB) AllocSpace objects, 13(1434KB) LOS objects, 37% free, 27MB/43MB, paused 1.203ms total 61.535ms
,I/ServiceDumpSys( 1777): dumping service [account]
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2640c rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3235): info:x10,
,D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 62
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:43:09.859Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:09.859Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:09.860Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2796c rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2640c rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/jxcore-log( 3179): 2015-11-25T13:43:14.861Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:14.861Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 9 peers.
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/jxcore-log( 3179): 2015-11-25T13:43:19.865Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:19.866Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:19.867Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:19.867Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/BTConnectToThread( 3179): Starting to connect,
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 63
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3179): 2015-11-25T13:43:21.515Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:21.517Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:21.518Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/GCM     ( 1489): Message class com.google.f.a.a.i
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:43:26.521Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:26.522Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/jxcore-log( 3179): 2015-11-25T13:43:31.525Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:31.526Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:31.526Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:31.527Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 64
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:43:32.761Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:32.761Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:32.762Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 9 peers.
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3179): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:43:37.764Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): ,
I/jxcore-log( 3179): 2015-11-25T13:43:37.765Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:,
I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69,
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6613, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6613, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 3179): 2015-11-25T13:43:42.769Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:42.769Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true,
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:42.770Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:42.770Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3179): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 65
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:43:44.770Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:44.772Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:44.773Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL,
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/jxcore-log( 3179): 2015-11-25T13:43:49.774Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:49.775Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Found 7 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,I/jxcore-log( 3179): 2015-11-25T13:43:54.779Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:54.780Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:54.780Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:54.781Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:,
I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 66
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:43:56.326Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:56.326Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:56.330Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:56.332Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 2
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start,
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:56.334Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:43:56.335Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:43:56.335Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 58:2A:F7:ED:96:BE
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [58:2a:f7:ed:96:be]: 7, f, 610c
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1,
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:,
I/        ( 3179): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag,
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2796c rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag,
W/bt-btif ( 3235): invalid rfc slot id: 67
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3179): 2015-11-25T13:44:01.682Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:44:01.682Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:01.683Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/jxcore-log( 3179): 2015-11-25T13:44:06.684Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:06.685Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 7 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d,
I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d,
I/SS      ( 3179): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,I/jxcore-log( 3179): 2015-11-25T13:44:11.688Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:44:11.689Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:44:11.689Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:44:11.690Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [58:2a:f7:ed:96:be]: 6, f, 410d
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 3235): invalid rfc slot id: 68
,W/bt-btif ( 3235): invalid rfc slot id: 68
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
I/jxcore-log( 3179): 2015-11-25T13:44:17.692Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:44:17.692Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:17.693Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Found 6 peers.
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 3179): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/jxcore-log( 3179): 2015-11-25T13:44:22.693Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:22.694Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3179): 2015-11-25T13:44:27.697Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:44:27.698Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:27.699Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:44:27.699Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3179): Starting to connect
,I/        ( 3179): Connecting to null, at 58:2A:F7:ED:96:BE
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=0
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0,
E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3235): invalid rfc slot id: 69
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:44:36.660Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:44:36.661Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:44:36.662Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3179): Found 6 peers.
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [34:fc:ef:11:ae:67]: 6, 10f, 608
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3179): we got incoming connection
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3179): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTListenerThread( 3179): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3179): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6456","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
I/HS      ( 3179): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT6456
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, LGE-Nexus 5_PT6456
,I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BTConnectedThread
I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271,
I/BtToRequestSocket( 3179): --DoOneRunRound ended
,I/jxcore-log( 3179): 2015-11-25T13:44:41.195Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3179): 2015-11-25T13:44:41.629Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:41.664Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:41.665Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:41.696Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:41.705Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:41.708Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:41.711Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:41.763Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:41.772Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:41.811Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:41.936Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:41.946Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:41.950Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3179): 
,V/GoogleAuthProtoRequest( 3253): [341] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/jxcore-log( 3179): 2015-11-25T13:44:42.068Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3179): 
,W/ExperimentUpdateService( 3253): [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3253): [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
W/ExperimentUpdateService( 3253): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3253): ,	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3253): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3253): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3179): 2015-11-25T13:44:42.123Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3179): 
,V/GoogleAuthProtoRequest( 3253): [342] a.<init>: mAccountName set to: thalitester@gmail.com
,I/jxcore-log( 3179): 2015-11-25T13:44:42.256Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.302Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.310Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3179): 
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova,
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3179): 2015-11-25T13:44:42.365Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data,
I/jxcore-log( 3179): 
,W/ExperimentUpdateService( 3253): [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.,
W/ExperimentUpdateService( 3253): [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3253): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3253): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3253): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3253): 	,at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3253): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3253): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3179): 2015-11-25T13:44:42.400Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data,
,I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:44:42.406Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.416Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.575Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.584Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.620Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.637Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.697Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.748Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.753Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.790Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.815Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.825Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:44:42.829Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.916Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.922Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.960Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.963Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.968Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:42.975Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:43.017Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:43.027Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:43.035Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:43.082Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:43.091Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:43.130Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:43.143Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:43.147Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:43.155Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:43.189Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:43.221Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:43.227Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): invalid rfc slot id: 59
,I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT6456
I/BtToSocketBase( 3179): Stop ReceivingThread
,I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
,I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3179): 2015-11-25T13:44:43.340Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): 
,W/bt-rfcomm( 3235): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 3235): RFCOMM_DisconnectInd LCID:0x47
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3179): 2015-11-25T13:44:46.669Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:44:46.669Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:44:46.670Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:44:46.670Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3179): Starting to connect,
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f26b2c rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [58:2a:f7:ed:96:be]: 7, f, 6109
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 5 peers.
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 3179): Added service request
,V/KeepSync( 3297): Connecting to GoogleApiClient
,I/        ( 3179): Started service discovery
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1777): Handling authorization failure
E/ClientConnectionOperation( 1777): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1777): 	,at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1777): 	at java.lang.Thread.run(Thread.java:818)
,E/ClientConnectionOperation( 1777): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1777): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1777): 	... 7 more,
V/KeepSync( 3297): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3297): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3297): IOException
E/KeepSync( 3297): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3297): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3297): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3297): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3297): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3297): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3297): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3297): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3297): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3297): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3297): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3297): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3297): 	... 10 more
W/KeepSync( 3297): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1144510, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3278"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3278, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3278, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 7 peers.
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2,
I/SS      ( 3179): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 8 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3179): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 8 peers.,
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3179): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/BtConnection( 3179): connectionTimeoutTimer
E/bt-btif ( 3235): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:71, channel:-1
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: Cancelled
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:45:46.681Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:45:46.682Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:45:46.683Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
W/jxcore-log( 3179): $$jxcore_callback_114 wasn't registered
W/jxcore-log( 3179): 
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4b
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 71
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/jxcore-log( 3179): 2015-11-25T13:45:51.684Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:45:51.685Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3179): Found 8 peers.
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3179): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,I/jxcore-log( 3179): 2015-11-25T13:45:56.689Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:45:56.690Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:45:56.690Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:45:56.691Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 58:2A:F7:ED:96:BE
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 8 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [58:3f:54:73:64:c0]: 6, 10f, 608
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: G3-1
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3179): we got incoming connection
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3179): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,I/BTListenerThread( 3179): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3179): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3179): Incoming connection Hand Shake finished for : LGE-LG-D855_PT4505
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, LGE-LG-D855_PT4505
,I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BTConnectedThread
I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271
,I/BtToRequestSocket( 3179): --DoOneRunRound ended
,I/jxcore-log( 3179): 2015-11-25T13:46:19.580Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:46:19.970Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:19.974Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:19.986Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.023Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.026Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.039Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.044Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.080Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.117Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.120Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.152Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:46:20.168Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:46:20.173Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.210Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.253Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.260Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.292Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.350Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.390Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.433Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.439Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.459Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.559Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.590Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.600Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.606Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.626Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.660Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.748Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.751Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.792Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.831Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.869Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.881Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.904Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.942Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:20.981Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:21.022Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:21.032Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:21.042Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:21.060Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:21.101Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:21.111Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:21.188Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:21.220Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:21.223Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:21.230Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): invalid rfc slot id: 70
,I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT4505
,I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
,I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
,I/BtToSocketBase( 3179): Close bt out
,I/BtToSocketBase( 3179): Close bt socket
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/jxcore-log( 3179): 2015-11-25T13:46:21.680Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/SS      ( 3179): Found 6 peers.
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3235): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
,W/bt-rfcomm( 3235): RFCOMM_DisconnectInd LCID:0x48
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 72
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:46:24.470Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:24.471Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:24.474Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:46:24.477Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 2
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:46:24.480Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:24.480Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:46:24.480Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
I/        ( 3179): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at E0:DB:10:14:E2:C0
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/UsageStatsService(  824): User[0] Flushing usage stats to disk
,I/BooksSync( 3504): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3504): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27414 rs_disc_pending=0
,W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3504): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3504): Soft error
E/BooksSync( 3504): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3504): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3504): Sync error
E/BooksSync( 3504): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3504): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3504): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1231906, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: G3-1
,W/bt-btif ( 3235): info:x10,
,D/        ( 3235): remote version info [e0:db:10:14:e2:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 74,
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:46:26.873Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:46:26.873Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:26.874Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3179): 2015-11-25T13:46:31.874Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:46:31.875Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:36.879Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:46:36.880Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:36.880Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:36.881Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
I/        ( 3179): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3179): Starting to connect,
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 3235): invalid rfc slot id: 75
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/jxcore-log( 3179): 2015-11-25T13:46:40.994Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:46:40.995Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:40.995Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3179): Found 6 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3179): Started service discovery
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:46:45.997Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:45.997Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:51.002Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:51.003Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:46:51.004Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:51.004Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3179): Connecting to null, at E0:DB:10:14:E2:C0
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/SS      ( 3179): Found 5 peers.
,I/SS      ( 3179): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 3235): invalid rfc slot id: 76
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:46:52.591Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed,
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:46:52.592Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:46:52.593Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/        ( 3179): Started service discovery
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3179): 2015-11-25T13:46:57.593Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:46:57.594Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3179): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4505","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4505, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4505, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3179): 2015-11-25T13:47:02.597Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:02.598Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:02.598Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:02.599Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0,
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 77
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:47:04.187Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:04.188Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:04.189Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/        ( 3179): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT760, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT760, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6456","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6456","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT6456, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT6456, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:47:09.191Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:09.191Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [08:ec:a9:50:75:41]: 7, f, 2205
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: A3-1
,I/jxcore-log( 3179): 2015-11-25T13:47:14.195Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:14.196Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:14.196Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:14.197Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at E0:DB:10:14:E2:C0
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3235): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3235): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3179): we got incoming connection
I/BTHandshakeSocketThread( 3179): Creating BTHandshakeSocketThread
I/BTListenerThread( 3179): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread started
,W/bt-btif ( 3235): info:x10,
D/        ( 3235): remote version info [e0:db:10:14:e2:c0]: 7, f, 6109
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/BTListenerThread( 3179): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 3179): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6613","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3179): MESSAGE_WRITE 82 bytes.
I/HS      ( 3179): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT6613
I/BTHandshakeSocketThread( 3179): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3179): Starting the connected thread incoming : true, samsung-SM-A300FU_PT6613
,I/BtToSocketBase( 3179): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3179): Creating BTConnectedThread
I/BtConnectorHelper( 3179): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3179): --DoOneRunRound started
,I/BtToRequestSocket( 3179): LocalHost address: localhost/127.0.0.1, port: 43271
,I/BtToRequestSocket( 3179): --DoOneRunRound ended
,I/jxcore-log( 3179): 2015-11-25T13:47:15.842Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3179): 
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 78
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:47:16.150Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:16.150Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:16.154Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:16.156Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 2
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:16.159Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:16.160Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:16.161Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/BTConnectToThread( 3179): Starting to connect,
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 50:2E:6C:AC:21:50
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,I/jxcore-log( 3179): 2015-11-25T13:47:16.263Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:16.422Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:47:16.565Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:16.649Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:16.727Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:16.967Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:16.998Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:17.059Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:17.068Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:17.076Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:17.082Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:17.118Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:17.150Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:17.213Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:47:17.220Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:17.261Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:17.301Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:17.589Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:47:17.752Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:17.824Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:17.976Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:18.138Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:18.301Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data,
,I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): 2015-11-25T13:47:18.375Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:18.552Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:18.647Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:18.829Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:18.904Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:19.000Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:19.191Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:19.281Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:19.378Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:19.557Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL,
,I/jxcore-log( 3179): 2015-11-25T13:47:19.827Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data,
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/jxcore-log( 3179): 2015-11-25T13:47:20.093Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:20.271Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:20.361Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:20.448Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:20.627Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:20.912Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3179): Found 8 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(6): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3179): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/jxcore-log( 3179): 2015-11-25T13:47:21.170Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:21.259Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3179): 
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 3235): invalid rfc slot id: 80
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:47:21.305Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:21.307Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:21.308Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:21.363Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:21.373Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:21.380Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:21.420Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:21.449Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:21.459Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:21.462Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3179): 
,W/bt-btif ( 3235): invalid rfc slot id: 73
,I/BtToSocketBase( 3179): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6613
,I/BtToSocketBase( 3179): Stop ReceivingThread
I/BtToSocketBase( 3179): Stop SendingThread
I/BtToSocketBase( 3179): Close local in
I/BtToSocketBase( 3179): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3179): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6613
I/BtToSocketBase( 3179): Close LocalOutputStream
I/BtToSocketBase( 3179): Close localHostSocket
I/BtToSocketBase( 3179): Close bt in
,I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
I/BtToSocketBase( 3179): Close bt in
I/BtToSocketBase( 3179): Close bt out
I/BtToSocketBase( 3179): Close bt socket
,I/jxcore-log( 3179): 2015-11-25T13:47:21.726Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,W/bt-rfcomm( 3235): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 3235): RFCOMM_DisconnectInd LCID:0x44
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1,
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f2724c rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: A3-1
,I/jxcore-log( 3179): 2015-11-25T13:47:26.309Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:26.310Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50,
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/art     (  824): Explicit concurrent mark sweep GC freed 63222(2MB) AllocSpace objects, 10(348KB) LOS objects, 31% free, 34MB/50MB, paused 1.507ms total 85.410ms
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2949): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at blb.a(PG:3937)
E/HttpOperation( 2949): 	at czp.a(PG:18188)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 12 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 14 more
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/SS      ( 3179): Found 8 peers.
I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3179): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2949): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2949): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2949): 	at jdm.a(PG:82)
E/HttpOperation( 2949): 	at jcs.o(PG:406)
E/HttpOperation( 2949): 	at jcn.a(PG:1379)
E/HttpOperation( 2949): 	at jcs.i(PG:143)
E/HttpOperation( 2949): 	at hec.a(PG:42)
E/HttpOperation( 2949): 	at hee.a(PG:102)
E/HttpOperation( 2949): 	at czr.a(PG:65)
E/HttpOperation( 2949): 	at kka.a(PG:108)
E/HttpOperation( 2949): 	at czp.a(PG:19176)
E/HttpOperation( 2949): 	at czp.a(PG:9081)
E/HttpOperation( 2949): 	at czq.run(PG:1686)
E/HttpOperation( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2949): 	at jdj.a(PG:4091)
E/HttpOperation( 2949): 	at jdj.a(PG:1125)
E/HttpOperation( 2949): 	at jdm.a(PG:77)
E/HttpOperation( 2949): 	... 15 more
E/HttpOperation( 2949): Caused by: faj: BadAuthentication
E/HttpOperation( 2949): 	at fal.a(PG:38)
E/HttpOperation( 2949): 	at jdj.a(PG:4089)
E/HttpOperation( 2949): 	... 17 more
E/ExperimentLoader( 2949): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2949): 	at jdm.a(PG:82)
E/ExperimentLoader( 2949): 	at jcs.o(PG:406)
E/ExperimentLoader( 2949): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2949): 	at jcs.i(PG:143)
E/ExperimentLoader( 2949): 	at hec.a(PG:42)
E/ExperimentLoader( 2949): 	at hee.a(PG:102)
E/ExperimentLoader( 2949): 	at czr.a(PG:65)
E/ExperimentLoader( 2949): 	at kka.a(PG:108)
E/ExperimentLoader( 2949): 	at czp.a(PG:19176)
E/ExperimentLoader( 2949): 	at czp.a(PG:9081)
E/ExperimentLoader( 2949): 	at czq.run(PG:1686)
E/ExperimentLoader( 2949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2949): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2949): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2949): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2949): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2949): 	at jdm.a(PG:77)
E/ExperimentLoader( 2949): 	... 15 more
E/ExperimentLoader( 2949): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2949): 	at fal.a(PG:38)
E/ExperimentLoader( 2949): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2949): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1297108, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3179): 2015-11-25T13:47:31.314Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:31.315Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:31.315Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:31.316Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 50:2E:6C:AC:21:50
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3179): Started service discovery
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 81
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:47:36.473Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:36.474Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:36.475Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:41.476Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:41.477Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:46.480Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:46.481Z SendDataConnector.js: Connect (retry count 2) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:46.481Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:46.482Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 50:2E:6C:AC:21:50
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 82
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:47:51.644Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed,
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:51.645Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): ,
I/jxcore-log( 3179): 2015-11-25T13:47:51.647Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:47:56.648Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50,
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:47:56.649Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/jxcore-log( 3179): 2015-11-25T13:48:01.652Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:01.653Z SendDataConnector.js: Connect (retry count 3) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:01.654Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:01.654Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3179): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 83
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:48:06.814Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:06.814Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:06.815Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:11.816Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:11.817Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:16.820Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:16.821Z SendDataConnector.js: Connect (retry count 4) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:16.821Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:16.822Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 50:2E:6C:AC:21:50
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3235): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 84
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3179): 2015-11-25T13:48:21.980Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:21.981Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:21.986Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:21.992Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50,
I/jxcore-log( 3179): ,
,I/jxcore-log( 3179): ---- round done--------,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ---- gotta redo : 50:2E:6C:AC:21:50, try count now: 2
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): do fake peer & start
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Connect to fake peer: 80:01:84:8A:B3:68
,I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:21.995Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:21.995Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:21.996Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
I/        ( 3179): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
I/        ( 3179): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 50:2E:6C:AC:21:50 done with result: Connection to 50:2E:6C:AC:21:50 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [80:01:84:8a:b3:68]: 7, f, 2205
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 85
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:48:24.346Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:24.347Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:24.347Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3179): 2015-11-25T13:48:29.348Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:29.349Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3179): Found 5 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3179): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3179): 2015-11-25T13:48:34.352Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:34.353Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:34.353Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:34.354Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [80:01:84:8a:b3:68]: 7, f, 2205
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 86
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:48:35.713Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed,
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:35.713Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): ,
I/jxcore-log( 3179): 2015-11-25T13:48:35.714Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3179): 2015-11-25T13:48:40.716Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:40.717Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
,W/bt-l2cap( 3235): L2CAP got conn_comp for unknown BD_ADDR
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3179): 2015-11-25T13:48:45.721Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:45.721Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:45.722Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:45.722Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): ,
I/        ( 3179): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 3179): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [80:01:84:8a:b3:68]: 7, f, 2205
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:87, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 87,
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:48:47.020Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:47.021Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:47.022Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 6 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3179): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3179): 2015-11-25T13:48:52.022Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:52.023Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8,
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/jxcore-log( 3179): 2015-11-25T13:48:57.026Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:57.026Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:57.027Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:48:57.027Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3179): Starting to connect
,I/        ( 3179): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 88
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:48:58.230Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:58.230Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:48:58.231Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3179): Found 6 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT760, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT760, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3235): onReceive,
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3179): 2015-11-25T13:49:03.233Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:03.234Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/        ( 3179): Cleared service requests
I/        ( 3179): Started peer discovery
,I/jxcore-log( 3179): 2015-11-25T13:49:08.238Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:08.238Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:08.239Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:08.239Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 89,
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3179): 2015-11-25T13:49:08.481Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
,I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:08.482Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:08.484Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:08.487Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
,I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- round done--------
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 2
I/jxcore-log( 3179): 
I/jxcore-log( 3179): do fake peer & start
,I/jxcore-log( 3179): 
I/jxcore-log( 3179): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:08.489Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:08.489Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:08.489Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null
I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
I/BTConnectToThread( 3179): Starting to connect
W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 7, f, 2205
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL,
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 90
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:49:09.275Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:09.275Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:09.276Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 7 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
D/BluetoothMapService( 3235): onReceive
,I/BTConnectionReceiver( 3967): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 3967): Bluetooth Device Name: HTC Desire 820
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3179): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT760, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT760, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:49:14.277Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:14.278Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3179): timeout now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): dun
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): weAreDoneNow , resultArray.length: 15,
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): done, now sending data to server,
I/jxcore-log( 3179): 
I/jxcore-log( 3179): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): -- RESULT DATA {"name:":"motorola-Nexus 6_PT7950","time":1000082,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:9D:93:0B","time":11131,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":11227,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":25751,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:1F:C9:5E","time":7737,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:B1:66","time":20045,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":14174,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":12231,"result":"OK","connections":1,"tryC
,I/jxcore-log( 3179): sendList : 100% : 49703 ms, 99% : 49703 ms, 95 : 43680 ms, 90% : 43680 ms.
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Result count 15, range 4243 ms to  49703 ms.
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): sendList failed peers count : 5 [25 %]
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 3
I/jxcore-log( 3179): 
I/jxcore-log( 3179): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): - Peer ID : E0:DB:10:14:E2:C0, Tried : 2
I/jxcore-log( 3179): 
I/jxcore-log( 3179): - Peer ID : 50:2E:6C:AC:21:50, Tried : 2
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): - Peer ID : 80:01:84:8A:B3:68, Tried : 2
I/jxcore-log( 3179): 
I/jxcore-log( 3179): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:15.237Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:15.239Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3179): 2015-11-25T13:49:19.281Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:19.282Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:19.284Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:19.284Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
,W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3235): invalid rfc slot id: 91
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:49:20.649Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:20.651Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:20.652Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:49:25.653Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:25.653Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 7 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86,
,I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2,
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 3179): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3179): Started service discovery
,I/jxcore-log( 3179): 2015-11-25T13:49:30.656Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:30.657Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:30.658Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:30.658Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null,
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C,
D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10,
D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1,
W/bt-btif ( 3235): bta_dm_check_av:0
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3235): process_service_search_attr_rsp,
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 92
I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:49:32.080Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:32.081Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:32.082Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:49:37.083Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:37.083Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:42.087Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:42.088Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:42.088Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:42.089Z SendDataConnector.js: do connect now
,I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10
,D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0
,W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 93
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:49:42.556Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:42.557Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:42.557Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3179): 2015-11-25T13:49:47.557Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:47.558Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:52.562Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:52.562Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:52.563Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:52.563Z SendDataConnector.js: do connect now
I/jxcore-log( 3179): 
,I/        ( 3179): Selected device address: 00:F4:6F:30:E0:6C, name: null,
,I/BTConnectToThread( 3179): Starting to connect
,W/BluetoothAdapter( 3179): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3179): Connecting to null, at 00:F4:6F:30:E0:6C
,D/BTIF_SOCK( 3235): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3235): info:x10,
,D/        ( 3235): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d,
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL,
,E/bt-btm  ( 3235): tBTM_SEC_DEV:0xa2f27b34 rs_disc_pending=1
W/bt-btif ( 3235): bta_dm_check_av:0,
W/bt-btif ( 3235): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3235): process_service_search_attr_rsp
,E/bt-btif ( 3235): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3235): invalid rfc slot id: 94
,I/BTConnectToThread( 3179): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3179): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3179): 2015-11-25T13:49:53.271Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
I/jxcore-log( 3179): 2015-11-25T13:49:53.272Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:53.273Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:49:53.276Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3179): 
,D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3235): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3235): aclStateChangeCallback: Device is NULL
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 4 peers.
I/SS      ( 3179): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Cleared service requests
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 6 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d,
I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3179): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT4660"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT4660, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT4660, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 6 peers.
I/SS      ( 3179): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3179): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Cleared service requests
I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 7 peers.
I/SS      ( 3179): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3179): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d,
I/SS      ( 3179): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 8 peers.
,I/SS      ( 3179): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3179): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3179): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3179): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07,
,I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b,
I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3248): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,W/bt-btm  ( 3235): Stopping oneshot timer
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3235): Disconnected process message: 10, size: 0
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 5 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3179): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3179): Added service request
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1965","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1965, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1965, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3179): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2890"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2890, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2890, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3179): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3179): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8472","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8472, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8472, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3179): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT382","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT382, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT382, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT2848","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT2848, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT2848, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT760, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT760, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3179): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9583","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT9583, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT9583, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3179): Cleared service requests
,I/        ( 3179): Started peer discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3179): Found 7 peers.
,I/SS      ( 3179): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3179): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3179): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3179): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3179): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3179): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3179): Peer(7): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3179): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3179): Added service request
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3248): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Started service discovery
,I/wpa_supplicant( 3248): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3179): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3179): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT760","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT760, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3179): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT760, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3179): DBG, CoordinatorConnector command called
I/jxcore-log( 3179): 
I/jxcore-log( 3179): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): stop tests now !
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): stop current!,
I/jxcore-log( 3179): 
I/jxcore-log( 3179): testSendData stopped
I/jxcore-log( 3179): 
,I/        ( 3179): Stoping All
I/        ( 3179): Stopping services
I/        ( 3179): Stopping services
I/        ( 3179): Stop Bluetooth
I/        ( 3179): Stop Bluetooth
I/BTListenerThread( 3179): Stopped
,I/jxcore-log( 3179): StopBroadcasting went ok
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): 2015-11-25T13:53:34.971Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3179): 
,I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3179): DBG, CoordinatorConnector command called
,I/jxcore-log( 3179): 
I/jxcore-log( 3179): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"F4:F1:E1:5C:3B:E2\",\"time\":4243,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"08:EC:A9:50:75:41\",\"time\":5669,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"B0:C5:59:3F:75:69\",\"time\":6080,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":7737,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"34:FC:EF:9D:93:0B\",\"time\":11131,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"F8:95:C7:87:85:54\",\"time\":11227,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"data
I/jxcore-log( 3179): ****TEST TOOK:  ms ****
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3179): 
I/jxcore-log( 3179): stop tests now !
I/jxcore-log( 3179): 
I/jxcore-log( 3179): end, event received
I/jxcore-log( 3179): 
I/jxcore-log( 3179): CoordinatorConnector close called
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3179): 
I/jxcore-log( 3179): The Coordinator has disconnected!
I/jxcore-log( 3179): 
I/jxcore-log( 3179): The Coordinator has closed!
I/jxcore-log( 3179): 
I/jxcore-log( 3179): stop tests now !
I/jxcore-log( 3179): 
I/jxcore-log( 3179): turning Radios off
I/jxcore-log( 3179): 
I/jxcore-log( 3179): Toggling radios to false
I/jxcore-log( 3179): 
D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  824): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3ffa2d2b mBinding = false
D/BluetoothManagerService(  824): Message: 2
D/WifiService(  824): setWifiEnabled: false pid=3179, uid=10265
E/WifiService(  824): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService(  824): Sending off request.
D/BluetoothAdapterState( 3235): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3235): Setting state to 13
I/BluetoothAdapterState( 3235): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3235): onBluetoothDisable()
I/BluetoothAdapterState( 3235): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService(  824): Message: 60
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  824): Bluetooth State Change Intent: 12 -> 13
D/BluetoothAdapterProperties( 3235): Scan Mode:20
D/BluetoothAdapterState( 3235): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/BtOppRfcommListener( 3235): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3235): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3235): L2CAP - PSM: 0x0017 not found for deregistration
D/btif_config_util( 3235): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothMapMasInstance( 3235): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3235): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3235): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3235): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3235): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3235): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3235): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3235): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/BluetoothMapService( 3235): onReceive
D/BluetoothMapService( 3235): STATE_TURNING_OFF
D/BluetoothMapService( 3235): MAP Service closeService in
D/BluetoothMapMasInstance( 3235): MAP Service shutdown
I/BtOppRfcommListener( 3235): stopping Accept Thread
I/BtOppRfcommListener( 3235): BluetoothSocket listen thread finished
I/jxcore-log( 3179): Radios toggled
I/jxcore-log( 3179): 
I/chromium( 3179): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
E/WifiStateMachine(  824): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
W/ContextImpl( 3939): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  824): Message: 30
,I/ActivityManager(  824): Start proc 4473:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothManagerService(  824): Message: 30
,D/LocalBluetoothProfileManager( 3939): Adding local MAP profile
,D/BluetoothMap( 3939): Create BluetoothMap proxy object
D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): Message: 30
,D/LocalBluetoothProfileManager( 3939): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3939): finishStartingService: stopping service
,D/BluetoothInputDevice( 3939): Proxy object connected
D/HidProfile( 3939): Bluetooth service connected
,D/BluetoothPan( 3939): BluetoothPAN Proxy object connected
D/PanProfile( 3939): Bluetooth service connected
D/BluetoothMap( 3939): Proxy object connected
D/MapProfile( 3939): Bluetooth service connected
D/BluetoothMap( 3939): getConnectedDevices()
D/BluetoothMap( 3939): Bluetooth is Not enabled
,D/AndroidRuntime( 4471): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4471): CheckJNI is OFF
,D/AndroidRuntime( 4471): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  824): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  824): Killing 3179:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,D/StrictMode( 4473): StrictMode policy violation; ~duration=255 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4473): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4473): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4473): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4473): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4473): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4473): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4473): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 4473): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 4473): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4473): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4473): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4473): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4473): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4473): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4473): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4473): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4473): StrictMode policy violation; ~duration=255 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4473): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4473): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4473): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4473): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4473): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4473): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4473): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4473): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4473): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4473): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4473): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4473): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4473): StrictMode policy violation; ~duration=253 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4473): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4473): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4473): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4473): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4473): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4473): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4473): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4473): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 4473): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4473): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4473): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4473): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4473): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4473): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4473): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4473): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4473): StrictMode policy violation; ~duration=249 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4473): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4473): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4473): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 4473): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4473): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4473): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4473): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4473): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4473): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4473): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4473): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4473): StrictMode policy violation; ~duration=238 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4473): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4473): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 4473): 	at android.app.SharedPreferencesImpl.getInt(SharedPreferencesImpl.java:238)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.shared.b.a.a(PG:1035)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.shared.b.a.a(PG:944)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4473): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4473): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4473): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4473): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4473): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4473): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4473): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4473): StrictMode policy violation; ~duration=234 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4473): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4473): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4473): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4473): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4473): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4473): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4473): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4473): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4473): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4473): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4473): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4473): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4473): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4473): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4473): StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 4473): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4473): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 4473): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 4473): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 4473): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 4473): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 4473): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 4473): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 4473): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 4473): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 4473): # via Binder call with stack:
D/StrictMode( 4473): android.os.StrictMode$LogStackTrace
D/StrictMode( 4473): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 4473): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 4473): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 4473): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 4473): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 4473): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 4473): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 4473): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 4473): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4473): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4473): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4473): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4473): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4473): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4473): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4473): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4473): StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4473): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4473): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4473): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4473): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4473): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 4473): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 4473): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 4473): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4473): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4473): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4473): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4473): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4473): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4473): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4473): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4473): StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4473): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4473): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4473): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4473): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4473): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4473): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4473): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4473): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4473): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4473): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4473): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4473): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4473): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 4473): StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4473): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4473): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4473): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4473): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4473): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 4473): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 4473): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 4473): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 4473): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 4473): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 4473): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 4473): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4473): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 4473): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4473): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 4473): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/ActivityThread( 4473): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/PackageSettings(  824): Skipping PackageSetting{3f14ca29 com.example.hello/10272} due to missing metadata
,W/com.google.a.a.a.b.a( 4473): Application name is not set. Call Builder#setApplicationName.
,I/WindowState(  824): WIN DEATH: Window{30b11393 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  824): Client connection lost with reason: 4
,E/libprocessgroup(  824): failed to kill 1 processes for processgroup 3179
W/ActivityManager(  824): Force removing ActivityRecord{1caef758 u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
,V/ActivityManager(  824): Display changed displayId=0
,I/ActivityManager(  824): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,W/ActivityManager(  824): Spurious death for ProcessRecord{b88ee93 3179:com.test.thalitest/u0a265}, curProc for 3179: null
D/TaskPersister(  824): removeObsoleteFile: deleting file=24_task.xml
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d905ec9:true
,I/Keyboard.Facilitator( 1209): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1209): run()
,I/Decoder ( 1209): createOrResetDecoder
,I/InputReader(  824): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  824): Killing 3633:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/art     ( 1061): Explicit concurrent mark sweep GC freed 71241(2MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 73MB/89MB, paused 2.099ms total 57.348ms
,I/art     (  824): Explicit concurrent mark sweep GC freed 49417(2MB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 1.457ms total 74.103ms
I/art     (  824): WaitForGcToComplete blocked for 72.591ms for cause Explicit
,I/art     (  824): Explicit concurrent mark sweep GC freed 5012(267KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 2.640ms total 59.125ms
,D/AuthorizationBluetoothService( 1489): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BuaReceiver( 3044): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,I/ConfigService( 1489): onCreate
,D/JobSchedulerService(  824): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  824): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/ActivityManager(  824): Start proc 4519:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,W/InputMethodManagerService(  824): Got RemoteException sending setActive(false) notification to pid 3179 uid 10265
,I/Keyboard.Facilitator( 1209): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1209): run()
,E/native  (  824): do suspend true
,I/art     ( 1307): Explicit concurrent mark sweep GC freed 5053(368KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 699us total 23.096ms
,D/Launcher.Workspace( 1307): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1307): 11683562 - stripEmptyScreens()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1209): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,E/DataBuffer( 1747): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@20f28ca5)
,I/art     ( 1747): Explicit concurrent mark sweep GC freed 20559(1167KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 1.307ms total 51.929ms
,E/DataBuffer( 1747): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1abe587a)
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loading LM = contacts
,V/Herrevad( 1777): NQAS connected
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1209): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1209): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1209): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1209): run()
I/StatsUtilsManager( 1209): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1209): shouldRecordStats() = Too Soon
,I/art     ( 4471): System.exit called, status: 0
I/AndroidRuntime( 4471): VM exiting with result code 0.
,D/VoicemailCleanupService( 4519): Cleaning up data for package: com.test.thalitest
,I/ContactLocale( 4519): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  824): Start proc 4555:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,I/ActivityManager(  824): Start proc 4576:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,W/LocationOracleImpl( 3967): Best location was null
,I/VS.Container( 3967): create_recognizer
,W/ContextImpl( 4576): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/SQLiteLog( 1489): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1489): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 1489): FATAL EXCEPTION: main
E/AndroidRuntime( 1489): Process: com.google.process.gapps, PID: 1489
E/AndroidRuntime( 1489): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1489): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 1489): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 1489): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 1489): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1489): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1489): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 1489): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1489): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1489): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 1489): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 1489): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1489): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1489): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1489): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1489): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1489): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1489): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1489): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1489): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1489): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 1489): 	... 9 more
,E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  824): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  824): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  824): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  824): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  824): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  824): 	... 5 more
,E/SQLiteDatabase( 4576): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4576): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4576): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4576): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4576): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4576): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4576): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4576): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4576): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4576): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4576): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4576): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4576): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4576): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4576): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4576): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 4576): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 4576): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4576): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4576): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4576): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 4576): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4576): Process: com.android.keychain, PID: 4576
E/AndroidRuntime( 4576): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4576): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4576): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4576): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4576): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4576): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4576): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4576): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4576): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4576): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4576): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4576): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4576): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4576): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4576): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 4576): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 4576): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4576): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4576): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4576): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Search.SharedPreferencesProto( 3967): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,D/OpenGLRenderer(  824): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  824): Validating map...
,E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  824): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  824): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  824): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  824): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  824): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  824): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  824): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  824): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  824): 	... 5 more
,E/SQLiteDatabase( 3967): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/jar_store.db'.
E/SQLiteDatabase( 3967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 3967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3967): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 3967): 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
E/SQLiteDatabase( 3967): 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
E/SQLiteDatabase( 3967): 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
E/SQLiteDatabase( 3967): 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
E/SQLiteDatabase( 3967): 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
E/SQLiteDatabase( 3967): 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
E/SQLiteDatabase( 3967): 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
E/SQLiteDatabase( 3967): 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
E/SQLiteDatabase( 3967): 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
E/SQLiteDatabase( 3967): 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
E/SQLiteDatabase( 3967): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3967): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3967): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3967): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3967): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/SQLiteOpenHelper( 3967): Couldn't open jar_store.db for writing (will try read-only):
E/SQLiteOpenHelper( 3967): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3967): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 3967): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 3967): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3967): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3967): 	at android.database.sqlite.SQLiteDatabase.openInner(SQL,iteDatabase.java:806)
E/SQLiteOpenHelper( 3967): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 3967): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 3967): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 3967): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3967): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 3967): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 3967): 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
E/SQLiteOpenHelper( 3967): 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
E/SQLiteOpenHelper( 3967): 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
E/SQLiteOpenHelper( 3967): 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
E/SQLiteOpenHelper( 3967): 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
E/SQLiteOpenHelper( 3967): 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
E/SQLiteOpenHelper( 3967): 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
E/SQLiteOpenHelper( 3967): 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
E/SQLiteOpenHelper( 3967): 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
E/SQLiteOpenHelper( 3967): 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
E/SQLiteOpenHelper( 3967): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 3967): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 3967): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 3967): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 3967): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,W/SQLiteOpenHelper( 3967): Opened jar_store.db in read-only mode
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 72948(3MB) AllocSpace objects, 8(693KB) LOS objects, 37% free, 27MB/43MB, paused 1.327ms total 31.239ms
,I/HotwordRecognitionRnr( 3967): Starting hotword detection.
I/MicrophoneInputStream( 3967): mic_starting com.google.android.apps.gsa.speech.audio.u@b073f28
,I/AudioFlinger(  361): AudioFlinger's thread 0xb4cd4000 ready to run
,I/SoundTriggerHwService::Module(  361): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 3967): mic_started com.google.android.apps.gsa.speech.audio.u@b073f28
,I/OpenGLRenderer(  824): Initialized EGL, version 1.4
,D/OpenGLRenderer(  824): Enabling debug mode 0,
,D/audio_hw_primary(  361): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  361): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  361): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  361): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  361): enable_audio_route: apply and update mixer path: audio-record
,I/HotwordWorker( 3967): onReady
,E/Search.SharedPreferencesProto( 3967): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,W/Icing   ( 1777): Received bad json for section weights override -- ignoring.
W/Icing   ( 1777): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 1777): Received bad json for section weights override -- ignoring.
W/Icing   ( 1777): Received bad json for corpus context scoring override -- ignoring.
,W/FileUtils( 3967): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/FileBytesWriter( 3967): Failed to write new file: loracle.new
W/LocationOracleImpl( 3967): Best location was null
,W/FileUtils( 3967): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/FileBytesWriter( 3967): Failed to write new file: loracle.new
W/LocationOracleImpl( 3967): Best location was null
,W/LocationOracleImpl( 3967): Best location was null
,D/WifiService(  824): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2be81fd1}
,I/HotwordDetector( 3967): Closing mic
I/MicrophoneInputStream( 3967): mic_close com.google.android.apps.gsa.speech.audio.u@b073f28
,W/TRUiThreadExecutor( 3967): Task does not implement UiTask: com.google.common.g.a.p@196d3cef
,I/WebViewFactory( 3967): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3967): Time to load native libraries: 2 ms (timestamps 3210-3212)
,I/LibraryLoader( 3967): Expected native library version number "",actual native library version number ""
,W/art     ( 3967): Attempt to remove local handle scope entry from IRT, ignoring
,D/audio_hw_primary(  361): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  361): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  361): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 3967): Hotword detection finished
I/HotwordRecognitionRnr( 3967): Stopping hotword detection.
,E/QMI_FW  (  824): xport_send: Sendto failed for port 3840
,E/LocSvc_api_v02(  824): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1659663635
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0

```
