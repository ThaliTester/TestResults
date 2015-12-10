#### Test 50650278c0f6ec2_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2706): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2706): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2706): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3190): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3190): CheckJNI is OFF
D/AndroidRuntime( 3190): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  824): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  824): addAppToken: AppWindowToken{2af6d084 token=Token{28a51697 ActivityRecord{6752d16 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3190): Shutting down VM
V/WindowManager(  824): Adding window Window{4236669 u0 Starting com.test.thalitest} at 3 of 8 (after Window{26eec628 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/MicrophoneInputStream( 1525): mic_close com.google.android.apps.gsa.speech.audio.u@8363e89
I/HotwordDetector( 1525): Closing mic
I/ActivityManager(  824): Start proc 3204:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1525): Hotword detection finished
I/HotwordRecognitionRnr( 1525): Stopping hotword detection.
I/ActivityManager(  824): Killing 2664:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/DataBuffer( 1756): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f7c415c)
I/art     ( 1756): Explicit concurrent mark sweep GC freed 13313(787KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.497ms total 51.122ms
I/ActivityManager(  824): Killing 2797:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1658647827
E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/kickstart(  879): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  879): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  879): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  879): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/WebViewFactory( 3204): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3204): Time to load native libraries: 1 ms (timestamps 4980-4981)
I/LibraryLoader( 3204): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3204): Binding Chromium to main looper Looper (main, tid 1) {3c069ac8}
,I/LibraryLoader( 3204): Expected native library version number "",actual native library version number ""
,I/chromium( 3204): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3204): Initializing chromium process, singleProcess=true
,W/art     ( 3204): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3204): ApplicationContext is null in ApplicationStatus
,W/chromium( 3204): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3204): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3204): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3204): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3204): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aa5bbd9:true
,D/BluetoothAdapter( 3204): 1057333522: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3204): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3204): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3204): CordovaWebView is running on device made by: motorola
,W/art     ( 3204): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3204): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3204): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3204): Validating map...
,V/WindowManager(  824): Adding window Window{27e04d49 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{4236669 u0 Starting com.test.thalitest})
,W/chromium( 3204): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  824): Explicit concurrent mark sweep GC freed 16793(812KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.041ms total 62.176ms
,I/OpenGLRenderer( 3204): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3204): Enabling debug mode 0
,I/ActivityManager(  824): Displayed com.test.thalitest/.MainActivity: +892ms (total +2m2s134ms)
,I/Keyboard.Facilitator( 1215): onFinishInput(),
W/BindingManager( 3204): Cannot call determinedVisibility() - never saw a connection for the pid: 3204
,D/JsMessageQueue( 3204): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3204): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576268544
,D/JX-Cordova( 3204): jxcore cordova android initializing
,I/kickstart(  879): STATUS: Received file 'm9kefs2'
I/kickstart(  879): STATUS: 950272 bytes transferred in 0.996978 seconds
I/kickstart(  879): STATUS: Successfully downloaded files from target 
,I/kickstart(  879): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  879): STATUS: Sahara protocol completed
,W/jxcore-log( 3204): Initializing JXcore engine
W/jxcore-log( 3204): JXcore engine is ready
,W/jxcore-log( 3204): Starting JXcore engine
,W/.test.thalitest( 3204): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9602]" dev="sockfs" ino=9602 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3204): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3204): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9771]" dev="sockfs" ino=9771 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3204): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20129]" dev="sockfs" ino=20129 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3204): Platform android
W/jxcore-log( 3204): 
W/jxcore-log( 3204): Process ARCH arm
W/jxcore-log( 3204): 
,I/jxcore-log( 3204): JXcore Cordova bridge is ready!
I/jxcore-log( 3204): 
,W/jxcore-log( 3204): JXcore engine is started
,I/Choreographer( 3204): Skipped 131 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3204): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3204): Toggling radios to true
I/jxcore-log( 3204): 
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  824): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  824): Message: 1
D/BluetoothManagerService(  824): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  824): setWifiEnabled: true pid=3204, uid=10265
E/WifiService(  824): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  824): New client listening to asynchronous messages
,I/ActivityManager(  824): Start proc 3261:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
D/SoftapController(  354): Softap fwReload - Ok
I/jxcore-log( 3204): Radios toggled
I/jxcore-log( 3204): 
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiMonitor(  824): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown,
,D/WifiMonitor(  824): startMonitoring(wlan0) with mConnected = false
E/WifiHW  (  824): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/ActivityManager(  824): Start proc 3280:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,W/ResourcesManager( 3261): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3270): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3270): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  824): Start proc 3306:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
I/ActivityManager(  824): Killing 2830:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/art     (  369): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 1.001ms total 10.613ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 8.815ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 196us total 8.361ms
,D/AdapterServiceConfig( 3261): Adding HeadsetService
D/AdapterServiceConfig( 3261): Adding A2dpService
D/AdapterServiceConfig( 3261): Adding HidService
D/AdapterServiceConfig( 3261): Adding HealthService
,D/AdapterServiceConfig( 3261): Adding PanService
D/AdapterServiceConfig( 3261): Adding GattService
D/AdapterServiceConfig( 3261): Adding BluetoothMapService
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1588e9b2:true
,D/BluetoothAdapterState( 3261): make
,I/bluedroid( 3261): init
I/BluetoothAdapterState( 3261): Entering OffState
,I/bte_conf( 3261): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3261): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3261): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3261): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3261): get_profile_interface socket
I/GKI_LINUX( 3261): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 3261): get_profile_interface map_client
,D/BluetoothAdapterProperties( 3261): Address is:F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  824): Bluetooth Adapter name changed to Nexus 6
,D/BluetoothAdapterProperties( 3261): Name is: Nexus 6
D/BluetoothManagerService(  824): Stored Bluetooth name: Nexus 6
D/BluetoothManagerService(  824): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  824): Message: 40
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3261): config_hci_snoop_log
,D/BluetoothManagerService(  824): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  824): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3261): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3261): Setting state to 11
I/BluetoothAdapterState( 3261): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  824): Message: 60
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  824): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3261): make
,I/BluetoothBondStateMachine( 3261): StableState(): Entering Off State
,I/BluetoothAdapterState( 3261): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3261): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10a90761
D/HeadsetService( 3261): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3261): classInitNative: succeeds
D/HeadsetStateMachine( 3261): make
,D/HeadsetStateMachine( 3261): max_hf_connections = 1
I/bluedroid( 3261): get_profile_interface handsfree
,D/HeadsetStateMachine( 3261): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3261): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10a90761
,D/BluetoothA2dp(  824): Proxy object connected
,D/A2dpService( 3261): Received start request. Starting profile...
,D/BluetoothA2dp( 1067): Proxy object connected
I/BluetoothAvrcpServiceJni( 3261): classInitNative: succeeds
I/bluedroid( 3261): get_profile_interface avrcp
,E/RemoteController( 3261): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3261): classInitNative: succeeds
D/A2dpStateMachine( 3261): make
,I/bluedroid( 3261): get_profile_interface a2dp
I/GKI_LINUX( 3261): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3261): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3261): classInitNative: succeeds
D/BluetoothAdapterService( 3261): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10a90761
D/HidService( 3261): Received start request. Starting profile...
I/bluedroid( 3261): get_profile_interface hidhost
D/BluetoothInputDevice( 1067): Proxy object connected
I/BluetoothHealthServiceJni( 3261): classInitNative: succeeds
D/BluetoothAdapterService( 3261): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10a90761,
D/HealthService( 3261): Received start request. Starting profile...
I/bluedroid( 3261): get_profile_interface health
I/BluetoothPanServiceJni( 3261): classInitNative(L105): succeeds
,D/BluetoothAdapterService( 3261): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10a90761
,D/BluetoothPan( 1067): BluetoothPAN Proxy object connected,
D/PanService( 3261): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 3261): initializeNative(L110): pan
I/bluedroid( 3261): get_profile_interface pan
I/BtGatt.JNI( 3261): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3261): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10a90761
D/BtGatt.DebugUtils( 3261): handleDebugAction() action=null
D/BtGatt.GattService( 3261): Received start request. Starting profile...
D/BtGatt.GattService( 3261): start()
I/bluedroid( 3261): get_profile_interface gatt
D/BluetoothAdapterService( 3261): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10a90761
D/BtGatt.AdvertiseManager( 3261): advertise manager created
,D/BluetoothAdapterService( 3261): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10a90761
,D/BluetoothMapService( 3261): Received start request. Starting profile...
D/BluetoothMapService( 3261): start()
D/BluetoothMap( 1067): Proxy object connected
,D/BluetoothMapEmailSettingsLoader( 3261): Found 0 applications
D/BluetoothMapEmailAppObserver( 3261): createReceiver()
,D/BluetoothMapEmailAppObserver( 3261): initObservers(),
D/BluetoothMapEmailAppObserver( 3261): getEnabledAccountItems()
,D/HeadsetStateMachine( 3261): Proxy object connected,
,D/HeadsetStateMachine( 3261): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3261): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3261): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3261): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3261): enable
,I/bt_hci_bdroid( 3261): init
,I/GKI_LINUX( 3261): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3261): btu_task pending for preload complete event
,I/bt_vendor( 3261): init
I/bt_vnd_conf( 3261): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3261): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3261): userial_init
,I/art     ( 1498): Explicit concurrent mark sweep GC freed 18312(915KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 808us total 19.591ms
,I/bt_userial_vendor( 3261): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3261): device fd = 53 open
,D/bt_userial( 3261): Entering userial_read_thread()
,I/ActivityManager(  824): Start proc 3348:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/bt_hwcfg( 3261): bt vendor lib: set UART baud 3000000
,I/ActivityManager(  824): Killing 2766:com.google.android.gm/u0a78 (adj 15): empty #17
,D/bt_hwcfg( 3261): Chipset BCM4354A2
D/bt_hwcfg( 3261): Target name = [BCM4354A2]
I/bt_hwcfg( 3261): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,D/Tethering(  824): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  824): Killing 2361:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/wpa_supplicant( 3270): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3270): Could not read interface p2p-dev-wlan0 flags: No such device
,I/bt_hwcfg( 3261): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3261): Settlement delay -- 100 ms
I/bt_hwcfg( 3261): Setting fw settlement delay to 100 
,I/ActivityManager(  824): Start proc 3365:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/WifiConfigStore(  824): Loading config and enabling all networks 
,D/WifiService(  824): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@dbac86a}
,E/WifiConfigStore(  824): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  824): Setting external_sim to 1
W/Settings( 2631): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  824): Setting OUI to 92-68-C3
I/WifiNative-HAL(  824): startHal
D/wifi    (  824): setting scan oui 0xaec815c8
D/WifiHAL (  824): Sending mac address OUI
,E/WifiStateMachine(  824): cancelDelayedScan -> 1
,D/WifiScanningService(  824): SCAN_AVAILABLE : 3
D/RttService(  824): SCAN_AVAILABLE : 3
D/WifiScanningService(  824): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  824): startHal
W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
D/wifi    (  824): getting scan capabilities on interface[0] = 0xaec815c8
D/WifiHAL (  824): Creating message to get scan capablities; iface = 5
D/WifiHAL (  824): In GetCapabilities::handleResponse
D/WifiHAL (  824): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  824): StartedState
D/CommandListener(  354): Setting iface cfg
D/RttService(  824): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiP2pService(  824): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  824): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 3270): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/native  (  824): do suspend false
,D/WifiNative-HAL(  824): p2pGetDeviceAddress
D/WifiNative-HAL(  824): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/bt_hwcfg( 3261): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3261): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3261): vendor lib fwcfg completed
,I/bt-btu  ( 3261): btu_task received preload complete event
,I/        ( 3261): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 3261): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3261): BTE_InitTraceLevels -- TRC_RFCOMM,
I/        ( 3261): BTE_InitTraceLevels -- TRC_AVDT
,I/        ( 3261): BTE_InitTraceLevels -- TRC_AVRC
,I/        ( 3261): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3261): BTE_InitTraceLevels -- TRC_BNEP
,I/        ( 3261): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 3261): BTE_InitTraceLevels -- TRC_GAP,
,I/        ( 3261): BTE_InitTraceLevels -- TRC_PAN,
,I/        ( 3261): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3261): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3261): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3261): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3261): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3261): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e21085 
,E/bt-btm  ( 3261): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e21085 
,D/StrictMode( 3365): StrictMode policy violation; ~duration=243 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3365): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3365): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3365): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3365): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3365): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3365): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3365): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3365): StrictMode policy violation; ~duration=242 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3365): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3365): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3365): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3365): StrictMode policy violation; ~duration=239 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3365): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3365): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3365): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3365): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3365): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3365): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3365): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3365): StrictMode policy violation; ~duration=234 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at android.app.SharedPreferencesImpl.awaitLoad,edLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3365): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3365): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3365): StrictMode policy violation; ~duration=223 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3365): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3365): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3365): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3365): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3365): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
,D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3365): StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3365): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3365): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3365): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3365): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3365): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3365): ,	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3365): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3365): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3365): # via Binder call with stack:
D/StrictMode( 3365): android.os.StrictMode$LogStackTrace
D/StrictMode( 3365): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3365): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3365): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3365): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3365): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3365): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3365): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3365): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3365): ,	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3365): StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3365): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3365): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3365): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3365): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3365): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3365): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
,D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3365): StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3365): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3365): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3365): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3365): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3365): StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3365): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3365): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3365): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3365): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3365): StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3365): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3365): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3365): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3365): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3365): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3365): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3365): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3365): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3365): 	at com.google.p.e.a(PG:170)
,D/StrictMode( 3365): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012),
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254),
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/BluetoothAdapterProperties( 3261): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
E/bt-btif ( 3261): Calling BTA_HhEnable
E/bt-btif ( 3261): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3261): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  824): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  824): Stored Bluetooth name: Nexus 6
D/BluetoothAdapterProperties( 3261): Name is: Nexus 6
D/BluetoothAdapterProperties( 3261): Scan Mode:20
D/BluetoothAdapterProperties( 3261): Discoverable Timeout:120
W/bt-btm  ( 3261): Stopping oneshot timer
,D/bte_conf( 3261): Device ID record 1 : primary
,D/bte_conf( 3261):   vendorId            = 000f
D/bte_conf( 3261):   vendorIdSource      = 0001
D/bte_conf( 3261):   product             = 1200
D/bte_conf( 3261):   version             = 1436
D/bte_conf( 3261):   clientExecutableURL = 
D/bte_conf( 3261):   serviceDescription  = 
D/bte_conf( 3261):   documentationURL    = 
D/bte_conf( 3261): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3261): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3261): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3261): ScanMode =  20
D/BluetoothAdapterProperties( 3261): State =  11
D/BluetoothAdapterProperties( 3261): Setting state to 12
I/BluetoothAdapterState( 3261): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  824): Message: 60
,I/BluetoothAdapterState( 3261): Entering On State
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  824): Broadcasting onBluetoothStateChange(true) to 13 receivers.
D/BluetoothAdapterProperties( 3261): Scan Mode:21,
D/BluetoothAdapterProperties( 3261): Discoverable Timeout:120
D/BluetoothMap( 1067): onBluetoothStateChange: up=true
D/BluetoothHeadset(  824): onBluetoothStateChange: up=true
D/BluetoothManagerService(  824): Creating new ProfileServiceConnections object for profile: 1
D/BluetoothHeadset( 1067): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  824): onBluetoothStateChange: up=true
D/BluetoothA2dpSink( 1067): onBluetoothStateChange: up=true
E/BluetoothA2dpSink( 1067): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
,D/BluetoothHeadset(  824): onBluetoothStateChange: up=true
D/BluetoothHeadset(  824): onBluetoothStateChange: up=true
D/BluetoothPan( 1067): onBluetoothStateChange(on) call bindService
D/BluetoothAvrcpController( 1067): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1067): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothHeadset( 1280): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 1067): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1067): onBluetoothStateChange: up=true
D/BluetoothHeadsetClient( 1067): onBluetoothStateChange: up=true
,E/bt_h4   ( 3261): vendor lib postload completed
E/BluetoothHeadsetClient( 1067): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothManagerService(  824): Bluetooth State Change Intent: 11 -> 12
W/com.google.a.a.a.b.a( 3365): Application name is not set. Call Builder#setApplicationName.
D/BluetoothManagerService(  824): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  824): Message: 40
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 3261): onReceive
D/BluetoothMapService( 3261): STATE_ON
,D/BluetoothMapMasInstance( 3261): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3261): MAS initSocket()
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3261): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3261): Accepting socket connection...
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2759e72f:true
,I/ActivityManager(  824): Killing 2866:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/BluetoothManagerService(  824): Message: 400
,D/BluetoothHeadset(  824): Proxy object connected
,D/BluetoothManagerService(  824): Message: 400
D/BluetoothHeadset( 1067): Proxy object connected
,D/BluetoothManagerService(  824): Message: 400
D/BluetoothHeadset(  824): Proxy object connected
,D/BluetoothManagerService(  824): Message: 400
D/BluetoothHeadset(  824): Proxy object connected
D/BluetoothManagerService(  824): Message: 400
,D/BluetoothHeadset( 1280): Proxy object connected
D/AuthorizationBluetoothService( 1498): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3348): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c85a879:true
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/AuthorizationBluetoothService( 1498): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/BluetoothAdapter( 3261): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3261): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3348): Adding local A2DP profile
I/BtOppRfcommListener( 3261): Accept thread started.
,D/BluetoothManagerService(  824): Message: 30
,D/LocalBluetoothProfileManager( 3348): Adding local HEADSET profile,
,D/BluetoothManagerService(  824): Message: 30,
,D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): Message: 30
,D/LocalBluetoothProfileManager( 3348): Adding local MAP profile
D/BluetoothMap( 3348): Create BluetoothMap proxy object
,D/BluetoothManagerService(  824): Message: 30
,D/BluetoothManagerService(  824): Message: 30
,D/LocalBluetoothProfileManager( 3348): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3348): finishStartingService: stopping service
,D/BluetoothA2dp( 3348): Proxy object connected
,D/A2dpProfile( 3348): Bluetooth service connected
,D/BluetoothInputDevice( 3348): Proxy object connected
D/HidProfile( 3348): Bluetooth service connected
,D/BluetoothPan( 3348): BluetoothPAN Proxy object connected
D/PanProfile( 3348): Bluetooth service connected
D/BluetoothMap( 3348): Proxy object connected
D/MapProfile( 3348): Bluetooth service connected
D/BluetoothMap( 3348): getConnectedDevices()
,D/BluetoothPbap( 3348): Proxy object connected
D/PbapServerProfile( 3348): Bluetooth service connected
,D/BluetoothManagerService(  824): Message: 400
,D/BluetoothHeadset( 3348): Proxy object connected
D/HeadsetProfile( 3348): Bluetooth service connected
,I/wpa_supplicant( 3270): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  824): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  824):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  824):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  824): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  824): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  824): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  824): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  824): will read network variables netId=0
,E/WifiStateMachine(  824): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  824): will read network variables netId=0
,I/wpa_supplicant( 3270): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3270): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3270): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3270): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  824): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  824): Start Dhcp Watchdog 1
,E/WifiStateMachine(  824):  WifiLinkLayerStats: 
E/WifiStateMachine(  824):  my bss beacon rx: 1
E/WifiStateMachine(  824):  RSSI mgmt: -52
E/WifiStateMachine(  824):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  824):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  824):  on_time : 0 tx_time=59 rx_time=83 scan_time=0
,D/ConnectivityService(  824): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  824): do suspend false
,E/WifiStateMachine(  824): scanCount==0 - aborting
,I/dhcpcd  ( 3407): version 5.5.6 starting
,I/dhcpcd  ( 3407): wlan0: rebinding lease of 192.168.1.122
,I/PowerManagerService(  824): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  824): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (205 us)
,I/dhcpcd  ( 3407): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3407): wlan0: leased 192.168.1.122 for 86400 seconds
,I/DisplayManagerService(  824): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  824): Display changed displayId=0
,D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6082000,
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,E/WifiStateMachine(  824): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  824): Excessive delay in setPowerMode(): 272ms
,D/ConnectivityService(  824): Adding iface wlan0 to network 100,
,I/DreamManagerService(  824): Entering dreamland.
,I/PowerManagerService(  824): Dozing...
I/DreamController(  824): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  824): cancelDelayedScan -> 5
,E/ConnectivityService(  824): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  824): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  824): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
E/native  (  824): do suspend false
,D/ConnectivityService(  824): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  824): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  824): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.81 rxSuccessRate=2.62 targetRoamBSSID=any RSSI=-52
,D/ConnectivityService(  824): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  824): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  824):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  824): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  824): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  824): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  824): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/WifiStateMachine(  824): cancelDelayedScan -> 7
V/BackupManagerService(  824): Scheduling immediate backup pass
E/native  (  824): do suspend true
,D/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  824): getDataEnabled: retVal=false
,I/ActivityManager(  824): Start proc 3450:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,E/GpsLocationProvider(  824): No APN found to select.
,V/GoogleAuthProtoRequest( 3280): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
V/BackupManagerService(  824): Running a backup pass
D/Tethering(  824): MasterInitialState.processMessage what=3
,V/BackupManagerService(  824): clearing pending backups
,V/PerformBackupTask(  824): Beginning backup of 14 targets
,D/PerformBackupTask(  824): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  824): doBackup() invoked
,I/PMBA    (  824): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  824): Getting widget state for user: 0
,I/art     (  824): Explicit concurrent mark sweep GC freed 50780(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.940ms total 55.737ms
,I/MusicStore( 3450): Database version: 120
,W/GmsBackupTransport( 1756): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1756): starting performBackup for @pm@
,V/GmsBackupTransport( 1756): performBackup done for @pm@
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 11:58:23 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449748703990], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449748703975]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Validated
D/ConnectivityService(  824): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  824): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  824): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  824): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  824): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524290
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/GpsLocationProvider(  824): NTP server returned: 1449748703799 (Thu Dec 10 12:58:23 GMT+01:00 2015) reference: 164259 certainty: 11 system time offset: -200
,D/AlarmManagerService(  824): Setting time of day to sec=1449748703
W/AlarmManagerService(  824): Unable to set rtc to 1449748703: Invalid argument
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1498): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1498): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1498): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1498): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1756): Error sending final backup to server: 
W/GmsBackupTransport( 1756): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1756): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1756): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1756): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1756): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1756): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1756): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1756): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1756): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1756): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1756): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1756): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1756): 	... 1 more
,D/BackupManagerService(  824): Now staging backup of com.google.android.talk
,W/ExperimentUpdateService( 3280): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3280): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3280): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3280): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3280): 	at com.a.a.k.run(SourceFile:110)
,E/Auth.Api.Credentials( 1791): [CredentialSyncAdapter] Unknown sync event.
,D/BackupManagerService(  824): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  824): Now staging backup of com.android.providers.settings
,I/art     ( 1498): Explicit concurrent mark sweep GC freed 11859(617KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 666us total 31.577ms
,D/BackupManagerService(  824): Now staging backup of com.android.sharedstoragebackup
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,V/GoogleAuthProtoRequest( 3280): [337] a.<init>: mAccountName set to: thalitester@gmail.com
,W/DriveInitializer( 1791): Background init thread started
D/BackupManagerService(  824): Now staging backup of com.google.android.gm
,W/ResourcesManager( 3450): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3450): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/DriveInitializer( 1791): Awaiting to be initialized
,D/BackupManagerService(  824): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  824): Now staging backup of com.android.nfc
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BackupManagerService(  824): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  824): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  824): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  824): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  824): Now staging backup of com.android.vending
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/BackupManagerService(  824): Now staging backup of android
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BackupManagerService(  824): Now staging backup of com.google.android.googlequicksearchbox
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GmsBackupTransport( 1756): Next backup will happen in 43199802 millis.
,E/HttpOperation( 2973): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2973): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2973): 	at jdm.a(PG:82)
E/HttpOperation( 2973): 	at jcs.o(PG:406)
E/HttpOperation( 2973): 	at jcn.a(PG:1379)
E/HttpOperation( 2973): 	at jcs.i(PG:143)
E/HttpOperation( 2973): 	at blb.a(PG:3937)
E/HttpOperation( 2973): 	at czp.a(PG:18188)
E/HttpOperation( 2973): 	at czp.a(PG:9081)
E/HttpOperation( 2973): 	at czq.run(PG:1686)
E/HttpOperation( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2973): 	at jdj.a(PG:4091)
E/HttpOperation( 2973): 	at jdj.a(PG:1125)
E/HttpOperation( 2973): 	at jdm.a(PG:77)
E/HttpOperation( 2973): 	... 12 more
E/HttpOperation( 2973): Caused by: faj: BadAuthentication
E/HttpOperation( 2973): 	at fal.a(PG:38)
E/HttpOperation( 2973): 	at jdj.a(PG:4089)
E/HttpOperation( 2973): 	... 14 more
V/JNIHelp ( 3450): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/BackupManagerService(  824): Backup pass finished.
,W/ExperimentUpdateService( 3280): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3280): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3280): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3280): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3280): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2973): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2973): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2973): 	at jdm.a(PG:82)
E/HttpOperation( 2973): 	at jcs.o(PG:406)
E/HttpOperation( 2973): 	at jcn.a(PG:1379)
E/HttpOperation( 2973): 	at jcs.i(PG:143)
E/HttpOperation( 2973): 	at hec.a(PG:42)
E/HttpOperation( 2973): 	at hee.a(PG:102)
E/HttpOperation( 2973): 	at czr.a(PG:65)
E/HttpOperation( 2973): 	at kka.a(PG:108)
E/HttpOperation( 2973): 	at czp.a(PG:19176)
E/HttpOperation( 2973): 	at czp.a(PG:9081)
E/HttpOperation( 2973): 	at czq.run(PG:1686)
E/HttpOperation( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2973): 	at jdj.a(PG:4091)
E/HttpOperation( 2973): 	at jdj.a(PG:1125)
E/HttpOperation( 2973): 	at jdm.a(PG:77)
E/HttpOperation( 2973): 	... 15 more
E/HttpOperation( 2973): Caused by: faj: BadAuthentication
E/HttpOperation( 2973): 	at fal.a(PG:38)
E/HttpOperation( 2973): 	at jdj.a(PG:4089)
E/HttpOperation( 2973): 	... 17 more
,E/ExperimentLoader( 2973): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2973): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2973): 	at jdm.a(PG:82)
E/ExperimentLoader( 2973): 	at jcs.o(PG:406)
E/ExperimentLoader( 2973): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2973): 	at jcs.i(PG:143)
E/ExperimentLoader( 2973): 	at hec.a(PG:42)
E/ExperimentLoader( 2973): 	at hee.a(PG:102)
E/ExperimentLoader( 2973): 	at czr.a(PG:65)
E/ExperimentLoader( 2973): 	at kka.a(PG:108)
E/ExperimentLoader( 2973): 	at czp.a(PG:19176)
E/ExperimentLoader( 2973): 	at czp.a(PG:9081)
E/ExperimentLoader( 2973): 	at czq.run(PG:1686)
E/ExperimentLoader( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2973): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2973): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2973): 	at jdm.a(PG:77)
E/ExperimentLoader( 2973): 	... 15 more
E/ExperimentLoader( 2973): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2973): 	at fal.a(PG:38)
E/ExperimentLoader( 2973): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2973): 	... 17 more
,I/ProviderInstaller( 3450): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3450): GMSCore installation verified
,I/ConfigStore( 3450): Config Database version: 1
,W/DriveInitializer( 1791): Background init thread ended
,I/jxcore-log( 3204): Test app app.js loaded
I/jxcore-log( 3204): 
,I/Choreographer( 3204): Skipped 396 frames!  The application may be doing too much work on its main thread.
,I/Keyboard.Facilitator( 1215): onFinishInput()
,I/chromium( 3204): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  824): Start proc 3510:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 37032, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/MediaRouter( 3450): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3450): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3450): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 3450): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  824): Start proc 3532:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/GHttpClientFactory( 3450): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3450): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 3532): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3532): simOperator:  IMSI: null
D/SprintDMReceiver( 3532): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1791): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1791): onCreate
,D/SystemUpdateService( 1791): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1791): active receiver: enabled
V/KeepSync( 3306): Connecting to GoogleApiClient
,I/SystemUpdateService( 1791): showing system update notification
,I/ValidateNoPeople(  824): skipping global notification
,V/SystemUpdateService( 1791): retry (wakeup: false) in 3599990 ms
,D/SystemUpdateService( 1791): onDestroy
,I/iu.SyncManager( 1791): SYNC; picasa accounts
,D/NetworkLogImpl( 1791): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1791): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1791): num queued entries: 0
,I/iu.UploadsManager( 1791): num updated entries: 0
I/iu.SyncManager( 1791): NEXT; no task
,D/ChimeraCfgMgr( 1791): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1791): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     (  824): Explicit concurrent mark sweep GC freed 28949(1417KB) AllocSpace objects, 5(121KB) LOS objects, 32% free, 33MB/49MB, paused 1.521ms total 48.050ms
,I/ActivityManager(  824): Start proc 3566:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,W/BaseAppContext( 1791): Using Auth Proxy for data requests.
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1791): Using Auth Proxy for data requests.
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1791): [AccountUtils] Account not ready
W/Kids    ( 1791): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1791): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1791): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1791): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1791): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1791): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1791): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1791): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1791): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1791): 	at java.lang.Thread.run(Thread.java:818)
,E/ClientConnectionOperation( 1791): Handling authorization failure
E/ClientConnectionOperation( 1791): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1791): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1791): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1791): 	... 7 more
,V/KeepSync( 3306): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3306): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3306): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3306): (284) automatic index on blob_node(is_deleted)
,I/GAv4    ( 3566): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3566):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3566):   adb logcat -s GAv4
,W/GAV2    ( 3510): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3510): Created application version: 3.6.8 (30608)
,W/GAv4    ( 3566): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3566): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3566): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Babel   ( 2631): connection state changed from DISCONNECTED to CONNECTED
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1498): Explicit concurrent mark sweep GC freed 18417(1103KB) AllocSpace objects, 3(330KB) LOS objects, 38% free, 25MB/41MB, paused 668us total 20.526ms
,E/KeepSync( 3306): IOException
E/KeepSync( 3306): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3306): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3306): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3306): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3306): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3306): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3306): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3306): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3306): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3306): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3306): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3306): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3306): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3306): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3306): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3306): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3306): 	... 10 more
W/KeepSync( 3306): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 37035, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  824): Killing 2913:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/BooksSync( 3510): Starting books sync for 61035162, extras: ade
,I/VacuumService( 1498): Vacuum at: now=1449748704852 tag=VacuumService
,I/GoogleURLConnFactory( 1498): Using platform SSLCertificateSocketFactory
,I/WebViewFactory( 3566): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/Uploader( 1498): No account for auth token provided
,I/LibraryLoader( 3566): Time to load native libraries: 4 ms (timestamps 5355-5359)
I/LibraryLoader( 3566): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3566): Binding Chromium to main looper Looper (main, tid 1) {3faecba5}
,I/LibraryLoader( 3566): Expected native library version number "",actual native library version number ""
,I/chromium( 3566): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3566): Initializing chromium process, singleProcess=true
,W/art     ( 3566): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3566): ApplicationContext is null in ApplicationStatus
,W/chromium( 3566): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3566): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3566): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3566): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/BooksConfig( 3510): GmsCore Version = 7.8.99 (2134222-430)
,W/AudioManagerAndroid( 3566): Requires BLUETOOTH permission
,I/NSApplication( 3566): Starting up...
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  824): Killing 1387:android.process.acore/u0a5 (adj 15): empty #17
,D/GCM     ( 1498): Connected
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3510): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3510): Soft error
E/BooksSync( 3510): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3510): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3510): Sync error
E/BooksSync( 3510): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3510): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3510): Finished books sync
,D/GCM     ( 1498): Message class com.google.f.a.a.p
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37035, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  824): Killing 3086:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/ActivityManager(  824): Start proc 3646:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/ActivityManager(  824): Killing 3108:com.android.musicfx/u0a18 (adj 15): empty #17
,D/WifiService(  824): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@dbac86a}
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1498): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1498): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1498): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1498): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1498): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1498): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1498): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,E/LocSvc_IzatApiV02(  824): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/WifiService(  824): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3a819b83}
,I/art     (  824): Explicit concurrent mark sweep GC freed 22256(1000KB) AllocSpace objects, 6(96KB) LOS objects, 32% free, 33MB/49MB, paused 1.329ms total 80.963ms
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1498): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1498): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1498): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1498): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1498): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1498): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1498): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1498): No account for auth token provided
,W/Uploader( 1498): No account for auth token provided
,W/Uploader( 1498): No account for auth token provided
,W/Uploader( 1498): No account for auth token provided
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1498): Failed to get auth token: User intervention required. Notification has been pushed.
,E/Uploader( 1498): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1498): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1498): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1498): 	,at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1498): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1498): ,	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1498): 	,at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1498): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1498): No account for auth token provided
,W/Uploader( 1498): No account for auth token provided
,W/Uploader( 1498): No account for auth token provided
,I/ActivityManager(  824): Start proc 3663:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
I/ActivityManager(  824): Killing 1825:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,W/Uploader( 1498): No account for auth token provided
,V/Herrevad( 1791): NQAS connected
,D/WifiService(  824): New client listening to asynchronous messages
,E/SQLiteLog( 3663): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal,
,W/Uploader( 1498):  no longer exists, so no auth token.
,I/art     ( 1791): Explicit concurrent mark sweep GC freed 15207(1187KB) AllocSpace objects, 17(272KB) LOS objects, 35% free, 28MB/44MB, paused 1.359ms total 49.868ms
,I/ActivityManager(  824): Start proc 3686:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/ResourcesManager( 3686): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1498): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1498): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1498): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1498): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1498): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1498): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1498): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1498): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/CalendarProvider2( 3686): Created com.android.providers.calendar.CalendarAlarmManager@5b04f6b(com.android.providers.calendar.CalendarProvider2@3c069ac8)
,I/ActivityManager(  824): Start proc 3708:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3663): PlayLogger.onLoggerConnected
,W/Uploader( 1498): No account for auth token provided
,D/TimeService( 3708): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449748707227
D/        ( 3708): TimeServiceNative: User Time to be set is 1449748707227
D/QC-time-services( 3708): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3708): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3708): Lib:time_genoff_operation: pargs->ts_val = 1449748707227
,D/QC-time-services( 3708): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  373): Daemon: Connection accepted:time_genoff
D/QC-time-services(  373): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449748707227
D/QC-time-services(  373): Daemon:genoff_opr: Base = 2, val = 1449748707227, operation = 0
D/QC-time-services(  373): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/27/70 8:11:20
D/QC-time-services(  373): Daemon:Value read from RTC seconds = 10051880000
D/QC-time-services(  373): Daemon:new time 1449748707227 
D/QC-time-services(  373): Daemon: delta 1439696827227 genoff 1439696827227 
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696827227 to memory
,D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  373): Updating the TOD offset
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696827227 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  373): Daemon:Update to modem bit set,
,D/QC-time-services(  373): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  373): Daemon: Base = 2, Value being sent to MODEM = 1133783907227
E/QC-time-services( 3708): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager(  824): Killing 3134:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,E/QC-time-services(  373): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  373): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/Uploader( 1498): No account for auth token provided
,I/ActivityManager(  824): Start proc 3728:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 344us total 17.115ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 345us total 14.944ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 344us total 20.036ms
,I/GAv4    ( 3728): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 3728):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3728):   adb logcat -s GAv4
,W/GAv4    ( 3728): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3728): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3728): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  824): Killing 3040:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/CalendarProvider2( 3686): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3686): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Babel   ( 2631): UserRecoverableAuthException.
,E/Babel   ( 2631): eei: BadAuthentication
E/Babel   ( 2631): 	at eeg.a(Unknown Source)
E/Babel   ( 2631): 	at eeg.a(Unknown Source)
E/Babel   ( 2631): 	at eeg.a(Unknown Source)
E/Babel   ( 2631): 	at g.a(Unknown Source)
E/Babel   ( 2631): 	at cae.a(SourceFile:3089)
E/Babel   ( 2631): 	at cae.a(SourceFile:1131)
E/Babel   ( 2631): 	at cws.a(SourceFile:4333)
E/Babel   ( 2631): 	at cws.a(SourceFile:1419)
E/Babel   ( 2631): 	at crl.a(SourceFile:492)
E/Babel   ( 2631): 	at crl.a(SourceFile:1468)
E/Babel   ( 2631): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2631): 	at cas.b(SourceFile:106)
E/Babel   ( 2631): 	at cap.d(SourceFile:335)
E/Babel   ( 2631): 	at caq.run(SourceFile:81)
E/Babel   ( 2631): Error getting auth token
,E/Babel   ( 2631): dvm
E/Babel   ( 2631): 	at g.a(Unknown Source)
E/Babel   ( 2631): 	at cae.a(SourceFile:3089)
E/Babel   ( 2631): 	at cae.a(SourceFile:1131)
E/Babel   ( 2631): 	at cws.a(SourceFile:4333)
E/Babel   ( 2631): 	at cws.a(SourceFile:1419)
E/Babel   ( 2631): 	at crl.a(SourceFile:492)
E/Babel   ( 2631): 	at crl.a(SourceFile:1468)
E/Babel   ( 2631): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2631): 	at cas.b(SourceFile:106)
E/Babel   ( 2631): 	at cap.d(SourceFile:335)
E/Babel   ( 2631): 	at caq.run(SourceFile:81)
,E/Babel   ( 2631): Account registration failed 1-Redacted-21
E/Babel   ( 2631): cyp: null -- null
E/Babel   ( 2631): 	at cae.a(SourceFile:3121)
E/Babel   ( 2631): 	at cae.a(SourceFile:1131)
E/Babel   ( 2631): 	at cws.a(SourceFile:4333)
E/Babel   ( 2631): 	at cws.a(SourceFile:1419)
E/Babel   ( 2631): 	at crl.a(SourceFile:492)
E/Babel   ( 2631): 	at crl.a(SourceFile:1468)
E/Babel   ( 2631): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2631): 	at cas.b(SourceFile:106)
E/Babel   ( 2631): 	at cap.d(SourceFile:335)
E/Babel   ( 2631): 	at caq.run(SourceFile:81)
,I/art     ( 2631): Note: end time exceeds epoch: 
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1498): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2631): Unexpected exception while authenticating.
E/Babel   ( 2631): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2631): 	at eeg.b(Unknown Source)
E/Babel   ( 2631): 	at eeg.b(Unknown Source)
E/Babel   ( 2631): 	at g.a(Unknown Source)
E/Babel   ( 2631): 	at cae.b(SourceFile:1146)
E/Babel   ( 2631): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2631): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2631): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2631): 	at java.lang.Thread.run(Thread.java:818)
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=40.00 rxSuccessRate=37.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 7 -> obsolete
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=40.00 rxSuccessRate=37.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 7 -> obsolete
,E/SQLiteLog( 3686): (284) automatic index on view_events(_id)
,I/art     ( 1498): Explicit concurrent mark sweep GC freed 44040(2MB) AllocSpace objects, 7(401KB) LOS objects, 36% free, 27MB/43MB, paused 1.411ms total 60.560ms
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicLeanback( 3450): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3450): Stop autocaching.
,I/art     (  824): Explicit concurrent mark sweep GC freed 17371(818KB) AllocSpace objects, 4(441KB) LOS objects, 32% free, 33MB/49MB, paused 1.255ms total 64.983ms
,I/ActivityManager(  824): Start proc 3778:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,W/ResourcesManager( 3778): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3778): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3778): VM with version 2.1.0 has multidex support
,I/MultiDex( 3778): install
I/MultiDex( 3778): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3778): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3778): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1498): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1498): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 1791): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3778): callingUid 10011, callindPid: 3778
,D/LocationInitializer( 1791): Restart initialization of location
,E/MDM     ( 1756): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAV2    ( 3510): Thread[GAThread,5,main]: No campaign data found.
,E/GmsUtils( 3450): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3450): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAV2    ( 3663): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  824): Killing 2706:com.android.vending/u0a19 (adj 15): empty #17
,I/ActivityManager(  824): Start proc 3812:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/Finsky  ( 3812): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3812): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  824): Start proc 3848:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3812): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3812): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 3848): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3848): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 3812): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3812): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 3812): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 3848): VM with version 2.1.0 has multidex support
I/MultiDex( 3848): install
I/MultiDex( 3848): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 3812): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 3848): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3848): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1498): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1498): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/ActivityManager(  824): Killing 3348:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  824): Killing 3365:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,V/GmsCoreStatsServiceLauncher( 1791): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/Finsky  ( 3812): [394] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/WearableService( 3778): callingUid 10011, callindPid: 3778
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1756): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1791): Restart initialization of location
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3812): [394] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3812): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,V/Finsky  ( 3812): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/Finsky  ( 3812): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3812): [1] 5.onFinished: Scheduling replication attempt 4.
,D/Finsky  ( 3812): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3812): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3812): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3812): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 3812): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3812): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3812): [1] DailyHygiene.reschedule: Scheduling new run in 95 minutes (failures=3)
,D/DeviceConnectionService( 1756): client connected with version: 7571000
,I/ActivityManager(  824): Killing 3532:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  824): Killing 3566:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,E/WifiStateMachine(  824): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=40.00 rxSuccessRate=37.00 targetRoamBSSID=any RSSI=-52
E/WifiStateMachine(  824): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,D/WifiService(  824): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3a819b83}
,D/HeadsetStateMachine( 3261): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3261): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3280): [338] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3280): [339] a.<init>: mAccountName set to: thalitester@gmail.com
,I/art     (  824): Explicit concurrent mark sweep GC freed 23233(1017KB) AllocSpace objects, 4(441KB) LOS objects, 32% free, 33MB/49MB, paused 1.521ms total 49.685ms
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3812): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3812): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3812): [1] 5.onFinished: Scheduling replication attempt 5.
,W/ExperimentUpdateService( 3280): [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3280): [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3280): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3280): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3280): 	at com.a.a.k.run(SourceFile:110)
,I/art     ( 1498): Explicit concurrent mark sweep GC freed 33893(1778KB) AllocSpace objects, 18(1984KB) LOS objects, 38% free, 25MB/41MB, paused 1.167ms total 46.997ms
,W/ExperimentUpdateService( 3280): [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3280): [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3280): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3280): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3280): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3812): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3812): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3812): [1] 5.onFinished: Giving up after 6 failures.
,V/KeepSync( 3306): Connecting to GoogleApiClient
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/HttpOperation( 2973): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2973): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2973): 	at jdm.a(PG:82)
E/HttpOperation( 2973): 	at jcs.o(PG:406)
E/HttpOperation( 2973): 	at jcn.a(PG:1379)
E/HttpOperation( 2973): 	at jcs.i(PG:143)
E/HttpOperation( 2973): 	at blb.a(PG:3937)
E/HttpOperation( 2973): 	at czp.a(PG:18188)
E/HttpOperation( 2973): 	at czp.a(PG:9087)
E/HttpOperation( 2973): 	at czq.run(PG:1686)
E/HttpOperation( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/HttpOperation( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2973): 	at jdj.a(PG:4091)
E/HttpOperation( 2973): 	at jdj.a(PG:1125)
E/HttpOperation( 2973): 	at jdm.a(PG:77)
E/HttpOperation( 2973): 	... 12 more
E/HttpOperation( 2973): Caused by: faj: BadAuthentication
E/HttpOperation( 2973): 	at fal.a(PG:38)
E/HttpOperation( 2973): ,	at jdj.a(PG:4089)
E/HttpOperation( 2973): 	... 14 more
,E/ClientConnectionOperation( 1791): Handling authorization failure
E/ClientConnectionOperation( 1791): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1791): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1791): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1791): 	... 7 more
,V/KeepSync( 3306): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3306): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3306): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3306): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3306): IOException
E/KeepSync( 3306): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3306): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3306): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3306): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3306): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3306): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3306): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3306): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3306): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3306): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3306): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3306): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3306): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3306): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3306): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3306): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3306): 	... 10 more
W/KeepSync( 3306): Sync result 2
,E/HttpOperation( 2973): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2973): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2973): 	at jdm.a(PG:82)
E/HttpOperation( 2973): 	at jcs.o(PG:406)
E/HttpOperation( 2973): 	at jcn.a(PG:1379)
E/HttpOperation( 2973): 	at jcs.i(PG:143)
E/HttpOperation( 2973): 	at blb.a(PG:3937)
E/HttpOperation( 2973): 	at czp.a(PG:18188)
E/HttpOperation( 2973): 	at czp.a(PG:9081)
E/HttpOperation( 2973): 	at czq.run(PG:1686)
E/HttpOperation( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2973): 	at jdj.a(PG:4091)
E/HttpOperation( 2973): 	at jdj.a(PG:1125)
E/HttpOperation( 2973): 	at jdm.a(PG:77)
E/HttpOperation( 2973): 	... 12 more
E/HttpOperation( 2973): Caused by: faj: BadAuthentication
E/HttpOperation( 2973): 	at fal.a(PG:38)
E/HttpOperation( 2973): 	at jdj.a(PG:4089)
E/HttpOperation( 2973): 	... 14 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 196552, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3510): Starting books sync for 61035162, extras: ade
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/BooksConfig( 3510): GmsCore Version = 7.8.99 (2134222-430)
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1215): run()
,I/Keyboard.Facilitator( 1215): flushDynamicLanguageModels()
E/HttpOperation( 2973): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2973): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2973): 	at jdm.a(PG:82)
E/HttpOperation( 2973): 	at jcs.o(PG:406)
E/HttpOperation( 2973): 	at jcn.a(PG:1379)
E/HttpOperation( 2973): 	at jcs.i(PG:143)
E/HttpOperation( 2973): 	at hec.a(PG:42)
E/HttpOperation( 2973): 	at hee.a(PG:102)
E/HttpOperation( 2973): 	at czr.a(PG:65)
E/HttpOperation( 2973): 	at kka.a(PG:108)
E/HttpOperation( 2973): 	at czp.a(PG:19176)
E/HttpOperation( 2973): 	at czp.a(PG:9081)
E/HttpOperation( 2973): 	at czq.run(PG:1686)
E/HttpOperation( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2973): 	at jdj.a(PG:4091)
E/HttpOperation( 2973): 	at jdj.a(PG:1125)
E/HttpOperation( 2973): 	at jdm.a(PG:77)
E/HttpOperation( 2973): 	... 15 more
E/HttpOperation( 2973): Caused by: faj: BadAuthentication
E/HttpOperation( 2973): 	at fal.a(PG:38)
E/HttpOperation( 2973): 	at jdj.a(PG:4089)
E/HttpOperation( 2973): 	... 17 more
E/ExperimentLoader( 2973): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2973): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2973): 	at jdm.a(PG:82)
E/ExperimentLoader( 2973): 	at jcs.o(PG:406)
E/ExperimentLoader( 2973): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2973): 	at jcs.i(PG:143)
E/ExperimentLoader( 2973): 	at hec.a(PG:42)
E/ExperimentLoader( 2973): 	at hee.a(PG:102)
E/ExperimentLoader( 2973): 	at czr.a(PG:65)
E/ExperimentLoader( 2973): 	at kka.a(PG:108)
E/ExperimentLoader( 2973): 	at czp.a(PG:19176)
E/ExperimentLoader( 2973): 	at czp.a(PG:9081)
E/ExperimentLoader( 2973): 	at czq.run(PG:1686)
E/ExperimentLoader( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2973): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2973): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2973): 	at jdm.a(PG:77)
E/ExperimentLoader( 2973): 	... 15 more
E/ExperimentLoader( 2973): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2973): 	at fal.a(PG:38)
E/ExperimentLoader( 2973): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2973): 	... 17 more
,I/ConfigService( 1498): onCreate
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 164723, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3510): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3510): Soft error
E/BooksSync( 3510): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3510): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3510): Sync error
E/BooksSync( 3510): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3510): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3510): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 198033, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1498): onDestroy
,D/HeadsetStateMachine( 3261): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3261): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3280): [340] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3280): [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3280): [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3280): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3280): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3280): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3280): [341] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3280): [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3280): [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3280): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3280): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3280): 	at com.a.a.k.run(SourceFile:110)
,I/art     (  824): Explicit concurrent mark sweep GC freed 33104(1499KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.438ms total 82.664ms
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2973): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2973): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2973): 	at jdm.a(PG:82)
E/HttpOperation( 2973): 	at jcs.o(PG:406)
E/HttpOperation( 2973): 	at jcn.a(PG:1379)
E/HttpOperation( 2973): 	at jcs.i(PG:143)
E/HttpOperation( 2973): 	at blb.a(PG:3937)
E/HttpOperation( 2973): 	at czp.a(PG:18188)
E/HttpOperation( 2973): 	at czp.a(PG:9081)
E/HttpOperation( 2973): 	at czq.run(PG:1686)
E/HttpOperation( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2973): 	at jdj.a(PG:4091)
E/HttpOperation( 2973): 	at jdj.a(PG:1125)
E/HttpOperation( 2973): 	at jdm.a(PG:77)
E/HttpOperation( 2973): 	... 12 more
E/HttpOperation( 2973): Caused by: faj: BadAuthentication
E/HttpOperation( 2973): 	at fal.a(PG:38)
E/HttpOperation( 2973): 	at jdj.a(PG:4089)
E/HttpOperation( 2973): 	... 14 more
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2973): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2973): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2973): 	at jdm.a(PG:82)
E/HttpOperation( 2973): 	at jcs.o(PG:406)
E/HttpOperation( 2973): 	at jcn.a(PG:1379)
E/HttpOperation( 2973): 	at jcs.i(PG:143)
E/HttpOperation( 2973): 	at hec.a(PG:42)
E/HttpOperation( 2973): 	at hee.a(PG:102)
E/HttpOperation( 2973): 	at czr.a(PG:65)
E/HttpOperation( 2973): 	at kka.a(PG:108)
E/HttpOperation( 2973): 	at czp.a(PG:19176)
E/HttpOperation( 2973): 	at czp.a(PG:9081)
E/HttpOperation( 2973): 	at czq.run(PG:1686)
E/HttpOperation( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2973): 	at jdj.a(PG:4091)
E/HttpOperation( 2973): 	at jdj.a(PG:1125)
E/HttpOperation( 2973): 	at jdm.a(PG:77)
E/HttpOperation( 2973): 	... 15 more
E/HttpOperation( 2973): Caused by: faj: BadAuthentication
E/HttpOperation( 2973): 	at fal.a(PG:38)
E/HttpOperation( 2973): 	at jdj.a(PG:4089)
E/HttpOperation( 2973): 	... 17 more
E/ExperimentLoader( 2973): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2973): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2973): 	at jdm.a(PG:82)
E/ExperimentLoader( 2973): 	at jcs.o(PG:406)
E/ExperimentLoader( 2973): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2973): 	at jcs.i(PG:143)
E/ExperimentLoader( 2973): 	at hec.a(PG:42)
E/ExperimentLoader( 2973): 	at hee.a(PG:102)
E/ExperimentLoader( 2973): 	at czr.a(PG:65)
E/ExperimentLoader( 2973): 	at kka.a(PG:108)
E/ExperimentLoader( 2973): 	at czp.a(PG:19176)
E/ExperimentLoader( 2973): 	at czp.a(PG:9081)
E/ExperimentLoader( 2973): 	at czq.run(PG:1686)
E/ExperimentLoader( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2973): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2973): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2973): 	at jdm.a(PG:77)
E/ExperimentLoader( 2973): 	... 15 more
E/ExperimentLoader( 2973): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2973): 	at fal.a(PG:38)
E/ExperimentLoader( 2973): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2973): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 256620, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3261): Disconnected process message: 10, size: 0
,I/BooksSync( 3510): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3306): Connecting to GoogleApiClient
,I/BooksConfig( 3510): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1791): Handling authorization failure
E/ClientConnectionOperation( 1791): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1791): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1791): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1791): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1791): 	... 7 more
,V/KeepSync( 3306): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3306): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3306): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3306): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3510): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3510): Soft error
E/BooksSync( 3510): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3510): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3510): Sync error
E/BooksSync( 3510): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3510): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3510): Finished books sync
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 289463, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1498): Explicit concurrent mark sweep GC freed 45287(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.690ms total 58.943ms
,E/KeepSync( 3306): IOException
E/KeepSync( 3306): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3306): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3306): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3306): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3306): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3306): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3306): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3306): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3306): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3306): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3306): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3306): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3306): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3306): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3306): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3306): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3306): 	... 10 more
W/KeepSync( 3306): Sync result 2
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 287214, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3261): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3270): wlan0: WPA: Group rekeying completed with c0:ff:d4:d3:aa:4a [GTK=CCMP]
,D/HeadsetStateMachine( 3261): Disconnected process message: 10, size: 0
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2973): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2973): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2973): 	at jdm.a(PG:82)
E/HttpOperation( 2973): 	at jcs.o(PG:406)
E/HttpOperation( 2973): 	at jcn.a(PG:1379)
E/HttpOperation( 2973): 	at jcs.i(PG:143)
E/HttpOperation( 2973): 	at blb.a(PG:3937)
E/HttpOperation( 2973): 	at czp.a(PG:18188)
E/HttpOperation( 2973): 	at czp.a(PG:9081)
E/HttpOperation( 2973): 	at czq.run(PG:1686)
E/HttpOperation( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2973): 	at jdj.a(PG:4091)
E/HttpOperation( 2973): 	at jdj.a(PG:1125)
E/HttpOperation( 2973): 	at jdm.a(PG:77)
E/HttpOperation( 2973): 	... 12 more
E/HttpOperation( 2973): Caused by: faj: BadAuthentication
E/HttpOperation( 2973): 	at fal.a(PG:38)
E/HttpOperation( 2973): 	at jdj.a(PG:4089)
E/HttpOperation( 2973): 	... 14 more
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2973): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2973): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2973): 	at jdm.a(PG:82)
E/HttpOperation( 2973): 	at jcs.o(PG:406)
E/HttpOperation( 2973): 	at jcn.a(PG:1379)
E/HttpOperation( 2973): 	at jcs.i(PG:143)
E/HttpOperation( 2973): 	at hec.a(PG:42)
E/HttpOperation( 2973): 	at hee.a(PG:102)
E/HttpOperation( 2973): 	at czr.a(PG:65)
E/HttpOperation( 2973): 	at kka.a(PG:108)
E/HttpOperation( 2973): 	at czp.a(PG:19176)
E/HttpOperation( 2973): 	at czp.a(PG:9081)
E/HttpOperation( 2973): 	at czq.run(PG:1686)
E/HttpOperation( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2973): 	at jdj.a(PG:4091)
E/HttpOperation( 2973): 	at jdj.a(PG:1125)
E/HttpOperation( 2973): 	at jdm.a(PG:77)
E/HttpOperation( 2973): 	... 15 more
E/HttpOperation( 2973): Caused by: faj: BadAuthentication
E/HttpOperation( 2973): 	at fal.a(PG:38)
E/HttpOperation( 2973): 	at jdj.a(PG:4089)
E/HttpOperation( 2973): 	... 17 more
,E/ExperimentLoader( 2973): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2973): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2973): 	at jdm.a(PG:82)
E/ExperimentLoader( 2973): 	at jcs.o(PG:406)
E/ExperimentLoader( 2973): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2973): 	at jcs.i(PG:143)
E/ExperimentLoader( 2973): 	at hec.a(PG:42)
E/ExperimentLoader( 2973): 	at hee.a(PG:102)
E/ExperimentLoader( 2973): 	at czr.a(PG:65)
E/ExperimentLoader( 2973): 	at kka.a(PG:108)
E/ExperimentLoader( 2973): 	at czp.a(PG:19176)
E/ExperimentLoader( 2973): 	at czp.a(PG:9081)
E/ExperimentLoader( 2973): 	at czq.run(PG:1686)
E/ExperimentLoader( 2973): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2973): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2973): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2973): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2973): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2973): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2973): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2973): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2973): 	at jdm.a(PG:77)
E/ExperimentLoader( 2973): 	... 15 more
E/ExperimentLoader( 2973): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2973): 	at fal.a(PG:38)
E/ExperimentLoader( 2973): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2973): 	... 17 more
,D/SyncManager(  824): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 348471, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3204): Toggling radios to false
I/jxcore-log( 3204): 
,D/BluetoothManagerService(  824): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  824): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@9fd3396 mBinding = false
,D/BluetoothManagerService(  824): Message: 2
,D/BluetoothManagerService(  824): Sending off request.
,D/WifiService(  824): setWifiEnabled: false pid=3204, uid=10265
D/BluetoothAdapterState( 3261): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3261): Setting state to 13
I/BluetoothAdapterState( 3261): Bluetooth adapter state changed: 12-> 13
E/WifiService(  824): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothAdapterProperties( 3261): onBluetoothDisable()
,I/BluetoothAdapterState( 3261): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true,
D/BluetoothManagerService(  824): Message: 60
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13,
D/BluetoothManagerService(  824): Bluetooth State Change Intent: 12 -> 13
D/BluetoothMapService( 3261): onReceive
,D/BluetoothMapService( 3261): STATE_TURNING_OFF,
D/BluetoothMapService( 3261): MAP Service closeService in
,D/BluetoothMapMasInstance( 3261): MAP Service shutdown
,V/BluetoothMapMasInstance( 3261): Accept exception: (expected at shutdown),
V/BluetoothMapMasInstance( 3261): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3261): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3261): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3261): 	,at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3261): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3261): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3261): ,	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
I/BtOppRfcommListener( 3261): stopping Accept Thread
,E/BtOppRfcommListener( 3261): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 3261): BluetoothSocket listen thread finished
,I/jxcore-log( 3204): Radios toggled,
I/jxcore-log( 3204): 
E/WifiStateMachine(  824): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  824): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  824): do suspend true
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1498): Read error: ssl=0x9cc03400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1498): SSL shutdown failed: ssl=0x9cc03400: I/O error during system call, Broken pipe
,I/ActivityManager(  824): Start proc 3959:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/BluetoothAdapterProperties( 3261): Scan Mode:20
D/BluetoothAdapterState( 3261): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 3261): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-btif ( 3261): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3261): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3261): L2CAP - PSM: 0x0017 not found for deregistration
,D/ConnectivityService(  824): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Forcing reevaluation,
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  824): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  824): scanCount==0 - aborting
,D/WifiScanningService(  824): SCAN_AVAILABLE : 1
D/WifiScanningService(  824): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  824): DefaultState
D/RttService(  824): SCAN_AVAILABLE : 1
D/RttService(  824): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNetworkAgent(  824): NetworkAgent: NetworkAgent channel lost
,E/native  (  824): do suspend true
,W/ContextImpl( 3959): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,E/WifiStateMachine(  824): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/ConnectivityService(  824): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  824): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  824): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1067): CM callback handler got msg 524292
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  824): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  824): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3450): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  824): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  824): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  824): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  824): MasterInitialState.processMessage what=3
,D/BluetoothManagerService(  824): Message: 20
D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@650f322:true
,I/wpa_supplicant( 3270): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,D/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  824): getDataEnabled: retVal=false
,I/wpa_supplicant( 3270): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/ActivityManager(  824): Start proc 3982:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothManagerService(  824): Message: 30
,E/GpsLocationProvider(  824): No APN found to select.
,D/BluetoothManagerService(  824): Message: 30
,D/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,D/LocalBluetoothProfileManager( 3959): Adding local MAP profile
E/PhoneInterfaceManager( 1280): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  824): getDataEnabled: retVal=false
D/BluetoothMap( 3959): Create BluetoothMap proxy object
D/BluetoothManagerService(  824): Message: 30
,E/GpsLocationProvider(  824): No APN found to select.
,D/BluetoothManagerService(  824): Message: 30
,D/LocalBluetoothProfileManager( 3959): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3959): finishStartingService: stopping service
,D/BluetoothInputDevice( 3959): Proxy object connected
,D/HidProfile( 3959): Bluetooth service connected
,D/BluetoothPan( 3959): BluetoothPAN Proxy object connected
D/PanProfile( 3959): Bluetooth service connected
D/BluetoothMap( 3959): Proxy object connected
D/MapProfile( 3959): Bluetooth service connected
D/BluetoothMap( 3959): getConnectedDevices()
,D/BluetoothMap( 3959): Bluetooth is Not enabled
,I/ActivityManager(  824): Killing 3708:com.qualcomm.timeservice/1000 (adj 15): empty #17
,D/bt_userial( 3261): RX termination
W/bt_userial( 3261): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3261): Leaving userial_read_thread()
W/bt-btif ( 3261): ag scb idx 1 not allocated
E/bt-btif ( 3261): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3261): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3261): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3261): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3261): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3261): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3261): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3261): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3261): hw_epilog_process
I/bt_userial_vendor( 3261): device fd = 53 close
,I/wpa_supplicant( 3270): wlan0: CTRL-EVENT-TERMINATING 
E/WifiMonitor(  824): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
D/Tethering(  824): InitialState.processMessage what=4
,D/Tethering(  824): sendTetherStateChangedBroadcast 0, 0, 0
,W/Settings( 2631): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1756): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GKI_LINUX( 3261): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3261): GKI_exit_task 0 done
I/GKI_LINUX( 3261): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3261): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3261): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 3261): Exit Disconnected: -1
D/BluetoothHeadset( 1067): Proxy object disconnected
D/BluetoothHeadset(  824): Proxy object disconnected
D/BluetoothHeadset( 1280): Proxy object disconnected
,D/BluetoothHeadset(  824): Proxy object disconnected
D/BluetoothHeadset(  824): Proxy object disconnected
,D/BluetoothAdapterState( 3261): Stopping profile services that were post enabled
,D/A2dpService( 3261): Received stop request...Stopping profile...
D/A2dpStateMachine( 3261): Exit Disconnected: -1
,D/BluetoothA2dp(  824): Proxy object disconnected
D/BluetoothA2dp( 1067): Proxy object disconnected
,D/HidService( 3261): Received stop request...Stopping profile...
,D/BluetoothInputDevice( 1067): Proxy object disconnected,
D/HealthService( 3261): Received stop request...Stopping profile...
D/BluetoothInputDevice( 3959): Proxy object disconnected
D/HidProfile( 3959): Bluetooth service disconnected
D/PanService( 3261): Received stop request...Stopping profile...
,D/BluetoothPan( 1067): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 3959): BluetoothPAN Proxy object disconnected,
D/PanProfile( 3959): Bluetooth service disconnected
D/BtGatt.DebugUtils( 3261): handleDebugAction() action=null
D/BtGatt.GattService( 3261): Received stop request...Stopping profile...
D/BtGatt.GattService( 3261): stop()
D/BtGatt.AdvertiseManager( 3261): advertise clients cleared
,D/HeadsetStateMachine( 3261): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3261): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3261): Cleaning up Bluetooth Handsfree callback object
D/BluetoothMapService( 3261): Received stop request...Stopping profile...
D/BluetoothMapService( 3261): stop()
,D/BluetoothMapEmailAppObserver( 3261): deinitObservers()
,D/BluetoothMapEmailAppObserver( 3261): removeReceiver()
D/BluetoothMap( 1067): Proxy object disconnected
,I/GKI_LINUX( 3261): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3261): GKI_exit_task 2 done
D/BluetoothMap( 3959): Proxy object disconnected
I/GKI_LINUX( 3261): GKI_shutdown(): task [A2DP-MEDIA] terminated,
D/MapProfile( 3959): Bluetooth service disconnected
W/BluetoothHidServiceJni( 3261): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 3261): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3261): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3261): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3261): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3261): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3261): Cleaning up Bluetooth PAN callback object
,D/BluetoothMapService( 3261): MAP Service closeService in
D/BluetoothAdapterState( 3261): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 3261): cleanup()
D/BluetoothMapService( 3261): MAP Service closeService in
D/BluetoothAdapterProperties( 3261): Setting state to 10
I/BluetoothAdapterState( 3261): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService(  824): Message: 60
D/BluetoothManagerService(  824): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  824): Broadcasting onBluetoothStateChange(false) to 17 receivers.
I/BluetoothAdapterState( 3261): Entering OffState
,D/BluetoothMap( 1067): onBluetoothStateChange: up=false
D/BluetoothHeadset(  824): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1067): onBluetoothStateChange: up=false
D/BluetoothA2dp(  824): onBluetoothStateChange: up=false
D/BluetoothA2dpSink( 1067): onBluetoothStateChange: up=false
,E/BluetoothA2dpSink( 1067): 
E/BluetoothA2dpSink( 1067): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@d90d1f3
E/BluetoothA2dpSink( 1067): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1067): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1067): 	,at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1067): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1067): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1067): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothHeadset(  824): onBluetoothStateChange: up=false
D/BluetoothHeadset(  824): onBluetoothStateChange: up=false
D/BluetoothAvrcpController( 1067): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1067): 
E/BluetoothAvrcpController( 1067): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@3b939eb0
E/BluetoothAvrcpController( 1067): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029),
E/BluetoothAvrcpController( 1067): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1067): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1067): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1067): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1067): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothHeadset( 1280): onBluetoothStateChange: up=false
D/BluetoothPbap( 3959): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 1067): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1067): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3959): onBluetoothStateChange: up=false
,D/BluetoothHeadsetClient( 1067): onBluetoothStateChange: up=false
,E/BluetoothHeadsetClient( 1067): 
,E/BluetoothHeadsetClient( 1067): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@4546129
E/BluetoothHeadsetClient( 1067): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1067): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1067): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1067): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1067): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
,E/BluetoothHeadsetClient( 1067): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothMap( 3959): onBluetoothStateChange: up=false
D/BluetoothManagerService(  824): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  824): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  824): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@9fd3396 mBinding = false
,D/BluetoothManagerService(  824): Sending unbind request.
,D/BluetoothManagerService(  824): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter( 1067): 987520177: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1067): 987520177: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1067): 987520177: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3261): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3261): GKI_exit_task 1 done
I/GKI_LINUX( 3261): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3261): cleanupNative: return from cleanup
,I/art     ( 3261): System.exit called, status: 0
I/AndroidRuntime( 3261): VM exiting with result code 0, cleanup skipped.
,I/ActivityManager(  824): Process com.android.bluetooth (pid 3261) has died
,D/StrictMode( 3982): StrictMode policy violation; ~duration=335 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3982): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3982): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3982): 	at java.io.File.doAccess(File.java:283)
,D/StrictMode( 3982): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3982): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3982): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3982): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3982): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3982): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3982): 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3982): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3982): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3982): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3982): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3982): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903),
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3982): StrictMode policy violation; ~duration=334 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3982): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3982): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3982): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3982): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3982): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510),
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3982): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3982): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553),
D/StrictMode( 3982): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3982): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3982): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3982): 	,at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3982): ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3982): StrictMode policy violation; ~duration=329 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3982): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3982): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182),
D/StrictMode( 3982): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3982): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3982): ,	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3982): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3982): 	at java.lang.System.loadLibrary(System.java:988),
D/StrictMode( 3982): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3982): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3982): ,	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3982): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
,D/StrictMode( 3982): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3982): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3982): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3982): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3982): StrictMode policy violation; ~duration=322 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3982): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3982): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3982): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3982): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3982): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3982): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3982): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3982): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3982): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3982): StrictMode policy violation; ~duration=310 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3982): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3982): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3982): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3982): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3982): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3982): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3982): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3982): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3982): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3982): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3982): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3982): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3982): StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3982): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3982): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3982): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3982): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3982): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3982): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3982): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3982): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3982): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3982): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3982): # via Binder call with stack:
D/StrictMode( 3982): android.os.StrictMode$LogStackTrace
D/StrictMode( 3982): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3982): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3982): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3982): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3982): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3982): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3982): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3982): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3982): 	at com.google.b.a.by.a(PG:125),
D/StrictMode( 3982): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3982): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3982): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3982): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3982): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3982): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3982): StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3982): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3982): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3982): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3982): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3982): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3982): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3982): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3982): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3982): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3982): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3982): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3982): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3982): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3982): StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3982): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3982): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3982): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3982): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3982): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3982): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3982): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3982): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3982): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3982): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3982): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3982): StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3982): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3982): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3982): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3982): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3982): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3982): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587),
D/StrictMode( 3982): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3982): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3982): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3982): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3982): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3982): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3982): StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3982): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3982): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3982): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3982): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3982): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3982): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3982): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3982): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3982): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3982): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3982): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3982): 	at com.google.p.e.b(PG:21)
,D/StrictMode( 3982): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3982): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3982): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3982): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3982): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3982): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3982): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3982): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3982): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3982): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,W/com.google.a.a.a.b.a( 3982): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  824): Message: 20
,D/BluetoothManagerService(  824): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2844402a:true
,I/ActivityManager(  824): Killing 3646:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1498): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/MusicLeanback( 3450): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  824): Start proc 4009:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/art     (  824): Explicit concurrent mark sweep GC freed 37200(1697KB) AllocSpace objects, 7(300KB) LOS objects, 32% free, 33MB/49MB, paused 1.413ms total 85.909ms
,D/SprintDMReceiver( 4009): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4009): simOperator:  IMSI: null
D/SprintDMReceiver( 4009): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1791): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1791): onCreate
,D/SystemUpdateService( 1791): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1791): active receiver: enabled
,I/SystemUpdateService( 1791): showing system update notification
,I/iu.Environment( 1791): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1791): num queued entries: 0
I/iu.UploadsManager( 1791): num updated entries: 0
I/iu.SyncManager( 1791): NEXT; no task
,D/ChimeraCfgMgr( 1791): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  824): skipping global notification
,V/SystemUpdateService( 1791): retry (wakeup: false) in 3599977 ms
,I/Babel   ( 2631): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  824): Start proc 4030:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1791): onDestroy
,I/ActivityManager(  824): Killing 3663:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/GAv4    ( 4030): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4030):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4030):   adb logcat -s GAv4
,W/GAv4    ( 4030): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4030): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4030): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 4030): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4030): Time to load native libraries: 4 ms (timestamps 9671-9675)
,I/LibraryLoader( 4030): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4030): Binding Chromium to main looper Looper (main, tid 1) {397f410f}
I/LibraryLoader( 4030): Expected native library version number "",actual native library version number ""
,I/chromium( 4030): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4030): Initializing chromium process, singleProcess=true,
W/art     ( 4030): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4030): ApplicationContext is null in ApplicationStatus
,W/chromium( 4030): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 4030): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 4030): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 4030): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 4030): Requires BLUETOOTH permission
I/NSApplication( 4030): Starting up...
,I/ActivityManager(  824): Killing 1525:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  824): Client connection lost with reason: 4
,I/ActivityManager(  824): Start proc 4086:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,V/MusicLeanback( 3450): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  824): Killing 3686:com.android.providers.calendar/u0a3 (adj 15): empty #17
,D/SprintDMReceiver( 4009): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4009): simOperator:  IMSI: null
,D/SprintDMReceiver( 4009): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1791): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1791): onCreate
,D/SystemUpdateService( 1791): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1791): active receiver: enabled
,I/SystemUpdateService( 1791): showing system update notification
,I/ValidateNoPeople(  824): skipping global notification
,V/SystemUpdateService( 1791): retry (wakeup: false) in 3599970 ms
,D/SystemUpdateService( 1791): onDestroy
,D/ChimeraCfgMgr( 1791): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ContextImpl( 3959): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  824): Start proc 4108:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,D/DockEventReceiver( 3959): finishStartingService: stopping service
,W/ResourcesManager( 4108): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 4108): Adding HeadsetService
D/AdapterServiceConfig( 4108): Adding A2dpService
D/AdapterServiceConfig( 4108): Adding HidService
,D/AdapterServiceConfig( 4108): Adding HealthService
,D/AdapterServiceConfig( 4108): Adding PanService
D/AdapterServiceConfig( 4108): Adding GattService
,D/AdapterServiceConfig( 4108): Adding BluetoothMapService
,I/ActivityManager(  824): Killing 3848:com.google.android.gms:car/u0a11 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1498): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,V/GoogleAuthProtoRequest( 3280): [342] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3280): [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3280): [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3280): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3280): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3280): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  824): Failed to find a new network - expiring NetTransition Wakelock
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1498): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1498): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1498): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1498): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3812): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3812): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3812): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3812): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3812): Ignoring header User-Agent because its value was null.
,V/GoogleAuthProtoRequest( 3280): [343] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3280): [343] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3280): [343] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3280): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3280): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3280): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1498): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1498): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1498): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1498): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3812): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 3812): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
,E/PlayEventLogger( 3812): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3812): 	,at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3812): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3812): Ignoring header User-Agent because its value was null.
,I/EventLogService( 1791): Opted in for usage reporting
,I/EventLogService( 1791): Aggregate from 1449747506338 (log), 1449747506338 (data)
,W/EventLogAggregator( 1791): Unknown tag: snet_gcore
W/EventLogAggregator( 1791): Unknown tag: snet_launch_service
,I/art     (  824): Explicit concurrent mark sweep GC freed 31156(1556KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 1.701ms total 56.321ms
,I/ServiceDumpSys( 1791): dumping service [account]
,I/art     ( 1498): Explicit concurrent mark sweep GC freed 60088(2MB) AllocSpace objects, 8(882KB) LOS objects, 36% free, 27MB/43MB, paused 1.651ms total 44.092ms
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1498): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1498): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1498): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1498): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3812): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 3812): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3812): 	,at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3812): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 3812): Ignoring header User-Agent because its value was null.
,V/GoogleAuthProtoRequest( 3280): [344] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3280): [344] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3280): [344] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3280): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3280): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3280): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3280): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3280): 	at com.a.a.k.run(SourceFile:110)
,I/UsageStatsService(  824): User[0] Flushing usage stats to disk
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1498): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1498): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1498): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1498): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3812): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3812): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3812): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3812): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3812): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1498): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1498): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1498): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1498): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1498): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3812): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3812): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3812): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3812): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3812): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 3812): Ignoring header User-Agent because its value was null.
,I/ProcessStatsService(  824): Prepared write state in 21ms
,I/ProcessStatsService(  824): Prepared write state in 13ms,
,I/ProcessStatsService(  824): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-52-29.bin
,I/GLSUser ( 1498): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1498): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1498): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1498): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1498): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1800000ms),I/art     ( 1498): Explicit concurrent mark sweep GC freed 91104(4MB) AllocSpace objects, 8(882KB) LOS objects, 36% free, 27MB/43MB, paused 2.121ms total 74.798ms
D/AndroidRuntime( 4435): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4435): CheckJNI is OFF
D/AndroidRuntime( 4435): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  824): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  824): Killing 3204:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  824): Skipping PackageSetting{22855ec4 com.example.hello/10272} due to missing metadata
I/WindowState(  824): WIN DEATH: Window{27e04d49 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  824): Client connection lost with reason: 4
E/libprocessgroup(  824): failed to kill 1 processes for processgroup 3204
W/ActivityManager(  824): Force removing ActivityRecord{6752d16 u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
V/ActivityManager(  824): Display changed displayId=0
W/ActivityManager(  824): Spurious death for ProcessRecord{27811c06 3204:com.test.thalitest/u0a265}, curProc for 3204: null
I/ActivityManager(  824): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
I/Keyboard.Facilitator( 1215): resetDictionaries() : en_US
D/TaskPersister(  824): removeObsoleteFile: deleting file=24_task.xml
D/BuaReceiver( 3068): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/InputReader(  824): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1215): run()
I/ActivityManager(  824): Start proc 4451:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/Decoder ( 1215): createOrResetDecoder
I/art     ( 1067): Explicit concurrent mark sweep GC freed 76475(3MB) AllocSpace objects, 0(0B) LOS objects, 13% free, 103MB/119MB, paused 1.198ms total 73.168ms
I/art     (  824): Explicit concurrent mark sweep GC freed 57084(3MB) AllocSpace objects, 13(476KB) LOS objects, 31% free, 34MB/50MB, paused 1.859ms total 88.869ms
I/ActivityManager(  824): Start proc 4468:com.google.android.googlequicksearchbox:search/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService
W/InputMethodManagerService(  824): Got RemoteException sending setActive(false) notification to pid 3204 uid 10265
I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 9.336ms
I/Keyboard.Facilitator( 1215): onFinishInput()
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 8.528ms
I/ConfigService( 1498): onCreate
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 18.892ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1215): run()
I/art     ( 1312): Explicit concurrent mark sweep GC freed 5060(369KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 641us total 28.583ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1215): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1215): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1215): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1215): run()
I/StatsUtilsManager( 1215): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1215): shouldRecordStats() = Too Soon
D/JobSchedulerService(  824): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  824): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/VoicemailCleanupService( 4451): Cleaning up data for package: com.test.thalitest
I/art     (  824): Explicit concurrent mark sweep GC freed 9214(476KB) AllocSpace objects, 3(330KB) LOS objects, 32% free, 33MB/49MB, paused 1.451ms total 110.392ms
I/ActivityManager(  824): Start proc 4494:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
D/Launcher.Workspace( 1312): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1312): 11683562 - stripEmptyScreens()
I/ContactLocale( 4451): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  824): Start proc 4517:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/ActivityManager(  824): Start proc 4537:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
I/ActivityManager(  824): Killing 3778:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
W/ContextImpl( 4517): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
I/art     ( 4435): System.exit called, status: 0
I/AndroidRuntime( 4435): VM exiting with result code 0.
E/NetworkScheduler.SchedulerReceiver( 1498): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1498): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PackageBroadcastService( 1791): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1791): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1791): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1791): Module APK com.google.android.play.games already loaded
W/FileUtils( 4517): Failed to chmod(/data/data/com.android.keychain/databases/grants.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
D/ChimeraCfgMgr( 1791): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1791): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 4451): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
E/SQLiteLog( 4517): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 4451): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 4451): Process: android.process.acore, PID: 4451
E/AndroidRuntime( 4451): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4451): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4451): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4451): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4451): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4451): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4451): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 4451): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 4451): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 4451): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4451): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4451): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1791): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AndroidRuntime( 4517): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4517): Process: com.android.keychain, PID: 4517
E/AndroidRuntime( 4517): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4517): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4517): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 4517): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4517): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4517): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4517): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4517): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:404)
E/AndroidRuntime( 4517): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 4517): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4517): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4517): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4517): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 1791): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1791): Process: com.google.android.gms, PID: 1791
E/AndroidRuntime( 1791): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1791): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1791): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1791): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1791): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1791): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1791): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1791): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1791): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1791): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1791): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1791): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1791): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1791): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1791): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1791): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1791): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
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
D/OpenGLRenderer(  824): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  824): Validating map...
I/LocationSettingsChecker( 1791): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1791): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
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
E/DriveAsyncService( 1791): disk I/O error (code 3850)
E/DriveAsyncService( 1791): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1791): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1791): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1791): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1791): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1791): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1791): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1791): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1791): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1791): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1791): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1791): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1791): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1791): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1791): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 1791): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1791): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1791): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1791): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1791): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1791): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1791): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1791): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1791): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1791): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1791): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1791): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1791): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1791): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1791): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1791): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1791): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1791): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1791): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1791): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1791): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1791): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1791): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1791): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1791): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1791): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1791): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1791): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1791): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1791): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1791): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1791): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1791): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1791): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1791): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1791): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1791): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1791): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1791): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1791): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1791): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1791): Sending signal. PID: 1791 SIG: 9
I/ActivityManager(  824): Start proc 4581:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
W/ResourcesManager(  824): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  824): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 4581): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4581): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/OpenGLRenderer(  824): Initialized EGL, version 1.4
I/ActivityManager(  824): Process com.google.android.gms (pid 1791) has died
W/ActivityManager(  824): Scheduling restart of crashed service com.google.android.gms/.usagereporting.service.UsageReportingService in 1000ms
W/ActivityManager(  824): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
W/ActivityManager(  824): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
W/ActivityManager(  824): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
W/ActivityManager(  824): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
W/ActivityManager(  824): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
D/WifiService(  824): Client connection lost with reason: 4
D/OpenGLRenderer(  824): Enabling debug mode 0
I/MultiDex( 4581): VM with version 2.1.0 has multidex support
I/MultiDex( 4581): install
I/MultiDex( 4581): VM has multidex support, MultiDex support library is disabled.
D/AndroidRuntime( 4468): Shutting down VM
V/JNIHelp ( 4581): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  824): Start proc 4601:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 4468): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 4468): FATAL EXCEPTION: main
E/AndroidRuntime( 4468): Process: com.google.android.googlequicksearchbox:search, PID: 4468
E/AndroidRuntime( 4468): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR e300
E/AndroidRuntime( 4468): 	at com.google.android.search.core.j.g$7.onFailure(HotwordWorker.java:378)
E/AndroidRuntime( 4468): 	at com.google.android.apps.gsa.shared.util.c.a.r$1.run(TaskRunnerImpl.java:329)
E/AndroidRuntime( 4468): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 4468): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4468): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4468): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4468): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4468): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4468): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4468): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4468): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR e300
E/AndroidRuntime( 4468): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime( 4468): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime( 4468): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime( 4468): 	at com.google.android.apps.gsa.shared.util.c.d$1.call(LazyListenableFuture.java:46)
E/AndroidRuntime( 4468): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4468): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4468): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4468): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4468): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 4468): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR e300
E/AndroidRuntime( 4468): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime( 4468): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime( 4468): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 4468): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 4468): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 4468): 	... 5 more
E/AndroidRuntime( 4468): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 4468): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime( 4468): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime( 4468): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime( 4468): 	... 9 more
E/AndroidRuntime( 4468): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 4468): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime( 4468): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime( 4468): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime( 4468): 	... 11 more
I/ProviderInstaller( 4581): Installed default security provider GmsCore_OpenSSL
E/DropBoxManagerService(  824): Can't write: system_app_crash
E/DropBoxManagerService(  824): java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
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
W/NativeLibraryUtils( 4581): Failed to open lock file
W/NativeLibraryUtils( 4581): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4581): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4581): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4581): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4581): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4581): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4581): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4581): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4581): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4581): 	... 3 more
I/ActivityManager(  824): Killing 3812:com.android.vending/u0a19 (adj 15): empty #17
I/ActivityManager(  824): Start proc 4626:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
W/ResourcesManager( 4626): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4626): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 4626): VM with version 2.1.0 has multidex support
I/MultiDex( 4626): install
I/MultiDex( 4626): VM has multidex support, MultiDex support library is disabled.
I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0

```
